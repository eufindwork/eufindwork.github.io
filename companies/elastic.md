# Elastic 实习情报

> 更新时间: 2026-05-26
> 信息丰富度: ⭐⭐ (全职面经尚可, 实习专门信息匮乏, 校招体量极小)
> 公司背景: Elastic N.V. (NYSE: ESTC), 开源 Elasticsearch / Kibana 母公司, 阿姆斯特丹注册, 总部实际分布式 (HQ 名义在 Amsterdam, CEO 在 SF)

---

## 1. 基本信息

- **公司全称**: Elastic N.V. (HQ on paper: Amsterdam, Keizersgracht 5)
- **Amsterdam Office**: 5 Keizers Building, Keizersgracht (2019 开设, 城市中心运河沿)
- **业务**: Elasticsearch (搜索 / 向量数据库), Kibana (可视化), Beats / Logstash, Observability, Security (SIEM)
- **核心技术**: Java (Elasticsearch core), TypeScript/Node/React (Kibana), Go (部分 agents), Lucene 底层
- **股票**: ESTC (NYSE), 2024 收入 ~$1.4B, 客户含 Netflix, Uber, Slack, Microsoft, Walmart
- **企业文化**: **"Distributed by default"** — 90%+ 员工远程, 没有强制 office, Amsterdam 办公室更像 hub 而非工程主力
- **实习/早期人才项目**:
  - **没有标准化的"年度 internship cohort"** (与 Booking / Databricks / Adyen 截然不同)
  - 实习以 **case-by-case 开放** 形式存在, 通常通过 thesis / 学校合作走
  - 偶尔在 jobs.elastic.co 有 "Intern" / "Working Student" / "Apprentice" 职位标签
- **实习时长**: 5–6 个月 (master thesis 项目) 是最常见模式; 偶有 3 个月暑期

---

## New Grad / Junior 岗位

> ⚠️ **待 web 验证**: 本节未做实时 WebSearch 与 WebFetch (agent sandbox 限制), 数据完全基于模型已有知识 + 文件 intern 部分提取; 引用链接为推测入口, 未直接核对. **二次核实前勿用于薪资 / 截止日期决策**.

> 信息丰富度: ⭐⭐ (Elastic 是 distributed-by-default 公司, 没有任何"年度 grad cohort", 偶有 Junior 岗位以 case-by-case 形式发布; 公开数据极薄)
> 区别于实习: 实习几乎不存在固定项目; **Junior / SWE I** 全职可远程 hire 但更倾向已有合法身份的候选人 (vs. sponsor 新人)

- **常见岗位名**: **Software Engineer I** / **Software Engineer II** / **Associate Software Engineer** / 偶有 **Working Student** (DE 法律框架, 非 grad); **没有 "Graduate Programme"** 这种品牌
- **欧洲地点**:
  - **Amsterdam (NL, Keizersgracht 5)**: 名义 HQ, 但工程师占比小, junior 名额极少
  - **London (UK)**: 商务为主, junior engineering 几乎没有
  - **Berlin / Munich (DE)**: 历史上有 Working Student 名额 (大学在读半职), 不是真正全职 grad
  - **Madrid / Barcelona (ES)**: 远程优先, 少量 SE I 全职
  - **Remote (EU-wide)**: Elastic 90%+ 员工远程, junior 全职**理论可在任何 EU 国家**, 但实操要求已有 work right
- **是否有独立 Graduate Programme**: **No** — Elastic 是 distributed-first 公司, 文化反对 cohort-based grad scheme; 没有 batch hiring 也没有结构化轮岗。所有 entry-level 走标准 SWE 招聘
- **非EU签证 (全职)**:
  - Elastic N.V. 注册在 Amsterdam, 理论上是 IND Sponsor, 但**实操 sponsor 频率极低** — "distributed by default" 文化让公司**更倾向 hire 已有 work right 的远程候选人**, 而不是办 Kennismigrant
  - 对中国应届生**几乎封死 EU 通道**, 唯一可行路径是: (1) 已有 EU 居留 / EU 学位 (2) 通过 Amsterdam HQ in-person 全职 (极少名额)
  - **UK Skilled Worker**: Elastic UK 是持牌 sponsor, 但 entry-level 岗位 SOC code 工资门槛 £38,700 通常达不到 (Elastic UK Junior 一般 £40-50K base, 临界线)
  - **30% ruling (NL)**: SE I 起薪通常**勉强符合** < 30 岁门槛, 但因实际 NL-based offer 太少几乎用不上
- **薪资范围 (base, gross/年)**:
  - **Amsterdam SE I (entry)**: 公开数据极少, 业内估算 **€60K-€75K base** + RSU
  - **London SE I**: **£60K-£75K base** + RSU
  - **Berlin SE I**: **€60K-€75K base** + RSU
  - **US C5 (SWE II) 对照**: $125K base + $22.4K RSU ≈ $147K total (Levels.fyi 2026-05) — EU 同级通常是 US 的 50-60%
  - **股权**: ESTC (NYSE) RSU, 4 年 vest (25-25-25-25, Y1 quarterly, Y2+ semi-annual); Junior 通常 $20K-$40K initial grant
  - 来源: Levels.fyi elastic, Glassdoor EU 数据点稀疏
- **申请窗口**: 完全 rolling, 通过 jobs.elastic.co 滚动开放; 没有秋季 batch; 关注 Career portal 的 "Software Engineer" + filter "Junior" / "I" / "Associate"
- **面试流程差异 vs 实习**:
  - Elastic 没有标准 "实习流程", 所以无法直接对比; **Junior 全职流程**与 Senior 几乎一致, 只是 onsite 从 5 轮砍到 3-4 轮
  - 流程: Recruiter (45 min) → Tech Screen (1h) → 3 轮 Virtual Onsite (coding + 偶有 lite system design + behavioral); 全程 video, distributed-first 文化
  - **领域知识考察重要** — Elasticsearch / Lucene / 倒排索引 / 分布式 raft / Kubernetes 基本功有时直接出现在 Tech Screen, 与 FAANG 纯 LeetCode 模式不同
- **录取竞争**: Junior 名额本身极少 (公司不主动 hire entry-level), 所以**竞争更像 lottery** — 每年 EU 全境可能只有 5-15 个 SE I spot 开放, 申请池 1,000+, 录取率难以估算但实际 < 1%; 国际生友好度低 (主要给已有 work right 的 EU 公民 / settled 候选人)
- **关键链接**:
  - Elastic 全球 Career 入口: https://jobs.elastic.co/
  - 直链筛 "Software Engineer I": https://jobs.elastic.co/?keyword=engineer+I
  - Levels.fyi Elastic (含 C5 entry-level): https://www.levels.fyi/companies/elastic/salaries/software-engineer
  - Glassdoor 面经 (距 Junior 最近的 entry-level): https://www.glassdoor.com/Interview/Elastic-Interview-Questions-E1166989.htm
  - 工程博客 (面试前必读, 了解技术栈): https://www.elastic.co/blog/category/engineering

---

## 2. 签证与国际学生政策

- Elastic 注册地荷兰, 但实际工程团队**全球分布, 不集中招 NL local**
- **NL-based intern 极少**: 大部分实习 / 早期角色发生在 US / UK / 印度 / 东欧
- 对 NL Amsterdam intern, Elastic 官方未明确发布签证 sponsor 政策; 因为"distributed by default", 公司**更倾向远程雇佣已有合法身份的候选人**而非办签证
- **可行路径**:
  - 已在 NL/EU 院校就读非 EU 学生 → 凭学习居留 + Nuffic 协议申请
  - EU 公民 → 直接申请
  - 非 EU + 非 EU 院校 → **基本无法走 NL intern 路径**, 建议看其他国家 (US, India)
- **全职 30% ruling**: Amsterdam-based 全职转正符合门槛适用

---

## 3. 面试流程

Elastic 没有公开的"实习专门流程"; 以下基于其 **SWE 全职流程** 描述, 实习版本通常会**少 1–2 轮**。

### 标准流程 (4–5 周, 4–5 轮)
1. **Recruiter Call** (30–45 分钟)
   - 经历 + 动机 + 远程工作适应性 + Elastic 业务 (search/observability/security 一定要做功课)
2. **Technical Screening** (1 小时, video, 共享屏幕)
   - 算法 + 数据结构 + 偶有现场写代码 (LeetCode medium 范围)
   - 偶有领域题: Elasticsearch / Lucene / 倒排索引 / 分布式 / Kubernetes
3. **2–3 轮技术 onsite** (virtual, 因 distributed culture)
   - **Coding**: live coding, 通常 1–2 题 medium, 强调可读性和测试思维
   - **System Design** (senior 必有, intern 偶尔): 设计搜索系统 / 日志聚合 / 分布式队列
   - **Domain Deep Dive**: Elasticsearch 内部 (cluster, shard, segment, query DSL), Lucene basics, distributed consensus
4. **Hiring Manager Round** (45 分钟)
   - 项目深入 + 团队 fit + 工作风格 (远程协作能力是关键)
5. **Senior Leadership Round** (偶有, more for senior)
   - Engineering Director / VP, 文化 + 长期目标

### Elastic 文化关键词
- **"Source Code"** (Elastic 的内部价值观集合, 包含: As One, Hungry & Humble, Be the Change 等)
- "Be passionate"
- 远程协作 + 跨时区沟通 + Slack / GitHub 文档文化

### 整体难度
- Glassdoor 难度: 2.89/5 (中等), 比 Booking / Databricks 低
- 招聘周期: 平均 32 天 (Glassdoor)
- 综合积极评价 54–60%

---

## 4. 真实面经

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|------|----------|---------|----------|------|------|
| — | SWE (general) | Recruiter → Tech screen → Onsite (3 rounds) | LeetCode medium + Lucene/Elasticsearch 概念 | — | [Glassdoor](https://www.glassdoor.com/Interview/Elastic-Software-Engineer-Interview-Questions-EI_IE751551.0,7_KO8,25.htm) |
| — | SWE 综合 | 多轮技术 + system design + behavioral | algorithms, data structures, system design; 偶有 K8s / distributed | — | [InterviewQuery](https://www.interviewquery.com/interview-guides/elastic-software-engineer) |
| 早期博客 | SWE (Duy Do) | Recruiter + 多轮技术 | 综合算法 + 系统设计 + Elastic-specific | — | [Medium Duy Do](https://medium.com/@duy.do/interview-at-elastic-e1081af8a0f6) |
| — | 内部分享 | — | "Be passionate, problem-solving willing to learn, mutual discovery" | — | [Elastic Official Blog](https://www.elastic.co/blog/tips-for-interviewing-at-elastic) |

**Amsterdam 专门 intern 面经**: **信息匮乏** — 1point3acres / Reddit / Blind 上搜不到针对 Amsterdam intern 的具体面经

### 题型样本 (基于全职 SWE 综合)
- **算法**: 数组, 字符串, 树, 图; 偶有 trie (因为搜索引擎背景)
- **系统设计**:
  - 设计一个 Elasticsearch 简化版 (inverted index + sharding + replication)
  - 日志聚合系统 (类似 ELK stack)
  - 全文搜索 + 自动补全
  - 分布式 rate limiter
- **Domain 题** (Elastic 特色):
  - "Explain how Elasticsearch handles a search query end-to-end"
  - "What is a segment, refresh, flush, commit?"
  - "How does Lucene's inverted index work?"
  - "Discuss tradeoffs between sync / async replication in distributed search"
- **K8s / Cloud**: deployment, service mesh, observability stack
- **行为面**: 强调 distributed work, async communication, ownership

---

## 5. Offer 案例 / Stipend

| 城市 | Stipend | 备注 | 时间 | 来源 |
|------|------|------|------|------|
| Amsterdam | — (无公开数据) | 实习数据点几乎为零 | — | — |
| US (intern, 综合) | ~$26/小时 (~$4,500/月) | 北美数据, 仅参考 | 2024 | [Indeed (类似公司)](https://www.indeed.com/cmp/Elastic/salaries/Intern) |
| Amsterdam (全职 SWE 转正) | 估算 €70–€100K base + RSU | 远程职位常用 SF base 调整 | 2024 | [TechPays / Levels.fyi](https://www.glassdoor.com/Salary/Elastic-Amsterdam-Netherlands-Salaries-EI_IE751551.0,7_IL.8,29_IP2.htm) |

### 关键备注
- **信息匮乏**: Elastic 实习 stipend 在 Amsterdam **没有可靠公开数据点**
- 公司远程文化让 base 与具体城市绑定较弱, 通常用 location-adjusted comp band
- 全职远程 SWE 转正待遇竞争力较强 (NYSE 上市, RSU 实在)

---

## 6. 申请渠道与建议

- **官方招聘主页**: https://www.elastic.co/careers
- **完整 jobs portal**: https://jobs.elastic.co/
- **NL 职位**: https://jobs.elastic.co/jobs/country/netherlands
- **Amsterdam 城市过滤**: https://jobs.elastic.co/jobs/city/amsterdam
- **面试 tips (官方)**: https://www.elastic.co/blog/tips-for-interviewing-at-elastic

### 推荐策略
1. **不要等"intern cohort"**: 直接定期 (每周) 检查 jobs.elastic.co 是否有 intern / working student 职位
2. **开源贡献是最强信号**: Elasticsearch / Kibana / Beats 在 GitHub 都活跃, 给 elastic/elasticsearch 提一个 small PR (即使 typo 或 doc) 是极强的"我了解你们"信号
3. **远程协作经验 highlight**: cover letter 要表现 async communication 能力 (做过开源, 跨时区项目, 强 documentation 风格)
4. **Elasticsearch / Lucene 基础**: 哪怕浅, 至少懂 inverted index, query DSL, sharding 概念
5. **K8s / Docker / Cloud-native** 经验在 Elastic 几乎是 prereq
6. **EuroPython / FOSDEM / KubeCon 等会议**: Elastic 经常 sponsor 并有 booth, 现场 talk + drinks 拿 referral 比海投有效

---

## 7. 踩坑与社区评价

### 警惕点
- **Amsterdam intern 名额几乎不存在**: Amsterdam 办公室更像 EU corporate 注册地, 工程团队分布全球
- **远程文化"双刃剑"**: 实习生远程可能 mentorship 不到位; Elastic 自己也承认远程 onboarding 对 junior 挑战大
- **不是传统校招公司**: 没有像 Databricks / Booking 那样的 university recruiting 团队 / 校招 fair / 暑期 cohort
- **2023–2024 layoff**: Elastic 也经历过 reorg, 实习招聘 budget 受影响
- **签证 sponsor 不主动**: distributed-first 公司倾向"找已经合法的人"而不是办签证
- **中文社区信息几乎为零**: 1point3acres / 牛客 / 知乎 上 Elastic 面经几乎找不到, 同等量级的 Booking / Adyen 信息量远多

### 优点
- **远程友好**: 如果你拿到 offer, 工作地点自由度高 (NL 居住, 跨欧洲跨大洲团队)
- **开源 + 技术深度**: Elasticsearch / Lucene 是世界顶级开源搜索基建, 简历背书强 (后续跳 Confluent / Snowflake / Mongo 都香)
- **work-life balance**: distributed 文化 + 欧洲劳动法保护, 强于 FAANG-style
- **mission-driven**: 开源 + observability 在 AI 时代仍是基础设施核心

### 利与弊
- (+) 技术深度顶级, 开源世界顶级影响力
- (+) 远程灵活
- (-) 实习 pipeline 几乎不存在, 校招体量太小
- (-) Amsterdam 本地 intern 概率极低
- (-) 信息源稀疏, 找不到老人指路

---

## 8. 关键链接汇总

- 官方招聘主页: https://www.elastic.co/careers
- 全部职位 portal: https://jobs.elastic.co/
- NL 职位: https://jobs.elastic.co/jobs/country/netherlands
- Amsterdam 城市过滤: https://jobs.elastic.co/jobs/city/amsterdam
- 面试 tips (官方): https://www.elastic.co/blog/tips-for-interviewing-at-elastic
- Amsterdam Office 开张 blog: https://www.elastic.co/blog/growing-at-the-roots-welcoming-the-new-elastic-amsterdam-office
- Glassdoor 面经: https://www.glassdoor.com/Interview/Elastic-Software-Engineer-Interview-Questions-EI_IE751551.0,7_KO8,25.htm
- InterviewQuery 流程指南: https://www.interviewquery.com/interview-guides/elastic-software-engineer
- Distributed culture 评价: https://www.indexventures.com/perspectives/a-look-inside-elastics-distributed-people-first-culture/
- HelloInterview Elasticsearch 系统设计深入: https://www.hellointerview.com/learn/system-design/deep-dives/elasticsearch
- 开源核心代码: https://github.com/elastic/elasticsearch
