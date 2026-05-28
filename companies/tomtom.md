# TomTom 实习情报

> 更新时间: 2026-05-26
> 信息丰富度: ⭐⭐⭐ (官方流程页清晰, 但实习面经稀疏, 公司处于战略收缩期)
> 公司背景: 老牌荷兰导航/地图公司, 上市 (AMS: TOM2), 商业模式从 GPS 设备转为 B2B 地图数据 (汽车厂 / Apple / Volkswagen / Renault)

---

## 1. 基本信息

- **公司全称**: TomTom International B.V.
- **HQ**: Amsterdam, De Ruijterkade 154 (中央火车站旁, IJ 河边)
- **NL 其他**: Eindhoven 办公室 (部分 mapmaking)
- **全球办公室**: Berlin (主要工程), Łódź (Poland, 大量工程), Madrid, Milan, Munich, Belgrade, Pune (印度, 地图制作和算法), Detroit, Bangkok 等
- **业务**: B2B 地图 (HD Maps for 自动驾驶), 导航 SDK, traffic, EV charging data; **PND 消费设备业务已显著萎缩**
- **股票**: TOM2 (Amsterdam, Euronext), 2024 报 €17M 亏损, 1 年股价 -26.7%
- **实习岗位类型**:
  - **Software Engineer Intern** (Amsterdam / Berlin / Łódź)
  - **Data Engineer Intern** (Amsterdam, 地图数据管道, Python/Spark/Scala)
  - **Map Data Sourcing Intern** (Berlin, 地图采编)
  - Data Scientist Intern (Madrid)
  - Marketing / Communications / Finance / Web Designer Intern 等
- **实习时长**: 通常 **6 个月** (thesis 友好, 也支持暑期 3 个月)
- **申请窗口**: rolling, 通过 Lever ATS 滚动开放

---

## New Grad / Junior 岗位

> 信息丰富度: ⭐⭐ (TomTom 自 2024-2025 连续两轮裁员后 grad 通道大幅压缩, 公开数据稀薄; 主要靠 Levels.fyi 实读 + Glassdoor + NL Times / Bits&Chips 行业报道拼凑)
> 区别于实习: 实习路径轻量 + 不办签证; **Junior / Graduate Engineer 全职** 走 Kennismigrant + 30% ruling, 但持续 hiring freeze 让 NL HQ 名额极少, Łódź / Berlin 更现实

- **常见岗位名**: **Junior Software Engineer** / **Junior Map Data Engineer** / **Junior Backend Engineer**; 偶有 **Graduate Software Engineer** (Łódź / Berlin 出现概率更高); **没有独立 Graduate Programme 品牌** — TomTom 不办 cohort scheme, 全职 entry-level 走标准招聘
- **欧洲地点**:
  - **Amsterdam (HQ)**: 因 2024-2025 持续裁员压力, 新 grad 名额**显著缩减**, 主要保留 senior / staff 招聘; NL 员工 ~1,200 / 全球 3,700 [来源 (实际打开过): https://nltimes.nl/2025/06/30/tomtom-scrapping-300-jobs-less-half-netherlands-ai-taking-work via 搜索 snippet]
  - **Łódź (PL)**: TomTom 最大 EU 工程 hub, Junior / Grad 名额最多; 招地图算法 / data engineering / SDK 全栈
  - **Berlin (DE)**: 部分软件岗 (HD Maps / Automotive SDK), Junior 偶有
  - **Madrid (ES)**: Data Scientist Junior 较多
  - **Belgrade (RS)**: 接收非 EU 学生本地申请
- **是否有独立 Graduate Programme**: **No** — TomTom 历史上有过 "Map Specialist Trainee Programme" 但 2023 后取消; 当前没有公开 cohort-based grad scheme
- **非EU签证 (全职)**:
  - TomTom International B.V. 仍是 IND **Recognised Sponsor**, 但实操中**仅对 senior 优先 sponsor** — Glassdoor 多份反馈 "currently only able to interview candidates who hold a visa that doesn't require sponsorship" 这条限制延续到 junior 全职
  - **Łódź (PL)** 是 visa 最 friendly 的路径 — 波兰 Blue Card 工资门槛低 (~PLN 95K/年 ≈ €22K), 中国应届生通过率最高
  - Berlin: EU Blue Card 工资门槛 2026 ~€48K (一般 IT) 或 €43K (shortage occupation)
  - **30% ruling (NL 2026)**: Junior base **勉强达到** Kennismigrant 阈值 **€4,357/月 <30 岁 = €52.3K/年** [来源 (实际打开过): https://www.jobbatical.com/blog/netherlands-highly-skilled-migrant-salary-thresholds-2026]; 但因 hiring freeze 实际 spot 极少
- **薪资范围 (base, gross/年)**:
  - **NL Junior SWE I (entry)**: **$70.7K = ~€65K base, 0 stock, 0 bonus** (Levels.fyi 2026-05-28 实读, 入门级单独数据点) [来源 (实际打开过): https://www.levels.fyi/companies/tomtom/salaries/software-engineer]
  - 全 NL TomTom SWE range: **€60.8K - €115K (L6-L9)**, median 偏低端
  - **Łódź (PL) Junior SWE**: PLN 100K-140K base (~€23K-€33K), 加 ~10% bonus
  - **Berlin Junior SWE**: €55K-€65K base
  - **股权**: TOM2 (Euronext) 股票池极小, Junior 完全没有 RSU; Levels.fyi entry 直读 stock = $0 [来源 (实际打开过): https://www.levels.fyi/companies/tomtom/salaries/software-engineer]
  - 加 8% holiday allowance (NL) / 13 个月 (PL 部分合同)
- **公司状态警告 (2024-2025 持续裁员)**:
  - **2024-09**: 首轮 ~300 人 (一说 500), AI pivot 重组 [来源 (搜索结果): https://siliconcanals.com/news/startups/travel-mobility/tom-tom-to-lay-off-500-employees/]
  - **2025-06**: 再裁 **300 人 = 全球员工 10%**, "less than half in Netherlands" → **多于一半在 Łódź / Berlin / Pune 等海外 hub**, 影响 route planner / sales / customer support 部门 (engineering core 受影响较小但仍冻 hc) [来源 (搜索结果): https://nltimes.nl/2025/06/30/tomtom-scrapping-300-jobs-less-half-netherlands-ai-taking-work]
  - 结论: Amsterdam Junior SWE hc **仍 frozen**, Łódź 不再是绝对 safe haven (本轮也受波及), 但仍是 sponsor 最容易的路径
- **申请窗口**: rolling year-round 通过 Lever ATS, 但实际**新 grad 名额发布频率极低** — 2024-2025 每月 Amsterdam Junior SWE 公开岗 < 2 个; Łódź 较稳定每月 5-10 个 Junior 岗位
- **面试流程差异 vs 实习**:
  - 流程结构与实习几乎一致 (Recruiter → Optional OA → Tech 1h → Manager → Offer), 仅**总长拉长到 5-7 周** (实习 4-6 周)
  - **新增 architecture / design 轮** (45 min, 中等深度, 不到 system design level)
  - Behavioral 部分对 TomTom 5 leadership behaviors 考察加深
- **录取竞争**: 因 hiring freeze + 公司业务收缩, 实际竞争**比报名数据看起来更激烈** — Amsterdam Junior 录取率 ~3-5%; Łódź 较宽松 ~10-15% 但 2025 H2 后 hc 也收紧; **国际生 friendliness 整体低** — TomTom 战略保守, sponsor 意愿不强
- **关键链接**:
  - TomTom Career 官方入口 (Junior 筛选): https://www.tomtom.com/careers/
  - Lever ATS 直链: https://jobs.eu.lever.co/tomtom
  - Levels.fyi TomTom SWE (2026-05-28 实读 $70.7K SWE I): https://www.levels.fyi/companies/tomtom/salaries/software-engineer
  - Glassdoor 面经 (含 Junior 流程): https://www.glassdoor.com/Interview/TomTom-Interview-Questions-E13632.htm
  - LinkedIn TomTom Junior jobs: https://www.linkedin.com/company/tomtom/jobs/?keywords=junior
  - 2025-06 第二轮裁员 (300 人 / NL <半) 报道: https://nltimes.nl/2025/06/30/tomtom-scrapping-300-jobs-less-half-netherlands-ai-taking-work
  - 2024-09 第一轮裁员报道: https://nltimes.nl/2024/09/26/tomtom-cut-300-jobs-shift-towards-ai

---

## 2. 签证与国际学生政策

- **关键限制 (Glassdoor 多份报告)**: **"TomTom is currently only able to interview candidates who hold a visa that doesn't require sponsorship"**
  - 这意味着 TomTom 对**实习签证支持非常有限**, 近期裁员压力下更加保守
  - 实际可行路径:
    - EU/EEA 学生 → 直接申请
    - 已在 NL/DE/PL 院校就读非 EU 学生 → 靠学习居留 + Nuffic 实习协议申请
    - **不在 EU 院校的非 EU 学生 → 几乎无法直接申请实习**
- **Erasmus+ / 学校交换协议**: TomTom 历史上接收过 Erasmus 学生 (例如西班牙交换在荷兰实习), 但是要靠学校签的实习协议而非 TomTom 直接 sponsor 签证
- **全职转正**: TomTom 仍是 IND 注册 sponsor, 但近年 senior 招聘冻结幅度大, 30% ruling 适用于符合门槛的全职

---

## 3. 面试流程

TomTom 流程相对**轻量**, 总长 4–6 周, 比 Booking / Adyen / Uber 都短。

### 标准流程 (6 步, 官方 how-we-hire 页)
1. **Application Review** — 简历筛选
2. **Initial Recruiter Call** — 30 分钟, 经历 + 动机 + 期望
3. **Optional Technical Assessment** — 短的 online coding task (非所有岗强制)
4. **Technical Interview** — **1 小时**, 通常包含:
   - 30 分钟 behavioral (基于 TomTom leadership behaviors)
   - 30 分钟 live coding (problem solving, screen share)
5. **Interview Loop** — 3–4 轮, 不同面试官, 涉及 system design + leadership 评估
6. **Final Decision & Offer**

### 技术考察重点
- **Software Engineer**: C++ / Python / Scala / Java; **数据导向** (Big Data, distributed systems); 与地图/导航相关算法 (Dijkstra, A*, R-tree, graph) 经常出现
- **Data Engineer**: Python + Spark + SQL; AWS / Azure 经验加分; 地图 ETL pipeline 思维
- **Map Data Sourcing**: 偏 GIS, QGIS / shapefile / OSM 经验
- **Data Scientist**: Python, numpy/sklearn/pytorch, 偶有 CV (卫星图像 segmentation 是 TomTom 实习的真实项目)

### 行为面常见
- "Tell me about a time you debugged a complex issue"
- "How do you handle disagreement with a teammate"
- "Why TomTom / why maps"
- TomTom leadership behaviors (Customer obsession, Take ownership, Be a team player, Grow yourself)

---

## 4. 真实面经

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|------|----------|---------|----------|------|------|
| — | SWE / Amsterdam | Recruiter → tech (30min behavior + 30min coding) → loop | 算法基础, 地图相关数据结构 | — | [Glassdoor](https://www.glassdoor.com/Interview/TomTom-Amsterdam-Interview-Questions-EI_IE38808.0,6_IL.7,16_IM1112.htm) |
| — | NL 综合 | Recruiter + tech interview | LeetCode easy/medium, system thinking | — | [Blind](https://www.teamblind.com/post/tomtom-nl-interview-jf15gcvp) |
| — | SWE | 整体流程描述 | Data-oriented systems, ML, algorithms for map processing | — | [InterviewQuery 综合](https://www.interviewquery.com/interview-guides/tomtom-software-engineer) |
| — | Data Science Intern / DS general | 项目讨论 + Python + 简单 ML 概念 | image segmentation 卫星图找建筑 polygon (实际实习项目报告) | — | [TomTom Careers 页面 / Glassdoor](https://www.tomtom.com/careers/jobdetails/3daed769-2ee7-4c7c-8589-9f24ac7b0639/data-scientist-intern/) |

**信息匮乏**: TomTom intern 专门面经在 1point3acres / Reddit / Blind 上**极少**, 主因是:
1. 招聘规模小, 数据点少
2. 公司战略不确定, 候选人不愿公开
3. 中文社区基本无报告

### 题型样本 (基于 Glassdoor 全部岗位汇总)
- **算法**: graph search, shortest path (Dijkstra/A*), tree traversal, hashmap
- **地图相关**: 给一组坐标, 找最近点 (k-d tree, R-tree); 计算 polygon 面积; 路径合并/简化
- **系统设计**: real-time traffic ingestion; geofence service; tile server
- **Data 岗**: SQL window functions, Spark partitioning, ETL idempotency

---

## 5. Offer 案例 / Stipend

| 城市 | Stipend | 备注 | 时间 | 来源 |
|------|------|------|------|------|
| Amsterdam | **~$1,284/月 (~€1,200)** SWE intern (winter 2024 报告, 含 transportation) | Levels.fyi | 2024 | [Levels.fyi](https://www.levels.fyi/internships/TomTom/Software-Engineer-Intern/) |
| Amsterdam | Glassdoor 个别数据点 €67,060/年 (Digital Marketing 异常值, 不代表 SWE) | — | — | [Glassdoor](https://www.glassdoor.com/Salary/TomTom-Digital-Marketing-Intern-Amsterdam-Salaries-EJI_IE38808.0,6_KO7,31_IL.32,41_IC3064478.htm) |
| Amsterdam (全职 SWE 对比) | €83,516 平均 (Glassdoor 全 tech) | 全职 | 2024 | [Glassdoor / TechPays](https://techpays.com/europe/netherlands/tomtom/amsterdam) |

### 关键备注
- TomTom intern stipend **本榜单偏低**, 约 €1,200–€1,500/月; 与 ASML 类似但无住房补贴
- 公司 financial 压力大 (2024 年亏损), 实习福利和 budget 收紧
- 转正 base 也比 Uber / Booking / Adyen 低 (€60–€80K range vs Uber 全职 €130K+)

---

## 6. 申请渠道与建议

- **官方招聘**: https://www.tomtom.com/careers/
- **学生项目页**: https://www.tomtom.com/careers/students/
- **职位 Lever portal**: https://jobs.eu.lever.co/tomtom
- **Amsterdam 职位过滤**: https://www.tomtom.com/careers/joboverview/?location=Amsterdam,+The+Netherlands
- **如何招聘 (流程)**: https://www.tomtom.com/careers/how-we-hire/

### 推荐策略
1. **签证状态自检**: 在投递前确认你不需要 TomTom sponsor (有荷兰学习居留 OR EU 护照); 否则白投
2. **强调地图/地理空间经验**: GIS, OSM, GeoJSON, R-tree, Spatial SQL — 这些在 TomTom 比通用算法更值得 highlight
3. **C++ / Spark / Python** 多语言加分; TomTom 是少有的仍重 C++ 的 NL 公司 (Map SDK, 嵌入式导航)
4. **Berlin / Łódź / Madrid 是更容易拿 offer 的备选** (Amsterdam HQ 招聘门槛最高, 其他 hub 名额更多)
5. **Erasmus+ / 学校协议**: 如果是欧洲在校生, 通过学校 partnership 申请比直接投递成功率高

---

## 7. 踩坑与社区评价

### 警惕点 (重要)
- **2024 年大规模裁员**: 300 人 (一说 500 人), 主要影响 application layer、sales、customer support; 公司称"AI pivot", 实质是收缩
- **战略不确定**: 设备业务退潮, 现在 90%+ 收入靠 B2B map licensing (Volkswagen, Renault, Apple); 未来与 Google/HERE 竞争激烈
- **股价低迷**: 1 年 -26.7%, 投资者信心弱
- **签证 sponsor 严格**: 这是与 Booking / Adyen / ASML 最大区别 — TomTom **明确不愿 sponsor 实习签证**
- **实习项目 quality 参差**: 部分实习生反馈"项目偏边缘, 做的东西不一定上线"
- **国际化程度**: Amsterdam HQ 国际化但 Łódź/Pune 较本地化

### 优点
- **地图/地理空间**领域是 niche 经验, 跳 Google Maps / HERE / Apple Maps / Mapbox 都吃香
- **Amsterdam HQ 位置**: 中央车站旁, 通勤体验顶级
- **轻量流程**: 4–6 周 vs Adyen 的 6–8 周, 适合时间紧的候选人
- **wellbeing 文化**: 工作时长比 Adyen / Uber 友好, work-life balance 评价较好 (Glassdoor 评分中位)

### 利与弊
- (+) 流程短, 节奏快
- (+) Map / 自动驾驶 niche 经验
- (-) 签证政策对非 EU 学生几乎是 dealbreaker
- (-) 公司财务和战略走下坡, intern 价值长期不确定
- (-) Stipend 低
- (-) 中文社区面经几乎为零, 信息不对称

---

## 8. 关键链接汇总

- 官方招聘主页: https://www.tomtom.com/careers/
- 学生与新毕业页: https://www.tomtom.com/careers/students/
- 招聘流程详解: https://www.tomtom.com/careers/how-we-hire/
- 所有职位 (Lever): https://jobs.eu.lever.co/tomtom
- Amsterdam 办公室介绍: https://www.tomtom.com/careers/offices/amsterdam/
- 全球办公室列表: https://www.tomtom.com/careers/offices/
- Glassdoor 面经: https://www.glassdoor.com/Interview/TomTom-Amsterdam-Interview-Questions-EI_IE38808.0,6_IL.7,16_IM1112.htm
- TomTom 2024 裁员报道: https://siliconcanals.com/news/startups/travel-mobility/tom-tom-to-lay-off-500-employees/
- AI 重组报道: https://bits-chips.com/article/tomtom-navigates-300-job-cuts-in-ai-driven-restructuring/
- TomTom 2025-06 第二轮 300 人裁员 (NL Times): https://nltimes.nl/2025/06/30/tomtom-scrapping-300-jobs-less-half-netherlands-ai-taking-work
- Levels.fyi TomTom SWE 2026-05 实读: https://www.levels.fyi/companies/tomtom/salaries/software-engineer
- NL 2026 Kennismigrant threshold: https://www.jobbatical.com/blog/netherlands-highly-skilled-migrant-salary-thresholds-2026
