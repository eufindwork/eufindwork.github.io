# Cohere (伦敦) 实习情报

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

> 信息丰富度: ⭐⭐⭐⭐ (Levels.fyi London SWE 2026-05-27 实测有具体 L3 MTS 数据点; Glassdoor UK MTS 数据样本较少, US 数据丰富, **London 中位 £172K total / base ~£135K**)
> 区别于实习: 全职 entry-level (0-2 年经验) — Cohere 以 "Member of Technical Staff" (MTS) 为主轴, 内部按 L3/L4/L5 分级但 title 不区分

- **常见岗位名**: Member of Technical Staff (Research / Engineering), Machine Learning Engineer, Software Engineer, Research Engineer; **无 "Junior" / "New Grad" 显式 title** — 新人按 L3 MTS 入职, 与有经验候选人共用同一 title
- **欧洲地点**: London (核心研究 + 工程 hub, 与实习一致) + Paris (40 人新办公室, 2024 扩张, 偏研究 + 企业销售支持); 极少 fully remote 欧洲岗
- **是否有独立 Graduate Programme**: **No** — Cohere ~400 人, 不跑 cohort grad pipeline; 一切走 MTS 通道, 与 OpenAI / Anthropic 模式一致 (paper + 代码 > 学历标签)
- **非EU签证 (全职)**:
  - **London**: Cohere UK Ltd 是 **Skilled Worker 持牌 sponsor** (Home Office register 已确认 [来源 (搜索结果): https://immigrationgpt.co.uk/company/Cohere-UK-Ltd]); 对非英国 new grad 可发 CoS
  - **关键更新**: UK Skilled Worker 最低 base 2025-07-22 起从 £38,700 **上调至 £41,700** (2026 仍有效) [来源 (搜索结果): https://www.jobbatical.com/blog/uk-skilled-worker-visa-minimum-salary-41700-threshold-employer-guide]; 另有 New Entrant 折扣线 £33,400; Cohere London L3 base ~£135K 远超达标
  - **Paris**: Passeport Talent (salarié qualifié) 可走, base 需 ≥ €43,243 (2026 SMIC × 1.8), Cohere Paris MTS base 估计 €90K+ 完全达标
  - 与实习 (Student Visa / carte de séjour étudiant) 路径完全不同, **全职更稳定**
- **薪资范围 (base, gross/年)**:
  - **London MTS L3 median 2026-05-27 实测**: **base ~£135K ($176K USD) / total £172K ($230K USD) / stock ~£42K ($54.1K) / bonus 0** — Levels.fyi L3 median (median 4 年经验, 2 年 tenure, 略偏高于纯 new grad) [来源 (实际打开过): https://www.levels.fyi/en-gb/companies/cohere/salaries/software-engineer/locations/london-metro-area]
  - **London SWE 区间**: £82.3K-£171K+ (Levels.fyi 2026-05 区间) → **纯 new grad L3 估计落在 £100-130K base**
  - **Glassdoor UK MTS average**: £44K base (样本极小, 偏向报告偏差, 与 Levels.fyi 严重不符 — 以 Levels 为准) [来源 (搜索结果, WebFetch 403): https://www.glassdoor.co.uk/Salary/Cohere-Member-Of-Technical-Staff-Salaries-E6413613_D_KO7,32.htm]
  - **US MTS average**: $240K base (Glassdoor US, 25-75 分位 $190K-$308K) — 欧洲 London 打 0.7-0.75 折大致符合 Levels.fyi 数据
  - **Paris MTS L3** (估计, 无 Levels 数据): €90-115K base + equity (高于 Mistral L3 €70-80K, 与 OpenAI Paris 持平)
  - **CEO Aidan Gomez 公开承诺 "extremely high salaries"** — 与 Anthropic/OpenAI 同档已被 Levels.fyi 验证
- **申请窗口**: rolling — 全年开放, Ashby 招聘页持续更新 [来源 (搜索结果): https://cohere.com/careers]; **paper deadline 时段 (ICML / NeurIPS) 后会集中放 Research MTS** 岗
- **面试流程差异 vs 实习**:
  - 多一轮: **Paper Bar 显著加重** (Research MTS 必有 1-2 轮 paper deep dive, 实习偶尔才有)
  - **System Design 必考** (实习只有 ML Intern 才考): ChatGPT 类 serving / training pipeline / multi-tenant inference
  - Coding bar 与实习同 (Colab + ML 实现题), 但**总轮次多 1-2 轮** (5-7 轮 vs 实习 4-5 轮)
  - OSS / paper 中至少一项**硬要求** — Cohere For AI (C4AI) 团队尤其看重 Aya / multilingual NLP 贡献
- **录取竞争**: 极高 — Pass rate 估计 5-10% (vs 实习 20-30%); 与 OpenAI / Anthropic / DeepMind 抢同一批人; **国际生 OK** 但需要 paper 或 OSS 硬通货, 学校牌子是加分项但非决定
- **关键链接**:
  - 官方 careers 页: [cohere.com/careers](https://cohere.com/careers)
  - Levels.fyi Cohere London SWE: [levels.fyi Cohere London](https://www.levels.fyi/en-gb/companies/cohere/salaries/software-engineer/locations/london-metro-area) (实际打开过, 2026-05-27 数据)
  - Cohere UK Ltd Skilled Worker 状态: [immigrationgpt.co.uk](https://immigrationgpt.co.uk/company/Cohere-UK-Ltd)
  - UK Skilled Worker 2026 £41,700 门槛: [Jobbatical](https://www.jobbatical.com/blog/uk-skilled-worker-visa-minimum-salary-41700-threshold-employer-guide)
  - Cohere Paris expansion: [Sifted - Aidan Gomez interview](https://sifted.eu/articles/aidan-gomez-cohere-interview)
  - Blind Cohere 讨论: [teamblind.com/Cohere](https://www.teamblind.com/company/Cohere/posts/cohere-interview)
  - Cohere Labs (研究 vs 工程区分): [cohere.com/research](https://cohere.com/research)

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
