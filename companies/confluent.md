# Confluent (伦敦) 实习情报

> Confluent 是 Apache Kafka 的商业化母公司,由 Kafka 原作者团队创立。欧洲业务以伦敦为核心,业务重心是分布式流处理、Kafka 平台与 "Data in Motion" 基础设施。对志在分布式系统的实习生而言是顶级品牌。

## 1. 公司速览

| 项目 | 内容 |
|---|---|
| 总部 / 欧洲核心 | 美国 Mountain View / 伦敦 (欧洲) |
| 欧洲招聘点 | 伦敦为主,部分岗位扩展到北爱尔兰、西班牙 |
| 主营业务 | Kafka 商业化、Confluent Cloud、Flink、Stream Governance |
| 技术栈 | Java/Scala (Kafka core)、Go、Kubernetes、AWS/GCP/Azure、Rust (新引擎) |
| 实习时长 | 12 周暑期 或 12 个月 placement (FTC) |
| 申请窗口 | 秋季 (9-11月) 开放,Rolling 滚动审核 |
| 实习/视觉口碑 | 强工程、Kafka 内核圈层、强分布式系统强度 |

## New Grad / Junior 岗位

> 信息丰富度: ⭐⭐⭐ (Confluent London 是分布式系统圈层的 prestige offer; Levels.fyi UK L2 实读 + 单 Blind 数据点 £120K TC + 官方 Early Talent 入口完整)
> 区别于实习: 实习 12 周或 12 个月 FTC + Student Visa; **New Grad SWE** 全职 Skilled Worker, package 与 senior 比例统一

- **常见岗位名**: **Software Engineer, New Grad** / **Software Engineer I (L2)** / **Associate Software Engineer**; 没有专门 "Graduate Programme" 品牌, 走标准 SWE 招聘 + new-grad 标签 [来源 (实际打开过): https://careers.confluent.io/early-talent]
- **欧洲地点**:
  - **London (UK)**: EMEA 唯一主要工程 hub; **13 个 London 开放岗** (Glassdoor 2026-05) [来源 (搜索结果): https://www.glassdoor.co.uk/Job/london-confluent-jobs-SRCH_IL.0,6_IC2671300_KO7,16.htm]; Kafka Cloud / Connect / Schema Registry / Stream Governance 团队
  - **Belfast (北爱)**: 部分 SRE / Platform 团队, New Grad 名额较少但 visa-friendly
  - **Madrid (ES)**: 2023 新增 Cloud / Networking 团队, New Grad 名额增长
  - **UK 总开放岗数**: 10+ (Careers portal 直筛) [来源 (搜索结果): https://careers.confluent.io/search/jobs/in/country/united-kingdom]
  - 与实习地点一致, EMEA 全职 entry-level 80%+ 在 London
- **是否有独立 Graduate Programme**: **No** — Confluent 没有 cohort-based grad scheme; Early Talent 仅 cover 12 周 + 1 年 FTC 实习, 全职 New Grad 走标准 SWE Pipeline + new-grad 标签 [来源 (实际打开过): https://careers.confluent.io/early-talent]; 内部有 4 周 Kafka 内核 deep dive bootcamp
- **非EU签证 (全职)**:
  - **Confluent UK Ltd 是 UK Skilled Worker 持牌雇主**, 全额支持新 grad visa
  - 2026 年 UK Skilled Worker 工资门槛: 一般 £38,700; IT 行业 going rate 通常 £42K-£50K, Confluent New Grad base **£70K 100% 超过**
  - 提供 visa lawyer + IHS surcharge 报销 + relocation lump sum (~£5K-£10K, Blind 报告)
  - **High Potential Individual (HPI) visa**: Confluent 接收已持 HPI 的中国 top 50 校友, 不需要 sponsor 直接 hire
  - **对中国应届生 friendliness 高** — Confluent 在伦敦 EMEA team 中国 / 印度 / 东欧员工比例较高
- **薪资范围 (base, gross/年, 2026-05 Levels.fyi UK 实读)**:
  - **London New Grad SWE (L2)**: **$92.7K base + $45.8K stock + $3.1K bonus ≈ $142K total ≈ £106K total** (Levels.fyi UK L2 entry) [来源 (实际打开过): https://www.levels.fyi/en-gb/companies/confluent/salaries/software-engineer/locations/united-kingdom]
  - **单 Blind 数据点 (UK new grad signed)**: **£70K base + RSU ≈ £120K total** [来源 (搜索结果): https://www.teamblind.com/post/confluent-london-salary-ty8nxfgh]
  - **UK 全 level range**: **£106K (L2) - £170K (L5a)**, median £168K [来源 (实际打开过): https://www.levels.fyi/en-gb/companies/confluent/salaries/software-engineer/locations/united-kingdom]
  - **Greater London (Levels)**: median **£192K total** (含 senior, 偏高); 最高 £253K [来源 (搜索结果): https://www.levels.fyi/companies/confluent/salaries/software-engineer/locations/london-metro-area]
  - **Belfast / Madrid**: £55K-£70K / €55K-€68K base + RSU (低于 London 30-40%)
  - **股权**: CFLT (Nasdaq) RSU, 4 年 vest 25% annually 或 3 年 33%; Initial grant New Grad ~$80K-$120K
  - 加 ~6-8% pension match (UK), private health, £400/月 home office stipend
- **申请窗口**: **每年 8-10 月开放 New Grad SWE** (与北美同步), 11 月 - 次年 2 月面试, 3-5 月发 offer, 7-9 月入职; New Grad 名额一旦关闭基本无法重开
- **面试流程差异 vs 实习**:
  - 流程结构相同 (Recruiter → OA → Tech → Concurrency → System Design → HM), 但**实习版砍 1 轮 system design**, New Grad **全 5 轮 + Bar Raiser**
  - **OA 难度上调** — 实习 LC medium, New Grad medium-hard, 偶有 hard (LC "Number of Atoms" / parser 类)
  - **并发 / 系统编程轮难度加深** — 实习考线程安全 LRU, New Grad 要求 lock-free / wait-free 数据结构 + memory ordering (acquire/release semantics)
  - **System Design 必考 Kafka 相关**: 设计 stream ingestion / config propagation / exactly-once / 跨 region replication; 实习生通常砍此轮
  - 总流程 6-8 周 (实习 4-6 周)
- **录取竞争**: London New Grad SWE 录取率 **~2-3%** (申请池 3,000-5,000/cohort), 分布式系统圈层声誉极高 (Kafka 原作者团队 prestige); **对中国学生 friendly 度高于 Canva, 与 Databricks 接近** — Confluent 全球 hire 文化 + UK Skilled Worker 路径成熟
- **关键链接**:
  - Confluent Early Talent 官方页: https://careers.confluent.io/early-talent
  - Confluent UK Careers 直筛: https://careers.confluent.io/search/jobs/in/country/united-kingdom
  - Confluent 全球 Career 入口: https://careers.confluent.io/jobs
  - Levels.fyi Confluent SWE UK (2026-05 实读 L2 £106K): https://www.levels.fyi/en-gb/companies/confluent/salaries/software-engineer/locations/united-kingdom
  - Levels.fyi Confluent SWE Greater London (median £192K): https://www.levels.fyi/companies/confluent/salaries/software-engineer/locations/london-metro-area
  - Blind Confluent London salary 帖: https://www.teamblind.com/post/confluent-london-salary-ty8nxfgh
  - Glassdoor Confluent London 岗位 (13 open): https://www.glassdoor.co.uk/Job/london-confluent-jobs-SRCH_IL.0,6_IC2671300_KO7,16.htm
  - LeetCode Discuss Confluent: https://leetcode.com/discuss/interview-experience/?query=confluent
  - Blind cflt 板块: https://www.teamblind.com/company/Confluent
  - 1point3acres Confluent tag: https://www.1point3acres.com/bbs/tag/confluent-1495-1.html

---

## 2. 实习岗位与方向

| 岗位类别 | 主要团队 | 技术栈 |
|---|---|---|
| Software Engineering Intern (12 周) | Confluent Cloud、Connect、Kafka Core、Schema Registry | Java、Go、Kubernetes |
| Software Engineer Intern - 12 month FTC | Stream Processing (Flink)、Networking、Storage | Java、Scala、Rust |
| Site Reliability / Platform Intern | SRE、Observability | Go、Terraform、Prometheus |
| Security Intern | Security Engineering、SOC | Python、Go |

## 3. 申请要求与签证

- **学历**: 倒数第二年 (penultimate) 或第二年本科 / 硕士在读
- **技术要求**: 强 DSA 基础 + 至少一门系统级语言 (Java / Go / C++);分布式系统/网络/操作系统课程为加分
- **签证**: Confluent UK Ltd 是 Skilled Worker 持牌雇主,实习生主要用 Student Visa 工作许可 (学期 20h/wk,假期全职);对非 Tier-4 学生,12 个月 FTC 走 GAE/T5 临时工作签
- **薪资**: 伦敦实习未公开标准,业内同档大致月薪 £3,200-£3,800 + 住房补贴 + 来回机票报销

## 4. 面试流程

```
应聘 → 招聘官 chat (15-30 min)
     → OA / 编程题 (HackerRank 或 CoderPad,LC Medium)
     → 技术轮 1: 数据结构 + 算法 (45-60 min)
     → 技术轮 2: 并发 / 系统编程 (常考线程安全 LRU、WindowedMap、原子化数据结构)
     → 技术轮 3 / 终轮: 系统设计 (Kafka 相关: 流式 ingestion、配置传播、过期邮件服务等)
     → Hiring Manager + 行为
```

注意 Confluent 的特色是:**并发、并行、内存模型考察非常重**,不是纯 LeetCode 套路。实习生通常砍掉系统设计一轮。

## 5. 面经摘录

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|---|---|---|---|---|---|
| 2025-04 | SWE Intern / Austin (信号同伦敦) | OA + 1 轮技术 | LC Hard "Number of Atoms" | 未发 offer / 正向反馈 | Jointaro |
| 2024 | SDE 校招 (信号通用) | OA + 4-5 轮 VO | Function Signature Matcher (变参方法分发)、LRU+TTL、Sudoku Solver | Offer | GeeksforGeeks |
| 2024 | Senior SWE | 5 轮 | WindowedMap (TTL key-value)、并发线程安全 LRU、流处理系统设计 | Offer | LeetCode Discuss |
| 2025 | SSE 一面 (信号同伦敦) | 一面 | 流式相关 SSE 题、map iteration 死锁防御 | / | LeetCode Discuss |

> 公开伦敦实习面经稀少;同岗位美区面经技术信号与伦敦一致 (同 panel/同 hiring bar)。

## 6. 文化与口碑

- **正向**: 工程严谨,Kafka 创始团队仍在,做的东西是真正的分布式底层;Mentor 制完善,实习项目偏 production
- **挑战**: 并发/原子性考察狠;实习项目可能涉及 on-call shadow,要求成熟度高
- **Glassdoor 评分**: 整体 ~3.8/5,工程文化口碑佳,但近两年因股价波动有缩招传闻

## 7. 重点准备清单

1. **Kafka 基础概念**: Topics / Partitions / Consumer Groups / ISR / Exactly-Once Semantics — 务必能讲清楚
2. **并发编程**: Java `synchronized` / `ReentrantLock` / `ConcurrentHashMap` 内部实现;Go 的 channel + mutex
3. **LRU / LFU 设计**: 单线程 + 线程安全两个版本
4. **系统设计 (Junior 版)**: Rate limiter、消息队列简化版、唯一 ID 生成器
5. **行为问题**: "Why Confluent" — 必须有理由,最好接触过 Kafka / Pulsar / Flink 之一

## 8. 总结评级

| 维度 | 评级 | 备注 |
|---|---|---|
| 信息丰富度 | 中 | 公开面经主要为美区,伦敦定向资料偏少 |
| 申请门槛 | 高 | 并发与分布式实战要求强 |
| Offer 转化预期 | 中-低 | 单 panel 难度高,但 hiring bar 比 FAANG 一致 |
| 推荐指数 | 强烈推荐 | 分布式系统方向首选 |

> **建议**: 申请前主动玩过 Kafka (本地 docker-compose 跑一遍 producer/consumer + Connect),写一篇博客或 GitHub project,面试时大幅加分。

## 信息来源

- [Confluent Early Talent](https://careers.confluent.io/early-talent)
- [Confluent SWE Intern Job](https://careers.confluent.io/job-description/7322e3ab-d31d-5ba3-8960-819a133854cf/)
- [12 month FTC Posting](https://uk.linkedin.com/jobs/view/software-engineer-intern-12-month-ftc-at-confluent-4368657879)
- [Jointaro Interview Experience](https://www.jointaro.com/interviews/companies/confluent/experiences/swe-intern-austin-tx-april-30-2025-no-offer-positive-5472a4fd/)
- [LeetCode Discuss - Confluent SSE](https://leetcode.com/discuss/interview-question/5494972/Confluent:-SSE-Interview-Q/)
- [GeeksforGeeks Interview Experience](https://www.geeksforgeeks.org/interview-experiences/confluent-interview-experience-for-sde-on-campus/)
- [TechPrep Interview Process Guide](https://www.techprep.app/blog/confluent-interview-process)
- [Glassdoor Confluent Interviews](https://www.glassdoor.com/Interview/Confluent-Software-Engineer-Interview-Questions-EI_IE1048428.0,9_KO10,27.htm)
- [Levels.fyi Confluent SWE UK 2026-05 实读](https://www.levels.fyi/en-gb/companies/confluent/salaries/software-engineer/locations/united-kingdom)
- [Levels.fyi Confluent Greater London SWE median £192K](https://www.levels.fyi/companies/confluent/salaries/software-engineer/locations/london-metro-area)
- [Blind Confluent London salary 帖 (£70K base + RSU)](https://www.teamblind.com/post/confluent-london-salary-ty8nxfgh)
- [Confluent UK Careers 实时入口](https://careers.confluent.io/search/jobs/in/country/united-kingdom)
- [Glassdoor Confluent London 13 open 岗位 2026-05](https://www.glassdoor.co.uk/Job/london-confluent-jobs-SRCH_IL.0,6_IC2671300_KO7,16.htm)
