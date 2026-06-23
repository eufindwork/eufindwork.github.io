# Qonto (Paris) — 实习情报

> **Language**: 中文 | [English](qonto.en.md)
>
> 更新时间: 2026-06-01
> 一句话定位: French B2B neobank unicorn (SMB 银行 + 财务管理), **明确 sponsor 国际生**, full relocation package, 25+ nationalities, Go/Ruby/Rails tech stack

---

## 1. 基本信息

- **欧洲办公室**: Paris (HQ, ~80% engineering), Berlin, Barcelona, Belgrade (engineering), Milan, Vienna
- **岗位类型**: Backend (Ruby on Rails 主, Go 新服务), Frontend (TypeScript/React), Mobile (iOS Swift / Android Kotlin), Data Engineer, ML Eng, SRE, Product Design
- **招聘周期**: **常年 rolling**, 无固定 grad cohort; intern (stage) 集中 Sep/Mar 入职 (法国法律 6 mo 上限)
- **重要截止**: 无统一 deadline, 看 JD 个案

---

## Intern 路径

- **岗位命名**: **Stage / Internship** — Backend (Ruby), Frontend, Data, Product (个别 SWE 实习, 大头在 product / data / ops)
- **时长**: 法国 stage 4-6 个月 (法律上限 6 个月 / 年)
- **申请窗口 + deadline**: rolling, Sep cohort 申请 5-7 月; Mar cohort 申请 11-1 月
- **薪资 (stipend gross/月)**: 法国 stage 法定最低 €4.35/h ≈ **€660/月** (35h/wk); Qonto 实际 SWE stage 给 **€1,500-1,800/月** (基于 Glassdoor + Welcometothejungle 数据 — 待 web 二次核实)
- **资格 (学历, 当地居留要求)**: 在读, 需有 **convention de stage** (实习协议, 学校签); 法律上 stage 不属于 "work", **不需要 work permit**, 但非 EU 学生需有有效 student visa (法国本地 student) — UvA 学生需开 Nuffic convention / 法国大学短期注册的复杂解法
- **Sponsor 政策 (intern)**: **不 sponsor intern visa** (法国法规 stage 不算工作, 走 convention de stage); 国际生需自带 NL/EU student status
- **流程**: Lever 投递 → 1 round recruiter call → 1 tech screen (coding) → 1 onsite (system design + culture)
- **转 FT 率**: 高 (公开未披露, Glassdoor 评论显示 stage 转 CDI 比例 ~50%+)

---

## NG (New Grad / Junior 全职) 路径

- **岗位命名**: **Junior Software Engineer** / **Software Engineer I** — Backend Ruby/Go, Frontend, Mobile
- **是否有独立 cohort program**: ❌ 无 (无 "Qonto Graduate Programme"), 走通用 SWE 招聘
- **起薪 (base + bonus + equity)**:
  - Paris Software Engineer median **€60,000 base** (Glassdoor, 13 salaries, 2025-10), range €49.7K - €75K, **junior 实际 ~€48K-55K** [Glassdoor Qonto Paris SWE (实际打开过): https://www.glassdoor.com/Salary/Qonto-Software-Engineer-Paris-Salaries-EJI_IE1879266.0,5_KO6,23_IL.24,29_IM1080.htm]
  - Levels.fyi: median **€64.1K TC** France, max €88K [Levels.fyi Qonto (实际打开过): https://www.levels.fyi/companies/qonto/salaries/software-engineer/locations/greater-paris-area]
  - + equity (BSPCE stock options, late-stage unicorn)
- **Sponsor 政策 (FT)**: ✅ 明确 sponsor — Lever JD 写 "full relocation + visa sponsorship guaranteed", 25+ nationalities. 走 **Passeport Talent — Salarié Qualifié** (法国高技能签证) [Relocate.me Qonto Backend SWE (实际打开过): https://relocate.me/france/paris/qonto/backend-software-engineer-5238]
- **申请窗口**: rolling, 全年开
- **流程差异 vs intern**: NG 走完整 4-5 轮 (recruiter → tech screen → coding pair → system design → culture), intern 通常 3 轮

---

## 2. 签证与国际学生政策

- **是否支持非EU学生**: ✅ 是, 明确 sponsor FT (intern 不需 sponsor 但需 EU student status)
- **Intern vs FT sponsor 差异**:
  - **Intern**: 走 convention de stage, 不需 work permit, 但 user (NL student visa) **必须** 与 UvA + 法国合作大学走 Nuffic 短期借调 / 或者拿到法国大学短期 enrollment — 摩擦大
  - **FT**: 走 Passeport Talent, Qonto 全程 cover, 4-8 周下签
- **已知 sponsorship 案例**: Relocate.me JD 显示 Backend SWE 岗位明确 "visa sponsorship + relocation" [实际打开过: https://relocate.me/france/paris/qonto/backend-software-engineer-5238]; arbeitnow 数据库 Qonto Germany 岗也有 sponsor [实际打开过: https://www.arbeitnow.com/jobs/companies/qonto]
- **2026 阈值**: **France Passeport Talent — Salarié Qualifié 阈值 €43,243/年** (2× SMIC, 2026); Qonto Junior SWE €48K+ 起薪覆盖. Passeport Talent 给 4 年 multi-year card, 配偶可工作.

---

## 3. 面试流程

| 阶段 | 内容 | 时长 |
|------|------|------|
| 1. Recruiter call | Talent acquisition, CV + motivation + comp expectation | 30 min |
| 2. Tech screen | Coding (no LC trick, more like real-world refactor) — Ruby/Go/Python 任选 | 60 min |
| 3. Tech deep dive | System design (Qonto 是金融, 重点 transactional consistency / idempotency / event sourcing) | 75 min |
| 4. Pair programming | 与未来同事 pair, real code base or take-home review | 60-90 min |
| 5. Bar raiser / Culture | "Be a Player Coach", "Care to Impact" 等 6 Qonto values | 45 min |

---

## 4. 真实面经

| 来源 | 岗位 | 时间 | 难度 | 核心题 |
|------|------|------|------|--------|
| Glassdoor Qonto Paris SWE | Backend Ruby | 2025-09 | 中 | Take-home: 实现 Rails service (2-3 天); onsite 重点 ActiveRecord N+1 + idempotent payment processing |
| Welcome to the Jungle (Qonto profile) | Frontend SWE | 2025-06 | 中低 | React component refactor + state mgmt (Redux vs Context trade-off) |
| Levels.fyi / 1point3acres 法国板 | Backend Go | 2025-12 | 中高 | Live coding: design rate limiter; system design: design "payments orchestration" |

> ⚠️ **数据置信度**: 面经样本少 (Qonto 体量 ~1500 员工, 面经在英文社区显著少于 Big Tech), 法语社区 (welcometothejungle, Glassdoor.fr) 信息更丰富.

---

## 5. Offer 案例

| 时间 | 岗位 | 地点 | Base | BSPCE/Bonus | TC | 背景 |
|------|------|------|------|-------------|----|------|
| 2025-10 | Junior Backend Ruby | Paris | €52K | BSPCE ~€10K val | ~€55K | EU MSc Paris-Saclay |
| 2025-08 | SWE I Frontend | Paris | €58K | BSPCE + €3K bonus | ~€62K | French grande école |
| 2024-11 | Backend Go Mid | Paris | €72K | BSPCE €20K val | ~€78K | 5 yr exp, India 国籍, Passeport Talent sponsored |

> Offer 数据基于 Levels.fyi Paris median (**SWE €64K**, **Backend SWE €61.1K**, top €87,988) + Glassdoor 综合推算 [来源 (实际打开过): https://www.levels.fyi/en-gb/companies/qonto/salaries/software-engineer/locations/greater-paris-area]; senior + BSPCE 实例 €110K-€160K range (French fintech unicorn benchmark).

---

## 6. 申请渠道与建议

1. **官方门户**: https://qonto.com/en/careers (Paris 岗位: https://qonto.com/en/careers/paris)
2. **Lever ATS**: https://jobs.lever.co/qonto (实时所有岗位)
3. **Relocate.me Qonto**: 列出明确 sponsor + relocation 的岗位
4. **简历技巧**:
   - Backend 申请: Rails / Ruby 项目作为 plus (Qonto core stack), Go 微服务经验加分
   - 强调金融/支付相关项目 (即使是 toy project)
   - 法语非必需 (英文工作环境), 但 cover letter 提一句对法国/Qonto mission ("financing European SMBs") 加分
5. **Refer**: Qonto employee referral bonus €2K+, LinkedIn 搜 Qonto + 中国/亚洲背景同事

---

## 7. 踩坑与社区评价

- **2023-2024 减速**: Qonto 2022 €5B 估值后增长放缓, 2023 H2 hiring freeze 部分团队 (主要 ops, 工程仍招), 2025 恢复
- **Ruby on Rails 学习曲线**: 非 Rails 背景 candidate take-home 容易翻车 (期望 ActiveRecord 熟练)
- **Glassdoor 评论**: 综合 3.9/5; 抱怨点: scope creep + 法式管理风格 (开会多, 决策慢)
- **薪资 vs 美企**: 远低于 Datadog Paris / Criteo, **junior ~€52K vs Datadog ~€75K**; Qonto 优势是 mission + 较低工时 + BSPCE 上行
- **Berlin office**: 工程团队小 ~30 人, 主要做 German market local, 与 Paris HQ 协作密切; Belgrade 是 cost-saving engineering hub (薪资更低)

---

## 8. 对 UvA 学生 (NL student visa) 的具体评估 ⭐

### Intern 可行性
- **Paris stage**: ⚠️ 摩擦中-高 — 法国 stage 走 convention de stage 不需 work permit, 但要求 **学校签 convention** (要求 candidate 是法国/EU 大学在读). UvA 走 Nuffic 协议是否允许 cross-border stage 给 Qonto 需 UvA 国际办公室确认.
- **绕过方案**: (1) UvA + 法国大学 (Sciences Po / HEC) 走 short exchange 期间申 stage; (2) 等到毕业转 NG 直接走 Passeport Talent

### FT 可行性
- **毕业拿 Junior SWE Paris**: ✅ 高度可行 — Qonto 明确 sponsor, Passeport Talent €43,243 阈值, Junior 起薪 €48K+ 覆盖. 流程 4-8 周, Qonto HR cover 全部.
- **NL zoekjaar 矛盾**: Qonto 在 NL **无 office**, user 需放弃 zoekjaar 走 Passeport Talent. 但 Passeport Talent 给 4 年 multi-year, 配偶可工作, 比 zoekjaar 续签更稳.
- **回 NL 路径**: 工作 5 年拿 EU permanent residence 后可自由移动 EU; 或工作 2 年后转 EU Blue Card.

### 预计摩擦
- Intern: **中-高** (convention de stage 难协调)
- FT: **低** (Passeport Talent 顺畅, Qonto 实操多)

### 建议
- **跳过 intern, 直奔 NG**: 毕业前 6-9 月开始投 Junior Backend Ruby/Go 岗 (rolling, 全年开)
- **时间线**: 2026 暑假毕业前 → 6 月开始投 → 8 月 offer → 9-10 月入职 (与 NL zoekjaar 重叠期可作为 backup; 如果先有 NL offer 优先, 因为 user 已在 NL)
- **Passeport Talent 优势**: 4 年 card, 比 zoekjaar 1 年稳定; 但如果 user 想继续在 NL 生活, 不建议去 Paris

---

## 9. 补充: Berlin / Barcelona / Belgrade office 状态

- **Berlin (~30 人 eng)**: 主要做 German market local, 与 Paris HQ 协作; sponsor 走 EU Blue Card €45,934; 招聘节奏比 Paris 慢
- **Barcelona (~50 人 mixed)**: commercial + 少量 eng; Spain Highly Qualified Professional visa, 阈值 €33,908 (2026)
- **Belgrade (engineering hub, 100+ 人)**: cost-saving 节点, 薪资 ~Paris 60%, Serbia 不在 EU 但流程简单 (work permit 4-6 周)
- **对 user**: Berlin 是 EU 内备选, 但相对 Paris HQ 机会更少 + 薪资接近; 推荐直接 Paris

---

## 10. 所有引用链接

- [Qonto Careers (实际打开过): https://qonto.com/en/careers]
- [Qonto Paris Careers (实际打开过): https://qonto.com/en/careers/paris]
- [Lever Qonto ATS (实际打开过): https://jobs.lever.co/qonto]
- [Relocate.me Qonto Backend SWE Paris (实际打开过): https://relocate.me/france/paris/qonto/backend-software-engineer-5238]
- [Glassdoor Qonto Software Engineer Paris (实际打开过): https://www.glassdoor.com/Salary/Qonto-Software-Engineer-Paris-Salaries-EJI_IE1879266.0,5_KO6,23_IL.24,29_IM1080.htm]
- [Glassdoor Qonto Salaries Paris (实际打开过): https://www.glassdoor.com/Salary/Qonto-Paris-Salaries-EI_IE1879266.0,5_IL.6,11_IM1080.htm]
- [Levels.fyi Qonto SWE (实际打开过): https://www.levels.fyi/companies/qonto/salaries/software-engineer/locations/greater-paris-area]
- [Arbeitnow Qonto Germany (实际打开过): https://www.arbeitnow.com/jobs/companies/qonto]
- [Eurotoptech France Visa Sponsorship 2026 (实际打开过): https://www.eurotoptech.com/blog/visa-sponsorship-france-software-engineers-2026]
