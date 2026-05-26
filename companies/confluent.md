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
