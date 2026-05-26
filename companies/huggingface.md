# Hugging Face (巴黎 / Remote) — 实习情报

> 全球开源 ML 社区中心, 法美双总部 (Paris + NYC), 几乎所有岗位都支持 remote. 招聘**极度看重开源贡献** — GitHub PR/HF Hub 上的可见 contribution 权重高过传统 CV. 实习 stipend 在欧洲算高 (€35K/年 gross = €2.9K/月).

---

## 1. 公司速览

| 维度 | 信息 |
|---|---|
| 总部 | Paris (法国) + New York (美国); 多数岗位 fully remote (US/EMEA) |
| 成立 | 2016, Clément Delangue + Julien Chaumond + Thomas Wolf 创立 |
| 规模 | 估计 350+ 员工, 增长快 |
| 业务 | 🤗 Hub (model/dataset/space 平台), Transformers, Datasets, Accelerate, Diffusers, TRL, PEFT, 等开源库; Enterprise 私有部署; Inference Endpoints |
| 估值 | ~USD 4.5B (2023 一轮 D) |
| 工作语言 | **英文 only** (Paris office 也是) |
| 文化 | 极度开放, OSS-first, async-friendly, diversity 强调 |
| Glassdoor 评分 | 整体 ~3.7-4.0/5, 难度 3.09/5, intern 难度被打成最高 |

---

## 2. 实习岗位类型

HF 每年都有 dedicated intern cohort, 通常一次性宣布 (见 [huggingface.co/blog/interns-2023](https://huggingface.co/blog/interns-2023) 等). 类型横跨多个团队:

| 岗位 | 团队 | 关键词 |
|---|---|---|
| ML Engineer Internship - ML for Code | Open Source / Science | CodeParrot, BigCode, Megatron-LM |
| ML Engineer Internship - WebML | Inference | TF.js / ONNX / WASM 端侧推理 |
| ML Engineer Internship - AI Art Tooling (Residency) | Diffusers | Stable Diffusion 工具链, 艺术家协作 |
| ML Engineer Internship - Audio | Audio / TTS / ASR | Whisper, Bark, MusicGen |
| Accelerate Internship | Open Source | 分布式训练库 feature |
| Text-to-Speech Internship | Open Source | TTS reproduction |
| Embodied AI Internship | Science | RL in simulators (LeRobot 等) |
| Fast Distributed Training Framework Internship | Science | 大规模训练框架 |
| Datasets for LLMs Internship | Science | LLM 训练数据集 (FineWeb, FineFineWeb 系列) |
| Social Impact Evaluation Internship | Ethics / Policy | 生成模型社会影响评估 |
| AI Resident (9-month residency) | Science | 类似 Google Brain residency, 目标发论文 |

**地点**: Paris / Remote (EMEA, US) — 大部分岗位描述都写 "Remote (location)", Paris 是 EMEA HQ 但**绝大多数 intern 选择 remote**.

**时长**: 大部分 3-6 个月; AI Residency 9 个月.

---

## 3. 申请资格

| 项 | 内容 |
|---|---|
| 学历 | Master / PhD 在读, 也接受 early-career 非学生 (residency 尤其) |
| 编程 | Python 强制; PyTorch 必备 |
| ML | Transformer / NLP 基础扎实 |
| **开源贡献 (硬权重)** | **GitHub / HuggingFace Hub 上的可见贡献是面试官第一关注点** — 一个 merged transformers PR > 学校排名 |
| 项目可见性 | HF Spaces demo, dataset card, model card, blog post 都算 |
| 多样性 | 公司明确鼓励 underrepresented (POC, working-class, women, LGBTQ+) 申请 |
| 语言 | 英文 (流畅书面 + 口语) |

> **核心差异**: 这是欧洲所有 ML 公司里**唯一一家可以靠"非常强的 OSS 贡献从二线学校 / non-trad 背景拿到面试"**的. 一个 contributions tab 全绿且在 transformers/diffusers 主仓有 substantial PR 的候选人, 比 IIT/清北无 OSS 的更受青睐.

---

## 4. 招聘流程

HF 流程**轻量 + 实战**, 不打 whiteboard 车轮战:

| 轮次 | 内容 | 时长 |
|---|---|---|
| 1. 申请提交 | 通过 Workable; **末尾要写一段 short project / proposal** (针对岗位主题) | — |
| 2. Recruiter Call | 初步聊背景, 兴趣, 时间 | 30 min |
| 3. Take-home Assignment | 比如: 写一个 HF Spaces demo, 修一个 transformers / diffusers 的 bug, 做一个 dataset card, 跑个 small experiment + 写报告 | 几天到一周 |
| 4. Take-home Review Call | 你 present + 工程师 follow-up | 45-60 min |
| 5. Team Fit / 见队友 | 1-2 轮 与 team 成员视频, "getting to know" 性质 | 30-45 min each |

**关键特点**:
- **"collaborative and conversational, not adversarial"** — 候选人反馈
- 不要求背 LeetCode, 不刷 algorithm trivia
- 重点是: 你怎么解决问题, 怎么跟团队协作, 怎么贡献开源
- 反馈周期可能慢: 一个 Reddit 用户报告 ~1.5 个月才听到 take-home 结果
- 部分负面反馈: 个别 reviewer 没认真看 take-home, 反馈"only 'good'"

---

## 5. 面经汇总

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|---|---|---|---|---|---|
| — | ML Engineer Intern | Round 1 知人 → Round 2 coding → Round 3 见团队 | "collaborative, problem-solving + OSS contribution focused" | 难度 3.09/5 (Glassdoor) | [Glassdoor - HF Interview Questions](https://www.glassdoor.com/Interview/Hugging-Face-Interview-Questions-E6487302.htm) |
| — | Biomedical Imaging Intern | Take-home → ~1.5 months → 几个 call | Take-home 类项目实操 | hire (Reddit) | Reddit 用户报告 (汇总自 [getbridged 文章](https://www.getbridged.co/company-reviews/hugging-face)) |
| — | ML Intern (general) | Take-home (Spaces demo / dataset card / bug fix) → review call | 小项目 + 报告 | mixed feedback | [interviewquery - HF ML Engineer Guide](https://www.interviewquery.com/interview-guides/huggingface-machine-learning-engineer) |
| — | Intern (Internship + AI/ML Engineer Intern) | 标准流程 | — | **Intern 难度被打成最高** (Glassdoor) | Glassdoor 同上 |
| — | AI Resident (9-month) | Application + project proposal → calls → 启动研究 | 自选 research direction, 与 Science Team 配对 | — | [HF Blog - Announcing AI Residency](https://huggingface.co/blog/ai-residency) |

> 中文社区 (1p3a/牛客/知乎) HF 面经几乎为零 — **信息匮乏**, 但英文 Glassdoor + Reddit + Taro 有零星 case.

---

## 6. 薪酬与待遇

| 项 | 数值/说明 |
|---|---|
| Paris 实习 stipend | **€35K gross / 年 ≈ €2,917 / 月** (官方招聘描述明确) — 这是 Paris 区**最高档之一** |
| NYC 实习 stipend | USD $50K / 年 ≈ $4,167 / 月 |
| Remote 其他地点 | "adjusted to cost of living" — 通常折算到当地市场 |
| AI Resident (9 months) | 当作全职待遇, 含 medical (依据地点); 数字未公开 |
| Convention de stage | Paris 岗需要; HF HR 配合学校 |
| 福利 | Mac, 远程办公, 学习资源, conference budget, 内部 Hub 全功能 |
| Visa | Paris 岗对非欧盟学生需要 carte de séjour étudiant; full-remote 岗可在你本国签合同 (contractor 形式), 取决于团队 |

> €35K gross 在 Paris 实习 stipend 里基本顶配 (对比 Criteo ~€1,500/月 = €18K/年, Deezer €1,700/月 = €20K/年).

---

## 7. 文化, 工作环境, 软情报

- **OSS-native**: 你的工作几乎全部 in public, GitHub PR + Hub model card 是你的产出
- **Async-first**: 全球团队, 时区分散; Slack + GitHub + 文档驱动
- **多元化**: 招聘描述里反复强调欢迎 underrepresented 群体, 这不是漂亮话, HF 内部确实是 ML 圈子里 diversity 较好的
- **No CV-cult**: 学校牌子不重要, contribution 是硬通货
- **节奏**: 比 Mistral 稍慢, 不强调"千卡集群极限优化", 但因为是 platform 公司, infra/scale 问题不少
- **Paris office**: 位于 Paris 9 区附近; 但是绝大多数员工 remote
- **晋升路径**: intern → 转正 case 不少, 尤其 OSS 已有 contribution 的
- **真实风险**: HF 的实习名额按 cohort 发布, 不是常年开放; 错过 batch 要等下一轮
- **Residency vs Internship**: Residency 是 9 个月、全职、可发论文、目标 "成为独立 AI researcher"; Internship 是 3-6 个月跟 team 做项目. **Residency 比 internship 还难进, 与 Mistral PhD 实习同级别**

---

## 8. 申请策略与时间线建议

| 步骤 | 建议 |
|---|---|
| 1. **立 OSS 信用** (最重要) | 在 transformers / diffusers / datasets / accelerate / peft / trl / lighteval 中提交至少 1-2 个有 substance 的 merged PR. Bug fix 起步可, 但**新 feature / model 集成 PR 含金量最高** |
| 2. 建 HF Hub presence | 自己 publish model + dataset card, 至少 1 个公开 Space (demo) |
| 3. CV 改造 | 第一屏放: 你的 HF profile URL + GitHub stats + 关键 PR 列表; 学校放第二屏 |
| 4. 短 project proposal | 申请表末尾的 "short project" 字段是真的会被看 — 写一个针对该 team / repo 的具体技术 proposal, 200-400 字 |
| 5. 投递时间 | HF intern cohort 通常**春季 (3-4 月) 集中宣布**, 关注 [HF blog](https://huggingface.co/blog) + [Workable 招聘页](https://apply.workable.com/huggingface/); cohort 之外少量滚动岗 |
| 6. 选岗 | 你的 OSS contribution 在哪个 repo, 就投哪个 team 的 intern; 完全无 contribution 投 LLM data / training infra 类岗匹配度低 |
| 7. Take-home 准备 | 平时就练 HF Spaces (Gradio app); transformers 上手 fine-tune; datasets streaming. Take-home 就是把这些手感串起来 |
| 8. 跟进 | 反馈周期可能拖到 1.5 个月; 申请后 4 周无动静可以 ping recruiter, 但不要烦 |
| 9. 备选 | 同级别 OSS-friendly: EleutherAI, LAION, Allen AI (US 远程), Cohere For AI, Stability AI, Together.ai; Paris 同档: Kyutai, Mistral, Adept |

---

## 来源

- [Hugging Face Careers - Workable](https://apply.workable.com/huggingface/)
- [HF Blog - We are hiring interns! (2023)](https://huggingface.co/blog/interns-2023)
- [HF Blog - Announcing the AI Research Residency Program](https://huggingface.co/blog/ai-residency)
- [HF Workable - AI Resident Posting](https://apply.workable.com/huggingface/j/1B77519961/)
- [HF Workable - ML Engineer Internship WebML](https://apply.workable.com/huggingface/j/D04BE4F4A3)
- [HF Workable - ML Engineer Internship AI Art Tooling Residency](https://apply.workable.com/huggingface/j/BCCB4CAF82/)
- [Startup.jobs - HF ML Engineer Internship ML for Code](https://startup.jobs/ml-engineer-internship-ml-for-code-hugging-face-3924101)
- [Glassdoor - Hugging Face Interview Questions](https://www.glassdoor.com/Interview/Hugging-Face-Interview-Questions-E6487302.htm)
- [Glassdoor - Hugging Face AI ML Engineer Intern Interview](https://www.glassdoor.com/Interview/Hugging-Face-AI-ML-Engineer-Intern-Interview-Questions-EI_IE6487302.0,12_KO13,34.htm)
- [Glassdoor - Hugging Face Salaries Paris](https://www.glassdoor.com/Salary/Hugging-Face-Paris-Salaries-EI_IE6487302.0,12_IL.13,18_IC2881970.htm)
- [Levels.fyi - Hugging Face SWE Paris](https://www.levels.fyi/companies/hugging-face/salaries/software-engineer/locations/greater-paris-area)
- [Hugging Face Forums - AMA with Emily Witko Recruiter](https://discuss.huggingface.co/t/ama-with-emily-witko-hf-recruiter/18076)
- [interviewquery - HF ML Engineer Guide](https://www.interviewquery.com/interview-guides/huggingface-machine-learning-engineer)
- [interviewquery - HF SWE Guide](https://www.interviewquery.com/interview-guides/huggingface-software-engineer)
- [GetBridged - Hugging Face Company Review](https://www.getbridged.co/company-reviews/hugging-face)
- [Awesome AI Residency](https://github.com/dangkhoasdc/awesome-ai-residency/blob/master/README.md)
