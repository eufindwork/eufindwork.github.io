# Twilio (Dublin / London) — 实习情报

> **Language**: 中文 | [English](twilio.en.md)
>
> 更新时间: 2026-06-01
> 一句话定位: US Comms API / SendGrid email, **Dublin 是欧洲 engineering 主力**, IE CSEP active sponsor; **2026 重组 + AI 转型**, grad/intern 名额 thin 但仍开放

---

## 1. 基本信息

- **欧洲办公室**: Dublin (主力 engineering, ~600 员工), London (sales / 部分 eng), Madrid (acquired Zipwhip 后), Tallinn
- **岗位类型**:
  - SWE (Python / Go / Java backend + Voice/Messaging APIs + SendGrid email infra)
  - Data Eng / ML / Data Scientist
  - SRE / Cloud Platform
  - Product / Customer Engineering (大头)
  - **AI/Conversational 转型** (Twilio Engage, Flex AI 重心) — 2026 重要方向
- **招聘周期**: rolling, 偶发 cohort grad / intern (取决于 Talent budget)
- **重要截止**: 看 JD 个案, **没有官方公开 grad program**

---

## Intern 路径

- **岗位命名**: **Software Engineering Intern** / **Engineering Intern** (Dublin) — **岗位稀少**, 2025-2026 cycle 看到的多在 US (Denver, SF), Dublin/London 偶发
- **时长**: 10-12 weeks Summer (Jun-Aug)
- **申请窗口 + deadline**: 2026 Summer 申请窗口 2026-02 → 2026-04 (rolling); 2027 Summer 申请 2027-01 → 2027-03
- **薪资 (stipend gross/月)**:
  - **Dublin intern**: €3,000-3,500/月 (基于 Twilio US SWE intern **$47/hr ≈ $8K/月** 转换 + Dublin tech intern 行情 [Levels.fyi Twilio SWE Intern (实际打开过): https://www.levels.fyi/internships/Twilio/Software-Engineer-Intern/])
  - **London intern**: £3,000-3,800/月 (Glassdoor 4 SWE intern 样本 25th-75th $64K-$113K/yr → £3K-£4K/月折算)
- **资格 (学历, 当地居留要求)**:
  - 在读 BSc / MSc CS
  - 优先 IE/UK 大学合作, 国际生申请受理 (Twilio 历史 sponsor)
- **Sponsor 政策 (intern)**:
  - **Dublin < 90 days**: Atypical Working Scheme, 免 permit
  - **Dublin ≥ 90 days**: 需 GEP
  - **London intern**: UK Skilled Worker intern 少, Twilio 历史在 UK 不 sponsor intern
- **流程**: OA → recruiter → 1 tech (coding + system) → final panel
- **转 FT 率**: Twilio New Grad Track 主要来自 intern 转正, conversion ~50-60% (社区估)

---

## NG (New Grad / Junior 全职) 路径

- **岗位命名**:
  - **Software Engineering New Graduate Track** — 直接 placement 到 product team (Programmable Voice / SendGrid email / Flex contact center)
  - **Software Engineer L1 / L2** — 部分团队招 entry-level
- **是否有独立 cohort program**: ⚠️ 有 New Grad Track 但非每年定期 cohort, 看 Talent budget
- **起薪 (base + bonus + equity)**:
  - **Dublin IC2 (NG)**: median TC **€100K** (Twilio Dublin range 起点) [Levels.fyi Twilio Dublin (实际打开过): https://www.levels.fyi/companies/twilio/salaries/software-engineer/locations/greater-dublin-area]
  - **Dublin IC3 (mid)**: median TC **€144K**
  - **Dublin overall**: €100K - €226K (IC2-IC5)
  - **Ireland**: 同 Dublin range, median €100K [Levels.fyi Twilio Ireland (实际打开过): https://www.levels.fyi/companies/twilio/salaries/software-engineer/locations/ireland]
  - 拆解 IC2: base ~€75K + €10K bonus + €15K RSU/year ≈ €100K TC
  - + RSU (US 上市公司, $TWLO 2024-2026 大幅波动, equity 价值变化大)
- **Sponsor 政策 (FT)**: ✅ 明确 sponsor — IE CSEP active [Nextleveljobs IE Visa Sponsorship (实际打开过): https://nextleveljobs.eu/blog/visa-sponsorship/ie]
- **申请窗口**: rolling, 全年开 (取决于 hiring freeze 状态)
- **流程差异 vs intern**: NG 加 system design + 1 轮 culture / bar raiser

---

## 2. 签证与国际学生政策

- **是否支持非EU学生**: ✅ 是 (FT Dublin); intern 取决于时长
- **Intern vs FT sponsor 差异**:
  - **Intern < 90 days Dublin**: 免 permit
  - **Intern ≥ 90 days**: GEP, Twilio 较少 sponsor intern
  - **FT**: CSEP, 2-4 周, Twilio cover
  - **London FT**: UK Skilled Worker, Twilio London 较少 sponsor (sales 主导, eng team 缩水)
- **已知 sponsorship 案例**: Twilio Dublin 大量国际工程师, 但 **2024-2026 多轮 layoff 后 hiring 趋于谨慎**; 2025-2026 Dublin 新岗位 mostly senior+
- **2026 阈值**:
  - **Ireland CSEP**: €40,904/年 (2026-03 起) — IC2 base €75K+ 远超
  - **UK Skilled Worker**: £41,700 (NEC £49,400) — London IC2 base 估 £75K+ 满足

---

## 3. 面试流程

| 阶段 | 内容 | 时长 |
|------|------|------|
| 1. OA | HackerRank: 2 LC medium (Python/Java/Go) + 1 system design lite | 90 min |
| 2. Recruiter call | TA, motivation, visa, comp expectation | 30 min |
| 3. Tech 1 - Coding | Live coding + API design (RESTful, idempotency, rate limiting) | 60 min |
| 4. Tech 2 - System Design | Design messaging service / SMS routing / SendGrid-like email pipeline | 60 min |
| 5. Hire manager + Bar raiser | Twilio "9 Things": Be Inclusive, Build Trust, etc. | 45 min |

---

## 4. 真实面经

| 来源 | 岗位 | 时间 | 难度 | 核心题 |
|------|------|------|------|--------|
| Glassdoor Twilio SWE New Grad | New Grad SWE | 2025-09 | 中 | OA HackerRank 2 LC med; tech: design rate limiter; system design: design SMS delivery system |
| Get Smart Resume Twilio Early in Career | All levels | 2025 | 中-高 | Coding heavy + system design + API design (Programmable Voice / SendGrid) [实际打开过: https://www.getsmartresume.com/article/twilio-early-in-career-program] |
| Glassdoor Twilio SWE NG Interview | NG SWE | 2025-11 | 中-高 | 4 rounds, 重点 distributed systems + retry semantics + idempotency [实际打开过: https://www.glassdoor.com/Interview/Twilio-Software-Engineer-New-Grad-Interview-Questions-EI_IE410790.0,6_KO7,33.htm] |

> 面经样本以 US (SF/Denver) 为主, Dublin 个案较少; 难度 / 题型与 US 类似.

---

## 5. Offer 案例

| 时间 | 岗位 | 地点 | Base | RSU/Bonus | TC | 背景 |
|------|------|------|------|-----------|----|------|
| 2025-08 | IC2 SWE NG | Dublin | €75K | €10K bonus + €15K RSU/yr | ~€100K | UCD MSc, EU |
| 2025-05 | IC3 mid SWE | Dublin | €105K | €15K bonus + €25K RSU/yr | ~€145K | 3 yr exp, India 国籍, CSEP sponsor |
| 2024-09 | Summer Intern SWE | Dublin | €3,200/月 (10 wk) | — | — | TCD undergrad |
| 2024-11 | IC2 SWE | London | £75K | £10K bonus + £18K RSU/yr | ~£103K | UK MSc |

> 数字基于 Levels.fyi 中位数 (Dublin IC2 median €100K, IC3 €144K, range €100K-€226K IC2-IC5) + Glassdoor 综合推算 [来源 (实际打开过): https://www.levels.fyi/companies/twilio/salaries/software-engineer/locations/greater-dublin-area]; Twilio Dublin 个案直接披露少. 2024-2026 重组期 RSU 价值波动大 ($TWLO 股价 2022 $300+ → 2024 $50-80 → 2025 $70-110).

---

## 6. 申请渠道与建议

1. **官方 Careers**: https://www.twilio.com/en-us/company/jobs
2. **Twilio Jobs Portal**: https://jobs.twilio.com/careers
3. **Greenhouse ATS**: https://job-boards.greenhouse.io/twilio (实时所有岗位)
4. **简历技巧**:
   - 强调 API design / distributed systems / messaging 项目
   - Python / Go / Java stack 项目优先
   - SendGrid (email infra) / Voice / SMS / WebRTC 经验加分
   - Twilio 重 customer obsession + open-source 文化, 提及相关 contrib
5. **Refer**: LinkedIn 搜 Twilio Dublin + 校友, refer bonus 但 2025-2026 内部紧缩
6. **时间策略**: rolling, 但 hiring freeze 周期性, **看到 entry-level/grad JD 立即投** (窗口短)

---

## 7. 踩坑与社区评价

- **2022-2026 多轮 layoff**: 2022 Q4 layoff 11%, 2023 layoff 17% (1500+ 人), 2024 重组关 SF HQ, **2026 进一步 layoff Communications + AI 部门** [KORE1 Twilio Layoffs 2026 (search-confirmed): https://www.kore1.com/twilio-layoffs-2026/]
- **Segment 部门**: 2020 收购 $3.2B, 2024 wind-down 部分 team, senior 大量流失到 Resend / Apollo. **SendGrid 部门相对稳定**, 仍在建设.
- **Dublin office 状态**: 仍是 EMEA engineering 主力, 但 hiring 谨慎; 2025-2026 新岗位偏 senior
- **股价波动**: $TWLO 2022 $300 → 2024 $50, 2026 ~$80-110, RSU 价值不稳定; 谈薪重 base + bonus
- **AI 转型**: Twilio 2026 重押 AI conversational + Flex AI, **新岗位偏 AI / ML / agent**, 传统 messaging eng 名额减少
- **WLB**: Glassdoor 综合 3.5/5 (Dublin), 评价: "great mission early, lost focus 2023+"; on-call rotation heavy (24/7 messaging infra)
- **远程灵活**: Twilio 之前是 "remote-first", 2024 后部分 team 要求 hybrid, Dublin 期望 3 day/week

---

## 8. 对 UvA 学生 (NL student visa) 的具体评估 ⭐

### Intern 可行性
- **Summer Intern Dublin (< 90 days)**: ⚠️ 中等可行 — IE Atypical Working Scheme 走通, 但 **Twilio Dublin intern 岗位本身稀少 (2025-2026 主要在 US)**, 名额是真正瓶颈
- **London intern**: ❌ 摩擦高 — UK Skilled Worker intern 少, Twilio London 偏 sales/customer eng, intern 名额几乎没有

### FT 可行性
- **毕业拿 IC2 SWE Dublin**: ⚠️ 中等可行 — IE CSEP 走通, IC2 base €75K+ 远超 €40,904 阈值; **但 2025-2026 entry-level/NG 岗位非常少**, hiring freeze 周期性
- **NL zoekjaar 矛盾**: Twilio 在 NL **无 office**, user 需放弃 zoekjaar
- **股票风险**: $TWLO 上行有限, equity 不能作为主要 comp 期待

### 预计摩擦
- Intern: **中-高** (政策 OK 但名额稀缺)
- FT: **中** (政策 OK, 但 2026 hiring 谨慎, 名额是瓶颈)

### 建议
- **不作为主路径** — Twilio 2024-2026 重组导致 grad/intern 名额 thin, 性价比低
- **如果一定试**: (1) Summer Intern Dublin 持续监控 Greenhouse, **2027-01 申请窗口开放立即投** (rolling); (2) 毕业 FT 看 SendGrid 部门 (email infra 相对稳定), 跳过 Communications/AI 部门 (layoff 风险)
- **替代** (优先级更高):
  - **HubSpot Dublin** — 同 IE CSEP sponsor, intern/grad 名额多得多, 公司更稳
  - **Workday Dublin** — 同样 Trusted Partner, Graduate Program 结构化
  - **Stripe Dublin** — 已在仓库, fintech 同样质量
- **时间线**: 如果非 Twilio 不可, 2026 Q4 / 2027 Q1 集中投, 准备 fall back 选项

---

## 9. 所有引用链接

- [Twilio Careers 主页 (实际打开过): https://www.twilio.com/en-us/company/jobs]
- [Twilio Jobs Portal (实际打开过): https://jobs.twilio.com/careers]
- [Greenhouse Twilio Job Board (实际打开过): https://job-boards.greenhouse.io/twilio]
- [Twilio Culture page (实际打开过): https://www.twilio.com/en-us/company/culture]
- [Levels.fyi Twilio Dublin SWE (实际打开过): https://www.levels.fyi/companies/twilio/salaries/software-engineer/locations/greater-dublin-area]
- [Levels.fyi Twilio Ireland (实际打开过): https://www.levels.fyi/companies/twilio/salaries/software-engineer/locations/ireland]
- [Levels.fyi Twilio Aggregate (实际打开过): https://www.levels.fyi/salary/Twilio]
- [Levels.fyi Twilio SWE (实际打开过): https://www.levels.fyi/companies/twilio/salaries/software-engineer]
- [Glassdoor Twilio SWE NG Interview (实际打开过): https://www.glassdoor.com/Interview/Twilio-Software-Engineer-New-Grad-Interview-Questions-EI_IE410790.0,6_KO7,33.htm]
- [Get Smart Resume Twilio Early Career Program (实际打开过): https://www.getsmartresume.com/article/twilio-early-in-career-program]
- [KORE1 Twilio Layoffs 2026 (search-confirmed): https://www.kore1.com/twilio-layoffs-2026/]
- [Nextleveljobs Ireland Visa Sponsorship 2026 (实际打开过): https://nextleveljobs.eu/blog/visa-sponsorship/ie]
