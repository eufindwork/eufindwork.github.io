# Klarna 实习情报（Stockholm）

> 范围：Software Engineer Intern、Machine Learning / Data Science Intern。Klarna 的核心工程团队仍在 Stockholm，其它办公室（柏林、伦敦、马德里、纽约）以业务/合规/商务为主。

---

## 1. 公司与招聘概况

| 维度 | 信息 |
| --- | --- |
| 总部 | Stockholm, Sweden |
| 业务定位 | BNPL（Buy Now Pay Later）龙头 + 支付 + 购物入口 + AI Shopping Assistant |
| 2024–2025 关键事件 | 1) 2022–2024 累计减员从 5,500 → ~3,400（多通过 attrition）；2) CEO Sebastian Siemiatkowski 公开宣布"AI 替代约 700 客服岗位，暂停所有招聘约 1 年"；3) 2024 末 / 2025 初承认"AI 替代走得过激"，重新开放招聘，特别是客服+部分技术岗；4) 2025 准备 / 启动 US IPO，对 headcount 与盈利能力高度敏感 |
| 实习项目类型 | Software Engineering Intern、Data Science Intern（含 Master Thesis Internship）、产品/设计/财务/法务等少量实习；很多通过 Master Thesis 项目转正 |
| 时长 | 3–6 个月，部分 Master Thesis 为 20 周左右 |
| 工作模式 | Hybrid（Stockholm Årsta HQ 一周 2–3 天在办公室）|
| 入职窗口 | 滚动开放；夏季实习窗口在前一年秋冬，论文实习全年可申请 |
| 实习是否可对外 | Klarna 历来对实习生 sponsor visa 极少，绝大多数实习要求已在欧盟/瑞典持合法身份 |

> AI 战略对实习的影响：客服 / 内容运营类岗位被 AI 替代显著；但 **Data Science、ML Engineer、AI Platform、Risk、Payments 后端**等岗位反而被进一步强化，2025 起这些方向重启招聘 — 实习生需要展示对 LLM / Agent / RAG / 风控建模的实际理解。

---

## 2. 岗位画像

### 2.1 Software Engineer Intern
- 技术栈：Java（主力）、Kotlin、Scala、Node.js / TypeScript、AWS（重度）、Kubernetes、Kafka、PostgreSQL、DynamoDB。
- 团队方向：Payments core、Merchant、Consumer App、Shopping、Risk Platform、Internal Developer Platform。
- 期待：扎实算法/数据结构、对分布式系统/微服务/事件驱动架构有概念、能在 6 周内端到端交付一个 service。

### 2.2 Data Science / ML Intern
- 技术栈：Python、SQL、Spark、AWS SageMaker、Airflow、PyTorch / scikit-learn / XGBoost。
- 团队方向：实时风控（fraud / credit decisioning）、Customer Lifetime Value、Return / Refund prediction、推荐与 Shopping、AI Assistant（GenAI）。
- 期待：能独立完成一个端到端 ML 项目（数据探索 → 特征工程 → 模型 → 评估 → 简单部署）；强 SQL + 统计基础。

---

## 3. 面试流程

### 3.1 SWE / DS Intern 通用流程

1. **Online Logic Test（Kattis Logic Test）** — 第一道硬门槛
   - 18 题 / 15 分钟，纯抽象推理（旋转、包围、增减、蛇形、合并/分裂），与 LeetCode 风格完全不同。
   - 关键设计：会在 recruiter call 的视频中再做一次（同样格式）验证一致性；若两次差距大会直接刷掉。
2. **Recruiter Call**（30 min）— 背景、动机、签证、薪资期望、价值观（Krew）。
3. **Take-home / Live Coding**
   - SWE：take-home 项目（通常是写一个小服务 + 单测）或 60–90 分钟实时编程；Java/Kotlin 偏多。
   - DS / ML：90 分钟 Live Coding & Team Fit — 给一个 toy dataset（sklearn 风格），允许任选模型，强调"分析过程 + 解释 + 可视化"。
4. **Technical Deep-Dive Interview**
   - SWE：项目深挖 + 中等 LC 题 + 系统设计概念（设计 idempotent payment、设计 retry / outbox pattern）。
   - DS：ML 概念问答（监督学习/过拟合/正则/树模型/embedding），常追问项目细节。
5. **Behavioral / Values（Krew）Interview**
   - Klarna 价值观叫 **Krew**：Open / Tough / Driven / Sharp / Sincere / Sustainable / Smart。
   - 行为题非常具体（举一个你挑战 manager 的例子；举一个你坚持不下去的事；举一个你 own 一件破事的例子）。
6. **Hiring Manager + Team Fit**
   - 与具体团队的 lead + 1–2 名 engineer 聊天；常常包含"如果给你这个 ambiguous 问题你会怎么做"。
7. **Bar Raiser**（部分流程出现）— 由非本团队的 senior 复审。

> 整体周期：6–7 轮，平均 36 天（jointaro / Glassdoor 综合）；DS 流程可达 6 轮 / 2 个月+。

### 3.2 题型/面经表

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
| --- | --- | --- | --- | --- | --- |
| 2024-07 | Software Engineer / Stockholm | Recruiter call → Take-home → Tech round → Behavioral → Team interview（含 HM） | 行为题："What do you want to work with here?"、"What project are you most proud of?"；Take-home 为一个 Web 项目；Tech round 含设计/讨论 | 走完最后一轮被 ghost，无 offer；候选人吐槽流程长且无反馈 | jointaro Software Engineer Stockholm 2024-07 |
| 2023-03 | Software Engineer / Stockholm | HR + 逻辑测试 → Tech round（take-home + 通用 Web 项目讨论） → Design round → Manager round | Design round：服务化拆分 + 一个 generic CRUD; Manager round：项目深挖 + Krew | 拒 offer | jointaro 2023-03 |
| 2024-08 | Senior SWE / Germany 远程 | 6+ 轮，含 bar raiser | 系统设计：设计一个 payment retry + outbox；行为题密集；HM 拒 | No offer | jointaro 2024-08 |
| 2025-01 | Engineering Manager / Stockholm | 6 轮，Kattis → recruiter → tech → values → team → HM | EM 流程含一个 mock 1:1 + 一个 architecture 讨论 | 拒 offer | jointaro 2025-01 |
| 2025-10 | Software Engineer / Paris 远程 | 包含 Kattis、Live Coding、Take-home review | Take-home 反馈周期长 (~3 周)；面试官评价不一致 | No offer | jointaro 2025-10 |
| 2023–2024 | Data Scientist / Stockholm | Kattis → Recruiter → 90 min Live Coding & Team Fit → ML deep dive → Behavioral → HM | Live Coding：给 sklearn 风格 toy dataset，要做 EDA、训模型、解释；后续问 "What is supervised learning"、过拟合 / regularization / cross-validation；项目深挖 | -- | Glassdoor / InterviewQuery |
| 2023 | Data Science Master Thesis Intern / Stockholm | 类似 DS 流程 + 论文方向匹配 | 论文计划讨论 + 一道 ML 概念题 + 一段编程 | 论文实习成为转正主要通道 | startup.jobs / Klarna 官方说明 |
| 2024 | Klarna 抽象逻辑测试 | 单独一项，作为所有岗位（含实习）必经 | 18 题/15 分钟，"shape sequence"；旋转、包围、增减、蛇形、合并；二次验证 | 不通过则全流程终止 | tsatestprep / psychometric-success / jobtestprep |

> 备注：Klarna 通过率历史上仅约 **29–31%**，"被 ghost" 高频出现，38% 候选人反馈负面体验。

---

## 4. 补偿与福利

| 项目 | Intern（Stockholm） |
| --- | --- |
| 月薪 | 顶部 Swedish 大厂区间约 **SEK 22,000–28,000/月**（约 USD 2,000–2,600）；Klarna 在 nucamp / Swedish intern 综述里被列为 12,000–18,000 SEK 高位段的代表，但近年传闻已涨到 25k+ |
| 福利 | 含 lunch / 健康 / 周五 happy hour / 公司股权 buyback 项目 |
| 转正路径 | 论文实习 → graduate role 是最常见路径；纯 6 周实习转正取决于 headcount 与团队意愿 |

> 与 Spotify Stockholm 实习相比：Klarna 实习起薪略低，但论文实习对学生而言时间利用率高且转正概率好。

---

## 5. 签证与跨境工作

- **欧盟 / EEA 学生**：自由工作，无小时上限。
- **非欧盟在瑞典在读**：student residence permit 一般允许在学期内全职 / 兼职打工，做实习需在签证有效期内。
- **海外申请者**：Klarna 历来很少为实习生 sponsor 签证；可走 Internship/Trainee permit，但需要 Migrationsverket 审批 1–3 个月。
- **全职毕业生**：Work permit；薪资远超 Migrationsverket 最低门槛，Klarna 会主动协助；EU Blue Card 也可走（瑞典 2025 门槛约 SEK 54,830/月）。

---

## 6. 申请策略 & 时间线

| 阶段 | 时间 | 备注 |
| --- | --- | --- |
| Job posting | 全年滚动，主要批次 9–11 月 | 论文实习 12 月前申请最佳 |
| Application + Kattis test | 24h–72h 内 | 别拖延，关闭测试链接后基本不再开 |
| Recruiter call | 1–2 周 | 同时确认 visa / 学制 |
| Take-home / Live coding | 2–4 周 | Take-home 建议 1 周内交付，最好附 README + 单测 |
| Tech / Values / HM | 4–8 周 | 多轮，跨周排期 |
| Offer | 36 天平均 | 决定窗口通常 1–2 周 |

申请技巧：
- Kattis Logic Test 提前在 TSAtestprep / JobTestPrep / Psychometric-success 刷题；模式固定。
- 在简历突出 **支付 / 风控 / 推荐 / GenAI** 相关项目；2024–2025 战略词是"AI assistant、cost-efficient operations、real-time risk、merchant growth"。
- 行为面准备 Krew 价值观对应故事（Open / Tough / Driven / Sharp / Sincere / Sustainable / Smart），最好每个 value 2 个故事。
- 论文实习对硕士尤其有利，能直接对接团队 + 学校学分。
- 流程长 + 易被 ghost：主动 follow up，并在等待期同时跑多家。

---

## 7. 中文 / 英文社区情报

| 来源 | 关键点 |
| --- | --- |
| Glassdoor Stockholm | Klarna SWE 通过率 ~29%、负面体验 38%、平均流程 36 天 |
| jointaro | 多份 2023–2025 SWE / DS / EM / Senior SWE 面经，质量高，是最佳英文一手来源 |
| Reddit r/cscareerquestionsEU / r/sweden | 直接搜索结果稀少；零散讨论提到"Klarna AI 替代浪潮后实习更难"，**信息匮乏** |
| Blind | 主要是离职 / 裁员相关讨论，实习相关较少 |
| TeamBlind Klarna Logic Test 帖 | 讨论 Kattis test 难度与作弊检测 |
| 1Point3Acres / 牛客 / 知乎 | 中文社区对 Klarna 关注度低；主要是 2018–2020 的 SWE 面经；2024 几乎无 fresh post，**信息匮乏** |

---

## 8. 关键风险 / 提示

1. **AI 替代余波**：客服 / 内容 / 部分前端 / Ops 实习显著减少；想要 stable 实习方向请投 ML / Data Science / Risk / Payments Core。
2. **流程长 + 易 ghost**：候选人体验差是 Klarna 公开的痛点之一；建议同时跑其它公司，主动 follow up。
3. **Kattis Logic Test 是硬门槛**：与算法题完全不同，必须提前练 — 否则 70%+ 候选人在此阶段挂掉。
4. **行为面密集**：Krew 价值观贯穿所有轮次；每位面试官都会从自己角度评 Krew 对齐。
5. **签证支持有限**：实习极少 sponsor；海外候选人需自行确认身份；论文实习可借学校 visa 通道。
6. **IPO 前波动**：2025 起 Klarna 准备 / 启动美国 IPO，headcount 与团队优先级可能随时调整，offer 后入职日期可能被推迟。

---

## 参考链接

- [Klarna Careers](https://www.klarna.com/careers/)
- [Klarna Application Process](https://www.klarna.com/careers/tips-and-tricks/application-process/)
- [Fortune: Klarna stopped all hiring to replace workers with AI (2024-12)](https://fortune.com/2024/12/12/klarna-stopped-all-hiring-replace-workers-with-ai/)
- [TechCrunch: Klarna CEO says it stopped hiring thanks to AI (2024-12)](https://techcrunch.com/2024/12/14/klarnas-ceo-says-it-stopped-hiring-thanks-to-ai-but-still-advertises-many-open-positions/)
- [Klarna CEO admits AI job cuts went too far](https://mlq.ai/news/klarna-ceo-admits-aggressive-ai-job-cuts-went-too-far-starts-hiring-again-after-us-ipo/)
- [Glassdoor Klarna Stockholm Interviews](https://www.glassdoor.com/Interview/Klarna-Stockholm-Interview-Questions-EI_IE389854.0,6_IL.7,16_IM1136.htm)
- [jointaro Klarna SWE Stockholm 2024-07](https://www.jointaro.com/interviews/companies/klarna/experiences/software-engineer-stockholm-stockholm-july-1-2024-no-offer-negative-8dc6b8f5/)
- [jointaro Klarna SWE Stockholm 2023-03](https://www.jointaro.com/interviews/companies/klarna/experiences/software-engineer-sweden-march-1-2023-declined-offer-negative-b1e30e85/)
- [jointaro Klarna EM Stockholm 2025-01](https://www.jointaro.com/interviews/companies/klarna/experiences/engineering-manager-stockholm-stockholm-january-1-2025-declined-offer-neutral-5285e3eb/)
- [InterviewQuery Klarna Data Scientist Guide](https://www.interviewquery.com/interview-guides/klarna-data-scientist)
- [Klarna Logic Test (TSA Test Prep)](https://www.tsatestprep.com/klarna-logic-test/)
- [Klarna Logic Test (Psychometric Success)](https://psychometric-success.com/aptitude-tests/test-types/klarna-logic-test)
- [Nucamp: Top 10 Tech Internships in Sweden](https://www.nucamp.co/blog/coding-bootcamp-sweden-swe-top-10-tech-internships-offered-in-sweden)
- [Levels.fyi Klarna Software Engineer Stockholm](https://www.levels.fyi/companies/klarna/salaries/software-engineer/locations/greater-stockholm)
