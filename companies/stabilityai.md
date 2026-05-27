# Stability AI (伦敦) 实习情报

> Stability AI 是 Stable Diffusion 母公司,伦敦总部。**2024 经历严重动荡**: 创始人 Emad Mostaque 3 月辞职,4 月裁员 10%,公司一度濒临破产。**2024 年 6 月被 Sean Parker / Prem Akkaraju / James Cameron 救火**,$80M 注资 + $400M 债务豁免,2024-2025 强势复苏 (营收三位数增长,与 WPP 战略合作)。**实习招聘恢复中但仍非常零星**,公开 internship 入口很少;**信息匮乏**,以下为综合判断。

## 1. 公司速览

| 项目 | 内容 |
|---|---|
| 总部 | 伦敦 (核心研究/工程在英国) |
| 当前领导 | CEO Prem Akkaraju (前 Weta Digital CEO);执行主席 Sean Parker;董事 James Cameron |
| 估值 | ~$1B (2024 救火后),曾估 $4B |
| 主营业务 | Stable Diffusion 系列 (image)、Stable Video、Stable Audio、与 Hollywood/广告联动 |
| 技术栈 | Python、PyTorch、Diffusers、CUDA、Triton、JAX (部分研究) |
| 实习时长 | 暂无公开标准 cohort |
| 申请窗口 | **无固定窗口** — 偶发性招聘,关注官方 careers 页 |

## New Grad / Junior 岗位

> ⚠️ **待 web 验证**: 本节未做实时 WebSearch (agent sandbox 限制权限), 部分薪资数据来自 Levels.fyi WebFetch 历史数据 + 模型已有知识; 引用链接未全部直接核对. **二次核实前勿用于薪资 / 截止日期决策**.

> 信息丰富度: ⭐ (信息极度匮乏 — 公司动荡后无公开 grad pipeline, Levels.fyi 零 London 数据, Glassdoor 仅 senior 样本)
> 区别于实习: 全职 entry-level (0-2 年经验) — Stability AI 几乎不直接招 junior, 极偏向 PhD + 2-5 年经验 ML / Research Engineer

- **常见岗位名**: Research Engineer, Research Scientist, ML Engineer, Software Engineer; **几乎不出现 "Junior" / "Graduate" / "Entry-level" title**; 内部分级不公开
- **欧洲地点**: London (核心研究 + 工程, 与实习一致); 部分 fully remote (UK / EMEA); 救火后无明确扩张计划
- **是否有独立 Graduate Programme**: **No** — Stability AI 救火后体量小 (估计 100-150 人), 招聘谨慎; 无 cohort, 无 grad pipeline; 实习偶发, 全职 junior 更偶发
- **非EU签证 (全职)**:
  - **Stability AI Ltd** 是英国 **Skilled Worker 持牌 sponsor** (Home Office register 确认), 理论可发 CoS; 但 2024 裁员 + 财务紧, **实际 new grad sponsor case 几乎零公开报告**
  - 全职 base 需 ≥ £38,700 (Skilled Worker 2024 新规); Stability ML Engineer base 应能达标但需 case-by-case
  - 与实习 (Student Visa) 不同, 全职稳定性低 (公司风险)
- **薪资范围 (base, gross/年)**:
  - **London ML Engineer entry-level** (估计): **£60-85K base** — 救火后预算谨慎, **低于 Cohere / DeepMind / Anthropic London 同级 30-40%**; Glassdoor 仅有 senior 样本 (£100-140K), 入门级**无公开数据点**
  - **Research Engineer / Scientist** (PhD): £80-110K base, 接近 Cohere 但低于 Anthropic; 顶尖 PhD 可议价
  - Equity: 救火后估值跌至 ~$1B, 早期 equity 已大幅缩水; 新 hire grant 较小
  - **警示**: 2024-04 裁员 10% 后, 薪资透明度更低; 主动 outreach 才能知道实际数字
- **申请窗口**: rolling 但**极度稀疏** — careers 页常年仅 5-15 岗, 偶有 1-2 个开放给 entry-level; 关注 LinkedIn 现员工 outreach 比官网申请更高效
- **面试流程差异 vs 实习**:
  - 流程相对短 (3-4 轮) — 公司体量小, Hiring Manager 直接决策权大
  - **Paper bar 高** (Research 岗): NeurIPS / ICCV / CVPR / SIGGRAPH 顶会论文是硬门槛; Diffusion / Flow Matching / Generative model 方向尤甚
  - **OSS 权重**: 在 CompVis / diffusers / Stable Diffusion fork 有 substantial PR 是巨大加分
  - Coding bar 低于 Cohere (不强调 LeetCode), 重 PyTorch 实战 + diffusion 内部机制
  - System design 偶尔出现 (大规模 inference / 推理优化方向)
- **录取竞争**:
  - bar 极高 (PhD + 论文 + 公司挑剔), 但**申请量也小** (公司动荡致候选人观望); 实际 net 难度可能低于 Cohere/DeepMind
  - **国际生**: 理论 OK 但实操不确定, sponsor 决心存疑
  - **风险溢价大**: 即使拿到 offer, 公司财务 + 留存 + 转正 + 长期签证 sponsor 都是问号; 应**优先 DeepMind/Cohere/Anthropic**, Stability 当备选
- **关键链接**:
  - 官方 careers 页: [stability.ai/careers](https://stability.ai/careers)
  - Built In London Stability AI: [builtinlondon.uk/company/stability-ai/jobs](https://builtinlondon.uk/company/stability-ai/jobs)
  - LinkedIn Stability AI Page: [linkedin.com/company/stability-ai](https://www.linkedin.com/company/stability-ai/)
  - r/MachineLearning Stability 讨论: [r/MachineLearning](https://www.reddit.com/r/MachineLearning/search/?q=stability+ai)
  - **公开 grad / junior 面经**: **零** — 中英文社区均无可考记录; 建议主动 LinkedIn outreach 现员工

---

## 2. 2024-2025 公司状态时间线

| 日期 | 事件 |
|---|---|
| 2024-03 | 创始人 / CEO Emad Mostaque 辞职 |
| 2024-04 | 裁员 10% (~20 人) |
| 2024-06 | Sean Parker 主导救火: $80M 注资 + $400M 债务豁免 |
| 2024-06 | 任命 co-CEO Shan Shan Wong + Christian Laforte (临时) |
| 2024-09 | 正式任命: Prem Akkaraju 为 CEO,James Cameron 加入董事会 |
| 2024-12 | 据报道债务清零、营收三位数增长 |
| 2025 | WPP (广告巨头) 战略投资;转向"AI for filmmaking / advertising" |
| 2026 | 获 Global Recognition Award |

## 3. 实习岗位与方向

> **重要**: Stability AI 官方 careers 页面公开岗位多,但**专门 Intern 入口很少**,大部分为正式 Engineer / Research 岗。建议主动邮件询问 + LinkedIn 触达。

| 岗位类别 | 状态 | 备注 |
|---|---|---|
| Research Intern (Generative Models) | **偶发** | Diffusion、Flow Matching、Video Models |
| ML Engineering Intern | **偶发** | 训练 infra、inference 优化 |
| SWE Intern | **稀少** | Backend、API、Platform |

## 4. 申请要求与签证

- **学历**: Research Intern 优先 PhD 在读 (Generative Models / Computer Vision / NLP);ML Engineering 接受硕士
- **硬条件**:
  - **Diffusion model 实现经验** (有自己跑过 Stable Diffusion 训练 / fine-tuning 强加分)
  - PyTorch + Diffusers / CompVis 代码库熟悉
  - CUDA / Triton 加分
  - 顶会论文 (NeurIPS / ICCV / CVPR / SIGGRAPH) 大幅加分
- **签证**: Stability AI Ltd 是英国本土公司,Skilled Worker sponsor 持牌;但实习生主要走 Student Visa
- **薪资**: 无公开数据;救火后预算谨慎,预估实习月薪 £3,500-£5,000

## 5. 面试流程 (估测,2024 前信号)

```
1. Recruiter / Hiring Manager 初谈 (兴趣 + 论文 + 项目)
2. 技术 / Coding 一轮 (PyTorch 实现 + ML 题)
3. Project Deep Dive (简历项目 + 提议研究方向)
4. Final + Behavioral
```

公司体量小 → 流程相对**快但人 / 资源稀缺**,Hiring Manager 直接决策权大。

## 6. 面经摘录

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|---|---|---|---|---|---|
| / | / | **信息匮乏** — 公开面经几乎零;无中英文有效面经 | / | / | 多源搜索均无 |

> **2024 大动荡 + 公司规模小,公开面经记录几乎为零**。建议查看 LinkedIn 现员工 outreach 直接问。

## 7. 文化与口碑 — **警示与希望并存**

### 警示
- **历史不稳定**: 创始人风格争议、资金紧张、裁员、leadership 大换血
- **Glassdoor 评分**: 2024 初一度跌至 2.5-3.0,负评集中在管理 / 战略
- **公司体量小** → 实习生影响力大,但 mentor 资源稀缺
- **路径不清晰**: 转正 + Skilled Worker sponsor 数据少,不确定

### 希望信号
- 2024-2025 救火后管理团队 + 资本到位,**新方向 (filmmaking / advertising AI) 清晰**
- James Cameron + Sean Parker 的 backing 大幅提升信用
- Stable Diffusion 品牌仍极强,CV/Generative model 简历加分巨大
- WPP 合作 → 商业化路径明确

## 8. 重点准备清单

### Research / ML Intern 方向
1. **Diffusion Model 理论**: DDPM、DDIM、SDE / Score-based、Classifier-Free Guidance
2. **必跑代码**:
   - 用 PyTorch / Diffusers 跑通 Stable Diffusion 推理
   - LoRA fine-tuning 跑一个个人 dataset
   - 实现 simple DDPM 训练循环
3. **进阶**: Flow Matching、Rectified Flow、Consistency Models
4. **Video / Audio**: Stable Video Diffusion、Stable Audio 代码库浏览
5. **System ML**: FlashAttention、xFormers、torch.compile、CUDA 优化

### 通用准备
1. PyTorch 内部机制 (autograd、torch.compile、custom op)
2. 至少一个 GitHub 公开 generative model 项目
3. 阅读 Stability 近期 blog / 论文 (Stable Diffusion 3、SD3.5、Stable Video Diffusion)

## 9. 总结评级

| 维度 | 评级 | 备注 |
|---|---|---|
| 信息丰富度 | 极低 (信息匮乏) | 面经空白,招聘 cohort 不固定 |
| 申请门槛 | 高 | Diffusion 实战 + 公司动荡谨慎招 |
| Offer 转化预期 | 低 | Intern 入口少 + 公司预算紧 |
| 推荐指数 | 谨慎推荐 | 对 Diffusion / Generative 方向 PhD 是好契机;否则 ROI 低 |

> **建议**:
> - 如果你的方向是 generative model / diffusion,Stability AI 仍是顶级品牌;主动 outreach (邮件 / LinkedIn) 比官网申请更高效
> - 接 offer 前关注公司财务健康度;CV 上的"Stability"价值仍非常高
> - 不建议把 Stability 列为唯一选项 → 同时申 Cohere / DeepMind / Mistral / Hugging Face 平衡风险

## 信息来源

- [Stability AI Careers](https://stability.ai/careers)
- [Stability AI Wikipedia](https://en.wikipedia.org/wiki/Stability_AI)
- [Stability AI Lays Off 10% - Crunchbase](https://news.crunchbase.com/ai/stability-ai-layoff/)
- [Stability AI Layoffs - UKTechNews](https://www.uktech.news/ai/stability-ai-layoffs-20240418)
- [Stability AI Decimates Staff - The Register](https://www.theregister.com/2024/04/18/stability_ai_layoff_staff/)
- [Stability AI CEO Departure - Sifted](https://sifted.eu/articles/stability-ai-layoffs-news)
- [James Cameron Joins Stability AI Board - Hollywood Reporter](https://www.hollywoodreporter.com/business/business-news/james-cameron-joins-board-ai-firm-stability-stable-diffusion-1236010034/)
- [Stability AI Built In London Jobs](https://builtinlondon.uk/company/stability-ai/jobs)
- [Stability AI Lightspeed Jobs](https://jobs.lsvp.com/jobs/stability-ai)
- [Stability AI 2026 Recognition Award](https://globalrecognitionawards.org/innovative-companies/stability-ai/)
- [Hollywood AI Adoption - Longreads](https://longreads.com/2025/08/21/hollywood-stability-ai/)
