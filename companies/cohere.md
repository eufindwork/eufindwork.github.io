# Cohere (伦敦) 实习情报

> **Language**: 中文 | [English](cohere.en.md)
>
> 更新时间: 2026-10-10
>
> Cohere 是加拿大企业级 LLM 公司,创始人 Aidan Gomez 是 Transformer 论文作者之一。**伦敦是欧洲核心办公室之一**,主要承担研究 + 企业销售。2024-2025 公司营收三倍增长,完成 Paris office 扩张 (40 人)。**ML/AI Intern 面试 bar 极高,Research Intern 需 PhD 在读 + 顶会论文**;非 PhD 候选人也可能通过 Engineering Intern 入口,但仍需扎实 ML 工程经验。

## 1. 公司速览

| 项目 | 内容 |
|---|---|
| 总部 | 多伦多 + 旧金山 (主) |
| 欧洲办公室 | 伦敦 + Paris (Paris 为欧洲中心 hub, 40 人) |
| 估值 | ~$5.5B (2024 D 轮) |
| 主营业务 | 企业级 LLM (Command 系列)、Embed、Rerank、Aya 多语言研究 |
| 技术栈 | Python、PyTorch / JAX、Triton、MLIR、Megatron / DeepSpeed |
| 实习时长 | 4-8 个月 (Co-op 模式) 或 12 周 Summer |
| 申请窗口 | 滚动开放;Summer cohort 1-2 月;Fall cohort 5-7 月 |
| 视觉信号 | LLM 顶级雇主之一,与 OpenAI / Anthropic 同层 |

## New Grad / Junior 岗位

> 核查日期: 2026-10-10 (实时 WebFetch + Ashby API; 本 session WebSearch 配额已用尽) | 信息丰富度: ⭐⭐⭐⭐ (依据: Levels.fyi London 2026-10-10 直读 57 条样本 + 官方 newsroom + Ashby 全量 posting)
> **2027 Intake 状态**: **No programme (new grad); Cohere Labs Scholars = Upcoming** — 无 new grad / junior title, 新人走 MTS 通道; Scholars Program 当前 closed: "We are currently evolving the Research Scholars program. Applications are expected to open in Fall 2026" (2026-10-10 尚未开放) [来源 (实际打开过): https://cohere.com/research/scholars-program]
> **2026 H2 动态**: 2026-09-16 与 Aleph Alpha 签 definitive business combination agreement — Berlin + Toronto 双总部, Heidelberg 保留为研究中心, 合并后 >1,000 人, 待监管批准、预计年内完成 [来源 (实际打开过): https://cohere.com/blog/cohere-and-aleph-alpha-sign-agreement]; 2026-10-05 PwC 合作、2026-08-06 University of Waterloo 人才合作 (加拿大) [来源 (实际打开过): https://cohere.com/newsroom]; (H1 背景) 2026-06-15 London 新办公室 100 New Oxford Street, 14,000+ sq ft, 最多 100 人, 扩 AI engineering / applied ML / infrastructure / customer deployment [来源 (实际打开过): https://cohere.com/blog/cohere-triples-uk-footprint-with-new-london-office-to-support-r-and-d-growth]

- **岗位名称**: Member of Technical Staff (Modeling / Post-Training / Pre-Training Data / Multilingual / Agent Code / RL Environments / Training Infra 等), Software Engineer, Integrations, Forward Deployed Engineer (Europe / UK Public Sector / France); 2026-10-10 Ashby 119 个 posting, 46 个含欧洲地点 (London 30 / Paris 16 / "Europe" 13 / UK 11 / Berlin 5 / Munich 3 / Brussels 2 等), 0 个 new grad / junior title (Ashby API curl 全量解析: https://api.ashbyhq.com/posting-api/job-board/cohere)
- **资格窗口**: MTS JD 多数不写年限 (MTS Multilingual 要求 PhD 或同等经验); 公共部门岗需 UK security clearance 或法国国籍 (France TPM / CSM); 部分 UK sales 岗写 "Existing right to work in the UK"; 语言: France 公共部门岗要求法语, 工程岗英语即可
- **欧洲地点**: London (研究 + 工程核心, 2026-06 新办公室), Paris, Berlin (posting 列为 key office; Aleph Alpha 合并后为双总部之一), Munich / Frankfurt / Brussels / Edinburgh (FDE 多地点 posting), Heidelberg (研究中心, 待合并完成)
- **项目结构**: 无 cohort / rotation, 新人按 L3 MTS 入职、与资深者同 title (Levels.fyi London 最低公开级别 = L3 "Member of Technical Staff"); Scholars Program = remote-first 全职带薪研究项目 (无需搬迁, 不要求发表经历), 时长 / stipend 页面未写
- **非EU签证 (全职)**: **UK**: Cohere UK Ltd 在官方 register = Worker (A rating), Skilled Worker [来源 (实际打开过): https://www.gov.uk/government/publications/register-of-licensed-sponsors-workers — 2026-10-09 版 CSV 下载检索] (旧版仅搜索结果); 门槛 £41,700 (特定情形 £33,400) [来源 (实际打开过): https://www.gov.uk/skilled-worker-visa/your-job]. **FR**: Passeport Talent salarié qualifié €39,582 仅限在法国取得的 master → 非法国学位走 EU Blue Card €59,373 [来源 (实际打开过): https://www.service-public.gouv.fr/particuliers/vosdroits/F16922] (旧版: "≥ €43,243", 2026-05). **DE (Berlin)**: Blue Card €50,700 / 短缺职业 €45,934 (⚠️ 待 web 验证: 官方页 Radware 拦截 / 404, 取 repo 基准值). Scholars FAQ "Will Cohere Labs sponsor work permits?" → 回答为 remote-first、"no requirement to relocate" (未明确承诺 sponsor). **NL 学生签 / zoekjaar**: 无 NL 办公室, zoekjaar 不适用; Scholars remote-first → 可能可在 NL 远程参与 (推断, 需确认雇佣形式)
- **薪资范围 (gross/年)**: **Levels.fyi London SWE (2026-10-10, 57 条)**: 中位 £177K (精确 £176,929), 均值 £183,886, 最高 £261,527, 区间 £82,900 – £177,000+; L3 MTS 行: total £236K / base £152K / stock £25.3K / bonus £0 (样本 5 年经验; 各列为 Levels.fyi 显示值, 不一定相加) [来源 (实际打开过): https://www.levels.fyi/en-gb/companies/cohere/salaries/software-engineer/locations/london-metro-area] (旧版: L3 base ~£135K / total £172K, 2026-05-27). 官方 posting 只公开 Canada / US 区间: MTS (Multilingual 等) base CA$295K – CA$535K (Toronto/Montreal) / CA$250K – CA$460K (Canada) / $205K – $380K (US CA/NY/WA); SWE Integrations CA$215K – CA$270K / $180K – $225K; 无 GBP / EUR 区间. Paris MTS 无 Levels 数据 (旧版估 €90-115K, 未验证)
- **申请窗口**: 全职 rolling; Scholars 预计 Fall 2026 开放 (截至 2026-10-10 未开); Winter 2027 实习 (SWE / ML / Research) 2026-05 已发布, 2026-10-10 仍在招, 含 London/UK/Europe [来源 (实际打开过): https://jobs.ashbyhq.com/cohere/8c035d3d-081d-4c8a-914a-72f4efaad254]
- **面试流程差异 vs 实习**: MTS 比实习多 1-2 轮 (5-7 轮 vs 4-5 轮): Research MTS 加 1-2 轮 paper deep dive, system design 必考 (serving / training pipeline / multi-tenant inference); coding 同实习 (Colab + ML 实现题) (2026-05 整理, 本轮未找到新面经)
- **录取竞争**: 极高, pass rate 估 5-10% (推断); paper 或 OSS 至少一项近乎硬通货; 公共部门岗 (clearance / 国籍) 对非EU 不可行
- **关键链接**: Careers https://cohere.com/careers (实际打开过) · Scholars https://cohere.com/research/scholars-program (实际打开过) · Levels.fyi London (见上) · Aleph Alpha 合并 https://cohere.com/blog/cohere-and-aleph-alpha-sign-agreement (实际打开过)

## 2. 实习岗位与方向

| 岗位类别 | 主要要求 | 备注 |
|---|---|---|
| **ML Intern / Co-op** | 本科末年或硕士,扎实 PyTorch | 工程偏重 — model training 工具、pipeline、infra |
| **Research Intern** | **PhD 在读** (ML / NLP / AI),顶会 (NeurIPS/ICML/ICLR/ACL/EMNLP/COLING) 论文为强信号 | 偏研究产出;exceptional 非 PhD 也接受 |
| **SWE Intern** | CS 本科末年,通用工程 | LLM 平台、API、infra |
| **ML Engineering Intern** | 介于 ML 与 SWE 之间 | Production ML、训练优化 |

## 3. 申请要求与签证

- **学历**: SWE Intern 倒数第二年本科;ML / Research Intern 偏好硕博
- **技术硬条件**:
  - Python + PyTorch / JAX 熟练
  - 至少一段 ML 相关项目 / 论文 / 实习
  - 分布式训练 (Distributed Data Parallel、Megatron、ZeRO) 加分
  - Triton / CUDA / MLIR 加分 (System ML)
- **签证**: **Cohere UK Ltd 是 Skilled Worker 持牌雇主** (Home Office register),London 实习对国际学生 OK,Student Visa 可用
- **薪资**:
  - SWE Intern 北美 ~$59/hr (Levels.fyi);伦敦预估 £4,000-£5,500 月薪
  - Stipend + $2,000 学习津贴 + workplace stipend
  - Aidan Gomez 公开放话: **"We're happy to pay extremely high salaries"**

## 4. 面试流程

```
1. Recruiter Screen (30 min, 背景 + 动机 + 简历过)
2. OA / Take-home (Colab notebook 形式,自带题目 → 代码 + 报告)
   - SWE Intern: 算法 + ML 概念
   - ML Intern: 实现 top-k decoding、attention layer、tokenization 等
3. Coding Interview (45 min Live, Google Colab + 实时讲思路)
4. Project / Manager Deep Dive
   - 简历项目 deep dive (30-60 min,问到代码细节)
   - Team 介绍 + 候选人兴趣对齐
5. ML Design / System Design (针对 ML Intern)
   - 设计 ChatGPT 类系统 / 训练 pipeline / inference 服务
6. (可选) 论文讨论 — Research Intern 必有
```

总耗时 **4-6 周**,Pass rate 中等偏低 (~20-30%)。

## 5. 面经摘录

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|---|---|---|---|---|---|
| 2024 中 | MLE VO / 信号通用 | Colab coding + ML design | 实现 top-k LLM token decoding + ML design (ChatGPT 类) | / | 一亩三分地 |
| 2024 中 | OA / Internship | Colab notebook | Attention / tokenization 实现 + 写报告 | / | 一亩三分地 |
| 2024 | Research Intern (Fall) | Resume → 论文讨论 + 技术 | 论文 deep dive + Transformers 实现细节 | / | Cohere job listing |
| 2025 | 通用面试讨论 | 4 轮 | 行业 / LLM 知识 → 缩到具体概念 | / | Blind |
| 2024 | 非 PhD ML Intern | Coding + project | 强调要"明确的兴趣 / 已有项目" | / | Glassdoor |

## 6. 文化与口碑

- **正向**:
  - **Cohere Labs (研究部门) 学术氛围浓**,与开源社区互动多 (Aya 项目、C4AI)
  - 薪资业界顶尖 (CEO 明确背书"高薪")
  - 创始人 Aidan Gomez 是 Transformer 作者 → 实习生有机会接触顶级科学家
  - 多元化 + open research 文化
- **挑战**:
  - **极高 bar**: ML Intern 也常被要求 PhD 在读或顶会论文
  - 多伦多 / 旧金山中心化 → 伦敦团队规模较小,可触及项目可能受限
  - 与 OpenAI / Anthropic / DeepMind 竞争激烈,顶尖人才稀缺
  - Glassdoor 评分 4.0+ (相对小样本)

## 7. 重点准备清单

### ML / Research Intern 方向
1. **必读论文**: "Attention Is All You Need" (Aidan 作者之一);BERT/GPT 系列;LoRA、QLoRA;RLHF;Chinchilla scaling
2. **必跑代码**:
   - 从零实现 Multi-head Attention + RoPE
   - 实现 top-k / nucleus / beam search decoding
   - Fine-tune 一个开源 LLM (LLaMA / Mistral / Cohere Command-R)
3. **分布式训练**: ZeRO、Tensor Parallelism、Pipeline Parallelism
4. **效率优化**: FlashAttention、KV cache、量化 (GPTQ / AWQ)

### SWE Intern 方向
1. LC Medium + 算法基础
2. Python 性能 (asyncio、multiprocessing)
3. Kubernetes / Docker / API 设计

### 行为面
1. "为什么 Cohere (而非 OpenAI / Anthropic)" — 必须真诚,谈企业 LLM 差异化
2. 项目 deep dive 准备 — 简历每个项目能讲到代码细节

## 8. 总结评级

| 维度 | 评级 | 备注 |
|---|---|---|
| 信息丰富度 | 中-高 | 海外面经丰富,伦敦定向略少但流程清晰 |
| 申请门槛 | 极高 | LLM 研究 + 工程双向高 bar |
| Offer 转化预期 | 低 | Pass rate 20-30%,Research Intern 更低 |
| 推荐指数 | 强烈推荐 (对 ML 方向) | 顶级 LLM 雇主,品牌价值与未来通道极佳 |

> **建议**: ML / 研究方向同学必申。准备时间至少 2-3 个月,论文 + 代码双修。简历必须有 ML 项目 + GitHub 公开实现。能拿到面试已是顶尖证明。

## 信息来源

- [Cohere Careers](https://cohere.com/careers)
- [Cohere Research Internship Fall 2025 - Built In](https://builtinlondon.uk/job/research-internship-fall-2025/4808713)
- [Cohere SWE Intern Job Ashby](https://jobs.ashbyhq.com/cohere/8c035d3d-081d-4c8a-914a-72f4efaad254)
- [Cohere ML Intern Spring/Summer 2026 - Jobright](https://jobright.ai/jobs/info/69698998f25a380066982e96)
- [Levels.fyi Cohere Intern Salary](https://www.levels.fyi/internships/Cohere-ai/Software-Engineer-Intern/)
- [Cohere ML Intern Interview Questions Glassdoor](https://www.glassdoor.com/Interview/Cohere-Machine-Learning-Intern-Interview-Questions-EI_IE6413613.0,6_KO7,30.htm)
- [一亩三分地 Cohere OA](https://www.1point3acres.com/bbs/thread-1059251-1-1.html)
- [一亩三分地 Cohere MLE VO](https://www.1point3acres.com/bbs/thread-1065950-1-1.html)
- [Cohere UK Ltd Sponsor Status](https://immigrationgpt.co.uk/company/Cohere-UK-Ltd)
- [Cohere European Expansion - Sifted](https://sifted.eu/articles/aidan-gomez-cohere-interview)
- [Cohere Labs Research](https://cohere.com/research)
- [Blind Cohere Interview Discussion](https://www.teamblind.com/company/Cohere/posts/cohere-interview)
- [Cohere AI Researcher Interview Guide](https://www.datainterview.com/blog/cohere-ai-researcher-interview)
- [Levels.fyi - Cohere London SWE 2026-05](https://www.levels.fyi/en-gb/companies/cohere/salaries/software-engineer/locations/london-metro-area)
- [Levels.fyi - Cohere SWE UK 全境](https://www.levels.fyi/companies/cohere/salaries/software-engineer/locations/united-kingdom)
- [UK Skilled Worker 2026 £41,700 threshold - Jobbatical](https://www.jobbatical.com/blog/uk-skilled-worker-visa-minimum-salary-41700-threshold-employer-guide)
- [Glassdoor - Cohere MTS Salaries (US)](https://www.glassdoor.com/Salary/Cohere-Member-Of-Technical-Staff-Salaries-E6413613_D_KO7,32.htm)
- [6figr - Cohere Salaries 2026](https://6figr.com/us/salary/cohere)
- [Blind - AI scientist / MTS comp Mistral vs Cohere London](https://www.teamblind.com/post/ai-scientist-member-of-technical-staff-compensation-for-mistralcohere-london-7x2nc1m1)
