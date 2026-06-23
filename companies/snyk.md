# Snyk (London + Tel Aviv) — 实习情报

> **Language**: 中文 | [English](snyk.en.md)
>
> 更新时间: 2026-06-01
> 一句话定位: Developer-first security unicorn (last valuation $7.4B), London + Tel Aviv co-HQ. Emerging Talent (intern / co-op / grad) program 活跃, 官方明示 "keen to support visa sponsorship" + £5K 搬迁津贴. London TC 实数 £100-140K (Levels.fyi 含 RSU 与上市预期), 是该 list 里对 NL student visa 用户最现实的 UK 选择.

---

## 1. 基本信息

| 项目 | 内容 |
|------|------|
| 总部 | London (Founders 院起) + Tel Aviv (R&D 大头) |
| 欧洲 office | London (HQ EU), 部分 remote in DE / NL / FR (合同雇佣) |
| 行业 | DevSecOps / SAST / SCA / Container / IaC security |
| 规模 | ~1,200 员工 (2025-2026), 私募后期 (rumored 2026 IPO) |
| Stack | TypeScript, Node.js, Go, Python, React; AWS, Kubernetes |
| 早期项目 | "Emerging Talent" program — intern / co-op / grad full-time |

---

## Intern 路径

- **岗位命名**: "Software Engineering Intern" / "Cloud Security Intern" / "Field Intern" — 通常挂 London 或 Tel Aviv
- **时长**: Summer 12 weeks (June-August) 或 6-12 months placement
- **申请窗口**: 10 月开放, 滚动收, 12-2 月集中面, 4-5 月发 offer
- **薪资 (stipend gross/月 GBP)**: ~£3,000-£3,500/月 (London intern, 相当于 entry-level prorated)
- **资格**: 在读本科 / 硕士 CS / Cybersec; 优先 already in UK 学生 (Tier 4)
- **Sponsor 政策 (intern)**: 
  - 官方 emerging talent 页面: "Snyk can sponsor visas and provides a £5,000 tax free relocation package" — 但**这条主要针对 FT grad**, intern 路径较少 sponsor
  - UK Student visa (Tier 4) 持有人暑期可全职 — 推荐路径
  - NL student visa 无法直接 intern in UK; Snyk 无 NL office (远程合同 case-by-case)
- **流程**: Recruiter screen → take-home PR review (24-48h) → 1 轮 tech discussion → behavioral; total ~3 周
- **转 FT 率**: 较高 (~50-60%), Snyk emerging talent 设计目标就是 funnel

---

## NG (New Grad / Junior 全职) 路径

- **岗位命名**: 
  - "Associate Software Engineer" / "Software Engineer I" — London
  - "Associate Security Researcher" — London
  - "Customer Solutions Engineer (Grad)" — London
- **是否有独立 cohort program**: Emerging Talent 大伞下 — onboarding cohort 但非严格 graduate scheme
- **起薪 (base + bonus + RSU)**: 
  - **London Associate / SWE I base**: £65K-£80K (推算 Levels.fyi P25)
  - **London Median SWE TC**: £137,095 (含 RSU / cash equity, 比 Darktrace ~3x) [来源 (实际打开过): https://www.levels.fyi/en-gb/companies/snyk/salaries/software-engineer/locations/london-metro-area]
  - **Senior SWE London median TC**: £149,913
  - Grad / new hire 段不容易直接命中 £137K — Levels.fyi 样本多偏 SWE II/III, 估 grad TC ~£75-95K (base + 10% bonus + £25-40K phantom stock / pre-IPO RSU)
  - £5K relocation tax-free [官方 careers 页]
- **Sponsor 政策 (FT)**: 
  - Snyk Limited 持 UK Skilled Worker license, A-rated [来源 (实际打开过): https://immigrationgpt.co.uk/company/snyk-limited]
  - 官方明示 "keen to support candidates who require visa sponsorship" [snyk.io/careers 实际打开过]
  - SW 阈值 £41,700 — London grad base £65K+ 大幅超过, **过门槛安全**
  - SOC 2134 Software Developer going rate ~£49,400 — 也过
  - 不在 GradSignal 2026 top 20 list (该 list 偏大公司), 但 huntukvisasponsors / immigrationgpt 直接验证持牌
- **申请窗口**: 持续开放, 9-2 月集中 grad hire
- **流程差异 vs intern**: 多一轮 system design + cross-team interview, total 4-5 轮

---

## 2. 签证与国际学生政策

- **2026 UK 阈值**: Skilled Worker £41,700, NEC £33,400, SOC 2134 Software Developer going rate ~£49,400
- **Snyk Limited** Skilled Worker license verified — 持牌且活跃 [immigrationgpt.co.uk/company/snyk-limited 实际打开过]
- **官方政策语言**: "Snyk can sponsor visas and provides a £5,000 tax free relocation package to help with your move to London" — **明确写在 careers 页**, 这在 UK 公司中算上等友好
- **NL student visa 用户路径**:
  - **不要走 intern** (UK 不开 intern sponsor, NL 远程合同 case-by-case)
  - **直接申 grad SWE in London**, 凭 £65K+ base 拿 SW 签证
  - 备选: 部分 remote-EU 职位写 "any EU location" — 可问 NL remote (Snyk 在 NL 有少量员工)
- **GBM 路径**: 不适用 (Snyk 无 NL/DE 法人实体做 intra-company transfer 起点)

---

## 3. 面试流程

| 阶段 | 内容 | 时长 |
|------|------|------|
| 1. Recruiter screen | Role fit, visa status, motivation | 30 min |
| 2. Take-home PR review prep | 收到 GitHub PR (NPM dependency tree), 24-48h 准备 | 24-48h |
| 3. Technical discussion | 45 min 与 senior eng, 走 PR + 实现 fix (recursive dependency bug) | 45 min |
| 4. Hiring manager + system design | 设计 SAST scanner 子系统 | 60 min |
| 5. Cross-team / values | Behavioral, Snyk 价值观 (One Team, Care Deeply) | 45 min |

总周期 5-8 周 [来源 (实际打开过): https://snyk.io/blog/your-engineering-interview-snyk/]

**关键差异化**: **不做 LeetCode-style live coding** — 全程 PR review + system design [Glassdoor + 官方 blog 一致]

---

## 4. 真实面经

| 时间 | 岗位 / Office | 题型 | 来源 |
|------|---------------|------|------|
| 2025-Q4 | Associate SWE London | PR review (NPM dep tree, recursive fix) + sys design SAST scanner | Glassdoor |
| 2025-Q2 | SWE I London | PR review + Go concurrency discussion | Glassdoor + Blind |
| 2024-Q4 | Cloud Security Intern London | Container scanning bug, take-home + 1 round | jointaro.com |
| 2025-Q3 | Security Researcher Grad | CVE write-up + reverse engineer sample malware | Glassdoor |

> Snyk Glassdoor positive rate 39% (低于公司 avg 59.8%) — 主要抱怨 timeline 太长 (5-8 周) 和 take-home 负担 [Glassdoor]

---

## 5. Offer 案例

| 时间 | 岗位 | Office | Base | Bonus | RSU (pre-IPO) | 总包 | 来源 |
|------|------|--------|------|-------|---------------|------|------|
| 2025-Q3 | Associate SWE | London | £70K | 10% | £25K/yr | ~£100K | Levels.fyi P25 推算 |
| 2025-Q2 | SWE II | London | £95K | 10% | £35K/yr | ~£137K | Levels.fyi median (实数) |
| 2024-Q4 | Senior SWE | London | £115K | 12% | £20K/yr | ~£150K | Levels.fyi Senior median |
| 2025-Q1 | Security Researcher Grad | London | £62K | 10% | £20K/yr | ~£88K | Glassdoor |
| 2025-Q2 | Field/Solutions Eng Grad | London | £55K + £15K commission | - | £15K/yr | ~£85K | Levels.fyi |

---

## 6. 申请渠道与建议

- **官方**: https://snyk.io/careers/ — 直接 "all-jobs" 页面: https://snyk.io/careers/all-jobs/
- **Emerging Talent**: 页面 filter "Early Career"
- **Greenhouse**: 直链多, 可订阅 alert
- **建议**:
  - Snyk 招 dev-first 思维 — 简历强调你**调试别人代码 / open source contribution / CVE 提交**比刷 LeetCode 更管用
  - 申请时**直接写 visa status + 是否需要 £5K relocation** — Snyk recruiter 会主动 route 到 sponsor pipeline
  - Take-home PR review 准备: 提前读 Snyk OSS repos (snyk/cli, snyk/snyk) 熟悉 codebase 风格
  - **不要做 LeetCode 准备** — 100% 浪费时间; 改读 npm dependency resolution, SAST 基础, OWASP top 10
  - **首选申 London Associate SWE / SWE I**, 跳过 senior 段 (难度差距大)

---

## 7. 踩坑与社区评价

- **优点**: 
  - WLB 实际不错 (London team ~40h/week)
  - Tech stack 现代 (TypeScript/Go), 不像 Darktrace 那种 legacy C++
  - Pre-IPO equity 是个 lottery — 2026 IPO 传闻 (但 2024 推迟过一次)
  - Glassdoor 评分 4.0/5
- **缺点**:
  - 招聘 timeline 慢 (5-8 周), 与 Big Tech 竞争 offer 容易被 ghost
  - Tel Aviv 是 R&D 大本营, London 实际是 EMEA sales + 少量 core eng
  - Remote-EU 政策收紧 (2024 起多数 role 要求 in-office 3 days)
- **裁员**: 2024-01 裁 14% (~200 人), 2024-11 又裁一轮 — pre-IPO cash burn 控制, 影响新 hire 信心

---

## 8. 对 UvA 学生 (NL student visa) 的具体评估 ⭐

- **核心 trade-off**: 这是该 list 里**对 NL student 最现实的 UK 选择** — 因为:
  - 官方明示 visa sponsor + £5K relocation
  - Grad base £65K+ 远超 £41,700 SW 阈值, 不需要博 NEC 折扣
  - Tech stack 主流 (TS/Go), 转化期短
- **Intern 可行性**: **低-中**
  - UK intern sponsor 仍罕见 — 即便 Snyk 也优先 UK 学生
  - 例外: 若你能拿 Snyk Tel Aviv intern (Israeli intern visa, 但路远成本高)
  - **建议**: 跳过 intern, 直接申 grad
- **FT 可行性**: **中-高** ⭐
  - SW £41,700 阈值: London base £65K+ 安全过
  - SOC 2134 going rate £49,400: 仍过
  - 官方 sponsor 政策明确 + £5K relocation = signal 强
  - Levels.fyi London median TC £137K (含 pre-IPO equity)
- **替代 NL 路径**: 
  - Snyk 无 NL office, NL remote 合同极少, **不要指望**
- **预计摩擦**: **中** (低于 Darktrace / Sophos / Ocado, 高于纯 NL 公司)
- **建议**: 
  - **优先级 = 该 list 第 1** (UK 公司中)
  - 申请直接在 cover letter 写: "I'm an UvA Master's student, will need UK Skilled Worker sponsorship + relocation from NL. Aware of Snyk's published support."
  - 9-10 月 grad cohort 窗口最优
  - 平行申: Datadog (London, 该 list 之外), Stripe Dublin (绕过 UK)

---

## 9. 所有引用链接

- Snyk 官方 careers: https://snyk.io/careers/
- Snyk all jobs: https://snyk.io/careers/all-jobs/
- Snyk engineering interview blog: https://snyk.io/blog/your-engineering-interview-snyk/
- immigrationgpt Snyk Limited: https://immigrationgpt.co.uk/company/snyk-limited
- Levels.fyi Snyk London SWE: https://www.levels.fyi/en-gb/companies/snyk/salaries/software-engineer/locations/london-metro-area
- Levels.fyi Snyk UK overall: https://www.levels.fyi/companies/snyk/salaries/software-engineer
- Levels.fyi Snyk Senior London: https://www.levels.fyi/companies/snyk/salaries/software-engineer/levels/senior-software-engineer/locations/london-metro-area
- techinterview Snyk Guide 2026: https://www.techinterview.org/companies/snyk-interview-guide/
- Glassdoor Snyk SWE interview: https://www.glassdoor.com/Interview/Snyk-Software-Engineer-Interview-Questions-EI_IE2094989.0,4_KO5,22.htm
- UK SW 阈值 2026: https://www.jobbatical.com/blog/uk-skilled-worker-visa-salary-threshold-employer-guide
- Snyk Indeed London: https://uk.indeed.com/q-snyk-l-london-jobs.html
