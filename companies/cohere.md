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
