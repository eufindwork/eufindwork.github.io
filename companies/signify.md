# Signify (前 Philips Lighting) 实习情报

> **Language**: 中文 | [English](signify.en.md)
>
> 更新时间: 2026-10-10
> ⚠️ **2026-10-10 勘误**: 本页 New Grad 段已刷新; 下文其他段落中以下旧说法已过时, 以 New Grad 段为准 — 开头 'Workday 仍挂 338660' 与 'Capital Markets Day 待公布' (338660 疑已下架; CMD 已于 2026-06-23 举行, 结果见 New Grad 段).
> 信息丰富度: ⭐⭐⭐ (官方 + Glassdoor 面经聚合 + Philips 母公司 stipend 公示 + 2026-01 layoff 报道; 缺中文社区面经)
> 一句话定位: 全球智能照明 / IoT 灯具龙头 (Philips Hue / WiZ / Interact), 2018 年从 Philips 分拆独立上市, R&D 重镇在 Eindhoven; 面试以行为面为主, 但 Hue / SW Dev 岗位有 case study + 技术深聊
>
> ⚠️ **2026 关键变化 (重要)**: (1) **Signify 2026-01-30 宣布全球裁员 900 人 + €180M cost-cutting 计划**, CEO As Tempelman 将 2026 定义为 "transitional year", 全公司战略 / portfolio review 结果将在 **2026-06-23 Capital Markets Day** 公布 [来源 (实际打开过): https://www.metaintro.com/blog/signify-job-cuts-2026, finance.yahoo.com (Reuters 同步)]. (2) 自 2023 年起累计裁员约 6,200 人 (员工总数从 34,619 降至当前估算 28,000 左右). (3) 股价 2026-01-30 财报后跌 15% 创新低. (4) **Junior IT / Digital Program 仍开放招聘** (Workday 仍挂 338660), 但**全公司 hiring climate 转保守**, grad cohort size 可能缩水 (官方未公布数字, 但 €180M 削减目标会传导). 建议: 申请前用 Glassdoor 看 2026 Q1-Q2 employee reviews + LinkedIn 看 Signify Eindhoven 离职动态.

⚠️ **务必区分**:
- **Signify** (本文档主体, NYSE: LIGHT.AS) ≠ **Signifyd** (反欺诈, San Jose) ≠ **Signify Health** (美国 home care, CVS 旗下)
- **Philips** (本文档参考, NYSE: PHG) 是另一家公司 — 医疗器械为主, 但与 Signify 共用 Eindhoven HighTech Campus, 实习政策和 stipend 高度可比

---

## 1. 基本信息

### 欧洲办公室
| 城市 | 角色 | 备注 |
|------|------|------|
| **Eindhoven (NL)** | Global HQ + 主 R&D | High Tech Campus 7; 智能照明 / Hue / Interact 主要工程团队所在地 |
| Amsterdam (NL) | 部分商业 + Philips 母品牌交接 | Philips 总部 1997 起在 Amsterdam, Signify 在荷兰有 office 分布 |
| Burgos (ES) | 部分制造 | — |
| 全球 | 70+ 国家 | Sales / 区域市场 |

### 实习岗位类型 (从 careers.signify.com / Built-In 公开岗位归纳)
- **Software Development** (Philips Hue 重点): App development (Flutter / DART), C++, Rust; 智能家居 features, 自动化, accessory
- **R&D / Hardware**: 灯具光学, 电源, 嵌入式 firmware
- **Data Science / Analytics**
- **Product Management** (Philips Hue PM intern, marketing intern)
- **Business Process Optimization**

### 实习时长与招聘周期
- **官方 SW Dev intern 最低 6 个月** (Philips Hue Internship Software Development 岗位 354870 历史描述明确写 "minimum 6 months"; 2026-06 抓取时该单一岗位已下架 HTTP 410, 但 careers.signify.com Eindhoven intern 列表仍有 7+ 活跃岗位包括 Communication / Sustainability Data / Digital Marketing / Product Management / Digital Control Solution / Mechanical Engineering intern 等) [来源 (实际打开过): https://www.careers.signify.com/global/en/job/354870/Internship-Software-Development-Philips-Hue (HTTP 410), 以及搜索结果 site:careers.signify.com 7+ 活跃岗位]
- **必须 full-time available 6 个月以上**
- 招聘周期: 全年滚动 (rolling), 没有固定 cohort; Glassdoor 数据显示**从申请到 offer 平均 20–28 天** (4 周)
- ⚠️ **2026-Q1 layoff 后状态**: SW Dev Philips Hue intern 岗 354870 已下架 (HTTP 410 Gone), 短期内**软件类 intern hiring 大概率收紧**; 但 R&D / 硬件 / Marketing / Sustainability 类 intern 仍在挂

---

## New Grad / Junior 岗位

> 核查日期: 2026-10-10 (实时 WebFetch + Workday API) | 信息丰富度: ⭐⭐⭐ (依据: Workday 实时检索 + CMD 2026 新闻稿 + Q2 2026 报告 + IND 登记册 + Levels.fyi NL; 缺 grad scheme 官方薪资 / cohort 数据)
> **2027 Intake 状态**: **Closed (未开放)** — 2026-10-10 Workday 检索 "graduate" / "junior" / "program" 均无 Eindhoven grad scheme 岗位; **Junior Digital Program (Graduate) 338660** 的 Workday API 返回 HTTP 403 "permission denied" (对照: 在招岗位 366156-1 正常返回) → 推断已下架; 官方 new-graduates 页只有 Talent Community 注册 [来源 (实际打开过): https://www.careers.signify.com/global/en/new-graduates]
> 2026 H2 动态: (1) **2026-06-23 Capital Markets Day** — "a more focused, better-performing company": Build (connected lighting / Consumer / 部分 Professional) vs Harvest (non-connected LED lamps / Conventional); 2029 目标 CSG 0-1%、adj. EBITA c. 10%、FCF 7-8% of sales; 执行重点含 "digital and AI" 与 "continued cost discipline"; 未公布新的裁员数字 [来源 (实际打开过): https://www.signify.com/static/cmd/2026/20260623-press-release-signify-capital-markets-day-2026.pdf]。(2) **Q2 2026 (2026-07-24)**: sales EUR 1,332M, CSG -3.6%, adj. EBITA 6.1%, restructuring EUR 31M (主要属 2026-01 宣布的 EUR 180M 降本计划), FTE 29,456 → 25,866 (同比, 主要是工厂人员) [来源 (实际打开过): https://www.signify.com/static/quarterlyresults/2026/q2_2026/signify-second-quarter-results-2026-report.pdf]; Q3 业绩 2026-10-23 发布

> ⚠️ **重要更正 (保留)**: "Edison Graduate Programme" 是 **GE Aerospace / GE Healthcare 的项目, 不属于 Signify**; Signify 的 grad scheme 是 **Junior IT Program (Graduate)** 与 **Junior Digital Program (Graduate)**

> ⚠️ **待 web 验证**: 下列 "资格窗口" 与 "面试流程" 中 Junior IT / Digital Program 的细节 (0-1 yr 经验、Assessment & Selection Day、case study) 来自 2026-06 版记录的 The Muse / Workday 搜索摘要; 2026-10-10 岗位已下架、new-graduates 页已无此描述, 无法复核; 二次核实前勿用于决策.

- **岗位名称**: **Signify's Junior IT Program (Graduate)** (The Muse 刊登, IT / 数字基础设施方向) / **Signify's Junior Digital Program (Graduate)** (Workday 338660, Digital organization 方向); 常规 junior 线: Software Development Engineer (Hue) [来源: https://www.careers.signify.com/jobs/software-development-engineer-hue-eindhoven/] — 2026-10-10 Workday 未见同类 Eindhoven 岗位
- **资格窗口**: 0-1 yr 经验的 digital / IT 方向毕业生 (见 ⚠️); 学位 / 语言要求无公开数据; 注意部分 Eindhoven 全职 JD 要求 "Fluency in Dutch" (如 Customer Support Engineer, 2026-10)
- **欧洲地点**: Eindhoven (HQ, High Tech Campus) 是 grad scheme 唯一已知地点。2026-10-10 Workday 全球 258 个岗位; "Eindhoven" 检索 18 条, 全职仅 Business Development Manager New Spaces / Strategic Sourcing Manager / Product circularity engineer / Functional Engineer (Pricing) / Customer Support Engineer, 其余为实习 [来源 (API 读取): https://lighting.wd3.myworkdayjobs.com/wday/cxs/lighting/jobs-and-careers/jobs]
- **项目结构**: 时长 / rotation / cohort size 均无公开数据
- **非EU签证 (全职)**: **Signify Netherlands B.V. (KvK 17061150)**、Signify N.V. (65220692)、Signify Holding B.V. (17054234) 均在 IND recognised sponsor 登记册 (2026-10-05 版) [来源 (实际打开过): https://ind.nl/en/public-register-recognised-sponsors/public-register-work] → 可办 Kennismigrant, 从 NL 学生签 / zoekjaar 转入可行 (推断); IND 2026 门槛 (月薪, 不含 holiday allowance): reduced (zoekjaar 期间 / 毕业 3 年内) €3,122, <30 岁 €4,357, ≥30 岁 €5,942 [来源 (实际打开过): https://ind.nl/en/required-amounts-income-requirements]; grad 起薪对 reduced 门槛通常不构成障碍, 对 <30 岁标准门槛可能偏紧 (推断)
- **薪资 (gross/年)**:
  - Levels.fyi Signify SWE Netherlands (2026-10-10): median total **€55.9K**, 区间 €46K–€55.9K+, 最高 €91,685, 平均 €63,269 [来源 (实际打开过): https://www.levels.fyi/companies/signify/salaries/software-engineer/locations/netherlands]
  - Levels.fyi Signify SWE 总览 (以 US 为主, 29 条, 2026-10-10): Level 14 "Junior Development Engineer (Entry Level)" 无数据; Level 15 $130K total ($121K base + $5.6K stock + $2.5K bonus); median $140K [来源 (实际打开过): https://www.levels.fyi/companies/signify/salaries/software-engineer]; 旧版 2026-06: n=15, median $143K, Level 15 base $115K + stock $7.5K/yr + bonus $3.3K
  - Eindhoven SWE 城市基准 (非 Signify 特定, Glassdoor 2026-05): median €60.6K, 25%-75% €47K-€75K [来源 (实际打开过): https://www.glassdoor.com/Salaries/eindhoven-software-engineer-salary-SRCH_IL.0,9_IC3043137_KO10,27.htm]
  - Junior IT / Digital Program 起薪: 无公开数据; 另有 8% holiday allowance; JD 写 "Annual performance and company bonus" + 25 天假 (Customer Support Engineer, 2026-10); grad 通常无 RSU
- **申请窗口**: 无公开 batch 时间表; 338660 在 2026-06-01 仍挂 (旧版记录), 2026-10-10 已不可访问; 下一期无公告, 只能注册 Talent Community 等通知
- **面试流程**: Junior IT / Digital Program: Assessment & Selection Day @ High Tech Campus Eindhoven (speed-dating interviews + case study, recruiter 按表现与偏好匹配岗位; 见 ⚠️); 常规 junior 岗: Recruiter → Tech → Manager; 2025-26 新面经未找到 (Glassdoor 403, WebSearch 配额用尽)
- **录取竞争**: 无 volume 数据; 降本期 (FTE 同比减少约 3,590) grad 招聘收紧 — 推断
- **关键链接**: new-graduates (实际打开过): https://www.careers.signify.com/global/en/new-graduates · Workday 338660 (推断已下架): https://lighting.wd3.myworkdayjobs.com/en-US/jobs-and-careers/job/Eindhoven/Signify-s-Junior-Digital-Program--Graduate-_338660 · CMD 2026 (实际打开过): https://www.signify.com/global/our-company/investors/news/cmd · Glassdoor 面经: https://www.glassdoor.com/Interview/Signify-Interview-Questions-E2101263.htm

---

## 2. 签证与国际学生政策

**核心结论: 大部分 SW Dev intern 岗位明确要求"必须在荷兰大学注册" — 对未在 NL 念书的非 EU 学生几乎封死。**

| 维度 | 政策 |
|------|------|
| Signify 是否是 IND recognised sponsor | **是** (Signify Netherlands B.V. 在 IND public register 中, 可以走 Highly Skilled Migrant 路径) |
| Intern 是否提供 visa sponsorship | **岗位描述里没明示**, 但 Philips Hue SW Dev intern 直接卡 "registered at a Dutch University" → 实操等于"只收已在荷兰的学生" |
| Erasmus / 三方协议路径 | 在 NL 念书的非 EU 学生可走"学校 + Signify + 学生"三方 internship agreement, 此时**不需要单独 work permit** |
| 不在 NL 念书的非 EU 学生 | 理论上可走"非欧盟实习生工作许可" (要求 internship at HBO/WO level + 学生有 ≥50% 荷兰最低工资的财力证明 + internship agreement); Labour Market Test 极少通过, 实操几乎没有公开案例 |

**对中国留学生的可行路径**:
1. **已在荷兰 (TU/e, TU Delft, UvA, etc.) 念书**: 最直接, 通过学校 career portal + tripartite agreement
2. **已在 EU 其他国家念书**: Signify 不强制要 Dutch uni, 但 SW Dev 类高度本地化, 通过率低于本地学生
3. **未在 EU**: 几乎只能等 Signify 在你母国办公室开 intern (印度 Bangalore 有 IT 实习; 中国上海有非 SW 实习)

> 来源: builtin.com (Philips Hue SW Dev intern 招聘描述), iamexpat.nl (非 EU 实习生 NL 政策)

---

## 3. 面试流程

### 标准 intern 流程 (基于 Glassdoor 多个 sample)
```
HR 初筛 (10–15 min, 偶尔 30 min)
   ↓
1 轮直属 supervisor / hiring manager 面试 (技术 + 行为混合)
   ↓
[偶尔] Case study (一周准备时间, 例如"为 Philips Hue 设计户外照明方案 + 竞品分析")
   ↓
Offer
```

### 题型分布
| 题型 | 占比 | 备注 |
|------|------|------|
| Behavioral | **主导** | "Tell me about a time..."; team fit, motivation, why Signify, why Eindhoven |
| Technical (SW Dev intern) | 中等 | "比预期的技术深度更深" — Flutter/Dart 经验, C++/Rust, app 开发流程, debug 思路 |
| Case study | 偶尔 | Hue / Marketing 实习常有; 一周 prep, 现场 30 min 讲解 |
| LeetCode 算法 | 极少 | Signify 不主打算法; 但**全职**有时会有 PrepInsta 报道的 coding online assessment, intern 几乎不需要 |
| 系统设计 | 没有 | Intern 不考 |

### 难度
- Glassdoor intern 自评难度 **2.9 / 5** (low-medium)
- 体验正面率: **84%**
- 平均周期: **20 天** (intern); 4 周拿 offer

### OA
- **大多数 intern 岗位没有 OA**
- 部分 PrepInsta 来源提到全职 SW recruitment drive 有 coding online assessment, **不适用于 intern**

> 来源: glassdoor.com/Interview/Signify-Intern..., glassdoor.com/Interview/Signify-Internship...

---

## 4. 真实面经

| 时间 | 岗位 / 城市 | 流程概述 | 题目 / 题型 | 结果 | 来源 |
|------|------------|---------|-----------|------|------|
| 2024–2025 | Intern / Eindhoven (general) | HR 10–15min → supervisor 1 轮 | 多数 behavioral, "no technical questions worth mentioning", "pretty chill" | Mixed | [Glassdoor Signify Intern](https://www.glassdoor.com/Interview/Signify-Intern-Interview-Questions-EI_IE2101263.0,7_KO8,14.htm) |
| ~2024 | Marketing Intern w/ Philips Hue / Eindhoven | HR → Hiring Manager | 1 周准备 case study: "为 Philips Hue 设计 outdoor lighting 方案 + 竞品分析" | Offer | [Glassdoor Signify Intern (同上)](https://www.glassdoor.com/Interview/Signify-Intern-Interview-Questions-EI_IE2101263.0,7_KO8,14.htm) |
| ~2024 | Intern (general) / Eindhoven | HR → supervisor | "意外的比预期更技术 / more technical than expected" (intern 反馈) | Offer | [Glassdoor Signify Interview Reviews](https://www.glassdoor.ca/Interview/Signify-Interview-Questions-E2101263_P2.htm) |
| 2025 (招聘描述) | Internship Software Development Philips Hue / Eindhoven | 申请要求: Flutter/DART, C++/Rust, NL 大学注册 | (岗位已 2025-01-30 关闭, 但每年重开) | — | [Built In job posting](https://builtin.com/job/internship-software-development-philips-hue/3868422) + [Signify Careers job 354870](https://www.careers.signify.com/global/en/job/354870/Internship-Software-Development-Philips-Hue) |

**总体评估**: 流程友好, 难度低于 ASML / Booking; behavioral 占主导, 但 SW Dev / Hue intern 会问 framework 选型, app 架构, debug 思路这些"半技术"问题。Glassdoor 上无系统性算法题分享。

> 注: 1point3acres / 知乎 / Reddit r/cscareerquestionsEU 在 Signify intern 关键词下**几乎没有面经**; 这部分对华人社区的可见度极低

---

## 5. Offer 案例 (Stipend)

### Signify 本身 (Eindhoven intern, Glassdoor 聚合)
- Glassdoor 显示 Signify intern 估算: $25–$45/hr, 月 $4,285–$7,724 — **此数据明显被美国 Signify Health intern 数据污染**, Eindhoven 本地实习生水平不会这么高, **不要拿来谈判**
- Eindhoven 实测 Glassdoor 数据点稀少, 30 个 Signify intern 全球 salary 样本无法精确切片到 Eindhoven 单独

### Philips 母公司 (强可比, 同城同政策)
Philips 官方公布的 Eindhoven intern 政策 (Data Science Intern 招聘描述):
| 项目 | 金额 (gross / net) |
|------|------------------|
| 月津贴 (full-time) | **€500 – €700 gross / 月** (按学位级别分; HBO 偏低, WO/Master 偏高) |
| 部分津贴 (part-time) | Pro-rata |
| **Housing 补贴** (relocate 到 office 附近) | Amsterdam 附近 €300 net/月; 其他 (含 Eindhoven) €255 net/月 |
| 交通补贴 | 如果没有 student OV-chipkaart, 实报实销 |
| 带薪假 | 按 internship term 计 |

**Signify intern stipend 推断**: Eindhoven 本地 SW Dev intern 大概率落在 **€500–€800 gross/月** + housing 补贴 ≈ €700–€1100 总, 比 ASML / Booking (€1,800–€2,500) 低一档, **属于偏 industrial / R&D 而非 software-first 公司的标准 stipend**。

| 城市 | Stipend 估算 | Team | 时间 | 来源 |
|------|------------|------|------|------|
| Eindhoven | €500–€700 gross/月 + €255 net/月 housing (Philips 同口径) | Hue / R&D / DS | 2024–2025 | [Quora 综述](https://www.quora.com/How-much-is-the-salary-of-a-software-engineer-intern-in-the-Netherlands) + [Philips Glassdoor Eindhoven](https://www.glassdoor.com/Intern-Salary/Philips-Eindhoven-Internship-Salary-EI_IE3496.0,7_IL.8,17_IM1106.htm) |

---

## 6. 申请渠道与建议

### 官方入口
- **Signify Careers (intern 总入口)**: https://www.careers.signify.com/global/en/internships
- **荷兰 intern 专页**: https://www.careers.signify.com/global/en/internships (search by Eindhoven)
- **具体岗位案例**:
  - Philips Hue SW Development: https://www.careers.signify.com/global/en/job/354870/Internship-Software-Development-Philips-Hue
  - Product Marketing w/ Philips Hue: https://www.careers.signify.com/jobs/product-marketing-internship-with-philips-hue-eindhoven-2/

### Philips 入口 (相关 / 比较)
- https://www.careers.philips.com/student/nl/en
- https://www.careers.philips.com/student/nl/en/internships-and-apprenticeships-benelux

### 简历 / 背景要求
- **必备 (SW Dev intern)**: 在 NL 大学读 BSc / MSc CS / SE / EE; 6 个月 full-time 可用; Flutter/DART **或** C++ / Rust 至少一个
- **加分**:
  - **GitHub 上有 IoT / smart home 相关项目** (Home Assistant integration, Zigbee, Matter)
  - 已贡献过开源 Hue API 客户端
  - Embedded / firmware 经验 (与 Signify R&D 高度匹配)
- **不需要**: LeetCode 刷题量, 算法竞赛
- **PM / Marketing intern**: 强 communication + case study 表达; 国际多元背景加分

### 内推
- LinkedIn 搜 "Signify Talent Acquisition" / "Signify Recruiter" + 城市 Eindhoven → 主动 connect + 短 message
- High Tech Campus 7 有 ~10 个共享空间 / café, Eindhoven 当地 meetup (TU/e 学生组织 Cosmos, Sirius) 是接触 Signify 工程师的有效场所
- **TU/e 校内有 Signify Lab** (Eindhoven Tech Lab 合作项目), 通过 TU/e BEP / Master Thesis 项目最容易切入

---

## 7. 踩坑与社区评价

| 维度 | 评价 |
|------|------|
| 流程节奏 | 快 (4 周拿 offer) — 在欧洲属于第一梯队效率 |
| OA 是否劝退 | 几乎不存在 OA, 不会被刷 |
| 对国际学生友好度 | **强卡 "Dutch university" 是最大坑**; 已在荷兰念书的学生很友好 (Eindhoven 是国际化最强的荷兰城市之一, ~50% TU/e 学生是国际生) |
| Stipend | **明显低于纯软件公司** (€500–€700 vs ASML/Booking 的 €1,800–€2,500) — Signify 走 industrial / lighting 公司的传统欧式 intern stipend, 别拿 Booking/Adyen 标准衡量 |
| 文化 | Glassdoor intern 评价 4.6 work-life balance, 4.5 D&I, 4.6 culture, 3.7 career — 即"过得舒服但晋升慢" |
| Mentor 与项目结构 | 部分 intern 反馈"被扔进去 learn on the go, 没结构化项目" — 双刃剑; 自驱型学生收益大, 期待 hand-holding 的会失望 |
| 转正路径 | "Open to converting interns to full-time"; 但 R&D / 灯具相关全职岗位本身在 Eindhoven 数量有限, 软件 / IoT / Hue 团队转正机会较好 |
| 行业前景 | 智能照明竞争激烈 (与 LG/三星/小米 等), Signify 全球市占第一但增长放缓; "Good company with bad prospects" 是部分员工评价 |

### 已知"坑"
- **Stipend 错觉**: Glassdoor 自动显示的 $25–$45/hr 是被 Signify Health (美国) 数据污染, 实际欧洲 intern 是 €500–€800/月 gross
- **6 个月 commitment**: 多数岗位拒短期 (3 个月) intern, 学校学期不匹配的同学要协调好
- **"必须 NL 大学注册" 卡死跨境申请** — 不要寄望 exception, 应优先选 Eindhoven (TU/e), Delft (TU Delft), Amsterdam (UvA/VU) 等 NL 院校的 exchange / dual degree
- **公司近况波动 (2026 更新)**: Signify 2023–2026 经历多轮 cost cut; **2026-01-30 最新一轮宣布全球裁 900 人 + €180M cost-cutting 计划**, 自 2023 以来累计裁员 ~6,200 人; CEO 将 2026 定义为 "transitional year", **2026-06-23 Capital Markets Day** 公布战略 review 结论; 软件类 intern 岗位 354870 已下架; 申请前必看 Glassdoor 最新 reviews + LinkedIn 看 Signify Eindhoven 员工动向 [来源 (实际打开过): https://www.metaintro.com/blog/signify-job-cuts-2026]
- **"Philips" 品牌混淆**: Hue 仍叫 Philips Hue, 但 owner 是 Signify; 申请时认准 Signify Careers 域名

---

## 8. 所有引用链接

### Signify 官方
- https://www.careers.signify.com/ (Careers 主页)
- https://www.careers.signify.com/global/en/internships (Intern 总入口)
- https://www.careers.signify.com/global/en/job/354870/Internship-Software-Development-Philips-Hue (SW Dev Hue intern 岗位)
- https://www.careers.signify.com/jobs/product-marketing-internship-with-philips-hue-eindhoven-2/ (PM Hue intern)
- https://www.careers.signify.com/global/en/latam-intern (LATAM intern, 参考结构)
- https://www.signify.com/global/our-company/blog/showcase/smart-home-lighting-with-hue-and-wiz (Hue+WiZ blog)
- https://www.signify.com/global/our-company/news/press-releases/2025/20250904-far-more-than-intelligent-lighting-philips-hue-reimagines-smart-home (Hue 2025 战略)

### Glassdoor (面经 + salary + reviews)
- https://www.glassdoor.com/Interview/Signify-Intern-Interview-Questions-EI_IE2101263.0,7_KO8,14.htm (Intern 面经主页)
- https://www.glassdoor.com/Interview/Signify-Internship-Interview-Questions-EI_IE2101263.0,7_KO8,18.htm (Internship 面经)
- https://www.glassdoor.ca/Interview/Signify-Interview-Questions-E2101263_P2.htm (全公司面经 381 条)
- https://www.glassdoor.com/Reviews/Signify-Internship-Reviews-EI_IE2101263.0,7_KO8,18.htm (Intern reviews)
- https://www.glassdoor.com/Reviews/Signify-Intern-Reviews-EI_IE2101263.0,7_KO8,14.htm (Intern reviews 另一版本)
- https://www.glassdoor.com/Intern-Salary/Signify-Eindhoven-Internship-Salary-EI_IE2101263.0,7_IL.8,17_IM1106.htm (Eindhoven intern salary)
- https://www.glassdoor.com/Salary/Signify-Intern-Salaries-E2101263_D_KO8,14.htm (Signify intern 全球 30 条)
- https://www.glassdoor.com/Jobs/Signify-intern-Eindhoven-Jobs-EI_IE2101263.0,7_KO8,14_IL.15,24_IC3043137.htm (Eindhoven intern 招聘列表)

### Philips (对照)
- https://www.careers.philips.com/student/nl/en (Philips NL 学生入口)
- https://www.careers.philips.com/student/nl/en/internships-and-apprenticeships-benelux (Benelux intern)
- https://www.glassdoor.com/Intern-Salary/Philips-Eindhoven-Internship-Salary-EI_IE3496.0,7_IL.8,17_IM1106.htm (Philips Eindhoven intern salary)
- https://www.glassdoor.com/Intern-Salary/Philips-Netherlands-Internship-Salary-EI_IE3496.0,7_IL.8,19_IN178.htm (Philips NL intern salary)
- https://techpays.com/europe/netherlands/philips (Philips NL 薪资众包)
- https://techpays.com/europe/netherlands/philips/eindhoven (Philips Eindhoven 薪资)
- https://www.levels.fyi/companies/philips/salaries/software-engineer/locations/netherlands (Philips NL SWE €72.2K–€86.6K)

### 第三方招聘平台
- https://builtin.com/job/internship-software-development-philips-hue/3868422 (Built In SW Dev Hue intern)
- https://builtin.com/job/product-management-internship/3868408 (Built In PM intern)

### 政策 / 签证
- https://www.iamexpat.nl/career/employment-news/what-are-dutch-internship-immigration-rules-non-eu-nationals (NL 非 EU 实习签证)
- https://ind.nl/en/public-register-recognised-sponsors (IND recognised sponsor 公开名录)
- https://www.jobbatical.com/blog/netherlands-highly-skilled-migrant-sponsor (Highly Skilled Migrant 指南)

### 2026 公司动态 / Layoff
- https://www.metaintro.com/blog/signify-job-cuts-2026 (**2026-01-30 宣布 900 人裁员 + €180M cost-cutting, 实际打开过**)
- https://finance.yahoo.com/news/signify-cut-jobs-revamp-save-123336319.html (Reuters: Signify cuts jobs in revamp to save €180M)
- https://www.signify.com/en-hk/our-company/news/press-releases/2026/20260424-signify-first-quarter-results-2026 (Signify Q1 2026 results, 2026-04-24)
- https://www.signify.com/static/quarterlyresults/2026/q1_2026/signify-first-quarter-results-2026-report.pdf (Q1 2026 完整 report)

### 技术栈 / 公司技术
- https://cloud.google.com/customers/signify (Signify GKE case study)
- https://cloud.google.com/customers/philipshue (Hue Google Cloud case study)
- https://aws.amazon.com/solutions/case-studies/signify-video-case-study/ (Hue Secure AWS IoT case study)
- https://prepinsta.com/signify-coding-questions-and-answers/ (Coding OA 参考 — 主要全职用)
