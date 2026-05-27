# Mistral AI (巴黎) — 实习情报

> 法国本土头牌大模型公司, 估值约 60-140 亿欧元 (2024-2025), 团队 ~100 人迅速扩张至 200+. 招聘门槛极高, 通常需要 NeurIPS/ICML 级别论文或顶会一作; Master 实习生需来自 "Tier 1" 工程师学院.

---

## 1. 公司速览

| 维度 | 信息 |
|---|---|
| 总部 | Paris (法国) — 主要办公室, 另有 London/Palo Alto/Singapore |
| 成立 | 2023 年 4 月, Arthur Mensch, Guillaume Lample, Timothée Lacroix 创立 |
| 估值/规模 | 约 USD 14B (2025), 约 100-200 名员工, 计划再招 125 人 |
| 业务 | 开源 + 闭源 LLM (Mistral 7B, Mixtral, Codestral, Large 2), API, Le Chat |
| 技术栈 | PyTorch, JAX, Megatron-LM, Slurm/K8s on 数千块 GPU, Rust 推理 |
| 工作风格 | 工程师驱动, 扁平结构, 快速 ship, 开源优先, Paris-first |
| Glassdoor 评分 | ~4.7/5 推荐率 100% (样本小); WLB 3.8/5 |

---

## New Grad / Junior 岗位

> ⚠️ **待 web 验证**: 本节未做实时 WebSearch 与 WebFetch (agent sandbox 限制), 数据完全基于模型已有知识 + 文件 intern 部分提取; 引用链接为推测入口, 未直接核对. **二次核实前勿用于薪资 / 截止日期决策**.

> 信息丰富度: ⭐⭐ (Mistral 整体公司信息有限, 公开 Junior / new grad 数据极少, Levels.fyi 主要是 mid/senior 数据, 应届岗几乎不公开 leveling)
> 区别于实习: 全职 entry-level (0-2 年经验); Mistral 招聘高度 senior-skewed, 真正意义上的 "new grad" 全职岗极少, 主要靠 **PhD 实习 + CIFRE 转正** 通道

- **常见岗位名**: ML Research Engineer、Research Scientist、Applied AI Engineer、Forward Deployed Engineer、Software Engineer (Infrastructure); 招聘页**几乎不挂 "Junior" / "Graduate"** 标签 — Mistral 偏好已有 1-3 年大模型经验或 PhD 在读 / 应届 PhD
- **欧洲地点**: 主基地 **Paris (9 区)**; 部分岗位 **London**; 极少 Zurich / Warsaw; Junior / 应届岗几乎默认 Paris onsite
- **是否有独立 Graduate Programme**: **No** — Mistral 是 100-200 人规模的 scaleup, 没有 graduate scheme; 唯一接近的是 **CIFRE (法国博士企业联合培养) → Full-time Research Engineer** 通道, 这是 PhD 学生的主入口
- **非EU签证 (全职)**:
  - **France Passeport Talent (Salarié Qualifié)**: 月薪 ≥ 2x SMIC (~€3,494/月 gross), 应届 ML Engineer 通常达标; Mistral 会 sponsor (相比实习的"靠学生身份"差别大)
  - **EU Blue Card (France)**: 阈值 ~€53,837/年 (2025), Mistral SWE 起薪 €78k+ 通常达标
  - **APS (Autorisation Provisoire de Séjour)**: M2 法国毕业生 12 个月 + 可延 24 个月找工作, 期间可全职; 是中国 / 印度 candidate 常用的"先实习 → 找全职 → sponsor"路径
- **薪资范围 (base, gross/年)** (Levels.fyi 2024-2025, Mistral 数据样本极小):
  - **Paris Junior / Entry ML Engineer** (估计, 公开数据稀少): base ~€78,000-95,000, +equity (pre-IPO 期权, 估值 ~$14B 但液体性差)
  - **Paris Mid ML Engineer**: Levels.fyi 中位 ~€108,000-142,000+ base
  - **Paris Senior ML Engineer**: €130-180k base + equity
  - 福利: 餐券、Gympass、私人医保、学习预算、全职股票期权
  - 与法国本土 (Criteo / Doctolib) 相比 Mistral 全职起薪高 ~30-50%
- **申请窗口**: **Rolling 全年滚动**; Mistral 招聘节奏快 (2024 100 人 → 2025 计划 +125 人), 但 bar 极高, 每个 req 候选人池庞大; 没有 cohort batch
- **面试流程差异 vs 实习**:
  - 实习 5-6 轮 (HR → Team Lead → LLM Quiz → Coding → System Design → Fit), 全职 **同样 5-6 轮但每轮深度上升**
  - **从零实现 attention 仍是高频考点** (全职 / 实习共通), 全职还会加 multi-GPU 训练 / inference optim / distributed training 题
  - System Design: 全职会问 inference serving (vLLM-style)、KV cache management、batch scheduling、multi-tenant serving
  - Founder round 在全职流程出现频率更高 (实习偶有)
- **录取竞争**: Mistral 公开"hire only the best", Master 实习命中率 < 5%, 全职 entry-level 类似严苛; 国际生 friendliness 中等 — sponsor visa 是支持的, 但 bar 远高于 Hugging Face / Criteo AI Lab; 顶会一作论文 / 大型开源 PR 是入场券
- **关键链接**:
  - Mistral Careers: https://mistral.ai/careers
  - Lever Mistral Jobs (全部 req): https://jobs.lever.co/mistral
  - Levels.fyi Mistral AI: https://www.levels.fyi/companies/mistral-ai/salaries
  - Glassdoor Mistral AI Interviews: https://www.glassdoor.com/Interview/Mistral-AI-Interview-Questions-E9945031.htm
  - datainterview Mistral Engineer Guide 2026: https://www.datainterview.com/blog/mistral-ai-engineer-interview
  - Welcome to the Jungle Mistral (法国本土招聘 / 福利更细): https://www.welcometothejungle.com/en/companies/mistral-ai/jobs
  - Reddit r/MachineLearning Mistral hiring 讨论: https://www.reddit.com/r/MachineLearning/search/?q=mistral

---

## 2. 实习岗位类型

| 岗位名 | 学位要求 | 团队 | 关键词 |
|---|---|---|---|
| AI Scientist Internship (Master) | M2, Tier 1 学校 (Math/Physics/ML) | Science Team | LLM 设计, NLP 研究, 模型优化 |
| AI Scientist Internship (PhD) | 在读 PhD, 顶会发表加分 | Science Team | 前沿研究, 自由选题, 发论文 |
| Applied Scientist / Research Engineer (Intern) | M2 或 PhD | Applied AI | 客户场景定制模型, 多模态 (文本/图像/语音) |
| Applied AI, Forward Deployed ML Engineer (Intern) | M2 (CS/Math/ML) | Applied Engineering | 客户 LLM 部署, 微调, RAG, eval |
| ML Research Engineer (有时开实习) | M2/PhD | Research Engineering | 预训练/后训练流水线, 千卡集群 |

**地点**: 主要为 Paris; 部分岗位 Paris/London/Zurich/Warsaw 三选一. 部分支持 CIFRE (法国博士+企业联合培养) 续期.

**时长**: 3-6 个月 (6 个月最佳), 倾向毕业前最后一段实习.

---

## 3. 申请资格 (Hard Requirements + 加分项)

| 项 | 内容 |
|---|---|
| 学历 | M2 / PhD 在读. Master 岗明确要求 "Tier 1 engineering schools or universities" — 中国学生约相当于清北 / 港科 / EPFL / Polytechnique / ENS / Cambridge / Oxford 级 |
| 语言 | 英文为主, 法语非必需但加分 |
| 编程 | Python 强制, PyTorch/TF, 加分: 对大型开源代码库的 contribution |
| 研究 | NLP/LLM/Transformer 相关 publication 强烈加分; PhD 岗几乎必备 |
| 数学 | 线性代数, 概率, 优化扎实 |
| 工程 | 熟悉分布式训练 (FSDP/DeepSpeed/Megatron), GPU profiling 加分 |
| 时间 | 倾向 "即将毕业" 的候选人, 可转正 (尤其 CIFRE 路径) |

> **重要警告**: Mistral 在 Master 实习这一档极其挑剔. 一亩三分地/Reddit 上几乎找不到非顶校非论文背景拿到面试的案例. 如果你 CV 上没有顶会/顶刊一作, 没有大型开源 PR, 没有 EPFL/Polytechnique/ENS/MIT 级学校, 命中率 < 5%. 这是诚实的判断, 不是劝退, 而是建议你**同时投 Hugging Face、Criteo AI Lab、Kyutai 等更可达的选择**.

---

## 4. 招聘流程 (基于 Glassdoor / interviewquery / datainterview)

Mistral 流程平均 ~15 天, 5-6 轮:

| 轮次 | 内容 | 时长 | 形式 |
|---|---|---|---|
| 1. HR Screen | 背景, 动机, 时间线, 期望 | 30 min | 电话/Google Meet |
| 2. Team Lead Screen | 简历深挖, 项目/论文细节 | 30-45 min | Video |
| 3. LLM Quiz | Transformer 架构, attention, KV cache, RAG, fine-tuning, embedding retrieval, scaling laws | 45-60 min | 严格 Q&A 格式 (非讨论), 求具体答案 |
| 4. Coding / Tech | LeetCode 中等; 也可能要求**从零手写 multi-head self-attention** (含 causal mask, batch) | 60-90 min | 共享编辑器 |
| 5. System Design / Take-home Panel | 训练系统设计, 推理服务架构; 或 take-home + 答辩 | 60-90 min | Video |
| 6. Fit / Founder Round | 与创始人或资深 member 谈愿景与匹配 | 30-45 min | Video |

**特点**:
- 流程**重 LLM 内深度** > 经典 ML 广度. KV cache, embedding, RAG pipeline 都是高频考点.
- Coding 要求**能从零实现 attention**, 不光是会调 API.
- "rigid Q&A" 风格 — 面试官在找你说出特定知识点, 而非开放讨论.

---

## 5. 面经汇总

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|---|---|---|---|---|---|
| 2024-2025 | Applied AI Engineer (Paris) | HR → Tech Manager → LLM Quiz → Coding → Take-home → Fit | LLM Quiz: KV cache, embedding retrieval, RAG; coding: multi-head attention from scratch | 难度 2.56-3/5 (Glassdoor), 11.1% positive | [Glassdoor Mistral Interviews](https://www.glassdoor.com/Interview/Mistral-AI-Interview-Questions-E9945031.htm) |
| 2024-2025 | Applied AI Engineer | 6 轮: HR / Team Lead / Business Case / Tech (LLM+SysDesign) / Take-home Panel / Fit | Business case 面向客户使用场景 | 信息匮乏 | [Mistral AI Engineer Guide - datainterview](https://www.datainterview.com/blog/mistral-ai-engineer-interview) |
| 2024 | Software Engineer | ~5-6 rounds, ~15 天 | LeetCode 中等, 系统设计聚焦推理/训练栈 | — | [Mistral AI SWE Interview - interviewquery](https://www.interviewquery.com/prep-guides/mistral-ai-software-engineer) |
| — | LLM Engineer | LLM Quiz 重头 | Transformer arch, fine-tuning, RAG | — | [Glassdoor LLM Engineer](https://www.glassdoor.com/Interview/Mistral-AI-LLM-Engineer-Interview-Questions-EI_IE1133892.0,7_KO8,23.htm) |

> 中文社区 (一亩三分地/牛客/知乎) 关于 Mistral 实习的具体面经几乎为零. **信息匮乏**, 建议直接看 Glassdoor / Reddit r/MachineLearning.

---

## 6. 薪酬与待遇

| 项 | 数值/说明 |
|---|---|
| 全职 SWE 薪资 (Paris) | €78.6K - €134K+ (Levels.fyi); 高级岗 €108-142K+ |
| 实习 stipend | 公开信息有限. 法国 stage 法定最低 **€4.35/小时 (2025)**, 折合月 €600+; **Mistral 一般明显高于法定**, 业内估计 €1,500-2,500/月; 海外渠道有提到 USD 8-11K/月 (该数字可能针对美国岗, Paris 实习未必如此) — **以 offer 为准** |
| 福利 | 餐券 (titre-restaurant), Gympass 月度补贴, 流动通行证 (mobility pass), 私人医保, 学习预算, 全职可拿股票期权 |
| Convention de stage | 必须. 学校出三方协议. >2 个月强制 gratification |
| 视觉认证 | 非欧盟学生需有效 carte de séjour étudiant (法国校籍直接拿); 海外校招需考虑 visa stagiaire (APS 不适用于实习) |

---

## 7. 文化, 工作环境, 软情报

- **节奏**: 周报/Slack/极少会议, 工程师高度自驱. 早期员工形容 "everyone wears many hats".
- **开源文化**: 模型权重和代码大量开放; 你在 GitHub/HF 上的可见贡献 (vLLM, transformers, llama.cpp 等 PR) 是真金白银的加分项.
- **WLB**: Glassdoor 3.8/5. 不是 996, 但 ship 节奏快, deadline 前压力大.
- **办公室**: Paris 9 区/中心. 多语种, 工作语言英文.
- **转正**: PhD 实习 → CIFRE/Full-time research engineer 通道相对清晰; Master 实习转正难度高但有先例.
- **风险点**: 团队规模快速膨胀 (100 → 200+), early-employee 红利在递减; 内部 mentorship 不像大厂结构化.

---

## 8. 申请策略与时间线建议

| 步骤 | 建议 |
|---|---|
| 1. 立 OSS 信用 | 在 HuggingFace / vLLM / transformers / candle / mistral.rs 中提交至少 1-2 个有 substance 的 PR (>50 行, 被 merge) |
| 2. 找一个公开可见的 LLM 项目 | GitHub 仓库 + 一篇短 blog 解释 design choices (微调, RAG, eval). 这远胜过课程作业 |
| 3. CV 调整 | publication / 顶会一作放最上方; 没有论文则首屏放开源 PR + 关键 ML 项目 |
| 4. 时间窗 | M2 stage 通常 3 月-9 月起 / 9 月-2 月起两期; **提前 4-6 个月** 在 jobs.lever.co/mistral 投, 越早越好 |
| 5. 内推 | 通过法国校友群 (X-Polytechnique, ENS, MVA, IP Paris) 找内推; Mistral 大量员工来自 MVA 项目 |
| 6. 准备深度 LLM | 重点啃 KV cache, paged attention, FlashAttention, RAG (BM25 + ANN), DPO/RLHF/PPO, scaling laws, MoE; 看 Anthropic/OpenAI/Meta 近 2 年综述 |
| 7. Coding 准备 | LeetCode Medium + **能在 45 min 内从零实现 Transformer block** (PyTorch, naked) |
| 8. 备选方案 | 同时投 Hugging Face, Kyutai (Paris, 与 Mistral 师出同门), Cohere, Anthropic, Meta FAIR Paris, Adept |

---

## 来源

- [Mistral AI Careers](https://mistral.ai/careers)
- [Lever - Mistral Jobs](https://jobs.lever.co/mistral)
- [Mistral AI - AI Scientist Master Internship](https://jobs.lever.co/mistral/292397f0-4ac7-4309-a0e8-63c97761a2cb)
- [Mistral AI - Applied AI Forward Deployed ML Engineer Internship](https://jobs.lever.co/mistral/881941e1-2741-48e2-8767-12866965fac5)
- [Glassdoor - Mistral AI Interview Questions](https://www.glassdoor.com/Interview/Mistral-AI-Interview-Questions-E9945031.htm)
- [Glassdoor - Mistral AI Applied AI Engineer Interview](https://www.glassdoor.com/Interview/Mistral-AI-Applied-AI-Engineer-Interview-Questions-EI_IE9945031.0,10_KO11,30.htm)
- [interviewquery - Mistral AI SWE](https://www.interviewquery.com/prep-guides/mistral-ai-software-engineer)
- [datainterview - Mistral AI Engineer Guide 2026](https://www.datainterview.com/blog/mistral-ai-engineer-interview)
- [datainterview - Mistral AI Researcher Guide](https://www.datainterview.com/blog/mistral-ai-researcher-interview)
- [Levels.fyi - Mistral AI Salaries](https://www.levels.fyi/companies/mistral-ai/salaries)
- [Glassdoor - Working at Mistral AI](https://www.glassdoor.com/Overview/Working-at-Mistral-AI-EI_IE9945031.11,21.htm)
- [Welcome to the Jungle - Mistral AI Jobs](https://www.welcometothejungle.com/en/companies/mistral-ai/jobs)
- [PropelGrad - Mistral AI Jobs & Internships](https://propelgrad.com/ai-jobs/at-mistral)
