# CLAUDE.md

个人 EU 科技实习 + new grad 情报库, 覆盖 **34 家公司**. Docsify 渲染, 无 build step. 部署在 `https://eufindwork.github.io` (GitHub Pages).

## 仓库结构

```
job_seek/
├── README.md              # 总览 + 4 张对比表 (intern) + Graduate 路径对比表 + 场景建议
├── _sidebar.md            # docsify 侧边栏 — 链接必须是绝对路径 (/companies/foo.md)
├── _template.md           # 单家公司模板
├── index.html             # docsify config (loadSidebar / relativePath / search)
├── .nojekyll              # GitHub Pages 跳过 Jekyll
└── companies/<name>.md    # 每家公司 ~9 sections
```

## 公司 `.md` 文件 schema

每家公司文件按以下顺序排列, section 之间用 `---` 分隔:

1. `## 1. 基本信息` — 公司 / 办公室 / 岗位 / 招聘窗口
2. `## New Grad / Junior 岗位` (**不带编号**, 插在 1 和 2 之间) — 全职 entry-level / graduate programme
3. `## 2. 签证与国际学生政策` (个别公司命名为 "岗位画像" / "实习岗位类型" 等)
4. `## 3. 面试流程`
5. `## 4. 真实面经` (table)
6. `## 5. Offer 案例` (table)
7. `## 6. 申请渠道与建议`
8. `## 7. 踩坑与社区评价`
9. `## 8. 所有引用链接`

文件命名: 小写, 无连字符 (`stabilityai.md` 而非 `stability-ai.md`).

## 关键规则

### 1. 侧边栏链接必须是绝对路径

`_sidebar.md` 必须用 `/companies/foo.md` (前导斜杠), 而非 `companies/foo.md`. docsify 在 `/companies/*.md` 页面会把相对路径再叠一层, 解析成 `/companies/companies/foo.md` → **404**. README 内的链接因为始终在根路径 `#/` 渲染, 用相对路径无碍.

### 2. Web 研究必须真跑

任何要求新增 / 更新数据的任务都要跑实时 `WebSearch` + `WebFetch`, **不能只用模型已有知识**. 启动 subagent 前先看 [.claude/settings.local.json](.claude/settings.local.json) 是否允许这两个工具 — background agent 无法响应权限弹窗, 缺权限会被默认 deny 然后静默 fallback. 当前 settings 已全开.

### 3. 数据未验证 → 必须标注

如果 web 验证跳过 / 失败, 在受影响 section 顶部加:
```markdown
> ⚠️ **待 web 验证**: 本节未做实时 WebSearch (原因), 数据基于 ...; 二次核实前勿用于薪资 / 截止日期决策.
```
不要让未经验证的数据看起来权威. 已经 web 验证过的 section **必须移除该标注**.

### 4. 引用必须可溯源

数据点 (薪资数字 / 截止日期 / 项目名称) 旁边带 inline URL. 优先级:
- 官方 careers 页 (实际 WebFetch 成功)
- Levels.fyi / TechPays (实际打开过)
- JoinTaro / 1point3acres / LeetCode Discuss / Reddit (实际打开过)
- Glassdoor 仅作辅助 (薪资数据浮动大)

引用格式: `[来源 (实际打开过): URL]`. 仅在搜索结果中见过但未打开的, 不要写 "实际打开过".

## 标准 Parallel Research 工作流

更新所有 34 家公司时, 拆 4 个 tier 并行 (4 个 subagent + `run_in_background: true`):

| Tier | 公司 (按文件名) |
|------|----------------|
| **Tier 1 大厂 (7)** | google, meta, amazon, microsoft, apple, nvidia, deepmind |
| **中型国际 (12)** | jetbrains, booking, adyen, asml, signify, uber, tomtom, elastic, databricks, confluent, canva, nebius |
| **欧洲本土 (11)** | spotify, klarna, zalando, deliveryhero, n26, mistral, criteo, deezer, revolut, arm, improbable |
| **AI/ML 专项 (4)** | huggingface, cohere, stabilityai, alan |

每个 agent 必须:
- 自带完整 schema (不依赖外部上下文)
- 用 Edit 工具精确定位插入点 (`## 2.` 标题, 注意非所有文件都用 `## 2. 签证与国际学生政策`)
- 报告时给每家公司一行 summary + 数据置信度 ⭐

## User 当前 ⭐ 活跃申请 (最高精度)

- **JetBrains** (Munich / Amsterdam / Prague)
- **Signify** (Eindhoven)
- **Nebius** (Amsterdam)
- **Booking** (Amsterdam)

对这 4 家做任何修改前都要保留之前的精确数据 (特别是 Signify 的 "Junior IT/Digital Program" 命名 — **不是** GE 的 "Edison Programme") 和 Nebius G16 Levels.fyi 直读数字.

## 写作风格

- **中文为主, 关键名词混英文** (visa / Skilled Worker / Kennismigrant / RSU / OA / OOD / TC / base 等不翻译)
- 不加多余 emoji (README 已有的 🏠 📋 🌐 🇪🇺 🤖 保留, 新增章节克制)
- 表格、blockquote 比段落优先 (扫读友好)
- 不写"用户友好""极致体验"这类营销词
