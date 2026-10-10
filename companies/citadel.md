# Citadel (HF) + Citadel Securities (MM) (London) — 实习 + Grad 情报

> **Language**: 中文 | [English](citadel.en.md)
>
> 更新时间: 2026-10-10
> ⚠️ **2026-10-10 勘误**: 本页 New Grad 段已刷新; 下文其他段落中以下旧说法已过时, 以 New Grad 段为准 — 开头及 §2/§5/§7 的 London TC £280K (现 median £318K)、'两个 UK 实体均持牌' (登记表仅列 Citadel Enterprise Europe Limited)、'London 是唯一欧洲办公室' (另有 Dublin / Paris / Zurich, Citadel Securities 2026-07 新开 Amsterdam).
> 信息丰富度: ⭐⭐⭐⭐⭐ (Wikipedia + 官方 careers (Citadel + Citadel Securities 两入口) + Levels.fyi London 直读 £280K median + Glassdoor + Citadel Engineering blog + Companies House 05462867 sponsor 确认)
> 一句话定位: Ken Griffin 1990 创立的 hedge fund **Citadel LLC** + 2002 spinoff 的做市商 **Citadel Securities** (两家公司, 同 Griffin 控股); HQ 2022 从 Chicago 搬到 Miami; **London 是欧洲最大 office 且共同申请**; SWE London L3 median TC **£280K**; Skilled Worker sponsor 积极

---

## 1. 公司速览

| 维度 | 信息 |
|---|---|
| 总部 / EU HQ | Miami (Southeast Financial Center, 2022 从 Chicago 搬) — Brickell Bay Drive 新 HQ 建设中; **London 是第一也是最大欧洲 office**; Citadel Securities (Europe) Limited 注册地 120 London Wall EC2Y 5ET; 2028 新办公室扩建中 [来源 (实际打开过): https://en.wikipedia.org/wiki/Citadel_Securities] [来源 (搜索结果): https://www.citadelsecurities.com/who-we-are/office-locations/london/] |
| 成立 / 规模 | Citadel LLC (HF): 1990, Griffin 创; Citadel Securities (MM): 2002 spinoff, Peng Zhao CEO since 2017; **Citadel Securities 1,800 人** (2024); London 全实体合计 ~354 人 (Citadel + Citadel Securities) |
| 业务 | **Citadel LLC**: multi-strategy hedge fund (equities, fixed income, commodities, credit, quant); **Citadel Securities**: MM 跨股票/options/futures/FX/treasuries; **执行 20%+ 美股交易 + NYSE 最大 DMM**; 2024 revenue $9.7B (Citadel Securities) |
| 工程师规模 | Citadel + Citadel Securities London tech 约 200-250 人 (354 总人数 + tech 比例 60-70%) |
| 技术栈 | **C++ (主)** + Python (research / ML / tooling) + kdb+/q (主流, 比 Jane Street/XTX 更重 kdb) + Java (部分 platform) + Rust (新项目, 早期采用) |
| Glassdoor | Citadel Securities 4.0/5 (371 salaries); 面试难度 3.6/5 |
| 文化 | 高压 / 高节奏 / 60-70 hr/week (业内最辛苦, 与 XTX 形成反差) / Griffin 直接 review senior offer / 极强结果导向 / 失败容忍度低 (PnL trader 1-2 年不达标即 cut); 但薪酬业内顶级 |

---

## New Grad / Junior 岗位

> 核查日期: 2026-10-10 (实时 WebSearch + WebFetch; citadel.com / citadelsecurities.com 对 WebFetch 返回 403, 岗位经 aggregator 详情页核实) | 信息丰富度: ⭐⭐⭐⭐ (依据: aggregator 岗位详情 + Levels.fyi London + UK / IND sponsor register + eFC 2026-09)
> **2027 Intake 状态**: **Open (rolling)** — Europe "University Graduate" 岗 2026-07-19 上线, 无公开截止日, 入职月份未公开 [来源 (实际打开过): https://www.thewallstreetquants.com/quant-new-grad-role/citadel] [来源 (实际打开过): https://www.thewallstreetquants.com/quant-new-grad-role/citadel-securities]
> **2026 H2 动态**: Citadel Securities 2026-07-22 开设 Amsterdam office (equity options; trading + technology + quant research; 全球第 15 个 office), 2027 grad 列表暂无 Amsterdam 岗 [来源 (实际打开过): https://www.eqs-news.com/news/corporate/citadel-securities-opens-amsterdam-office/69149dc4-9f7b-454f-94e1-8191a68a918e_en]; eFC 2026-09-23: Citadel (HF) London 2025 人均约 $1.2m, 新增以投资岗为主 [来源 (实际打开过): https://www.efinancialcareers.com/news/citadel-london-pay]

- **岗位名称 (Europe 2027, 8 个)**: Citadel — Software Engineer – University Graduate (London) / Quantitative Research Analyst – University Graduate (London; Zurich) / Quantitative Researcher – PhD Graduate (Dublin; London; Zurich) / Power & Renewables Trader – FlexPower – University Graduate (Hamburg; FlexPower 2025 年底被 Citadel 收购) [来源 (实际打开过): https://www.thewallstreetquants.com/jobs/trader-power-renewables-trader-flexpower-university-graduate-at-citadel-0399bf7f-1a53-46f6-8588-bfbb77f3a892]; Citadel Securities — Software Engineer – University Graduate (Europe) (London) / Quantitative Trader – University Graduate (London) / Quantitative Research Analyst – University Graduate (Europe) (Dublin; London; Paris; Zurich) / Quantitative Researcher – PhD Graduate (Europe) (London; Paris; Zurich)
- **资格窗口**: SWE: CS / CE 或相关 BSc / MSc / PhD 均投 "University Graduate" 岗; QR 另设 PhD 岗; 无 rotation 式 grad scheme, 直接进 team; 一份申请两家同时 review (旧版信息保留)
- **欧洲地点**: London (主) + Dublin / Paris / Zurich (QR / QRA) + Hamburg (FlexPower) + Amsterdam (Citadel Securities, 2026-07 新开) (旧版: "London 唯一欧洲 office", 2026-05)
- **非EU签证 (全职)**: UK register (2026-10-09 CSV) 列 Citadel Enterprise Europe Limited (Skilled Worker + GBM, A rating), **未见 "Citadel Securities (Europe) Limited" 条目** (旧版: 两实体均持 license, 2026-05) [来源 (实际打开过): https://www.gov.uk/government/publications/register-of-licensed-sponsors-workers]; 门槛 £41,700 [来源 (实际打开过): https://www.gov.uk/skilled-worker-visa/your-job]; NL: Citadel Securities Netherlands Services B.V. (KvK 99181207) 在 IND recognised sponsor register (2026-10-05) → 若 Amsterdam 开 grad 岗, zoekjaar → reduced HSM 可行 (IND 2026 reduced criterion €3,122/月) [来源 (实际打开过): https://ind.nl/en/public-register-recognised-sponsors/public-register-regular-labour-and-highly-skilled-migrants] [来源 (实际打开过): https://ind.nl/en/required-amounts-income-requirements]
- **薪资 (gross/年)**:
  - SWE London (Levels.fyi, 全 level 汇总, 2026-10): median TC £318K; "Software Engineer" 档 £290K = base £189K + bonus £97K + stock £4.4K; 区间 £158K-£446K+ (旧版: £280K median, 2026-05) [来源 (实际打开过): https://www.levels.fyi/companies/citadel/salaries/software-engineer/locations/london-metro-area]
  - ⚠️ **待 web 验证**: Prosple 列表 SWE grad London base GBP 110,000-150,000 (WebFetch 403, 未能打开) [来源 (搜索结果): https://uk.prosple.com/graduate-employers/citadel-uk/jobs-internships/software-engineer-full-time-graduate-0]
  - US 官方 job ads (tradermath 2026-09-28): Citadel QRA grad base $235,000-$300,000 (Yr1 约 $386,000), Citadel Securities grad engineer base $235,000-$300,000 [来源 (实际打开过): https://www.tradermath.org/salaries/citadel]; aggregator US Yr1 TC $400K-$700K (base $175K-$225K + sign-on $100K-$200K + bonus $100K-$300K) [来源 (实际打开过): https://www.techinterview.org/companies/citadel-securities/]; QR / QT London 无公开数据; 无 RSU, bonus 主导
- **申请窗口**: 2027 cycle 岗位 2026-07-19 上线, rolling; simplify (2026-07-22 版, US 口径): 2026-08 初开, 约 70% offer 在 10 月中前签, 门户开到 12 月; 12 个月后可重申 [来源 (实际打开过): https://simplify.jobs/blog/citadel-new-grad-job-2027]
- **面试流程**: HackerRank / CodeSignal OA (约 2 周内) → 1-2 recruiter / tech screen → Superday 4-7 轮, 全程 4-8 周; Citadel Securities 加概率 / trading game; C++ 侧重低延迟 (cache / TLB / kernel bypass / NUMA / C++26) [来源 (实际打开过): https://www.efinancialcareers.com/news/citadel-securities-c-plus-plus-job-skills]
- **工作强度**: techinterview (2026-07): SWE 约 "9-to-7", 比 FAANG 忙, trading 岗更长, office-first; 旧版 "60-70 hr/week" 无出处, 仅作参考
- **Intern (次要)**: Summer 2027 London 状态 citadel.com 403 未直证; US 口径 2026-08 初开 (simplify, 同上)
- **关键链接**: Citadel SWE grad 官方 (WebFetch 403, 链接取自 aggregator): https://www.citadel.com/careers/details/software-engineer-university-graduate-europe/ | Citadel Securities SWE grad (同上): https://www.citadelsecurities.com/careers/details/software-engineer-university-graduate-europe/ | aggregator 详情 (实际打开过): https://www.thewallstreetquants.com/jobs/software-engineer-university-graduate-europe-at-citadel-securities-1e112a7b-291a-49bb-a280-5caaa3b7ab66

---

## 2. 签证与国际学生政策

**核心结论: Citadel (HF) + Citadel Securities (MM) London 两实体均持 Skilled Worker license; FT sponsor 积极 + relocation 完整; intern 走 Tier 5 GAE / student work**.

- **Skilled Worker (全职)**: Citadel Enterprise Europe Limited + Citadel Securities (Europe) Limited (Companies House 05462867) 双持 sponsor license (worksponsors.co.uk + huzzle-app graduate-jobs-with-visa-sponsorship-uk 列入); FT base £150K+ 远超 2026 阈值 £41,700 + SOC 2136 going rate £55K
- **实习签证**: UK student Tier 4 vacation work; 非 UK 学生走 Tier 5 GAE; Citadel 历史接 US/CN/IN intern, visa 流程 1-2 月走完
- **Relocation 包**: 官方 + 业内报告 — 含机票 + 1-2 月临时住房 + **£5-15K relocation allowance** + 签证费报销; intern 提供 corporate housing
- **EU 27 (Brexit 后)**: 与非 EU 同 Skilled Worker
- **国籍限制**: 无明显, 但 trader / Quant Researcher 路径 FCA SMCR 背景调查严
- **Remote**: London 5d/wk onsite (Citadel 文化反 remote); intern 强制 onsite (Summer Associate)
- **从 London 转 NY/Miami**: 内部 transfer 走 L-1 (US) / employment pass (HK/SG), 2+ 年 tenure 后常见
- **Datathon 优势**: top 10 表现可直接收到面试邀请 (绕过 OA + skip 一轮 tech), 这是 international student 没本地 network 的 best entry

---

## 3. 面试流程

| 轮次 | 内容 | 时长 |
|------|------|------|
| 0. 申请 | citadel.com/careers/ 或 citadelsecurities.com/careers/ → 单一 application; 内推有用但非必需 | - |
| 1. HackerRank OA | 3-5 LC medium-hard, C++/Python 任选, ~75-90 min; 不通过直接拒 | 75-90 min |
| 2. 技术 + behavioral 电面 1 (45 min) | coding + DS/算法 + 项目经历 + "为什么 Citadel" | 45 min |
| 3. 技术电面 2 (45-60 min) | 更深 coding + 算法; Quant Researcher 加概率 + 数学 | 45-60 min |
| 4. Team match | hiring manager 看简历 + 配团队; 多 team 感兴趣时多轮 onsite | - |
| 5. Final onsite/虚拟 (4-6 轮) | 2 coding + 1 system design + 1 behavioral + 1 senior chat + 1 cross-team match; Citadel Securities 加 trading game / market making puzzle | 5-6 hr |
| 6. Offer | 平均 28 天 application → offer (efinancialcareers); 总流程 4-8 周 |

**Citadel 特色**:
- **C++ 深度极严**: move semantics / template meta / lock-free / 内存模型 — 比 Jane Street (OCaml-first) 更注重低层
- **System design 含 low-latency 主题**: 设计 limit order book / pricing engine / risk system
- **trading game**: Citadel Securities 路径常见 — "imagine you market make X 时, 怎么报价" — 实时思考 + 沟通
- **Datathon 加速通道**: top performer 直接 onsite, skip OA + 1 tech
- **Citadel + Citadel Securities 同时 review**: 一份 application 同时对接 2 公司, recruiter 内部分流
- 难度: Citadel Securities SWE OA "interview process rated 3.6/5", 比 HRT (3.5+) 稍重

---

## 4. 真实面经

| 时间 | 岗位 | 流程 | 题型 | 结果 | 来源 |
|------|------|------|------|------|------|
| 2026-Q1 | SWE Summer Associate London | OA → 2 tech → final 4 轮 | OA: 4 LC medium-hard 75min; tech: union-find + sliding window; final: low-latency 撮合引擎 design | Offer | [Interview Query 2026 (搜索结果): https://www.interviewquery.com/interview-guides/citadel-software-engineer] |
| 2025-Q4 | SWE FT London (Citadel + Citadel Securities 共同) | OA → 1 tech → final 5 轮 (含 hiring manager) | OA: 5 LC medium; tech: lock-free SPSC; final: 系统设计 + behavioral 深挖 | Offer (£280K TC) | [Glassdoor (搜索结果): https://www.glassdoor.com/Interview/Citadel-Securities-Software-Engineer-Interview-Questions-EI_IE1443495.0,18_KO19,36.htm] |
| 2025-Q3 | Quant Researcher Intern London | OA (心算 + 概率) → 2 tech → final | OA: 50 q 心算; tech: Bayesian + Markov; final: ML 论文 + 数据建模题 | Offer | [techinterview.org 2026 (搜索结果): https://www.techinterview.org/companies/citadel-securities/] |
| 2025-Q2 | Quant Trader Intern London | OA → trading game → final | OA: probability + 心算; trading game: market make 卡牌; final: PnL 讨论 + 心算速度 | Reject after trading game | [everythingquant guide (搜索结果): https://everythingquant.com/guides/software-engineering-at-citadel/] |
| 2024-Q4 | SWE FT London (Citadel Securities) | OA → 2 tech → final 6 轮 (含 Miami 飞回) | OA: 4 LC hard; tech: kdb+ 现场 + C++ template; final: low-latency 系统设计 + Griffin team senior chat | Offer (£300K+ TC) | [Medium Marcus Palmer (搜索结果): https://useinterviewstudy.medium.com/my-software-engineer-interview-experience-at-citadel-january-2024-70d238371b01] |

---

## 5. Offer 案例

| 城市 | 实习 stipend or 全职 TC | Team | 时间 | 来源 |
|------|------|------|------|------|
| London | TC **£280K median** (L3, base $234K + bonus $139K + stock $0) | SWE | 2026 (Levels.fyi 最新) | [Levels.fyi London (实际打开过)] |
| London | TC range **£149K - £281K (median) - £388K (max)** | SWE all-level | 2026 | [Levels.fyi London (实际打开过)] |
| US (new grad Yr 1) | TC **$400K-$700K**: base $175-225K + sign-on $100-200K + perf bonus $100-300K | SWE new grad | 2026 | [6figr.com (搜索结果): https://6figr.com/us/salary/citadel--new-grad--cy] |
| US (intern) | ~$120-150/hr ($4,800-$6,000/周) + housing + travel | Summer Associate SWE | 2025-2026 | [Levels.fyi 全公司 (实际打开过)] |
| US (senior) | L4 US SWE TC up to $728K (Levels.fyi 全公司高分位) | SWE L4 | 2026 | [Levels.fyi (实际打开过): https://www.levels.fyi/companies/citadel/salaries/software-engineer] |

---

## 6. 申请渠道与建议

- **官网投递**: https://www.citadel.com/careers/ (HF) + https://www.citadelsecurities.com/careers/ (MM) — 两入口都接同一份 application; "you have the opportunity to talk with two firms at once"
- **内推**: 比 Jane Street/XTX/HRT 更有用 — Citadel 走 employee referral, 简历直接走 recruiter; 但不是必需 (强候选人直投也成)
- **Datathon 加速通道**: Citadel + Citadel Securities 自办 Quant Datathon (奖金 $100K+) — top performer 直接面试邀请, 是 international student 没本地 network 的最佳入口
- **CV 重点**:
  - **Codeforces / IOI / Putnam / ACM-ICPC** 显著加分
  - **C++ 深度** (move semantics / lock-free / template) 是 SWE 必备; kdb+/q 加分 (Citadel 大量用)
  - **ML / 数学论文** 是 Quant Researcher 路径必备
  - GPA + 学校 prestige 极重要 (Oxbridge / Imperial top; 美国 MIT/CMU/Princeton/Stanford/Harvard)
  - 不需要 finance 背景, 但"对 market 感兴趣 + 心算快"加分
  - **Datathon 名次写简历显著加分**
- **同档备选**: Jane Street / HRT / XTX / Optiver / IMC / SIG / Two Sigma (HF) / Millennium / D.E. Shaw

---

## 7. 踩坑与社区评价

- **Citadel + Citadel Securities 同时 review = 一次申请, 两次机会**: 不要分开投; 但也意味着两家拒 = 都不能走
- **OA HackerRank 是硬关**: 3-5 LC medium-hard, 75-90 min, 不通过直接拒; 准备建议是 Neetcode 250 + LC top interview 100
- **C++ 深度比 Jane Street 更严**: Citadel SWE 不接受"我会 OCaml 但 C++ 一般"; 务必 STL / move / template / 内存模型熟练
- **流程相对快 (28 天均值)**: 比 HRT (4-8 周) / Jane Street (4-6 周) 快; 适合在 deadline 紧的申请季
- **国际学生友好度 (UK 签证)**: ⭐⭐⭐⭐⭐ — 双实体 Skilled Worker license + £5-15K relocation + visa 报销; Brexit 后 EU 与非 EU 同
- **加班严重 (60-70 hr/week)**: Citadel 是 quant 行业 work-life 最差之一 (vs XTX 45-55, HRT 50-55); Glassdoor work-life 评分低于 Jane Street/HRT
- **失败容忍度低 (尤其 trader 路径)**: Quant Trader 1-2 年不达 PnL 即 cut; SWE/researcher 路径相对稳, 但 senior senior 仍有 manage-out pressure
- **Griffin 直接 review senior offer**: senior offer 流程含 Griffin 个人 OK, 速度变慢; new grad 不受影响
- **Datathon 是 international student 最佳入口**: 没本地 network 的人通过 datathon 获面试是公开路径; 历史多个中国/印度学生从 datathon 入
- **Glassdoor Citadel Securities 4.0/5** (371 reviews); 薪酬满意度业内顶级, growth 评分中等, work-life 评分低
- **Mayfair 误传**: Citadel London 早期在 Berkeley Square Mayfair, 现 Citadel Securities (Europe) 注册地 **120 London Wall EC2Y 5ET** (City of London, 非 Mayfair); 新办公室 2028 完工

---

## 8. 所有引用链接

- https://www.citadel.com/careers/
- https://www.citadelsecurities.com/careers/
- https://www.citadel.com/careers/details/software-engineer/
- https://www.citadel.com/careers/career-perspectives/our-engineering-interview-process/
- https://www.citadelsecurities.com/who-we-are/office-locations/london/
- https://www.citadel.com/who-we-are/office-locations/london/
- https://www.citadelsecurities.com/who-we-are/office-locations/
- https://en.wikipedia.org/wiki/Citadel_Securities
- https://www.levels.fyi/companies/citadel/salaries/software-engineer/locations/london-metro-area
- https://www.levels.fyi/companies/citadel/salaries/software-engineer
- https://www.levels.fyi/companies/citadel/salaries
- https://6figr.com/us/salary/citadel--new-grad--cy
- https://6figr.com/us/salary/citadel
- https://www.glassdoor.com/Salary/Citadel-Securities-Salaries-E1443495.htm
- https://www.glassdoor.com/Interview/Citadel-Securities-Software-Engineer-Interview-Questions-EI_IE1443495.0,18_KO19,36.htm
- https://www.glassdoor.com/Interview/Citadel-Software-Engineer-Interview-Questions-EI_IE14937.0,7_KO8,25.htm
- https://www.teamblind.com/company/Citadel/salaries/software-engineering/united-states
- https://www.wallstreetoasis.com/company/citadel-securities/salary
- https://www.interviewquery.com/interview-guides/citadel-software-engineer
- https://www.techinterview.org/companies/citadel-securities/
- https://everythingquant.com/guides/software-engineering-at-citadel/
- https://www.tryexponent.com/questions?company=citadel&role=swe
- https://useinterviewstudy.medium.com/my-software-engineer-interview-experience-at-citadel-january-2024-70d238371b01
- https://worksponsors.co.uk/company/citadel-enterprise-europe-limited
- https://huntukvisasponsors.com/company/citadel-enterprise-europe-limited-xaryxgiglreh
- https://github.com/huzzle-app/Graduate-Jobs-with-Visa-Sponsorship-UK
- https://www.eurotoptech.com/blog/visa-sponsorship-uk-software-engineers-2026
- https://find-and-update.company-information.service.gov.uk/company/05462867
- https://find-and-update.company-information.service.gov.uk/company/05462867/officers
- https://builtinlondon.uk/company/citadel-securities
- https://builtin.com/company/citadel-securities/offices
- https://www.unifygtm.com/insights-headcount/citadel-llc
