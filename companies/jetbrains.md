# JetBrains 实习情报

> 更新时间: 2026-05-26
> 信息丰富度: ⭐⭐⭐⭐ (官网项目库 + Levels.fyi stipend + Glassdoor 面经 + JetBrains 官方博客; 缺中文社区面经)
> 一句话定位: 捷克起家 / 总部 Prague 的开发者工具公司, IntelliJ IDEA / PyCharm / Kotlin 等 IDE 与编程语言的母公司, 全部实习均为有偿, 走"先选 project + 提交 test task → mentor 面试"的非标准流程

---

## 1. 基本信息

### 欧洲办公室与 intern 可投地区
JetBrains 实习项目"office, hybrid, fully remote 均可, 但必须在公司有办公室的国家境内远程"。官方明确说明的实习 / relocation 可达国家:

| 国家 | 城市 | 备注 |
|------|------|------|
| 荷兰 | Amsterdam | 2019 年开设, Huidekoperstraat 26-28; 含 Datalore (数据科学 IDE / Jupyter notebook) 团队 |
| 德国 | Munich, Berlin | Levels.fyi 有 Munich intern 历史数据 |
| 捷克 | Prague | 创始地之一, 工程团队规模最大 |
| 塞浦路斯 | Limassol | 公司注册地之一 |
| 亚美尼亚 | Yerevan | 重要工程枢纽 |
| 波兰 | Warsaw | Levels.fyi 显示 2025 Warsaw intern 数据 |
| 塞尔维亚 | Belgrade | 接受塞尔维亚 resident 申请 |
| 英国 | London | 部分项目允许 |

> 来源: jetbrains.com/careers/internships/, internship.jetbrains.com (项目页面 "Available locations" 字段)

### 实习岗位类型
- **Development** (主力): IDE 内核 / Kotlin 编译器 / 静态分析 / Analysis API / Compose Multiplatform / IntelliJ Platform / 各语言插件
- **Research / AI4SE**: 与 TU Delft 合作的 AI for Software Engineering 项目 (LLM + 代码生成 + 测试生成)
- **Data Science**: Datalore (Amsterdam), Kotlin Notebook, Kotlin DataFrame
- **Non-technical**: UI/UX 设计, Marketing, Community, HR, Finance, Legal

### 实习时长与招聘周期
- **官方时长**: 3 个月 full-time, 或 6 个月 part-time, 与学校时间可商量
- **薪资**: 全部 paid (官方原话: "All internships at JetBrains are paid")
- **2025/2026 实例 Cycle**: 部分项目截止 2025-11-07, 面试至 12-09, 12-10 公布结果 → 即"秋季提交 → 冬季面试 → 春/夏入职"
- **Summer cohort**: 通常春季初提交, 6 月入职

---

## 2. 签证与国际学生政策

**核心结论: JetBrains 实习不提供 visa sponsorship, 但提供 relocation 到指定国家。**

| 维度 | 政策 (官方原文 / 含义) |
|------|------------------------|
| 申请人居住地要求 | 必须 reside in EU / Armenia / Serbia (或英国学生身份), 且无 legal/visa restrictions |
| 学生签证持有者 | 可以申请 (官网注明 "holders of student visas") |
| 内部 visa support (intern) | **没有** ("we do not offer visa/permit support within the internship framework") |
| Relocation 支持 (intern) | 仅支持 full-time 3 个月 summer internship; relocation 国家: Armenia, Cyprus, Czechia, Germany, Netherlands; 必须本身就有目标国 work + residence permit 或 passport; case-by-case 决定 |
| Full-time 转正后 | 提供完整 work permit / 居留 / 文件翻译 / 1 个月临时住房 / 机票 / 行李运输 / 部分国家提供语言课; 历史上 1 年内有 90+ 员工 + 家属 (含宠物) 被 relocation |

**对中国留学生的可行路径**:
1. **已在 EU 念书 (含学生签)**: 直接申请, JetBrains 不为你办新签证, 但你可以用学校的 internship agreement 在荷兰/德国/捷克实习 (需走 Nuffic 三方协议或学校 Erasmus+ 框架)
2. **已在英国念书**: 也可申请 (申请页面 explicitly accepts UK students)
3. **不在 EU/UK/AM/RS 念书**: 官方意义上 ineligible; 可发信 `internship@jetbrains.com` 个案咨询, 但成功率极低
4. **替代路径**: 优先申请 Armenia (Yerevan), 因为是唯一对"非 EU 居住"做个案 relocation 的国家

> 来源: jetbrains.com/careers/internships/, blog.jetbrains.com/life-at-jetbrains/2026/05/relocating-with-jetbrains-...

---

## 3. 面试流程

### 整体流程 (非标准!)
JetBrains 实习**没有 OA + 多轮 LeetCode 的传统模式**, 全流程围绕"项目 + 导师"展开:

```
① 浏览项目库 (internship.jetbrains.com)
   ↓
② 选 1–5 个项目, 提交申请 (Hub 账号登录)
   ↓
③ 完成项目特定的 test task (点击 "Solve the task" 后开始倒计时)
   ↓
④ Mentor 审阅 test task 解答, 通过者收邮件邀请
   ↓
⑤ 1 轮技术 / 行为面试 (Mentor + dev) — 大多数为 behavioral, 也可能问技术
   ↓
⑥ 录用决定
```

### 题型分布
| 题型 | 占比 | 备注 |
|------|------|------|
| **Test task (home assignment)** | 80% 权重 | 与目标项目高度相关; 例如 Kotlin Analysis API 项目会让你实现 mini parser / static analyzer |
| **Behavioral 面试** | 主要 | "Tell us about yourself", 项目经历, 协作风格 |
| **技术口试** | 偶尔 | OOP 基础 (Abstract class vs interface), Git, JVM (GC, stack/heap), 语言细节 (Kotlin `==` vs `===`, nullable types) |
| **算法 / LeetCode** | 极少 | JetBrains 不像 FAANG 主刷算法; 但 SWE Senior 岗位 Glassdoor 显示有 90 min 技术面 + 90 min 系统设计 + 7 天 take-home |

### OA
- **没有传统在线笔试**; test task 本身就承担了筛人功能
- Test task 难度对标 medium 工程任务, 而不是 LeetCode 题

### 流程节奏
- Glassdoor 数据: 全公司平均 hire 周期 **35.77 天** (70 个样本)
- Intern 全流程: 大约 2 个月 (例: 1 月面试, 4 月录用)
- 2025–2026 cycle 公开节奏: 申请截止 11/7 → 面试至 12/9 → 12/10 出结果

> 来源: glassdoor.com/Interview/JetBrains-Software-Engineer-Internship..., jetbrains.com/careers/internships/, internship.jetbrains.com/projects/1666

---

## 4. 真实面经

| 时间 | 岗位 / 城市 | 流程概述 | 题目 / 题型 | 结果 | 来源 |
|------|------------|---------|-----------|------|------|
| 2024-01 | Software Engineer Internship / Amsterdam | Test task → 1 轮 dev 面试 | "Tell us about yourself, describe one issue from your projects and how you handled it" | 未披露 | [Glassdoor](https://www.glassdoor.com/Interview/JetBrains-Software-Engineer-Internship-Interview-Questions-EI_IE222299.0,9_KO10,38.htm) |
| 2025-04 | Software Engineer Internship | Test task → mentor 面试 | Abstract class vs interface; Git 基础; GC; Stack vs Heap memory | 未披露 | [Glassdoor 同上] |
| 2025-Summer | SE Intern / Warsaw | 项目: Kotlin / IDE 相关 | 未披露具体题目 (Senior Undergrad) | Offer | [Levels.fyi](https://www.levels.fyi/internships/JetBrains/Software-Engineer-Intern/) — $14.60/hr ($2,531/mo) |
| 2025-Summer | SE Intern / Amsterdam (remote) | 标注为 remote, "not open" | — | Offer | [Levels.fyi](https://www.levels.fyi/internships/JetBrains/Software-Engineer-Intern/) — $10.07/hr ($1,746/mo) |
| 2024-Summer | SE Intern / Munich | Master 在读 | — | Offer | [Levels.fyi](https://www.levels.fyi/internships/JetBrains/Software-Engineer-Intern/) — $11.54/hr ($2,000/mo) |
| 2023-Summer | SE Intern / Munich | Junior Undergrad; 公司提供交通+午餐 | — | Offer | [Levels.fyi](https://www.levels.fyi/internships/JetBrains/Software-Engineer-Intern/) — $23/hr ($3,987/mo) — **2025 后明显下调, 可能已过时** |
| 2024–2025 | AI4SE Research Intern / TU Delft (NL) | TU Delft 论文项目 → 转正 | LLM 应用于代码生成 / 测试生成 / 数据泄漏检测 | 转 FTE (Milan/Nadine/Saga/Sergey 四人) | [JetBrains Research Blog 2025-09](https://blog.jetbrains.com/research/2025/09/ai4se-interns-jetbrains-part-1/) |

**总体难度评估** (Glassdoor intern 自评): **2.93 / 5** (low-medium), 体验正面率 **83%**

> 注: site:reddit.com 和 1point3acres 两边都没搜到 JetBrains 实习面经 — 该公司在华人社区曝光度低, 直接面经几乎没有

---

## 5. Offer 案例 (Stipend)

| 城市 | Stipend (gross) | Team / 项目 | 时间 | 来源 |
|------|----------------|------------|------|------|
| Warsaw | $2,531 / 月 (~€2,330) | SE Intern (Senior UG) | 2025 Summer | [Levels.fyi](https://www.levels.fyi/internships/JetBrains/Software-Engineer-Intern/) |
| Amsterdam | $1,746 / 月 (~€1,610) | SE Intern (remote) | 2025 Summer | [Levels.fyi](https://www.levels.fyi/internships/JetBrains/Software-Engineer-Intern/) |
| Munich | $2,000 / 月 (~€1,840) | SE Intern (Master) | 2024 Summer | [Levels.fyi](https://www.levels.fyi/internships/JetBrains/Software-Engineer-Intern/) |
| Munich | $3,987 / 月 (~€3,670) — **outlier, 可能已过时** | SE Intern (Junior UG, 含交通+餐食) | 2023 Summer | [Levels.fyi](https://www.levels.fyi/internships/JetBrains/Software-Engineer-Intern/) |

**Stipend 总结**: 2024–2025 趋势在 €1,600–€2,400 gross/月 区间, 与荷兰 Highly Skilled Migrant intern 行情吻合。2023 Munich 那笔 $4k 数据是 outlier, 不要参考。

---

## 6. 申请渠道与建议

### 官方渠道
- **实习项目库 + 申请入口**: https://internship.jetbrains.com/ (登录 JetBrains Hub 账号)
- **公司 career 总入口**: https://www.jetbrains.com/careers/
- **Career 项目 Greenhouse**: https://job-boards.eu.greenhouse.io/jetbrains (全职岗位为主, 偶尔含 intern)
- **联系邮箱**: internship@jetbrains.com (visa / 个案咨询)

### 项目选择技巧
1. **每个 cycle 最多投 5 个 project**, 因此要精选与自己 stack 高度匹配的
2. Test task 一旦点击 "Solve the task" 就**开始计时**, 务必先把任务下载 + 看完再点
3. 单个 cycle 中如果一个 project 含多个 task, **共用一个总倒计时** — 仔细分配时间
4. Mentor 看到一个高质量 test task 解决方案比刷再多 LeetCode 都有用 — 提交前 cleanup 代码 / 写 README / 简单 design rationale

### 简历 / 背景要求
- **必备**: EU/UK/AM/RS 居住权 + 学生 (或毕业 ≤1 年)
- **加分**: 
  - 对应项目栈深度 (e.g. Kotlin Analysis API 项目要求 Java/Kotlin + parser/static analysis 经验)
  - **开源 contribution 到 JetBrains 旗下 repo** (kotlin, intellij-community, intellij-kotlin 等) — 这是 mentor 最直接的信号
  - 编译器 / IDE / DSL 相关课程或项目
- **Kotlin Ecosystem Mentorship Program** (https://blog.jetbrains.com/kotlin/2026/05/kotlin-ecosystem-mentorship-program/) 是另一条曲线救国: 通过它接触 JetBrains 核心 contributor → 拿 referral

### 内推
- JetBrains 没有公开 referral bonus, 但**项目页面通常列出 mentor 名字** — 在 GitHub / Twitter / 学术会议接触 mentor 比走 LinkedIn cold message 有效得多

---

## 7. 踩坑与社区评价

| 维度 | 评价 |
|------|------|
| 流程节奏 | 中等; 30–60 天, 比 FAANG 快, 比 startups 慢 |
| OA 是否劝退 | 没有 OA, 但 test task 工作量 ≈ 一个小型 weekend project, 时间紧的同学需提前规划 |
| 对国际学生友好度 | **居住地硬性门槛 (EU/AM/RS/UK)** 是最大坑; 不办 visa 是公开声明, 不要寄望 exception |
| 文化 | Glassdoor 整体 4.x / 5, intern 评 4.6 culture; 公司文化偏工程师驱动, hierarchy 弱 |
| 项目质量 | 实习生从 Day 1 就贡献 production / research 代码, AI4SE 项目甚至能转 FTE |
| Stipend | 不算顶尖 (Amsterdam €1.6k, Warsaw €2.3k), 但对 IDE / 编程语言爱好者来说,"做 Kotlin/IntelliJ 本身"比薪资更有 prestige |
| Remote 限制 | 仅在 JetBrains 有 office 的国家 remote, 中国境内不能 remote |
| 转正路径 | AI4SE / Research 路径有明确转正案例; 工程 intern 转正条件不公开, 但通常需要 cycle 内 mentor 主动推 |

### 已知"坑"
- **多个项目只在某些 cycle 开放** — 不要等"完美 fit"的项目, 看到合适就投
- **Stipend 在不同国家差异极大** (Warsaw > Amsterdam, 2023 vs 2024 数据差 2x); 接 offer 前问清楚 housing / transit 是否包含
- **2023 Munich $4k/月那笔不要拿来谈判** — 是个 outlier
- **没有 referral bonus** → cold apply 与"找 mentor pre-pitch"是仅有的两条路

---

## 8. 所有引用链接

- https://internship.jetbrains.com/ (项目库 / 申请入口)
- https://www.jetbrains.com/careers/internships/ (实习政策, paid, 3/6 月, EU/AM/RS, 不办 visa)
- https://www.jetbrains.com/careers/ (career 总入口)
- https://www.jetbrains.com/careers/locations/germany/ (Munich/Berlin 办公室)
- https://www.jetbrains.com/careers/locations/czech-republic/ (Prague 办公室)
- https://internship.jetbrains.com/projects/1666 (Project Distiller for Kotlin Analysis API — 截止 2025-11-07 案例)
- https://internship.jetbrains.com/admissions/98 (Marketing Internship 2024-2025)
- https://www.glassdoor.com/Interview/JetBrains-Software-Engineer-Internship-Interview-Questions-EI_IE222299.0,9_KO10,38.htm (面经主页, 难度 2.93/5, 体验 83% 正面)
- https://www.glassdoor.com/Interview/JetBrains-Interview-Questions-E222299.htm (全公司面经)
- https://www.glassdoor.com/Interview/JetBrains-Munich-Interview-Questions-EI_IE222299.0,9_IL.10,16_IC4990924.htm (Munich 面经)
- https://www.levels.fyi/internships/JetBrains/Software-Engineer-Intern/ (Stipend 4 个数据点)
- https://www.levels.fyi/companies/jetbrains/salaries/software-engineer/locations/greater-amsterdam-area (Amsterdam 全职 €92.1K–€126K)
- https://techpays.com/europe/netherlands/jetbrains (荷兰薪资众包数据)
- https://blog.jetbrains.com/life-at-jetbrains/2026/05/relocating-with-jetbrains-visa-support-relocation-process-and-what-to-expect/ (Relocation 政策官方博客)
- https://blog.jetbrains.com/research/2025/09/ai4se-interns-jetbrains-part-1/ (TU Delft AI4SE 转正案例)
- https://blog.jetbrains.com/kotlin/2026/02/kotlin-ecosystem-mentorship/ (Kotlin Mentorship Program — 接触 maintainer 的路径)
- https://blog.jetbrains.com/kotlin/2026/05/kotlin-ecosystem-mentorship-program/ (Mentorship 2026 结果公示)
- https://leetcode.com/company/jetbrains/ (LeetCode 公司题库 tag)
- https://job-boards.eu.greenhouse.io/jetbrains (Greenhouse 全职岗位)
- https://github.com/JetBrains/kotlin (开源贡献入口)
- https://github.com/JetBrains/intellij-kotlin (Kotlin plugin for IDEA)
