# Snowflake (欧洲) — 实习情报

> 美国云数据仓库 / Data Cloud 大厂 (NYSE: SNOW). 欧洲工程实习集中在 **Berlin + Warsaw** 两个 R&D hub, London / Amsterdam / Dublin / Paris 主要是 GTM/Sales/Support, **几乎不开 SWE intern**. OA 用 HackerRank, 题目"比 FAANG 还硬" (DP + 系统类居多), 国际生 friendliness 中等 — Berlin / Warsaw 工程岗对 Blue Card sponsor 友好, 但 entry-level new grad headcount 少, 主路径仍是 intern → return offer.

---

## 1. 公司速览

| 维度 | 信息 |
|---|---|
| 总部 | Bozeman, Montana + San Mateo, CA (US); NYSE: SNOW |
| 成立 | 2012, 2020 IPO, ~7,000+ 员工 (全球) |
| 业务 | Cloud Data Warehouse / Data Cloud / AI Data Cloud (Snowpark, Cortex AI, Iceberg) |
| 欧洲工程 hub | **Berlin (R&D)**、**Warsaw (R&D)**; London/Amsterdam/Dublin/Paris 主要 GTM/Sales |
| 欧洲办公室 | Amsterdam, Berlin, Dublin, London (3 Crown Place EC2A 4EF), Madrid, Milan, Munich, Paris, Stockholm, Warsaw, Zurich [来源 (实际打开过): https://careers.snowflake.com/us/en/locations] |
| 技术栈 | C++ / Java 为底层 query engine 主力, Python (Snowpark/AI), Go, K8s, AWS/Azure/GCP 多云, Apache Iceberg |
| Glassdoor (Berlin SWE Intern) | Intern 4.3/5 (19 reviews), 整体 3.8/5 [来源 (搜索结果): https://www.glassdoor.com/Reviews/Snowflake-Intern-Reviews-EI_IE928471.0,9_KO10,16.htm] |
| 文化 | "Engineering-driven", database internals 强调, 美式直接, Berlin 办公室口碑两极 |

> ⚠️ 关键认知差: Snowflake 在 London / Amsterdam / Dublin **没有 SWE intern**, LinkedIn 上 London 仅 1 个 EMEA Communications Intern, 工程实习 99% 在 **Berlin 或 Warsaw**.

---

## New Grad / Junior 岗位

> 信息丰富度: ⭐⭐⭐ (Berlin / Warsaw Levels.fyi 数据齐全, 但欧洲专门 Graduate Programme 几乎没有, 信息散落)

- **常见岗位名**: Software Engineer (entry, IC1)、Software Engineer Intern (Backend / AI-ML / Infra Automation / Engineering Systems / Document AI)、Research Intern (AI); 全职 entry-level 偶有但放在 general SWE req 里, 无 "Graduate Programme" 品牌
- **欧洲地点 (工程)**: **Berlin** + **Warsaw**; London 工程主要 senior (Java Platform / Metadata IC4+), 不招 entry SWE
- **是否有独立 Graduate Programme**: **No (欧洲)** — Snowflake 全球只有美国总部的 GenSWE (General Software Engineering Program) [来源 (实际打开过): https://careers.snowflake.com/us/en/generalsoftwareengineeringprogram]; 欧洲走"intern → return offer"主路径, ~70-80% 强 intern 转正 [来源 (搜索结果): https://www.getsmartresume.com/article/snowflake-internship-new-graduate-opportunities]
- **非EU签证 (全职)**:
  - **Germany Blue Card (Berlin)**: 2025 阈值 ~€48,300/年 (普通) / €43,759 (短缺职业, IT 包含), Snowflake Berlin IC1 base €94.6K, 远超阈值, **明确 sponsor** (Berlin 办公室是 R&D hub, 大量国际员工)
  - **Poland Blue Card / Type A 工作许可 (Warsaw)**: 阈值低 (~PLN 9,000/月 = €2,100), Snowflake Warsaw IC1 base ~PLN 200K+/年, **可 sponsor**
  - **UK Skilled Worker (London)**: Snowflake UK 有 sponsor license (LinkedIn 全职 senior 岗写"sponsor available"), 但 London 不开 entry-level SWE, 实际利用率低
  - **NL Kennismigrant (Amsterdam)**: Amsterdam 工程岗位极少, 主要 Commercial Solution Engineer, 不是国际生 SWE 路径
  - **Ireland GE Permit (Dublin)**: 同 NL, Dublin 主 Cloud Support 岗, 非 SWE
- **薪资范围 (base, gross/年)** (Levels.fyi 2026-05 更新):
  - **Berlin IC1**: base **€94.6K**, RSU **€43.8K/年** (4年 vest, 25%/年), bonus €4.7K → **TC ~€143K** [来源 (实际打开过): https://www.levels.fyi/companies/snowflake/salaries/software-engineer/locations/berlin-metropolitan-region]
  - **Berlin IC2**: base **€117K**, RSU **€75K/年**, bonus €11.4K → **TC ~€203K**
  - **Warsaw IC1**: base **~PLN 200K** (~$46.5K), RSU ~$15.5K/年, bonus ~$5.9K → **TC ~$68K** [来源 (实际打开过): https://www.levels.fyi/companies/snowflake/salaries/software-engineer/locations/warsaw-metropolitan-area]
  - **London / Amsterdam / Dublin / Paris IC1**: **Levels.fyi 无数据点** (因为这些办公室基本不招 entry SWE)
  - 福利: RSU 是大头 (上市公司, NYSE 流动性好), Berlin/Warsaw 还有 Edenred 餐券 / 健康保险 / 公司股票 ESPP 15% 折扣
- **申请窗口**:
  - 实习 (Berlin/Warsaw): **每年 9-11 月开放次年 summer**, fall intern 9-10 月开放, "early application 拿优势" (US 9-10 月 rolling 与欧洲同步) [来源 (搜索结果): https://www.getsmartresume.com/article/snowflake-internship-new-graduate-opportunities]
  - 全职: Rolling 全年, 主要 H1/H2 各 1 波
- **面试流程差异 vs 实习**:
  - 实习: HackerRank OA (3 题 90-120 分钟) + 2-3 轮技术 (主要 coding)
  - 全职 entry: 同 OA + 4 轮 (2 coding + 1 system design + 1 BQ), Snowflake **"system design 是 IC1+ 必考"** (intern 偶有), 偏 database internals 而非纯 LeetCode
  - 全 panel 4 stages, **2-4 周走完** [来源 (搜索结果): https://www.glassdoor.com/Interview/Snowflake-Berlin-Interview-Questions-EI_IE928471.0,9_IC2622109.htm]
- **录取竞争**: Acceptance rate ~6-8% (interns + new grads), 比 FAANG 略难, OA 砍人凶 [来源 (搜索结果): https://www.getsmartresume.com/article/snowflake-internship-new-graduate-opportunities]; intern 转正受 **team headcount 限制** (无 floating pool), Glassdoor 多条 review 抱怨 "贡献再多, team 没 headcount 就拿不到 return"
- **关键链接**:
  - 官方 University Recruiting: https://careers.snowflake.com/us/en/university
  - GenSWE Program (US only): https://careers.snowflake.com/us/en/generalsoftwareengineeringprogram
  - Berlin 办公室页: https://careers.snowflake.com/us/en/berlin-germany
  - Warsaw 办公室页: https://careers.snowflake.com/us/en/warsaw-poland
  - Levels.fyi Berlin SWE: https://www.levels.fyi/companies/snowflake/salaries/software-engineer/locations/berlin-metropolitan-region
  - Levels.fyi Warsaw SWE: https://www.levels.fyi/companies/snowflake/salaries/software-engineer/locations/warsaw-metropolitan-area
  - Levels.fyi Intern (全球): https://www.levels.fyi/internships/Snowflake/Software-Engineer-Intern/
  - Internship FAQ: https://careers.snowflake.com/us/en/blogarticle/snowflake-internship-faqs

---

## 2. 签证与国际学生政策

- **Berlin (Germany)** — R&D hub 的国际化程度最高, Blue Card 直接 sponsor; 实习身份用学生签证 (Working Student 路径) 或 J-1-style 实习签证, 4-6 个月实习要先确认学校能否开 mandatory internship 证明
- **Warsaw (Poland)** — 多个 intern req (Backend / AI-ML / Document AI / Engineering Systems / Research), 国际生用 student residence permit, 工作时长不超 20h/wk 学期内 / 全职假期, 全职 Blue Card 阈值低易达标 [来源 (实际打开过): https://careers.snowflake.com/us/en/warsaw-poland]
- **London (UK)** — 不开 SWE intern, **避坑**; 全职 senior 才走 Skilled Worker route
- **Amsterdam (NL)** — 工程岗极少 (主要 Commercial Solution Engineer), **不要把 Snowflake Amsterdam 列入 NL 工程实习目标**
- **Dublin (IE)** — 同上, Cloud Support 为主, **非 SWE 实习方向**
- **Paris (FR)** — 同 Amsterdam / Dublin, GTM 为主
- **实习时长**: Berlin posting **明确写 minimum 4 个月, 推荐 6 个月, 最长支持 12 个月**, start date 灵活 (符合德国 mandatory internship + 法国 stage 6 个月习惯) [来源 (搜索结果): https://www.glassdoor.com/Interview/Snowflake-Berlin-Interview-Questions-EI_IE928471.0,9_IC2622109.htm]
- **学校 / 学历**: BSc/MSc 在读, "Computer Science / Computer Engineering / EE / Physics / Math 或相关专业"; PhD 偏 Research Intern (AI) 路径
- **结论**: 国际生 EU 工程实习路径 = **Berlin 或 Warsaw 二选一**, 其他欧洲 office 当作 GTM 公司看待

---

## 3. 面试流程

| 轮次 | 内容 | 时长 | 备注 |
|---|---|---|---|
| 1. Recruiter Screen | 简历 / 动机 / 时间 | 30 min | 英文, 偶问 visa |
| 2. OA (HackerRank) | **3 题, 90-120 分钟**, DP / Graph / String / Array, "比 FAANG 还硬" | 90-120 min | C++ / Java / Python 任意, "correctness + efficiency" 双标准 [来源 (实际打开过): https://medium.com/@sonavikash733/snowflake-berlin-software-engineering-intern-coding-test-0f00a57d422e] |
| 3. Technical Phone 1 | Coding, 类似 OA 难度, 但口述思路 | 60 min | LRU Cache、Range Module、interval merge 等"工程实现型"题 [来源 (实际打开过): https://learncswithus.com/2025/07/21/snowflake-onsite-interview/] |
| 4. Technical Phone 2 | Coding 2 (intern 可能合并) | 60 min | Sliding window / line sweep / TreeMap |
| 5. (全职/IC2+) System Design | log ingestion / distributed buffer / query optimization, 偏 database internals | 60 min | 强调 trade-off, "infra-level thinking" |
| 6. Behavioral / Hiring Manager | 团队冲突、技术决策、ambiguous situation | 45-60 min | 招 culture fit + long-term match |

**整体时长**: Glassdoor 全公司平均 **29 天**; intern fast track ~1 天 [来源 (搜索结果): https://www.glassdoor.com/Interview/Snowflake-Interview-Questions-E928471.htm]; 顺利 candidate 报告 **referral 1/12 → offer 2/7 (约 4 周)** [来源 (搜索结果): https://www.1point3acres.com/bbs/interview/software-engineer-482586.html]

**OA 砍人重灾区**: 3 题 120 分钟必须 AC 2.5+ 才有戏; DP / BFS / DFS 是高频, 边界 case 与时空复杂度都看; 一位 Berlin candidate "全部 AC 但因为只用 Python 没 Java/C++ 被挂", **建议同时备 Java 或 C++** [来源 (实际打开过): https://medium.com/@sonavikash733/snowflake-berlin-software-engineering-intern-coding-test-0f00a57d422e]

---

## 4. 真实面经

| 时间 | 岗位 | 流程 | 题型 | 结果 | 来源 |
|---|---|---|---|---|---|
| 2024 (Berlin) | SWE Intern Berlin | HackerRank OA 120 min × 3 题 | DP 0/1 Knapsack (股票最大利润) / Frequency Counting (可疑用户) / Array Partition (奇偶分区) | 拒 (全 AC 但语言要求 C++/Java) | [Medium](https://medium.com/@sonavikash733/snowflake-berlin-software-engineering-intern-coding-test-0f00a57d422e) (实际打开过) |
| 2026 (US/全球) | SWE 全职 | OA + 3 轮 60 min (Coding + BQ + System Design) | Prime String (DP+sieve), Text Scoring (prefix/suffix), String Transformation (DP+rotation) | 进入 onsite | [LinkJob.ai](https://www.linkjob.ai/interview-questions/snowflake-hackerrank-oa/) (实际打开过) |
| 2025 (中文社区) | SWE Onsite | 2 phone (LRU Cache + Range Module) + 4 onsite (2 coding + behavioral + system design) | Sliding window 最频繁元素 / Interval merge + line sweep / Log ingestion service 设计 | offer | [learncswithus](https://learncswithus.com/2025/07/21/snowflake-onsite-interview/) (实际打开过) |
| 2024 (US Intern) | Core Engineer Intern | Referral 1/12 → Phone 1/14 → R1 2/3 → R2+R3 2/4 → R4 2/6 → Offer 2/7 → Letter 2/15 | OA (Java/C++ 强制) + 3 轮技术 + 1 BQ | offer | [1point3acres](https://www.1point3acres.com/bbs/interview/software-engineer-482586.html) (实际打开过) |
| 2022 (Berlin) | SWE Berlin | Onsite | 候选人描述 "the worst interview experience during my lifetime", hiring manager 态度差 | 拒 | [Glassdoor Berlin](https://www.glassdoor.com/Interview/Snowflake-Berlin-Interview-Questions-EI_IE928471.0,9_IC2622109.htm) (搜索结果) |

**总结**: OA 是最大门槛 (3 题 120 分钟, DP/Graph 高频), Java/C++ 优先; onsite 后 system design 偏 database internals (log ingestion / interval queries / cache), 不是套 grokking-the-system-design 那种 web service.

---

## 5. Offer 案例

| 城市 | Level | Base (年) | RSU (年) | Bonus | TC | 时间 | 来源 |
|---|---|---|---|---|---|---|---|
| Berlin | IC1 (entry SWE) | €94.6K | €43.8K | €4.7K | **~€143K** | 2025-2026 | [Levels.fyi Berlin](https://www.levels.fyi/companies/snowflake/salaries/software-engineer/locations/berlin-metropolitan-region) (实际打开过) |
| Berlin | IC2 | €117K | €75K | €11.4K | **~€203K** | 2025-2026 | 同上 |
| Berlin | IC3 (Senior) | €139K | €162K | €15.1K | **~€316K** | 2025-2026 | [Levels.fyi Germany](https://www.levels.fyi/companies/snowflake/salaries/software-engineer/locations/germany) (实际打开过) |
| Warsaw | IC1 | ~PLN 200K (~$46.5K) | ~$15.5K | ~$5.9K | **~$68K (~PLN 290K)** | 2025-2026 | [Levels.fyi Warsaw](https://www.levels.fyi/companies/snowflake/salaries/software-engineer/locations/warsaw-metropolitan-area) (实际打开过) |
| Berlin | SWE Intern | **~€4,500-4,900/月** ($25.96-28.27/hr) | — | — | — | 2025-2026 | [Levels.fyi Intern](https://www.levels.fyi/internships/Snowflake/Software-Engineer-Intern/) (实际打开过) |
| Warsaw | SWE Intern | **~PLN 10,000-15,000/月** ($2,480-3,900/mo, $14-22/hr) | — | — | — | 2025-2026 | 同上 |
| US (参考) | IC1 | $163K | $63.6K | $12.4K | **~$239K** | 2025-2026 | [Levels.fyi US](https://www.levels.fyi/companies/snowflake/salaries/software-engineer) (实际打开过) |

> Berlin intern 月薪 ~€4,500-4,900 在德国实习市场 **属于第一梯队** (对比: SAP/AWS Berlin 实习 ~€2,000-2,800, Snowflake 显著高); Warsaw 实习虽然按欧洲基数低, 但 PLN 折算购买力很可观.
>
> RSU 4 年 vest 25%/25%/25%/25% (年度 cliff, 之后季度) — Snowflake (NYSE: SNOW) 是上市公司, 股票流动性好但 2024-2026 股价波动大, RSU 实际价值随股价浮动.

---

## 6. 申请渠道与建议

- **官网投递**: https://careers.snowflake.com/us/en/search-results — 按 "Berlin" / "Warsaw" + "Intern" 筛, 9-11 月 peak; 注意大量 req 是 US 的, 投欧洲一定核对 location
- **LinkedIn**: 关注 Snowflake EMEA recruiter (Berlin / Warsaw 各 2-3 名 UR recruiter 主驻), 强制选 location filter
- **内推**: Snowflake 内推系统成熟, 1point3acres 长期有 internal referrer 帖; Berlin / Warsaw R&D 员工较少, 找校友比找 random employee 通过率高
- **CV 重点**:
  - **必有**: 一段 system / infra 项目 (database / distributed / OS / compiler / 编译原理 / Storage 任意一个), Snowflake 极看重 "engineering implementation completeness"
  - SQL 深度 (不是 CRUD, 是 query plan / optimizer 概念)
  - C++ 或 Java 强类型语言 (Python only 是 OA 致命伤)
  - LeetCode Hard DP / Graph 经验 (能写出来 prefix sum, segment tree, union find)
- **同档备选** (欧洲 R&D-heavy 美式数据/云公司):
  - **Databricks** (Amsterdam) — 同赛道竞品, Amsterdam 反而有 SWE intern
  - **Confluent** (London) — Kafka 商业化, London 有 SWE
  - **Elastic** (Amsterdam / 全 remote) — 同搜索/数据
  - **MongoDB** (Dublin / 阿姆) — DB 同赛道
  - **AWS** (Berlin / Dublin) — 云基础设施

---

## 7. 踩坑与社区评价

- **避坑 1: London / Amsterdam / Dublin / Paris 不投 SWE intern** — 这些办公室主要 GTM (Sales / SE / Marketing / Support), LinkedIn London 800+ Snowflake 岗中 SWE intern = 0, 唯一 intern 是 EMEA Communications Intern. 投了浪费时间.
- **避坑 2: OA 强制 Java/C++** — Medium 上一位 Berlin candidate 全 AC 但被拒, 推测因为只用 Python. Posting 写 "Excellent programming skills in C++ or Java"; 准备时不要只刷 Python.
- **避坑 3: Intern 转正 team-based, 没有候选池** — Glassdoor 多条 review 抱怨 "工作再努力, team 没 headcount 就没 return offer"; 选 team 时优先问 "你们今年 headcount 计划".
- **避坑 4: Berlin 办公室口碑两极** — 一条 Glassdoor 2022 review 描述 hiring manager "缺基本面试 / 管理培训, zero psychological safety". 看小红书 / Blind / Glassdoor 对应 team review 再投.
- **正面**:
  - Berlin intern 4.3/5 (19 reviews), 100% recommend, 薪水竞争力强 [来源 (搜索结果): https://www.glassdoor.com/Reviews/Snowflake-Intern-Reviews-EI_IE928471.0,9_KO10,16.htm]
  - 真实 production code (不是 toy project), exposure 强
  - Berlin / Warsaw 工程文化国际化, 英语为工作语言, 德/波 语非必须
- **国际学生友好度**: **Berlin ⭐⭐⭐⭐ / Warsaw ⭐⭐⭐⭐**, 其他欧洲城市 ⭐ (因为没岗); 全职 Blue Card sponsor 顺畅, intern visa 需要学校配合开 mandatory internship 证明.

---

## 8. 所有引用链接

- [Snowflake University Recruiting](https://careers.snowflake.com/us/en/university)
- [GenSWE Program (US only)](https://careers.snowflake.com/us/en/generalsoftwareengineeringprogram)
- [Snowflake Berlin 办公室](https://careers.snowflake.com/us/en/berlin-germany)
- [Snowflake Warsaw 办公室](https://careers.snowflake.com/us/en/warsaw-poland)
- [Snowflake Amsterdam 办公室](https://careers.snowflake.com/us/en/amsterdam)
- [Snowflake Locations 总览](https://careers.snowflake.com/us/en/locations)
- [Snowflake Internship FAQs](https://careers.snowflake.com/us/en/blogarticle/snowflake-internship-faqs)
- [Job Search (全球)](https://careers.snowflake.com/us/en/search-results)
- [Levels.fyi Snowflake 全球 SWE](https://www.levels.fyi/companies/snowflake/salaries/software-engineer)
- [Levels.fyi Snowflake Berlin SWE](https://www.levels.fyi/companies/snowflake/salaries/software-engineer/locations/berlin-metropolitan-region)
- [Levels.fyi Snowflake Germany SWE](https://www.levels.fyi/companies/snowflake/salaries/software-engineer/locations/germany)
- [Levels.fyi Snowflake Warsaw SWE](https://www.levels.fyi/companies/snowflake/salaries/software-engineer/locations/warsaw-metropolitan-area)
- [Levels.fyi Snowflake Intern (全球)](https://www.levels.fyi/internships/Snowflake/Software-Engineer-Intern/)
- [Glassdoor Snowflake Interview](https://www.glassdoor.com/Interview/Snowflake-Interview-Questions-E928471.htm)
- [Glassdoor Snowflake Berlin Interview](https://www.glassdoor.com/Interview/Snowflake-Berlin-Interview-Questions-EI_IE928471.0,9_IC2622109.htm)
- [Glassdoor Snowflake Intern Reviews](https://www.glassdoor.com/Reviews/Snowflake-Intern-Reviews-EI_IE928471.0,9_KO10,16.htm)
- [Glassdoor Snowflake SWE Intern Berlin Salary](https://www.glassdoor.com/Monthly-Pay/Snowflake-Software-Engineer-Intern-Berlin-Germany-Monthly-Pay-EJI_IE928471.0,9_KO10,34_IL.35,49_IM1020.htm)
- [Built In London — Snowflake](https://builtinlondon.uk/company/snowflake)
- [Medium — Snowflake Berlin SWE Intern Coding Test](https://medium.com/@sonavikash733/snowflake-berlin-software-engineering-intern-coding-test-0f00a57d422e)
- [LinkJob.ai — Snowflake HackerRank OA 2026](https://www.linkjob.ai/interview-questions/snowflake-hackerrank-oa/)
- [Prepfully — Snowflake SWE Interview Guide](https://prepfully.com/interview-guides/snowflake-software-engineer-interview)
- [Algo.monster — Snowflake Interview Guide](https://algo.monster/interview-guides/snowflake)
- [learncswithus — Snowflake Onsite 面经](https://learncswithus.com/2025/07/21/snowflake-onsite-interview/)
- [1point3acres — Snowflake Intern 面经 + Timeline](https://www.1point3acres.com/bbs/interview/software-engineer-482586.html)
- [1point3acres — Snowflake tag](https://www.1point3acres.com/bbs/tag/snowflake-2246-1.html)
- [GetSmartResume — Snowflake 2025 Internship & New Grad Guide](https://www.getsmartresume.com/article/snowflake-internship-new-graduate-opportunities)
- [Prosple — Snowflake Graduate Programs](https://prosple.com/graduate-employers/snowflake)
- [Welcome to the Jungle — Snowflake Berlin SWE Intern](https://www.welcometothejungle.com/en/companies/snowflake/jobs/software-engineer-intern_berlin_uhvum33k)
- [LinkedIn — Snowflake 全球 Jobs](https://uk.linkedin.com/company/snowflake-computing/jobs)
- [LinkedIn — Snowflake London Jobs](https://uk.linkedin.com/jobs/snowflake-jobs-london)
