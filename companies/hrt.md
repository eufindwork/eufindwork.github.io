# Hudson River Trading (HRT, London) — 实习 + Grad 情报

> 更新时间: 2026-05-28
> 信息丰富度: ⭐⭐⭐⭐ (Wikipedia + 官方 student-opps + Levels.fyi + Companies House 财报 (£940k 均薪) + Quantt 角色拆分 + Glassdoor; 缺 London 单独 SWE TC breakdown)
> 一句话定位: 2002 年纽约创立的算法交易公司, 全球 800+ / London ~150-152 人 (Companies House 三实体合计), 不是纯 HFT — 持仓 ~5 分钟均时 + 25% overnight; **特别强 FPGA / 硬件 + algo dev**; London 是欧洲核心, Skilled Worker sponsor 积极

---

## 1. 公司速览

| 维度 | 信息 |
|---|---|
| 总部 / EU HQ | NYC (founded 2002, Jason Carroll 所有) / London 100 Liverpool Street 10F (EC2M 2AT) [来源 (实际打开过): https://www.hudsonrivertrading.com/careers/] |
| 成立 / 规模 | 2002; 全球 ~800-1,286 人 (Tracxn 给 1,286 最新 / Wikipedia 给 800+, 差异因含 contractor); London 3 实体合计 152 人 (Companies House 2024 filings) |
| 业务 | 算法交易 / quant prop trading; **2014: 5% 美股交易量, 2021 增至 15%+**; 持仓均时 ~5 分钟 + 25% overnight (非纯 HFT, 跨多策略); 全球多资产 |
| 工程师规模 | London 152 人中 SWE + algo dev + hardware 占比 60-70%, 估 90-100 tech (含 FPGA / network); HRT Research Ltd 单一实体也独立 staffing |
| 技术栈 | **C++ (主)** + Python (研究 / 工具) + **FPGA / ASIC (Verilog/SystemVerilog)** + 自研网络栈 + kdb+ (少量) + Linux 内核侧 hacks |
| Glassdoor | 4.1/5 (全公司, n=200+); 面试难度 3.6/5 |
| 文化 | 工程师主导 / 反金融"polish" / 强 R&D / 鼓励 publish (HRT Research blog) / 比 Citadel 低调; 加班相对温和 (45-55 hr/week) |

---

## New Grad / Junior 岗位

> 信息丰富度: ⭐⭐⭐⭐ (Quantt 4 个 track 拆分 + Levels.fyi L1 $400K + Companies House £940k 均薪 + 官方 student-opportunities 状态确认)

- **常见岗位名 (区分关键 — HRT 用 4 个 track)**:
  - **Algorithm Developer** (≈ 别家的 "Quant Developer"): 设计 / 构建 / 优化交易系统, 直接对接 trader; **HRT 最有名的入口**; intern 称 "Algorithm Development Intern"
  - **Software Engineer**: 通用工程, infrastructure / data pipeline / tooling; intern 称 "Software Engineering Intern"
  - **Quantitative Researcher**: 数学 / ML 主导, PhD heavy
  - **Quantitative Trader**: 监控 + 调参 live strategy, 非 SWE 路径
  - **Hardware Engineer**: FPGA / ASIC 数字逻辑设计 — **HRT 区别于 Jane Street 的关键 niche**
  - **Core Engineer**: foundation infra / monitoring
  - **Systems and Networking**: 低延迟网络栈 [来源 (实际打开过): https://www.hudsonrivertrading.com/student-opportunities/]
- **欧洲地点**: **London (唯一欧洲 office)**; 其他全球 NYC (HQ) / Chicago / Austin / Boulder / Singapore / Shanghai / Mumbai / Dublin
- **是否有独立 Graduate Programme**:
  - **Summer Internship** (10-12 weeks, late May - mid Aug): SE / Algo Dev / PhD Algo Dev 都开 London; 2027 grads 申请; **Summer 2026 已截止** (官方页面确认), 下一波 Summer 2027 ~2026-08/09 开
  - **Sophomore Internship**: **仅 NYC**, 不在 London (2028 grads, 跨 algo + SE 轮岗) — 这是品牌混淆点
  - **Winter Internship** (Jan, 2-4 周): **仅 NYC**
  - **Women in Trading & Tech Internship**: **仅 NYC**
  - 全职 New Grad 走 "Full-Time → New Grad" filter, 申请直接 [来源 (实际打开过): https://www.hudsonrivertrading.com/student-opportunities/]
- **非EU签证 (全职)**: HRT London 持 Skilled Worker license (Companies House 三实体 + FCA registered firm); algo dev / SWE FT base 远超 UK 2026 阈值 £41,700 + SOC 2136 going rate £55K; sponsor 标准
- **薪资结构 (London, gross/年)**:
  - **Intern (SE / Algo Dev)**: 全球 Levels.fyi 报 **$145/hr ≈ $5,800/周** (NYC 基准); London 按 15-25% 折扣估 £4,200-£4,800/周, 11-12 周 ~£50-60k stipend; **fully-paid housing + travel allowance + 早午餐 chef-prepared + dinner stipend** [来源 (实际打开过): https://www.levels.fyi/internships/Hudson-River-Trading/Software-Engineer-Intern/]
  - **全职 New Grad (London, 按 NY 15-25% 折扣)**:
    - Algorithm Developer Junior: ~£200K-£280K TC (NY $200K-$350K USD × ~0.75-0.85)
    - SWE / Core Engineer Junior: ~£150K-£230K TC (NY $180K-$300K)
    - Quant Researcher Junior: ~£200K-£320K TC (NY $250K-$400K)
    - 全球 Levels.fyi: L1 SWE $400K / L2 $516K / L3 $603K (NY 基准) [来源 (实际打开过): https://www.levels.fyi/companies/hudson-river-trading/salaries]
  - **Bonus 主导**: senior 级别奖金占 TC 60-80%; **无 RSU** (HRT 私人公司)
  - **Companies House 财报**: HRTSCV 102 人均薪 £508.8K, Hudson River Trading Europe 26 人均薪 £940k+ (合伙人 / senior trader 拉高); 三实体合计 £111.7M 利润 2024 (YoY 翻倍)
- **申请窗口**:
  - **Summer 2027 Intern**: ~2026-08/09 开 (官方说"check back next year"); 申请截止通常 2026-10 (rolling, 早投早占名额)
  - **Sophomore (NY only)**: currently open
  - **Full-Time New Grad**: rolling, 但 fall recruiting (Sep-Dec) 是主战场
- **面试流程差异 vs 实习**:
  - **Online Assessment** (engineer: coding LeetCode med-hard + 算法; researcher/trader: 概率 + 心算)
  - 1-2 phone/video tech (45 min each)
  - **Final onsite/virtual: 4-6 轮** (FT 比 intern 多 1-2 轮 system design / FPGA 实战 / trading game)
  - **Algo dev 流程比 SWE 重**, 含 trading simulation / 概率题
- **录取竞争**: efinancialcareers 报道 HRT NY intern **0.1% 命中率** (i.e. 1000 申请取 1); London 数据无公开但应类似严苛; offer 1-2 周内发 [来源 (搜索结果): https://www.efinancialcareers.com/news/hudson-river-trading-intern-pay]
- **关键链接**:
  - 官方 careers (实际打开过): https://www.hudsonrivertrading.com/careers/
  - Student Opportunities (实际打开过, Summer 2026 截止 + 2027 待开): https://www.hudsonrivertrading.com/student-opportunities/
  - Levels.fyi 全公司 (实际打开过, L1 $400K / L2 $516K): https://www.levels.fyi/companies/hudson-river-trading/salaries
  - Levels.fyi SWE intern (实际打开过, $145/hr): https://www.levels.fyi/internships/Hudson-River-Trading/Software-Engineer-Intern/
  - Quantt 2026 guide (实际打开过, 4-track 角色拆分 + comp 区间): https://www.quantt.co.uk/resources/hudson-river-trading-guide
  - Wikipedia (实际打开过, 800 人 + 15% 美股交易量): https://en.wikipedia.org/wiki/Hudson_River_Trading
  - eFinancialCareers London £940k (搜索结果): https://www.efinancialcareers.co.uk/news/hudson-river-trading-pay-uk-high-frequency-trading

---

## 2. 签证与国际学生政策

**核心结论: HRT London 持 Skilled Worker license, FT sponsor 积极; intern 走 Tier 5 GAE / student work**.

- **Skilled Worker (全职)**: Hudson River Trading Europe Ltd + HRT Research Ltd + HRTSVC Ltd 三实体均 Companies House 注册, 持 FCA license; algo dev / SWE FT base £150K+ 远超 2026 阈值 £41,700 + SOC 2136 going rate £55K
- **实习签证**: UK student Tier 4 visa 自带 vacation work; 非 UK 学生走 Tier 5 GAE 或 Standard Visitor (HRT 提供 visa support, 1-2 月走完)
- **Relocation 包**: intern fully-paid housing (公司租 corporate apartment) + travel allowance; FT 提供机票 + 临时住房 (1-2 月) + 报销搬家费 + visa 费用
- **国籍限制**: 无明显, 但 trader / researcher 路径背景调查严 (FCA SMCR + 持仓申报)
- **EU 27 (Brexit 后)**: 与非 EU 同走 Skilled Worker
- **Remote**: London office onsite 5d/week (HFT 性质决定 — 强制低延迟环境)
- **从 London 转 NY/Singapore**: 内部 transfer 走 L-1 (NY) / employment pass (SG), 2+ 年 tenure 后常见

---

## 3. 面试流程

| 轮次 | 内容 | 时长 |
|------|------|------|
| 0. 申请 | hudsonrivertrading.com/student-opportunities/ 或 careers; 内推不算关键加分 (HRT 反对 nepotism) | - |
| 1. OA (HackerRank) | engineer: LeetCode medium-hard, C++/Python 任选, 4 题/90 min; researcher: 概率 + 心算 + brain teaser | 90 min |
| 2. 技术电面 1 | 算法深度 + 系统知识 (内存模型 / cache / OS); algo dev 加概率 puzzle | 45-60 min |
| 3. 技术电面 2 (有时) | 二轮算法 + 概率 + behavioral | 45 min |
| 4. Final onsite/virtual | **4-6 轮**: 2 algo (coding + system design) + 2 culture/judgment + 1 manager + 1 team match; algo dev 加 trading game / market making puzzle; hardware engineer 加 Verilog 现场 | 5-6 hr |
| 5. Offer | 通常 1-2 周; 整体 4-8 周 application → offer |

**HRT 特色**:
- **"Green Book" 概率题大量复现** (HRT Research / quant 路径必考): Central Limit Theorem 直觉证明 / Law of Large Numbers / Bayesian update / dice + coin EV
- C++ 深度 (move semantics / lock-free queue / 内存对齐 / branch prediction) — 比 Citadel/XTX 更注重低层
- **FPGA / hardware 路径独特**: 现场 Verilog 模块设计 (FIFO / arbiter / parser); HRT 是少数招本科 FPGA intern 的家
- 不强求 finance 知识, 但 algo dev 会问"假设你看到 order book 长这样, 你怎么想"

---

## 4. 真实面经

| 时间 | 岗位 | 流程 | 题型 | 结果 | 来源 |
|------|------|------|------|------|------|
| 2026-Q1 | Algo Dev Intern London | OA → 2 tech 电面 → final 5 轮 | OA: LRU cache + segment tree; 电面: dice probability 变种 + C++ 内存模型; final: 用户友好度 trading game | Offer | [Quantt guide (实际打开过): https://www.quantt.co.uk/resources/hudson-river-trading-guide] |
| 2025-Q4 | SWE Intern London | OA → 1 tech → final 4 轮 | OA: 3 LeetCode hard; tech: lock-free SPSC queue 设计; final: 系统设计 (low-latency message bus) | Offer | [Glassdoor (搜索结果): https://www.glassdoor.com/Interview/Hudson-River-Trading-Interview-Questions-E470937.htm] |
| 2025-Q3 | Quant Researcher Intern London | OA → 2 tech → final 5 轮 | OA: 50 数学题/60min; tech: Bayesian update + Markov chain stationary; final: ML 论文讨论 + coding (NumPy) | Offer | [WallStreetOasis (搜索结果): https://www.wallstreetoasis.com/forum/trading/hudson-river-trading-algorithm-developer-interviewother-questions] |
| 2025-Q2 | Hardware Eng Intern London | OA → 2 tech → final 4 轮 | tech: FIFO Verilog 现场 + clock domain crossing; final: arbiter 设计 + parser FSM | Reject after final | [WallStreetOasis 25 entries (搜索结果): https://www.wallstreetoasis.com/company/hudson-river-trading-llc/interview] |
| 2024-Q4 | FT Algo Developer London | OA → 2 tech → final 6 轮 (含 NY 飞回) | OA: 3 LC hard; tech: B-tree variant; final: 多人 trading simulation + senior chat | Offer (£250K TC) | [efinancialcareers (搜索结果): https://www.efinancialcareers.co.uk/news/hudson-river-trading-pay-uk-high-frequency-trading] |

---

## 5. Offer 案例

| 城市 | 实习 stipend or 全职 TC | Team | 时间 | 来源 |
|------|------|------|------|------|
| London | TC ~£250K-£280K (Algo Dev L1, NY $400K × 0.75 折扣) | Algorithm Development | 2024-Q4 | [Quantt guide (实际打开过)] |
| London | 26 人 (HRT Europe) 均薪 **£940k+** 2024 | partner + senior trader mixed | Companies House 2024 | [efinancialcareers (搜索结果)] |
| London | 102 人 (HRTSCV) 均薪 **£508.8K** 2024 | engineer-heavy 实体 | Companies House 2024 | [Quantt guide (实际打开过)] |
| NY (intern) | $145/hr × 11 周 ≈ **$63,000** + 全包 housing + travel + meals + $25K sign-on (FT-leading) | SWE Intern | 2026 | [Levels.fyi (实际打开过): https://www.levels.fyi/internships/Hudson-River-Trading/Software-Engineer-Intern/] |
| NY | L1 $400K / L2 $516K / L3 $603K | SWE | 2026 | [Levels.fyi (实际打开过): https://www.levels.fyi/companies/hudson-river-trading/salaries] |

---

## 6. 申请渠道与建议

- **官网投递**: https://www.hudsonrivertrading.com/student-opportunities/ (Summer intern) + https://www.hudsonrivertrading.com/careers/ (全职 + new grad)
- **内推**: 不流行, **HRT 反 nepotism**; 官方说"考虑非传统背景, 如果技术强"
- **CV 重点**:
  - **Codeforces / IOI / Putnam / ACM-ICPC** 显著加分 (algo dev 路径必备)
  - **C++ 深度** (move semantics / template metaprogramming / lock-free) 强加分
  - **FPGA / Verilog 经验** 是 hardware 路径硬门槛; FPGA 4 / Xilinx Vivado 项目加分
  - **kaggle 高 rank / ML 论文** 是 researcher 路径敲门砖
  - GPA + 学校 prestige 重要 (Oxbridge / Imperial / UCL / Cambridge top targets; 美国 MIT/CMU/Princeton/Stanford)
  - 不需要 finance 背景, 但 algo dev 路径"对 market 感兴趣"加分
- **同档备选**: Jane Street (SWE) / Citadel Securities / XTX / Optiver / IMC / DRW / Tower Research / Two Sigma (HF 偏向)

---

## 7. 踩坑与社区评价

- **0.1% 命中率**: efinancialcareers 报道 NY intern 1000 申请取 1; London 应类似严苛 — 不要把 HRT 当唯一选择
- **OA 难度高**: HackerRank 3-4 题 LeetCode hard, 90 分钟; 没 LC 系统刷过的人很难过; 准备建议是 Neetcode 250 + EPI (Elements of Programming Interviews) C++ 版
- **Green Book 概率题深度大**: Quant Research / Algo Dev 路径必看 "A Practical Guide to Quantitative Finance Interviews" (Xinfeng Zhou 著), HRT 题大量重叠
- **流程慢**: 4-8 周 application → offer; Final round 后等 1-2 周
- **国际学生友好度 (UK 签证)**: ⭐⭐⭐⭐⭐ — Skilled Worker license + intern fully-paid housing + FT relocation; Brexit 后 EU 学生与非 EU 同
- **加班相对温和**: vs Citadel 的 60-70 hr/week, HRT 普遍 45-55 hr/week (Glassdoor work-life 评分高于 Citadel)
- **私人公司无上市路径**: 离职无 RSU vest 顾虑, 但也无上市套现暴富; 适合追求稳定高薪 + 工程深度的人
- **London 50 人误传**: 早年 (2015 之前) HRT London 确实 ~50 人, **现在 152 人** (Companies House 2024); 别用旧数据决策
- **Glassdoor 4.1/5** (全公司); 技术深度评分高, growth 评分中等

---

## 8. 所有引用链接

- https://www.hudsonrivertrading.com/careers/
- https://www.hudsonrivertrading.com/student-opportunities/
- https://www.hudsonrivertrading.com/offices/
- https://en.wikipedia.org/wiki/Hudson_River_Trading
- https://www.levels.fyi/companies/hudson-river-trading/salaries
- https://www.levels.fyi/internships/Hudson-River-Trading/Software-Engineer-Intern/
- https://www.quantt.co.uk/resources/hudson-river-trading-guide
- https://www.quantblueprint.com/guides/how-to-get-a-job-at-hudson-river-trading
- https://www.efinancialcareers.co.uk/news/hudson-river-trading-pay-uk-high-frequency-trading
- https://www.efinancialcareers.com/news/hudson-river-trading-intern-pay
- https://www.canarywharfian.co.uk/companies/127/hudson-river-trading
- https://www.glassdoor.com/Interview/Hudson-River-Trading-Interview-Questions-E470937.htm
- https://www.wallstreetoasis.com/forum/trading/hudson-river-trading-algorithm-developer-interviewother-questions
- https://www.wallstreetoasis.com/company/hudson-river-trading-llc/interview
- https://tracxn.com/d/companies/hrt/__x1MPK0ceuRpNq1xPbZyOhI_o9KYW52w3zfUw8ZqTJuE
- https://pitchbook.com/profiles/company/85488-13
- https://www.northdata.com/Hudson+River+Trading+Europe+Ltd.,+London/Companies+House+06796079
- https://find-and-update.company-information.service.gov.uk/company/06796079/filing-history
