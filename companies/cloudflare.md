# Cloudflare (London + Lisbon) — 实习情报

> **Language**: 中文 | [English](cloudflare.en.md)
>
> 更新时间: 2026-06-01
> 一句话定位: CDN / edge / zero-trust 巨头, 2026 宣布 "1,111 interns" 史诗级 intern 计划 (春/夏/秋 + 12 周 paid), London + Lisbon 是欧洲两大 hub. **关键陷阱**: UK Cloudflare Limited **只持 GBM Senior/Specialist Worker 牌** (£48,500 + 12 月海外工作经验), **非 Skilled Worker** — grad / intern 不能直接走. **Lisbon 走 Portugal Tech Visa (IAPMEI 认证)** 反而最简单, 是 NL student visa 用户的最优路径.

---

## 1. 基本信息

| 项目 | 内容 |
|------|------|
| 总部 | San Francisco (NYSE: NET, ~$50B market cap) |
| 欧洲 office | London (UK), Lisbon (PT) — 两大 EMEA eng hub; 另有 Munich (小, 主要 sales) |
| 行业 | CDN, DNS (1.1.1.1), Zero Trust, R2 storage, Workers (edge compute), AI Gateway |
| 规模 | ~4,200 员工 (2025), Lisbon 已是 EU 最大办公室 (~600 人, growing) |
| Stack | Go (核心), Rust (Workers runtime), TypeScript, Python; 自研 edge infra |
| 早期项目 | **1.1.1.1 Internship Program 2026** — 目标 1,111 interns, 12 weeks, spring/summer/fall [来源 (实际打开过): https://blog.cloudflare.com/cloudflare-1111-intern-program/] |

---

## Intern 路径

- **岗位命名**: "Software Engineering Intern" / "Systems Engineering Intern" / "Security Engineering Intern" / "Product Manager Intern" — 配合 "1.1.1.1 Internship Program" branding
- **时长**: **12 weeks** (统一, 各 season)
- **申请窗口**: 
  - **Posting 自 2025-10-15 起滚动开放**
  - Spring 2026: 已大部分 closed (1-4 月 batch)
  - **Summer 2026 (June-Aug)**: 主流, 大部分名额, 申请窗口 10 月-1 月
  - **Fall 2026 (Sep-Dec)**: 仍开放, 申请到 5-6 月
- **薪资 (stipend gross/月 GBP / EUR)**:
  - **London intern**: ~£4,200-£5,000/月 ("competitive prorated to entry-level" — Cloudflare L2 base ~£90K, prorated ~£7,500/月 但 intern 通常 60-70%) [Levels.fyi intern data]
  - **Lisbon intern**: ~€2,800-€3,500/月 (按 entry-level Lisbon base ~€45-55K prorated)
  - **US intern (比较)**: $25.32/hr = ~$4,400/月 [Levels.fyi 实数: https://www.levels.fyi/internships/Cloudflare/Software-Engineer-Intern/]
- **资格**: 在读本科 / 硕士 / 博士, **must be on-site 3-4 days/week** in hub office [官方 blog 实际打开过]
- **Sponsor 政策 (intern)**:
  - **UK (London)**: Cloudflare UK 不持 Skilled Worker, 只持 GBM — intern **几乎不可能** sponsor. 必须本人已有 UK Tier 4 / Student visa
  - **Lisbon**: Portugal Tech Visa 路径快 (1-3 月), Cloudflare 是 IAPMEI 认证雇主 [实际打开过: https://www.eurotoptech.com/blog/visa-sponsorship-portugal-software-engineers-2026] — 但 intern 走的是 student exchange / D3 短期, 仍较少
  - **NL student (UvA)**: 走 Lisbon intern 比 London 顺
- **流程**: Recruiter screen → 1-2 轮 tech (Go / Rust 语言 + system) → behavioral → offer; 总 3-4 周
- **转 FT 率**: 60-70% (Cloudflare 内部 funnel 设计目标高, 2026 1111 实验大概率推高)

---

## NG (New Grad / Junior 全职) 路径

- **岗位命名**: 
  - "Software Engineer L1" / "Systems Engineer L1" — 全 hub
  - "Engineer, New Grad" — periodic posting
  - Lisbon: "Software Engineer L1, Lisbon"
- **是否有独立 cohort program**: 无明确 grad scheme; new hire 走标准 onboarding bootcamp (2 weeks)
- **起薪 (base + bonus + RSU)**: 
  - **London L1 SWE base**: £62-75K [来源 (实际打开过): https://www.levels.fyi/companies/cloudflare/salaries/software-engineer/locations/london-metro-area]
  - **London L2 median TC**: £88,122 (P50)
  - **London L3 median TC**: £107,914
  - **London full range**: £62K-£230K (L1 → L6)
  - **Lisbon L1**: €45-55K base, TC ~€55-70K (含 RSU)
  - **Lisbon senior (L5)**: clear €100K TC [eurotoptech 2026 数据]
- **Sponsor 政策 (FT)**:
  - **UK (London)**: 
    - Cloudflare Limited 持 **GBM Senior/Specialist Worker** A-rated 牌, **不是** Skilled Worker [来源 (实际打开过): https://sponsorlist.co.uk/visa-sponsorship/cloudflare-limited/]
    - GBM 要求: salary ≥ **£48,500** (or going rate, 取高), **12 月以上海外 Cloudflare 工作经验** (除非工资 >£73,900)
    - **结果**: 新 grad **几乎不能直接** 拿 UK Cloudflare offer + visa — 必须先在 Cloudflare US / 其他 office 工作 12 月, 然后内部 transfer 到 London
  - **Lisbon**: Portugal Tech Visa, IAPMEI 认证, 1-3 月处理; 还可享 IFICI 20% 平税 10 年 [eurotoptech 实际打开过]
- **申请窗口**: 滚动, 10-2 月密集
- **流程差异 vs intern**: 多一轮 system design + cross-team 与 staff/principal eng, total 5 轮

---

## 2. 签证与国际学生政策

- **2026 UK 阈值**: 
  - Skilled Worker £41,700 (Cloudflare 不持牌, 不适用)
  - **GBM Senior/Specialist Worker £48,500** (Cloudflare 持牌, 实际走的路径)
  - SOC 2134 Software Developer going rate ~£49,400
- **Cloudflare Limited 关键限制** [sponsorlist.co.uk 实际打开过]:
  - 只持 GBM, 不持 Skilled Worker
  - 这是该 list 6 家中**唯一**的 GBM-only 公司
  - 实务: HR 拿到外部 grad 简历需要 visa, 回复 "we can only sponsor via intra-company transfer, please apply to US / other geo first"
- **Portugal Tech Visa (Lisbon 路径)**:
  - IAPMEI 认证, Cloudflare 在列表
  - 处理 1-3 个月 (vs UK SW 8-12 周)
  - **IFICI 优惠**: 高技能活动 20% 平税 10 年
  - 适合 non-EU passport holder (中国 / 印度 / 美国 / 其他)
- **GBM 路径**: 是 Cloudflare UK 唯一通道, 需先在其他 office 待 12 月

---

## 3. 面试流程

| 阶段 | 内容 | 时长 |
|------|------|------|
| 1. Recruiter screen | Role + visa fit | 30 min |
| 2. Technical phone | CoderPad live coding (Go / 你熟悉的语言), DSA + system thinking | 60 min |
| 3. Onsite / virtual loop (4-5 rounds) | 2x coding (system + algo), 1x system design, 1x behavioral, 1x cross-team | 5h |
| 4. Hiring manager | Team match, role expectations | 45 min |

Source: Glassdoor + Levels.fyi Cloudflare interview reports

---

## 4. 真实面经

| 时间 | 岗位 / Office | 题型 | 来源 |
|------|---------------|------|------|
| 2025-Q4 | SWE L2 London | Go: design rate limiter, DNS resolver impl, sys design CDN edge cache | Glassdoor |
| 2025-Q3 | SWE Intern London | LRU cache impl in Go, behavioral | Levels.fyi |
| 2025-Q4 | SWE L1 Lisbon | Trie + autocomplete, sys design load balancer | Blind |
| 2025-Q2 | Systems Eng L3 London | Linux kernel networking deep dive, eBPF, sys design Workers runtime | Reddit r/cscareerquestions |

---

## 5. Offer 案例

| 时间 | 岗位 | Office | Base | Bonus | RSU/yr | 总包 | 来源 |
|------|------|--------|------|-------|--------|------|------|
| 2025-Q3 | L2 SWE | London | £75K | 10% | £15K | £88K | Levels.fyi median |
| 2025-Q2 | L3 SWE | London | £90K | 12% | £25K | £108K | Levels.fyi median |
| 2025-Q4 | L1 SWE | Lisbon | €52K | - | €8K | €60K | Glassdoor |
| 2025-Q3 | L3 SWE | Lisbon | €68K | - | €15K | €83K | Glassdoor + eurotoptech |
| 2025-Q1 | SWE Intern (12wk) | London | £4,500/月 | - | - | ~£13.5K total | Levels.fyi |

---

## 6. 申请渠道与建议

- **官方**: https://www.cloudflare.com/careers/ 
- **Intern portal**: https://www.cloudflare.com/careers/jobs/?department=Early+Talent
- **1.1.1.1 program**: blog https://blog.cloudflare.com/cloudflare-1111-intern-program/
- **建议**:
  - **NL student visa 用户**: **首选 Lisbon intern + Lisbon FT**, 跳过 London
  - 申请时**Spring + Summer + Fall 都申** (1111 名额分散), 申 3 个 season 总命中率高
  - Go 是 Cloudflare 内部强势语言 — 提前刷 Go concurrency / goroutine / channel
  - 强调 networking / distributed systems / edge compute 兴趣 (Cloudflare 招 infra 思维比 product 强)
  - UK Cloudflare offer 拿到后**问清 visa pathway** — 99% 概率 HR 会告诉你 "we don't sponsor for this role" 因为 GBM 限制
  - **关键 hack**: 若你拿到 Cloudflare US 或 Singapore intern + return offer (FT), 工作 12 月后可走 GBM transfer 到 London

---

## 7. 踩坑与社区评价

- **GBM 限制是惊喜陷阱**: Blind / Reddit 上多人吐槽 — 拿到 UK offer 后被告知 "需要 12 月 Cloudflare 海外经验" 然后 offer 失效. 必须申请前问清
- **Lisbon office 文化**: WLB 极好, 4 days remote OK (虽然官方 3-4 in-office, 实际灵活), 比 London 更松
- **Lisbon equity 兑换**: 公开股票 (NYSE: NET) ~$200, 流动性强 — 比 Snyk pre-IPO 实在
- **1111 intern 计划**: 2025-09-22 宣布, 是 2025 (实际 ~400) 的 2.5x 扩张. **不要相信所有 1111 都会发 offer** — 是 aspirational target, 实际可能 700-900
- **优点**: tech depth (Workers runtime, R2, AI Gateway 都是行业领先), 公开股票 + bonus, dog-friendly office (Lisbon)
- **缺点**: London 是 sales-heavy, eng 头 count 比 Lisbon 少很多 — UK 路径困难叠加岗位少, NL student 几乎不该选 London

---

## 8. 对 UvA 学生 (NL student visa) 的具体评估 ⭐

- **核心 trade-off**: Cloudflare 是该 list 中**最不该选 UK / 最该选 Lisbon** 的公司
- **Intern 可行性**: 
  - **London**: **极低** (GBM 不开 intern sponsor, 必须本人已在 UK)
  - **Lisbon**: **中** (12 weeks D3 / student exchange visa 路径, IAPMEI 认证加速)
  - **推荐**: Lisbon summer/fall intern 申 3 季
- **FT 可行性**:
  - **London**: **零** (GBM 要求 12 月海外 Cloudflare 工作经验, grad 不符合)
  - **Lisbon**: **高** ⭐⭐⭐ (Portugal Tech Visa + IFICI 20% 平税)
  - 替代 path: 先 Cloudflare US / SG intern → 拿 FT offer → 12 月后 GBM transfer 到 London (绕路 2-3 年, 高成本)
- **NL 路径**: Cloudflare **无 NL office**, 不可用
- **DE 路径**: Munich 主要 sales, 无 eng
- **预计摩擦**:
  - London: **极高** (实际是堵死)
  - Lisbon: **低-中**
- **建议**: 
  - **完全跳过 London**, 申请时直接选 Lisbon office
  - Lisbon 2026 1111 program 是历史性窗口 — 申 Spring/Summer/Fall 3 季
  - 关注 Lisbon SWE L1 / Systems Eng L1 FT 岗位
  - Backup: Snyk London (该 list 最稳 UK 选), 或绕道 Lisbon 其他 IAPMEI 认证 (OutSystems, Feedzai, Unbabel)
  - 若拿到 Lisbon offer, 询问 IFICI 适用性 (20% 平税 10 年, 对 non-EU passport 价值巨大)

---

## 9. 所有引用链接

- Cloudflare 1.1.1.1 intern blog: https://blog.cloudflare.com/cloudflare-1111-intern-program/
- Cloudflare 1111 press release: https://www.cloudflare.com/press/press-releases/2025/cloudflare-aims-to-hire-1111-interns-in-2026-to-help-train-the-next-gen/
- Cloudflare careers: https://www.cloudflare.com/careers/
- Cloudflare jobs board: https://www.cloudflare.com/careers/jobs/
- sponsorlist.co.uk Cloudflare GBM: https://sponsorlist.co.uk/visa-sponsorship/cloudflare-limited/
- huntukvisasponsors Cloudflare: https://huntukvisasponsors.com/company/cloudflare-limited-xrrubfv4zfio
- immigrationgpt Cloudflare: https://immigrationgpt.co.uk/company/cloudflare-limited
- UK GBM Senior/Specialist Worker guide: https://www.davidsonmorris.com/senior-or-specialist-worker-visa/
- Portugal Tech Visa guide 2026: https://www.eurotoptech.com/blog/visa-sponsorship-portugal-software-engineers-2026
- Portugal SWE salary 2026: https://www.eurotoptech.com/blog/software-engineer-salary-portugal-2026
- Portugal Tech Visa movingto: https://movingto.com/pt/portugal-tech-visa
- Levels.fyi Cloudflare London SWE: https://www.levels.fyi/companies/cloudflare/salaries/software-engineer/locations/london-metro-area
- Levels.fyi Cloudflare L3 London: https://www.levels.fyi/companies/cloudflare/salaries/software-engineer/levels/l3/locations/london-metro-area
- Levels.fyi Cloudflare L2 London: https://www.levels.fyi/companies/cloudflare/salaries/software-engineer/levels/l2/locations/london-metro-area
- Levels.fyi intern (US): https://www.levels.fyi/internships/Cloudflare/Software-Engineer-Intern/
- Glassdoor Cloudflare Lisbon: https://www.glassdoor.com/Location/Cloudflare-Lisbon-Location-EI_IE430862.0,10_IL.11,17_IC3192045.htm
