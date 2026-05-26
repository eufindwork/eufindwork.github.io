# Improbable (伦敦) 实习情报

> Improbable 是 2012 年成立的英国分布式仿真公司,曾因 SpatialOS (大规模多人在线游戏底层) 估值 $2B+。**近年方向频换**: 游戏 → 防务 → 元宇宙 → Web3。2023 年卖掉防务部门 (NOIA Capital);2024-2025 公司重心转向 M-Squared / Somnia 元宇宙与 onchain 游戏。**实习生招聘明显萎缩,公开 2024 / 2025 SWE Intern 入口几乎消失**。**信息匮乏 + 公司前景不确定**,需谨慎。

## 1. 公司速览

| 项目 | 内容 |
|---|---|
| 总部 | 伦敦 10 Bishops Square (Spitalfields) |
| 估值 | 曾达 ~$2B (2017 SoftBank 投资后),近年下行 |
| 主营业务 | M-Squared (元宇宙) + Somnia (onchain) + SpatialOS 维护 |
| 历史 | 2023 出售防务业务 → 2024 投资 7 家公司 → 2025 押注 onchain |
| 技术栈 | Go (主)、C++、Rust、TypeScript / React、Kubernetes、AWS/GCP |
| 实习时长 | 历史上 3-6 个月 paid placement |
| 申请窗口 | 历史上 11-2 月,2024-2025 入口不明确 |

## 2. 实习岗位与方向

> **重要警示**: Improbable 官方 careers 页 2024-2025 公开 SWE Intern 招聘极少;过去主要的 "Defence SWE Internship" 已随防务业务出售而消失。剩下的招聘以 Senior / Mid-level 为主。

| 岗位类别 | 状态 | 备注 |
|---|---|---|
| SWE Intern - Distributed Systems | **历史岗位** (2022-2023 活跃) | SpatialOS networking + state sync |
| SWE Intern - Defence | **已停招** (业务被剥离) | 转去 NOIA Capital 子公司 |
| SWE Intern - MSquared / Web3 | **零星岗位** | 偶有,但更多是新晋 startup spin-off |
| Senior SWE - SpatialOS (London) | **活跃** | 非 intern |

## 3. 申请要求与签证

- **学历**: 倒数第二年本科 / 硕士在读 (CS / Math / Physics)
- **技术要求 (历史)**: C++、Go、Python、Java、JavaScript、TypeScript 至少两门;喜欢游戏 / 分布式 / 仿真者优先
- **签证**: Improbable Worlds Limited 是 Skilled Worker 持牌雇主,但实习生主要用 Student Visa;international students 历史录取过,需当时是 UK 在校生
- **薪资 (历史)**: 月薪 £3,000-£3,500 (3-6 个月 placement)

## 4. 面试流程 (基于 2022-2023 历史信号)

```
1. 简历 + 编程挑战 (HackerRank / CodeSignal)
2. 技术电面 (45 min,DSA + Go 或 C++ 基础)
3. Onsite / Virtual Final (2-3 轮,4-5h)
   - 算法 / 数据结构
   - 系统设计 light (distributed state / consistency 入门)
   - 团队 fit + Behavioural
```

## 5. 面经摘录

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|---|---|---|---|---|---|
| 2022 | SWE Intern Defence / London | OA + 技术 + Onsite | 图算法 + 分布式状态同步 | / | Bright Network |
| 2023 | SWE Intern / London | HackerRank + 技术电面 | LC Medium + 系统设计 light | / | Glassdoor (sparse) |
| 2024 | Senior SWE SpatialOS | 完整 4-5 轮 | Go 并发、分布式一致性 | Offer (信号说明面试 bar 仍在) | Golang Cafe job post |

> **2024-2025 SWE Intern 公开面经几乎为零**;以上以 Senior 信号 + 历史信号代理。**信息匮乏**。

## 6. 文化与口碑 — **警示**

- **正向 (历史)**: 工程 bar 高,过去吸引大量牛剑 / IC 优秀本科;技术深度好;Demo 性强 (大规模仿真)
- **当前挑战**:
  - **多次方向调整 → 内部 morale 起伏大**
  - 2023 出售防务 → 大量工程师走 NOIA
  - 当前重心 Web3 / onchain 对部分 candidate 不吸引
  - 财务: 2023 财年利润 £11m,营收 £66m — 数字健康但相对 2017 高点已大幅缩水
  - Glassdoor 评分近年明显下滑,从 4.0+ 跌至 ~3.3-3.5

> 综合: **品牌"光环"还在,实际机会与方向匹配度需自查**。

## 7. 重点准备清单 (若仍想冲)

1. **Go 语言深度**: goroutine、channel、context、内存模型
2. **分布式一致性入门**: CAP、CRDT、State machine replication 基本概念
3. **C++ for game engines**: 性能优化、缓存友好布局
4. **Web3 / Blockchain (新方向)**: Ethereum、smart contract、L2、Somnia 项目了解
5. **行为题**: 解释自己 "为什么 Improbable" — 必须有诚实理由 (元宇宙 / 仿真 / Web3 兴趣)

## 8. 总结评级

| 维度 | 评级 | 备注 |
|---|---|---|
| 信息丰富度 | 低 (信息匮乏) | 2024-2025 公开实习数据极少 |
| 申请门槛 | 中-高 | 技术 bar 还在,但岗位少 |
| Offer 转化预期 | 低 (因岗位极少而非难度) | 实习 cohort 近乎消失 |
| 推荐指数 | **谨慎/不推荐** | 公司方向不稳;品牌价值衰减中 |

> **建议**: 把 Improbable 当作"机会型"申请。如果开了 SWE Intern 入口,可以一搏 (品牌力还有);但不要把它列在 Top 3,不要为它牺牲其他 deadline。优先冲 Confluent / Arm 等"硬科技稳定品牌"。

## 信息来源

- [Improbable Careers](https://www.improbable.io/careers)
- [Improbable Wikipedia](https://en.wikipedia.org/wiki/Improbable_(company))
- [Improbable Defence Sale News - Sifted](https://sifted.eu/articles/improbable-sell-defence-arm-news)
- [Improbable Defence Sold to NOIA - Shephard Media](https://www.shephardmedia.com/news/training-simulation/improbable-defence-confirms-sale-of-uk-business/)
- [Bright Network Improbable SWE Intern 2022](https://www.brightnetwork.co.uk/graduate-jobs/improbable/software-engineer-internship-london-2022)
- [Bright Network Defence SWE Intern](https://www.brightnetwork.co.uk/graduate-jobs/improbable/software-engineer-defence-internship-london-2022)
- [Improbable Senior SWE SpatialOS - Golang Cafe](https://golang.cafe/job/senior-software-engineer-spatialos-with-improbable-london-uk)
- [Glassdoor Improbable Jobs London](https://www.glassdoor.com/Jobs/Improbable-software-engineering-intern-London-Jobs-EI_IE746448.0,10_KO11,38_IL.39,45_IC2671300.htm)
- [Built In London Improbable Profile](https://builtinlondon.uk/company/improbable)
