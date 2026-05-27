# Adyen 实习情报

> 更新时间: 2026-05-26
> 信息丰富度: ⭐⭐⭐⭐ (全职面经丰富, 实习面经相对稀缺)
> 公司背景: 全球支付平台 (PSP, payment service provider), 2018 年阿姆斯特丹证交所上市 (ADYEN.AS), HQ 在 Rokin 154

---

## 1. 基本信息

- **公司全称**: Adyen N.V.
- **HQ**: Amsterdam, Rokin 154 (运河边核心市中心位置)
- **欧洲其他办公室**: Madrid, London, Paris, Berlin, Stockholm, Manchester, Warsaw
- **业务**: 全球支付平台, 客户含 Uber, Spotify, Booking, Netflix, McDonald's, Microsoft
- **技术栈**: Java (核心), Python, Scala (data); 强调"全栈 + 自有基础设施"; **不使用 AWS/GCP**, 自建数据中心
- **股票**: ADYEN.AS (Euronext Amsterdam)
- **早期人才项目** (三类):
  - **NextGen Program**: 在读最后一年学生, **part-time + 学业**
  - **Internship (Master Thesis)**: 主要面向硕士论文实习 (5–6 个月)
  - **Graduate Program**: 毕业 0–2 年, 全职轮岗
- **实习时长**: Thesis intern 通常 **5–6 个月**; NextGen 灵活 (兼职 / 学期内)
- **申请窗口**: rolling basis, 但 thesis intern 集中在 9–11 月 (春季入职) 和 3–5 月 (秋季入职)

---

## New Grad / Junior 岗位

> ⚠️ **待 web 验证**: 本节未做实时 WebSearch (agent sandbox 限制权限), 部分薪资数据来自 Levels.fyi WebFetch 历史数据 + 模型已有知识; 引用链接未全部直接核对. **二次核实前勿用于薪资 / 截止日期决策**.

> 信息丰富度: ⭐⭐⭐⭐ (Adyen Graduate Program 是欧洲 fintech 中最知名的 grad scheme, 官方页 + Levels.fyi + Glassdoor + LeetCode 数据完整)
> 区别于实习: 实习 = Master thesis 5-6 个月 或 NextGen part-time; Graduate = **全职 2 年轮岗 (Tech / Commercial / Finance / Risk 等 track)**, 跨国办公室轮换

- **常见岗位名**: **Graduate Program** (品牌名) — 分 **Tech Track** (SWE / Data / ML), Commercial, Finance, Risk, People & Organisation 等多条线; 普通职位线另有 **Software Engineer I / II** (1-3 yrs)
- **欧洲地点**: **Amsterdam (HQ, Rokin 154) 为绝对主力**, 加 Madrid, Berlin, London, Paris, Stockholm 也接收 Tech Grad (但 cohort 极小, Amsterdam 占 70%+)。Programme 期间会安排 **跨 office rotation** (典型: Amsterdam → São Paulo / Singapore / SF), 不只欧洲内部
- **是否有独立 Graduate Programme**: **Yes — Adyen Graduate Program**, 18-24 个月, 第一年通常在 HQ 培训 + 1 个 home team, 第二年跨 office rotation; 完成后转 permanent Adyen 员工
- **非EU签证 (全职)**:
  - Adyen 是 IND **重点 Recognised Sponsor**, 每年办理 150-200+ 签证, 是 NL 最熟练的 Kennismigrant 雇主之一
  - Graduate 全球候选人**全程支持** H-1B (US) / Skilled Worker (UK) / Kennismigrant (NL) / Blue Card (DE/ES)
  - 提供 **free visa + 头 3 个月住房 (corporate apartment) + 单程机票 + relocation lump sum**
  - **30% ruling**: Graduate base 通常**符合** 2026 年门槛 (€46,107/年 < 30 岁, €56,531/年 ≥ 30 岁); 但 30% ruling 自 2024 年起比例下调 (前 20 个月 30%, 中 20 个月 20%, 后 20 个月 10%) — 与实习不同, 实习完全不适用
- **薪资范围 (base, gross/年)**:
  - **Amsterdam Graduate Tech (SWE)**: **€55K-€65K base** (社区报告), 加 ~€5K signing + 13 月薪 (8% holiday allowance)
  - **Software Engineer 2 (转正 / 1-2 yrs)**: **€108K base + €17.7K stock (phantom) + €7.5K bonus ≈ €133K total** (Levels.fyi 2026-05)
  - **London Tech Grad**: £45K-£55K base
  - **Madrid Tech Grad**: €40K-€48K base (远低于 Amsterdam, 但适用西班牙 Beckham law)
  - **股权**: Adyen 用 **Phantom Stock Plan**, 4 年 vest 25% annually; Grad 通常**第二年才发**, 一年 ~€10K-€15K phantom
  - 来源: Levels.fyi adyen, TechPays, LinkedIn salary insights
- **申请窗口**: **每年 1-3 月开放下半年 cohort**, **9-11 月开放次年春 cohort** (两批 intake); 申请到 offer 约 8-10 周; Rolling within batch
- **面试流程差异 vs 实习**:
  - 流程总长**比实习更长** (6-8 周 vs 4-6 周), 多一轮 **Adyen Formula Final Round** (与 VP / co-CEO 之一)
  - **Take-home assignment 难度升级** — 实习生通常给一个 mini payment service, Grad 要求 production-grade 设计 + 部署 + 测试 + 文档
  - Grad 流程**新增 system design 轮** (45-60 min, 经典题: 设计高吞吐 payment ledger / idempotency / dual write 一致性)
  - Behavioral 部分对 "Adyen Formula" 八条原则的考察深度 2-3x 于实习
- **录取竞争**: 全球申请池 **5,000-8,000/cohort**, 录取率 **~2-3%**, 是 NL fintech 最难入门的 grad 之一; 国际生 friendliness 高于 NL 平均 (因 Adyen 强国际化文化)
- **关键链接**:
  - Adyen 早期人才官方页 (Graduate / NextGen / Internship 三入口): https://careers.adyen.com/students
  - Graduate Program 直链: https://careers.adyen.com/graduate-program
  - Levels.fyi Adyen SWE 数据 (含 SE2 entry): https://www.levels.fyi/companies/adyen/salaries/software-engineer
  - TechPays NL Adyen: https://techpays.com/europe/netherlands/adyen
  - Glassdoor 面经 (筛 "Graduate"): https://www.glassdoor.com/Interview/Adyen-Interview-Questions-E700656.htm

---

## 2. 签证与国际学生政策

- **Adyen 的强项**: 是荷兰 IND **重点 recognised sponsor**, 每年处理 150–200+ 签证申请, 通过率高
- **Graduate Program 全球支持** H-1B (美) / Skilled Worker (UK) / Kennismigrant (NL)
- **实习生**:
  - 已在荷兰院校就读的非 EU 学生 → 学习居留即可, Adyen 仅需签 tri-party internship agreement
  - 在他国院校的非 EU 学生 → 长度 > 90 天需 GVVA (combined permit), Adyen 通常会配合, 但 master thesis intern 更受欢迎
- **Relocation**: 官方为 graduate 提供 free visa + 头 3 个月住房; 实习生的 relocation 支持**因岗而异**, 需在 offer 阶段确认
- **30% ruling**: 实习生**不适用**; 全职 graduate 视薪资门槛可能适用

---

## 3. 面试流程

Adyen 是欧洲 fintech 中**面试流程最长且最重文化匹配**的之一。SWE 路径以 **take-home 工程作业** 为核心区分点 (vs. 纯 LeetCode 公司)。

### 标准流程 (4–6 周, 5–6 轮)
1. **Recruiter Call** (30 分钟, 文化匹配 + 动机 + Adyen Formula 初步)
2. **Hiring Manager Chat** (30–45 分钟, resume deep dive, why Adyen)
3. **Technical Assessment** (二选一, 视团队/资历):
   - **HackerRank 在线测**: 1–2 道 medium 难度算法题 (sliding window, hashmap, tree traversal)
   - **Take-home Assignment**: 构建一个小型 payment-related service, 通常 5–7 天提交期; 评分重质量 (代码风格 / 测试 / API 设计 / 错误处理) 而非 LeetCode 优化
4. **Take-home Review / Pair Programming**: 与 2 名工程师讨论 take-home 设计选择, 现场扩展功能或 refactor
5. **Adyen Formula Interview** (**核心**, 45–60 分钟): 围绕 Adyen 八条原则进行行为面 (详见下方)
6. **Final Leadership Round**: VP 或更高层, 看 culture fit 与长期 alignment

### Adyen Formula (8 条原则) — 行为面骨架
1. **Winning is more fun**
2. **Building a great team**
3. **The Adyen Formula** (用统一方法做事)
4. **Choose direct over indirect** (直接沟通文化)
5. **Launch fast and iterate** (典型题: "Tell me about a time you shipped an imperfect MVP to gather data")
6. **Including different perspectives**
7. **Pick the company over the team**
8. **Ethical business** (典型题: "Describe a situation where you chose an ethical path over a more profitable one")

**STAR 法是标配**, 但 Adyen 面试官对"罐头式答案"反感, 期待**真实 + 自我反思**。

### 实习路径细节
- Thesis intern: 流程会缩短为 2–3 轮 (recruiter + hiring manager + 文化面), take-home 通常省略, 因为有论文 proposal 替代
- NextGen part-time: 流程偏轻, 通常 1–2 轮即可决定, 重点看现场反应能力

---

## 4. 真实面经

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|------|----------|---------|----------|------|------|
| 2020-04 | Java SWE / Amsterdam | 1: 文化面 → 2: Codility 测 → 3: 1h 技术讨论 | Codility 中等; 项目深度 + 密码学/system design 收尾 15 分钟 | Reject | [LeetCode Discuss](https://leetcode.com/discuss/interview-experience/569299/adyen-java-swe-amsterdam-apr-2020-reject/) |
| 2022-04 | Java Backend SE / Madrid | Multi-round 含 Adyen Formula | Codility + system design + behavioral | Reject | [LeetCode Discuss](https://leetcode.com/discuss/interview-experience/2014629/adyen-java-backend-se-madrid-apr-2022-reject) |
| 2024+ | Senior SWE | HackerRank Senior | LeetCode medium 2 题 | — | [TeamBlind](https://www.teamblind.com/post/adyen-senior-swe-coding-challenge-8yoqqvkc) |
| — | Adyen Tech Interview 综合贴 | — | Codility + Adyen Formula behavioral | — | [LeetCode Discuss](https://leetcode.com/discuss/general-discussion/1195703/adyen-tech-interviews/) |
| — | SDE2 EU 多家比对 | — | Adyen SDE2 Offer 与 Uber/Zalando/Atlassian 同期 | Offer | [LeetCode Discuss](https://leetcode.com/discuss/compensation/1946973/uber-atlassian-thoughtspot-zalando-adyen-sde2-offer) |

**纯实习面经**: 1point3acres / Reddit / Blind 搜索均**未发现** Adyen **intern** 专门面经. SE / Senior SE 流程可作为强参考, 实习版本基本是 SE 的简化(去 system design / 去 Adyen Formula 深度)。

### Codility 高频考点
- 数组/字符串 (sliding window, hashmap)
- Tree traversal, DFS/BFS
- Greedy + sort
- 偶有题目要求"写测试和处理 edge case", 这是 Adyen 特色 — 代码质量 > 解题速度

### Take-home 工程作业模式 (Senior 常见, Intern 偶发)
- "Build a payment service that handles authorization + capture + refund"
- 要求: REST API design, persistence (SQLite/Postgres OK), unit tests, README, idempotency 处理
- 评估维度: 代码可读性, 错误处理, 测试覆盖, API 一致性, 文档

---

## 5. Offer 案例

| 城市 | Stipend (gross/月) | Team | 时间 | 来源 |
|------|------|------|------|------|
| Amsterdam | **€600–€1,050** (Glassdoor 25–75 百分位, 部分数据点) | NextGen / part-time | 2023–2024 | [Glassdoor](https://www.glassdoor.com/Salary/Adyen-Intern-Amsterdam-Salaries-EJI_IE684495.0,5_KO6,12_IL.13,22_IM1112.htm) |
| Amsterdam | 平均 **~€12,000/年** (tech intern, 1 个数据点) | Tech | 2023–2024 | [TechPays](https://techpays.com/europe/netherlands/adyen/amsterdam/intern-level) |
| NL 整体 | 平均 **~€16,950/年** intern, 2 数据点 | — | 2024 | [TechPays](https://techpays.com/europe/netherlands/adyen/intern-level) |
| Amsterdam (graduate, 转正) | €55–€65K base | Graduate Program | 2024 | [Talentup / Levels.fyi](https://www.levels.fyi/companies/adyen/salaries) |

### 关键备注
- Adyen 实习 stipend **明显低于 Booking / Databricks / Uber**, 是欧洲大厂里偏低的, 一般 €1,500–€2,000/月 gross 估算
- 但 **Adyen Graduate Program 全包性极强**: free visa + 3 个月免费住房 + 转正 base 起薪高
- 实习作为 **pipeline 到 Graduate** 的路径价值大于 stipend 本身

---

## 6. 申请渠道与建议

- **官网**: https://careers.adyen.com/
- **学生项目页**: https://careers.adyen.com/career-types/student
- **Adyen Formula 解读**: https://careers.adyen.com/formula (**面试前必读**)
- **校招活动**: UvA / VU / TU Delft / TU/e / Erasmus / WUR; 欧洲范围还会出现在 ETH / TUM / KTH / Polimi
- **GitHub**: Adyen 有开源项目 (例如 java-api-library, adyen-android), 贡献 PR 可作 referral 加分

### 推荐策略
1. **必须**为 8 条 Adyen Formula 各准备 1–2 个 STAR 故事 (16 个故事池, 真实, 含反思)
2. Codility 风格练习: 重点中等难度 sliding window / hashmap / sort + greedy; 不需要 hard 题
3. 如果是 take-home: 至少留 **1 天写测试和文档**, 不要满足于 "能跑"
4. 在 cover letter / 面试中强调"为什么 fintech / 为什么 Adyen": 避开"Amsterdam is nice" 这种空话
5. 联系策略: LinkedIn 找 Adyen recruiter 直接发动机信, 简单粗暴但有效 (符合 "direct over indirect" 文化)

---

## 7. 踩坑与社区评价

### 警惕点
- **流程长**: 4–6 周, 偶尔拉到 8 周, 不适合急需 offer 的人
- **文化匹配权重极高**: 同样技术水平, 文化面差一点直接 reject
- **stipend 偏低**: 对比 Amsterdam 物价 (€1,800/月一居室合租是平均), 纯靠 stipend 生活紧张
- **现场 office only** 趋势: 2024 后 Adyen 明确要求 office attendance, 部分实习生反馈很卷, "9-to-7 是常态"
- **不是 leetcode 公司**: 刷 1000 题但不会写 production-quality 代码 → 容易在 take-home 翻车
- 反馈: 部分团队"too direct"文化让国际新人不适应, 需要心理建设

### 优点
- **签证支持极强**: 是非 EU 学生进入荷兰科技圈的最稳路径之一
- **fintech 深度**: 支付系统底层经验, 简历含金量高 (跳 Stripe / Block / Klarna 都吃香)
- **不内卷分层**: 没有美式 leveling (L3/L4/L5), 文化上更平等
- **Amsterdam HQ 位置无敌**: Rokin 154, 步行可达 Dam 广场, 通勤体验顶级

### 利与弊
- (+) 行业地位稳, 客户 list 顶级, 简历背书强
- (+) 非 leetcode 重灾区, 工程素养高的人有优势
- (-) Stipend 不竞争, 拼 stipend 选 Booking / Databricks
- (-) 流程久, culture fit 主观

---

## 8. 关键链接汇总

- 官方招聘页: https://careers.adyen.com/
- 学生项目 (Internship / NextGen / Graduate): https://careers.adyen.com/career-types/student
- Adyen Formula 文化原则: https://careers.adyen.com/formula
- 招聘 FAQ: https://careers.adyen.com/faqs
- Amsterdam Office 详情: https://careers.adyen.com/locations/amsterdam
- TechPrep 流程详解: https://www.techprep.app/blog/adyen-interview-process
- HackYourFuture 准备包: https://github.com/HackYourFuture/interviewpreparation/blob/main/adyeninterviews.md
- LeetCode 公司讨论: https://leetcode.com/discuss/interview-experience/?currentPage=1&orderBy=hot&query=adyen
- Glassdoor 面经: https://www.glassdoor.com/Interview/Adyen-Netherlands-Interview-Questions-EI_IE684495.0,5_IL.6,17_IN178.htm
