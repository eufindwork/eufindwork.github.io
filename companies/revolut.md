# Revolut (伦敦) 实习情报

> Revolut 是英国估值最高的金融科技 unicorn (~$45B),2024 年获 UK 全牌照 (UK Banking Licence)。以"高强度文化"出名,实习与正职门槛在伦敦市场内属最严苛之一。**面试流程长、压强大、有 IQ 测试,Glassdoor 上文化评论两极分化严重 (Toxic 标签突出)**,申请前需了解。

## 1. 公司速览

| 项目 | 内容 |
|---|---|
| 总部 | 伦敦 (Canary Wharf) |
| 估值 / 员工 | ~$45B / 10,000+ |
| 主营业务 | Banking、Crypto、Wealth、Business、Lending |
| 技术栈 | Kotlin / Java (主)、Python、PostgreSQL、Kafka、AWS、Kubernetes |
| 实习时长 | 10 周 (Rev-celerator: Internship) |
| 申请窗口 | 全年 rolling,Summer cohort 主入口 1-3 月 |
| 实习/视觉口碑 | 高薪、blue chip 名号、CV 加分;但**文化负评极多** |

## 2. 实习岗位与方向

| 岗位类别 | 主要团队 | 备注 |
|---|---|---|
| SWE Intern (Backend) | Banking / Wealth / Crypto / Lending | Kotlin/Java 为主 |
| SWE Intern (Frontend / Mobile) | App / Web | iOS Swift, Android Kotlin, React |
| ML Intern | Risk、Anti-Fraud、Personalization | Python + PyTorch + Spark |
| Data Engineer Intern | Data Platform | Spark、Kafka、ClickHouse |
| Product / Operations Intern | (非 SWE,流程类似) | / |

## 3. 申请要求与签证

- **学历**: 倒数第二年 (penultimate),硕士也接受;Top 校招项目偏好牛剑 / IC / UCL / Warwick / 顶尖海外
- **核心硬条件**: 已有 1+ 段相关实习 (fintech/银行/防务/医疗) → 官方明示无相关实习者很难录取
- **签证**: Revolut Ltd 是 Skilled Worker 持牌雇主,实习生主要用 Student Visa;Grad 转正后 sponsor Skilled Worker
- **薪资 (Glassdoor)**:
  - Intern: 平均 £23,250 / 年 pro-rated,区间 £16.9k - £29.8k
  - Grad SWE: ~£60-70k Total Comp
  - 实习期间 *有薪* (近两年起,早期偶有无薪初阶段反馈)

## 4. 面试流程 (5-6 阶段)

```
1. Recruiter Screen (15-30 min)
   → 背景、动机、为什么 Revolut

2. HackerRank OA (60-90 min)
   → 2-4 题 DSA + SQL + 部分类 IQ / 数学谜题

3. Technical Live Coding (45-60 min)
   → 自己 IDE,实现一个小服务 / 2-3 道算法

4. System Design (针对 Senior;实习生通常合并到 LC + SOLID)
   → 速率限制、事件追踪、聊天系统

5. Team Fit / Bar Raiser (Senior leader)
   → 文化对齐、长期价值、领导力检验
```

总耗时 **3-6 周**,Pass rate 据多数公开样本约 **30-40%**。

## 5. 面经摘录

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|---|---|---|---|---|---|
| 2025-04 | SWE Intern / London | OA (LC + SQL + 类 IQ) + 1 轮 LC + 工程问答 | LC easy-medium、SOLID 哪条最关键、DB 基础 | Offer / Neutral | Jointaro |
| 2024 | Grad Java Backend / London | Recruiter + OA + 视频 + 终轮 | 算法 + Java 内存 + Spring | 拒 | 一亩三分地 |
| 2024 | SWE Intern / London | HackerRank + 1 轮 panel | DSA Medium + 类 IQ 题 | / | Glassdoor |
| 2023-2024 | SWE | 5 stages | DSA + System Design + 文化对齐 | / | efinancialcareers |
| 2024 | 电话面试 / Phone Screen | 招聘官筛 | Why Revolut + 简历深问 | Pass | 一亩三分地 |

## 6. 文化与口碑 — **重点警示**

### Glassdoor / Blind / Reddit 反复出现的负面信号

- **"Toxic culture"** 反复出现 — 高强度、长工时 (60-70h 常态)、PIP (绩效改进) 严苛
- **创始人 Nik Storonsky 严苛风格** — 周报、目标管理极致量化,周末加班默认
- **离职率** — 部分团队 18 个月内更替过半
- **Senior engineer 评价**: "Good pay, but serious problems with culture"
- **ML engineer 评价 (相对正面)**: "Fast-paced, lots of impact"

### 正向信号

- 高薪、品牌响、CV 含金量高
- 项目责任大、有 real ownership
- 转正 / 跳槽下家拿到 IB / FAANG 概率不低

> 综合评价: **"金光闪闪的 CV 烙印,但工作期身心准备要足"**。适合冲学历包装与高强度试炼者,慎选给注重 WLB 同学。

## 7. 重点准备清单

1. **HackerRank 高频**: LC Medium 算法 (Top 150) + SQL Window Function + 1-2 道脑筋急转弯
2. **Java/Kotlin 内存模型**: GC、JVM、并发 (ConcurrentHashMap, ThreadPool)
3. **SOLID 原则深问**: 必备能解释每个 + 真实代码示例
4. **DB 基础**: 索引、事务隔离级别、PostgreSQL EXPLAIN
5. **"为什么 Revolut"**: 必须有具体回答 — 用过产品、关注哪个业务线
6. **行为题**: 反复练习"压力下你怎么完成 deliverable"

## 8. 总结评级

| 维度 | 评级 | 备注 |
|---|---|---|
| 信息丰富度 | 高 | 中英文面经均充足,Glassdoor 数据厚 |
| 申请门槛 | 极高 | 5 stages + 严苛 bar + 需先前实习 |
| Offer 转化预期 | 低 | Pass rate ~30-40% |
| 推荐指数 | 谨慎推荐 | CV 镀金佳,但需提前评估工作强度 |

> **建议**: 把 Revolut 当作"高风险高回报"实习去申。先做完整 LeetCode Top 100 + 至少一段 fintech/bank 同领域实习再投。Offer 拿到后,认真和现 / 前员工聊文化,再决定是否签。

## 信息来源

- [Revolut Internship Program](https://www.revolut.com/internship-programme/)
- [Glassdoor Revolut Intern Salaries London](https://www.glassdoor.com/Salary/Revolut-Intern-Salaries-EJI_IE1176471.0,7_KO8,14_IL.15,21_IM1035.htm)
- [Jointaro Interview Experience](https://www.jointaro.com/interviews/companies/revolut/experiences/software-engineerinternship-london-england-april-5-2025-accepted-offer-neutral-be3e6f8c/)
- [efinancialcareers 5-stage process](https://www.efinancialcareers.co.uk/news/revolut-reveals-its-five-stage-interview-process-for-software-engineers)
- [TechPrep Revolut Interview Guide](https://www.techprep.app/blog/revolut-interview-process)
- [InterviewQuery Revolut Guide](https://www.interviewquery.com/interview-guides/revolut-software-engineer)
- [一亩三分地 Revolut 面经](https://www.1point3acres.com/interview/company/revolut)
- [一亩三分地 Java Backend 面经](https://www.1point3acres.com/interview/thread/1163723)
- [Glassdoor Revolut London Interviews](https://www.glassdoor.com/Interview/Revolut-London-Interview-Questions-EI_IE1176471.0,7_IL.8,14_IM1035.htm)
- [efinancialcareers competitive internships](https://www.efinancialcareers.com/news/revolut-how-to-get-an-internship)
