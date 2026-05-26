# Apple 实习情报 (London / Munich / Cambridge UK)

> 更新时间: 2026-05-26
> 信息丰富度: ⭐⭐⭐⭐ (Munich 数据最厚, London/Cambridge ML 数据次之)
> 一句话定位: 全球最值钱的硬件+软件+服务公司, 欧洲三大工程中心 (Munich Silicon, London Pay/Swift Server, Cambridge AIML)

---

## 1. 基本信息

- **欧洲办公室 (本任务范围)**:
  - **Munich (慕尼黑)**: Apple 在欧洲大陆**最大的工程枢纽** (2000+ 工程师), 重点是 **European Silicon Design Center** (Cellular SoC IP, AMS, Digital Design, DV, Power Integrity), 也有 ML & AI Workflows team
  - **London (伦敦)**: Apple Pay Server, Swift on Server, Swift Compiler & Runtime, 部分 Services 团队
  - **Cambridge (UK)**: **AIML R&D** 中心, 重点是 SaLT (Speech and Language Technology, NLP/ASR), Siri Understanding, Speech Research; 多为 PhD intern
- **实习岗位类型 (实际抓到的岗位名)**:
  - **SWE Intern**: Apple Pay (London), Swift on Server (London), Swift Compiler & Runtime (London), SWE Intern (ML & AI Workflows, Munich)
  - **ML/AIML Intern**: NLP & Speech Recognition - SaLT (Cambridge), Siri Understanding (UK), NLP/SII (general), AIML Residency
  - **Silicon Intern (Munich)**: AMS Digital Design, SoC Design for Test, Top-Level Functional Verification, SoC Power Integrity/EMIR, SoC Performance Modeling, Cellular SoC IP
- **实习时长**: **最少 3 个月**官方明确, ML/PhD intern 常 3-6 个月; UK 学校 placement year 也有 (12 个月长实习)
- **招聘周期**: 全年 rolling, 但欧洲暑期段 (3-9 月开放, 5-9 月入职) 是高峰; Cambridge AIML 强烈倾向 PhD 自然学期空档

## 2. 签证与国际学生政策

- **UK (London / Cambridge)**:
  - Apple UK Limited 是 UK Home Office **Register of Licensed Sponsors** 上的注册雇主, 可办 Skilled Worker; 但 **实习不走 Skilled Worker**, 通常走:
    - **Student visa 的允许工作时长** (在校学生 / placement year 模块): 最常见
    - **Graduate visa**: 毕业后 2 年开放期, 可直接做实习
    - **GAE (Government Authorised Exchange) visa**: 短期结构化实习, Apple 历史上用过此路径
  - 没有 RTW (right to work) 的非EU学生, Apple 一般要求你已经在英国学校就读, 单独为实习办签证基本不发生
- **Germany (Munich)**:
  - **EU Blue Card** 是全职路径, 实习不适用
  - 实习走 **学生工作许可** (学期内 ≤20h/week, 假期全职) 或 **强制性实习 Pflichtpraktikum** (大学要求, 申请最顺)
  - 非EU 学生需有德国 / EU 学校学籍, Apple 不会单独给实习生 sponsor 签证
- **结论**: Apple 欧洲实习对**已经在欧洲学校就读**的国际学生 (中国/印度学生 via UK/DE 高校) 非常友好, 但**纯境外申请并要求 sponsor 实习签证**几乎不可能成功
- **已知 sponsorship 案例**: 全职 SWE 通过 Skilled Worker 在 London/Cambridge 有公开案例; 实习级别公开案例罕见

## 3. 面试流程

### 3.1 SWE Intern (Munich / London) — 主流程

总轮数: **3 大阶段, 通常 5-7 次接触**
1. **Recruiter Screening** (~30 min, 英语, 偶尔德语客套): 简历过一遍, 项目高层次, 兴趣 team, 时间表
2. **Tech Screening** (~45-75 min): 一轮电话/Zoom 技术面, 1 道 coding (LeetCode Medium 居多) + 项目深挖 + 计算机基础 (OS/网络/CA)
3. **Final Day / "Final Day Interviews"** (Munich 模式被多次确认):
   - **4 个 45-min 背靠背 session** (虚拟 onsite 或现场)
   - 内容: 项目讨论 + 计算机架构 + LeetCode + 团队匹配
   - **会议节奏快**, 部分面试官只问 follow-up 不重新自我介绍

题型分布 (SWE intern):
- 算法: **40%** (LeetCode Easy/Medium 为主, Hard 偶尔出现)
- 系统/CS 基础: **25%** (process vs thread, OS, OOP, 测试)
- 项目深挖: **25%**
- BQ / 团队匹配: **10%**

难度评估: **2.9-3.2 / 5** (Glassdoor SWE Intern 综合; 实习生反映"中等偏易, 但 Final Day 强度大")

OA: **不强制**. Munich/London 内部多用 "tech screening" 替代标准 OA, 仅少数线上 Hackerrank 提交记录

### 3.2 AIML / ML Intern (Cambridge UK / SaLT / SII)

- **R1**: 30-min Zoom, **research interest** + 简单背景, 几乎不写代码
- **R2** (整天 / 半天):
  - **30-min 学术 seminar**: 候选人讲自己的研究 (PhD intern 必备)
  - **4 个 1-hour interview**:
    - **Coding**: LeetCode **Medium** 难度, 1-2 题; 语言不限但 Swift/Metal/CoreML 加分
    - **ML 基础**: backprop, optimizer, transformer, attention, 自家话题 (PrivML, NLU/NLG)
    - **Research deep dive**: PhD 工作细节, 假设性 follow-up
    - **Team fit / BQ**

题型分布 (ML intern):
- ML 理论: **35%**
- Research / 论文讨论: **30%**
- 算法 coding: **20%**
- BQ: **15%**

OA: 通常无, research 路线不挂 OA

### 3.3 Silicon / Hardware Intern (Munich)

- **R1**: Recruiter screen
- **R2**: Tech phone screens — **analog design + digital design** 二选一或双轨
- **R3**: Onsite **5-6 sessions**, 每个 45-60 min
  - 模拟设计 (Op-Amp 设计常考)
  - 数字 / RTL / SystemVerilog / UVM (DV intern)
  - 计算机架构 (pipelining, cache, virtual memory)
  - C/C++ 编程
  - 项目深挖 + BQ
- **整体周期**: **3 个月**从首面到 offer, 部分候选人反馈 4 个月

### 3.4 AIML Residency (非典型实习, 但常被混为一谈)

- 面试: phone screen → 30-min research talk → **3 个 technical interviews**
- 100% Glassdoor positive (样本小)
- 难度评分 3/5

## 4. 真实面经

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|------|-----------|----------|-----------|------|------|
| 2024-06 | SWE Intern / Munich | Recruiter → Tech screen → Final Day 4×45min | "Draw a circle in a matrix" + 计算机架构 + 项目深挖 | **Offer** | [Jointaro](https://www.jointaro.com/interviews/companies/apple/experiences/software-engineerinternship-munich-bavaria-june-1-2024-accepted-offer-positive-6fae99ff/) |
| 2024-04 | SWE Intern / Munich | 单轮 75 min | 项目管理 + 项目深挖, "clear but difficult" follow-up | 未知 | [Glassdoor Munich](https://www.glassdoor.com/Interview/Apple-Munich-Interview-Questions-EI_IE1138.0,5_IL.6,12_IC4990924.htm) |
| 2024 | SWE Intern / 通用 | 2 轮 (manager BQ + 技术) | "代码语言由 team 决定" + LeetCode-style team-related | 81% positive | [Glassdoor SWE Intern](https://www.glassdoor.com/Interview/Apple-Software-Engineer-Intern-Interview-Questions-EI_IE1138.0,5_KO6,30.htm) |
| 2023+ | ML Intern / 通用 | 30 min Zoom → 1h seminar + 4×1h | LeetCode Medium + ML 基础 + research deep dive | 83% positive, 19 天 | [Glassdoor ML Intern](https://www.glassdoor.com/Interview/Apple-Machine-Learning-Intern-Interview-Questions-EI_IE1138.0,5_KO6,29.htm) |
| ~2020 | CV Engineer / Munich (非实习, 但流程类似) | **7 轮** | camera model, projection matrix, pose detection (heatmap + PAF), CNN, activation, backprop, bias-variance, C++ & Python coding | 未知 | [知乎 7 轮 CV 面经](https://zhuanlan.zhihu.com/p/166449699) |
| 2024 | AIML Resident | Phone → 30-min research talk → 3 technical | research + ML 基础 | 100% positive (样本小) | [Glassdoor AIML Resident](https://www.glassdoor.com/Interview/Apple-AIML-Resident-Interview-Questions-EI_IE1138.0,5_KO6,19.htm) |
| 2025-08 | ASIC DV Intern / 通用 (Durham 数据点, Munich 类似) | OA → 技术轮 | FSM pattern detector, C++ Fibonacci, swap, Verilog blocking/non-blocking, hash table, Linux | **Offer** (positive) | [Jointaro ASIC DV](https://www.jointaro.com/interviews/companies/nvidia/) ※可对比的 Apple Silicon DV 数据 |

## 5. Offer 案例 (Stipend)

| 城市 | Stipend (报告值) | 备注 | 来源 |
|------|-------------------|------|------|
| **Munich** (SWE Intern) | 约 **€2,500–€3,200 / 月** (社区报道, Apple 在德最高 Praktikum 段) | 全 Apple Munich 全职 ICT3 SWE 中位 ~€156K/年; intern ≈ 全职月薪的 0.4-0.5x | [Levels.fyi Apple Munich](https://www.levels.fyi/companies/apple/salaries/software-engineer/locations/munich-metro-region) |
| **London** (SWE Intern) | 约 **£3,000–£4,200 / 月** (≈ £35K–£50K 年化, Bright Network 历史范围) | 全 Apple UK ICT3 全职 ~£111K-£164K | [Levels.fyi Apple UK](https://www.levels.fyi/companies/apple/salaries/software-engineer/locations/united-kingdom), [Indeed London](https://uk.indeed.com/cmp/Apple/salaries/Intern/London-ENG) |
| **Cambridge** (AIML PhD Intern) | 约 **£4,500–£6,000 / 月** (PhD 段, 论文产出可附带 conference funding) | 与 Apple Research Intern levels.fyi $60/hr 一致 (~$10K/月美刀对标) | [Levels.fyi Apple Research Intern](https://www.levels.fyi/internships/Apple/Research-Intern/) |
| Apple Hardware Intern (通用) | **$47/hr** (≈ £35-38/hr 等值) | levels.fyi 报告值, Munich Silicon intern 估算落在此范围 | [Levels.fyi Apple HW Intern](https://www.levels.fyi/internships/Apple/Hardware-Engineer-Intern/) |
| Apple SWE Intern (US 基准) | **$60/hr** | 欧洲 stipend 一般 ~60-80% 美国水平 | [Levels.fyi Apple SWE Intern](https://www.levels.fyi/internships/Apple/Software-Engineer-Intern/) |

> ⚠️ **关于 "London £8-12k/月" 的传言**: 这一数字对应**美国 SF/Cupertino 全职**或**特殊 PhD residency**, 普通 SWE intern London **未达到此水平**. £8-12k/月仅在 DeepMind 这类研究岗、或带 housing/relocation 全包后总折算时见到.

## 6. 申请渠道与建议

- **官网投递**:
  - https://jobs.apple.com/en-gb/search?team=internships-STDNT-INTRN (UK)
  - https://jobs.apple.com/en-us/search?location=germany-DEU&team=internships-STDNT-INTRN (DE)
  - Cambridge ML: https://machinelearning.apple.com/work-with-us
- **内推途径**:
  - LinkedIn 直接搜 "Apple recruiter London / Munich / Cambridge", connect + 短信; Apple recruiter 回复率比 FAANG 其他家高
  - 校内 career fair (Cambridge, Imperial, UCL, TUM, ETH 都有 Apple booth)
  - 在 Swift / swift-foundation / open source repos 提 PR, 在 issues 里被注意到
- **简历/背景要求**:
  - **SWE intern**: 必备 — LeetCode Medium 流畅, C++/Swift/Python 至少一门精通; **加分** — 系统编程 / OS / 编译器 经验, 之前的 Apple/FAANG 实习
  - **ML intern**: **PhD 在读** (Cambridge 几乎是硬要求); 顶会论文 (ACL, EMNLP, NAACL, INTERSPEECH, ICASSP — SaLT 团队特别看 speech/NLP), PyTorch + Transformers 框架熟练, **CoreML** 经验加分明显
  - **Silicon intern (Munich)**: SystemVerilog/UVM (DV), Cadence/Synopsys EDA 工具, RTL design, signal integrity, semiconductor physics
- **Cover letter**: 在 UK 申请实际上很重要; Apple 招聘看 motivation + 具体 team fit

## 7. 踩坑与社区评价

- **Munich offer 周期长**: 反复确认的 pattern 是 "1 月间隔×3" — 从首面到 offer letter 实际 3-4 个月. 持有其他 offer 时**主动催 recruiter** 是常见操作
- **Final Day 强度**: 4 个 45-min 背靠背 + 偶有早午餐与 hiring manager 闲聊, 累; 中场休息 5 分钟很正常
- **Team 锁定问题**: Apple 实习是 **team-based hiring** — 即使技术面通过, 没有 team 愿意要你也会挂. **多 team 同时申请**或在 recruiter 那边表态 flexible 重要
- **Cambridge AIML 极其偏 PhD**: Master/Bachelor 难度极大; SaLT/SII 几乎清一色 NLP/Speech PhD
- **保密文化重**: Apple 在欧洲不允许 intern 在 LinkedIn 详写所做内容; 也禁止 PR/blog. 影响后续找工时 portfolio 展示
- **国际学生友好度**: ⭐⭐⭐ (中等) — 已经在欧洲读书的 OK, 海外直申极难
- **转正率**: Apple 欧洲转正比北美低 — 受 headcount 控制紧, 但有 return offer (next summer) 案例多

## 8. 所有引用链接

- [Apple Munich Glassdoor Interview Questions](https://www.glassdoor.com/Interview/Apple-Munich-Interview-Questions-EI_IE1138.0,5_IL.6,12_IC4990924.htm)
- [Apple SWE Intern Glassdoor](https://www.glassdoor.com/Interview/Apple-Software-Engineer-Intern-Interview-Questions-EI_IE1138.0,5_KO6,30.htm)
- [Apple ML Intern Glassdoor](https://www.glassdoor.com/Interview/Apple-Machine-Learning-Intern-Interview-Questions-EI_IE1138.0,5_KO6,29.htm)
- [Apple AIML Resident Glassdoor](https://www.glassdoor.com/Interview/Apple-AIML-Resident-Interview-Questions-EI_IE1138.0,5_KO6,19.htm)
- [Jointaro SWE Intern Munich 2024](https://www.jointaro.com/interviews/companies/apple/experiences/software-engineerinternship-munich-bavaria-june-1-2024-accepted-offer-positive-6fae99ff/)
- [Zhihu 慕尼黑 Apple CV 7轮面经](https://zhuanlan.zhihu.com/p/166449699)
- [Apple Careers UK Internships](https://jobs.apple.com/en-gb/search?location=united-kingdom-GBR&team=internships-STDNT-INTRN)
- [Apple Careers Germany Internships](https://jobs.apple.com/en-us/search?location=germany-DEU&team=internships-STDNT-INTRN)
- [Apple Machine Learning Research — Work With Us](https://machinelearning.apple.com/work-with-us)
- [Apple AIML SaLT NLP Intern Cambridge (Prosple)](https://prosple.com/graduate-employers/apple-uk/jobs-internships/aiml-intern-nlp-salt)
- [Apple AI/ML Intern NLP SaLT (Jobs UK)](https://jobs.apple.com/en-gb/details/200412082/ai-ml-intern-nlp-and-speech-recognition-machine-learning-salt)
- [Apple Swift Compiler Intern (Jobs UK)](https://jobs.apple.com/en-gb/details/200579813/internship-swift-compiler-and-runtime-engineer)
- [Apple Pay London Intern 2024 (Bright Network)](https://www.brightnetwork.co.uk/graduate-jobs/apple/apple-pay-software-development-engineer-internship-london-2024)
- [Apple Swift on Server London Intern (Bright Network)](https://www.brightnetwork.co.uk/graduate-jobs/apple/software-engineer-internship-swift-on-server-london-2024)
- [Levels.fyi Apple SWE Intern](https://www.levels.fyi/internships/Apple/Software-Engineer-Intern/)
- [Levels.fyi Apple HW Intern](https://www.levels.fyi/internships/Apple/Hardware-Engineer-Intern/)
- [Levels.fyi Apple Research Intern](https://www.levels.fyi/internships/Apple/Research-Intern/)
- [Levels.fyi Apple Munich SWE](https://www.levels.fyi/companies/apple/salaries/software-engineer/locations/munich-metro-region)
- [Levels.fyi Apple UK SWE](https://www.levels.fyi/companies/apple/salaries/software-engineer/locations/united-kingdom)
- [Indeed Apple Intern London Salary](https://uk.indeed.com/cmp/Apple/salaries/Intern/London-ENG)
- [Apple Munich Office Overview](https://www.apple.com/careers/us/work-at-apple/munich.html)
- [GlobalVisaAlly Apple UK sponsorship](https://www.globalvisaally.com/company/apple-uk-limited-gb)
- [DavidsonMorris UK Intern Visa](https://www.davidsonmorris.com/internship-visa-uk/)
- [Prepfully Apple Hardware Engineer Guide](https://prepfully.com/interview-guides/apple-hardware-engineer)
- [Apple AIML Residency 2024 (machinelearning.apple.com)](https://machinelearning.apple.com/updates/aiml-residency-program-application-2024)
