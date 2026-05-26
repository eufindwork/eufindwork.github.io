# Uber Amsterdam 实习情报

> 更新时间: 2026-05-26
> 信息丰富度: ⭐⭐⭐⭐ (全职面经丰富, 实习面经偏少但 Uber 官方有公开 EMEA intern blog)
> 公司背景: Uber Technologies Inc. (NYSE: UBER) 阿姆斯特丹 EMEA HQ, 主要负责 Marketplace / Maps / Payments / Mobile / Safety 等产品 & 工程

---

## 1. 基本信息

- **公司全称**: Uber Technologies, Inc.
- **EMEA HQ**: Amsterdam, Mr. Treublaan 7 (Oosterdokseiland 附近, 中央车站可步行)
- **EMEA 工程其他 hubs**: Aarhus (丹麦, 数据基础设施 + Grail), Sofia (保加利亚, mobile/web), Lisbon (新增, Marketplace)
- **业务**: Mobility (打车), Delivery (Uber Eats), Freight (货运), Ads
- **股票**: UBER (NYSE)
- **实习岗位类型 (EMEA SWE)**:
  - **Software Engineer Intern** (Amsterdam / Aarhus / Sofia 三选一, 但 Amsterdam 名额最少)
  - **Machine Learning Intern** (常见 team: Marketplace, Search, Fraud)
  - Data Scientist / Analytics Intern
  - Strategic Finance / Operations Intern (非工程)
- **实习时长**: **3 或 6 个月** (常见 6 个月, 部分 thesis 项目 9 个月)
- **申请窗口**: 通常 8–10 月开放, 11–12 月截止, 次年春/夏入职; 错过窗口几乎只能等下一年

---

## 2. 签证与国际学生政策

- Uber 在 NL 是 **IND recognised sponsor**, 对 highly skilled migrant 支持成熟
- **实习生**:
  - 在 NL 院校就读 → 学习居留即可
  - 其他欧洲院校 (EU 籍) → 无需签证, 注册 BSN 即可
  - 非 EU + 不在 NL 院校 → 需 GVVA, Uber 支持但**优先 6 个月以上 thesis 项目** (短期暑期 SWE intern 拒绝率较高)
- **关键点**: Uber EMEA intern blog 案例中 **Yukie Nomiya 是罗马大学 (Italy, EU)** 的 CS 学生 → EU 学生最容易拿 Amsterdam intern; 非 EU 学生**最佳路径是先拿 NL 院校学籍**
- **Relocation**: 实习生通常提供单程机票 + 1 个月企业管家公寓; 后续自己找房
- **30% ruling**: 实习生**不适用**; 全职转正符合门槛适用

---

## 3. 面试流程

Uber 是欧洲 mobility/delivery 中**门槛最高的实习**之一, 流程明显比 ASML / TomTom 严格, 接近美国 FAANG 但稍轻。

### 实习标准流程 (5–6 周, 5 轮)
1. **Recruiter Screen** (30 分钟, HR, 动机 + 经历 + 项目匹配)
2. **Online Assessment (CodeSignal)**
   - 通常 70–90 分钟, 3 题
   - 题型: dynamic programming, linked list, number base conversion (典型组合)
   - 平台是 CodeSignal, 支持运行 / 调试
3. **Hiring Manager Round** (45 分钟)
   - 项目经历 deep dive, 文化适配, why Uber, why Amsterdam
   - 给问问题机会, 强烈建议提前研究目标 team
4. **Coding Round** (60 分钟, virtual, CodeSignal/CoderPad)
   - LeetCode medium (常见 array / hashmap / graph BFS-DFS / interval / tree)
5. **Low-Level Design (LLD) Round** (60 分钟, intern 偶尔有)
   - 设计一个小系统 (e.g., parking lot, ride matching, rate limiter)
6. **Behavioral / Culture Round** (45 分钟)
   - Uber 价值观: "We build globally, we live locally", "We are customer obsessed", "We see issues, we own them"
   - STAR 法回答

### 流程特征
- **Recruiter 主动给准备资料**: 通常会发给候选人一份准备指南 (各轮考点说明), 这点 EMEA Uber 做得比其他公司透明
- **风格 conversational**: 多份报告评价"interview 像 mutual discussion 而非考核"
- **接受率低**: Uber 整体 SWE intern offer rate < 5%

---

## 4. 真实面经

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|------|----------|---------|----------|------|------|
| 2022-07 → 2023-01 | SWE Intern → SWE I / Amsterdam | 6 个月实习 → 转正 Driver Earnings Experience team | — (blog 未给具体题) | Offer | [Uber EMEA Intern Blog](https://jobs.uber.com/en/people-stories/life-at-uber/inside-uber-s-software-engineering-internship-in-emea/) |
| 2021-09 | SWE Intern → SWE II / Aarhus → mentor | 实习生 → 现 UCS team mentor | distributed systems | Offer | [Uber Blog](https://www.uber.com/blog/uber-swe-intern-emea/) |
| 2023 (summer) | SWE Intern / Aarhus | 3 个月 → 转正 | leetcode medium + behavioral | Offer | [Uber Blog Tips from Aarhus](https://www.uber.com/blog/ace-an-uber-engineering-interview-tips-from-aarhus/) |
| — | Senior SDE / Amsterdam | HR + HM + take-home (7 天) + 2-3 onsite | take-home 设计 + system design | Offer (multi-company) | [Aikikode Blog](https://aikikode.me/blog/interview-preparation-2022/) |
| 2024-ish | SWE / Amsterdam | 4-5 轮 (HR + HM + 多个技术) | DP, linked list, base conversion (CodeSignal); LLD; behavioral | Multiple reports on Glassdoor | [Glassdoor](https://www.glassdoor.com/Interview/Uber-Amsterdam-Interview-Questions-EI_IE575263.0,4_IL.5,14_IM1112.htm) |
| — | SWE / Amsterdam | LeetCode 风格 + system design | DP, linked list, basic conversions; LLD: parking lot 类 | — | [Blind](https://www.teamblind.com/post/Uber-Amsterdam-interview-experience-CYzHAUmP) |
| — | SWE Intern / GeeksforGeeks | OA 3 题: DP + linked list + base conv | — | — | [GFG](https://www.geeksforgeeks.org/interview-experiences/uber-interview-experience-for-swe-intern/) |
| — | Tips from Aarhus | — | 建议: 多刷 LeetCode medium, 提前准备 STAR 故事 | — | [Uber Blog](https://www.uber.com/blog/ace-an-uber-engineering-interview-tips-from-aarhus/) |

### 真实题型样本 (来自社区聚合)
- **OA (CodeSignal)**: DP (e.g., longest increasing subsequence), Linked list reverse / merge, Base conversion (binary/octal/hex)
- **Coding**: LeetCode medium 数组 / 字符串 / 树 / 图; 偶有 trie / sliding window
- **LLD**: ride matching, rate limiter, in-memory cache, food delivery dispatcher
- **System Design (senior)**: distributed rate limiter, real-time fraud detection (实习一般不到这一步)
- **Behavioral**: "Tell me about a time you owned a problem", "Describe a conflict with a teammate", "Why Uber" (必备)

---

## 5. Offer 案例 / Stipend

| 城市 | Stipend (gross/月) | 备注 | 时间 | 来源 |
|------|------|------|------|------|
| Amsterdam | **€1,800–€2,800/月** intern (估算; Glassdoor 中位 ~€820/月 数据可疑, 见下) | SWE intern | 2023–2024 | [Glassdoor](https://www.glassdoor.com/Salary/Uber-Intern-Amsterdam-Salaries-EJI_IE575263.0,4_KO5,11_IL.12,21_IM1112.htm) |
| Amsterdam | 平均 **€44,800/年** tech intern total comp (1 数据点) | Tech | 2023 | [TechPays](https://techpays.com/europe/netherlands/uber/amsterdam/intern-level) |
| Amsterdam | 估算总包 €20K–€30K/年 含 stock/bonus | — | 2024 | [Glassdoor](https://www.glassdoor.com/Salary/Uber-Intern-Amsterdam-Salaries-EJI_IE575263.0,4_KO5,11_IL.12,21_IM1112.htm) |
| Amsterdam (Ops Intern) | 平均 €22,800/年 | Operations | 2023 | [TechPays](https://techpays.com/europe/netherlands/uber/amsterdam/ops/intern-level) |
| Amsterdam (SWE 全职 II 转正) | €129K–€186K total (Levels.fyi 中位) | full-time | 2024 | [Levels.fyi](https://www.levels.fyi/companies/uber/salaries/software-engineer/levels/software-engineer-ii/locations/netherlands) |

### 关键备注
- Glassdoor 报的 "€820/月" 与 TechPays 的 "€44,800/年" 数据冲突大. 社区主流估算 **€2,000–€2,800/月 gross** 比较合理 (匹配 Booking / Databricks 同级别)
- 转正后 Uber Amsterdam SWE II 是欧洲最高薪科技岗之一 (Levels.fyi 中位 €129K+), 30% ruling 后 take-home 极强
- Uber EMEA intern 与全职 conversion rate 较高 (blog 中 Yukie 和 Eleonora 都已转正)

---

## 6. 申请渠道与建议

- **官方早期人才页**: https://www.uber.com/us/en/careers/teams/university/
- **EMEA SWE 实习介绍 blog**: https://jobs.uber.com/en/people-stories/life-at-uber/inside-uber-s-software-engineering-internship-in-emea/
- **Aarhus 面试 tips (Uber 官方)**: https://www.uber.com/blog/ace-an-uber-engineering-interview-tips-from-aarhus/
- **LinkedIn**: 直接搜 "Uber Amsterdam Software Engineer Intern", recruiter 经常发起对话

### 推荐策略
1. **早申请**: 8–10 月开放, **优先在 9 月初投递** (Uber recruiter 明确说 priority window 是 10 月前)
2. **LeetCode**: 公司 tag 刷至少 50 题 (medium 为主, 偏向 DP / linked list / array)
3. **CodeSignal 练习**: 提前用同样平台练 3 题 70 分钟模式
4. **目标 team**: 申请时可指定 team (Mobility, Delivery, Maps, Safety) — Amsterdam 实习更偏 Marketplace / Driver Experience / Maps
5. **行为面**: 准备 6–8 个 STAR 故事映射 Uber values
6. **EU vs 非 EU**: 非 EU 学生**强烈建议先拿 NL/EU 院校学籍** (TU Delft / UvA / TU/e), 短期暑期非 EU intern 拒签风险高

---

## 7. 踩坑与社区评价

### 警惕点
- **EMEA 名额少**: 全球 SWE intern 大部分在 SF / Bellevue / Sunnyvale; EMEA 三个 hub (Amsterdam + Aarhus + Sofia) 加起来年招几十人量级
- **Amsterdam 比 Aarhus / Sofia 更难拿**: Amsterdam 是 EMEA HQ, 资历要求更高, recruiter 经常引导到 Aarhus
- **2022–2023 hiring freeze 影响**: 2022 年 Uber 全球冻招, 2023 才恢复, 2024 又收紧, 实习 quota 波动大
- **流程长**: 5–6 轮 5–6 周, 不适合急 offer
- **签证拒签风险 (非 EU + 非 NL 院校)**: 部分报告 recruiter 在第一通电话就告知"我们只能 sponsor NL 在校学生"

### 优点
- **品牌强**: Uber 简历背书 EU/US 通吃
- **技术栈现代**: Go, Python, Java, Kotlin, Swift, distributed systems
- **mentorship 制度成熟**: 1 manager + 1 mentor + 同期 cohort, 6 个月足够做有意义的 production project
- **转正待遇好**: 30% ruling + RSU + Amsterdam 文化氛围
- **公司公开度**: Uber Engineering Blog 是行业顶级技术博客 (Cadence, Schemaless, Peloton, Aresdb 等)

### 利与弊
- (+) Amsterdam 实习能直接进 EMEA HQ, 经验含金量极高
- (+) intern → grad → SDE I → SDE II 通道顺畅
- (-) EU 名额少, 非 EU 学生路径窄
- (-) 流程长且竞争极激烈, 整体接受率 < 5%

---

## 8. 关键链接汇总

- 大学招聘入口: https://www.uber.com/us/en/careers/teams/university/
- EMEA SWE Intern Blog: https://jobs.uber.com/en/people-stories/life-at-uber/inside-uber-s-software-engineering-internship-in-emea/
- Aarhus 面试 tips: https://www.uber.com/blog/ace-an-uber-engineering-interview-tips-from-aarhus/
- Uber Engineering Amsterdam team: https://www.uber.com/blog/uber-engineering-amsterdam-team-profile/
- Uber Engineering Blog: https://eng.uber.com / https://www.uber.com/blog/
- Glassdoor 面经: https://www.glassdoor.com/Interview/Uber-Amsterdam-Interview-Questions-EI_IE575263.0,4_IL.5,14_IM1112.htm
- Blind 讨论: https://www.teamblind.com/post/Uber-Amsterdam-interview-experience-CYzHAUmP
- Levels.fyi NL: https://www.levels.fyi/companies/uber/salaries/software-engineer/levels/software-engineer-ii/locations/netherlands
- Pragmatic Engineer (level changes): https://blog.pragmaticengineer.com/uber-engineering-levels/
