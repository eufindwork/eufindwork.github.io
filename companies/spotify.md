# Spotify 实习情报（Stockholm / London / NYC）

> 范围：Backend Engineering Intern、Machine Learning Engineering Intern、Mobile (iOS / Android) Engineering Intern。重点关注 Stockholm（瑞典）与 London（英国）办公室，并对比 NYC。

---

## 1. 公司与招聘概况

| 维度 | 信息 |
| --- | --- |
| 总部 | Stockholm, Sweden（瑞典最具代表性的科技品牌） |
| 主要工程办公室 | Stockholm（核心 R&D）、London（产品/广告/工程）、NYC、Boston、Gothenburg |
| 业务核心 | 音乐 / 播客 / 有声书流媒体、推荐与个性化、广告平台、创作者工具 |
| 近期重大事件 | 2023 年 12 月宣布裁员约 17%（约 1,500 人），2024 全年继续 attrition-driven 减员；2024–2025 内部强调"产能优化 + AI 化"；2025 年实习项目在 HR Blog 公开重申"在转型与 AI 时代仍持续招聘实习生"|
| 实习项目名称 | Spotify Global Summer Internship Program |
| 时长 | 约 10 周（6 月初–8 月中），全职 |
| 申请窗口 | 通常前一年 10–12 月开放，1–2 月轮次结束；2025 招聘官博客确认 2026 summer 项目继续招聘 |
| 工作模式 | 大部分团队 Stockholm/London 都要求一定 on-site / hybrid，远程或跨境实习极少 |
| Visa 政策 | 官方写明**不为实习生 sponsor 工作签证**，因此非欧盟学生申请 Stockholm/London 需自行确保身份合法（瑞典 student residence permit 通常允许校外工作；英国 Student visa Tier 4 可工作 ≤20 小时/周学期内、假期全职） |

### 1.1 Stockholm vs London 区别

| 维度 | Stockholm（HQ） | London |
| --- | --- | --- |
| 团队侧重 | 推荐、Personalization、Audio Infra、Music Understanding、Platform、Mobile Core | Ads、Marketplace、Podcast、Audiobook、部分 Backend、Frontend |
| 工程文化 | "Squad / Tribe / Guild / Chapter" 模型最原汁原味的诞生地 | 较新办公室，团队偏产品/商业化 |
| 实习薪资（参考 Levels.fyi） | 2024 Stockholm SWE Intern 约 **USD 19.84/hr ≈ 3,439 USD/月**（约 SEK 35k 左右） | 2025 London SWE Intern 约 **USD 26.68/hr ≈ 4,625 USD/月**（约 £3,400–3,700/月） |
| 签证难度 | 非欧盟需 Sweden Migrationsverket 学生许可或实习/工作许可，Spotify 不发起 sponsor | 需 UK Student Visa 或 Graduate Visa，Spotify 同样不为实习 sponsor |
| 城市生活成本 | 高（瑞典物价 + 税），实习薪扣完税到手有限 | 极高（伦敦房租），Spotify 薪资稍微缓解 |

> NYC 对比：2025 NYC SWE Intern ≈ **USD 47/hr ≈ USD 8,147/月**，加每日 USD 15 餐补，是三个 hub 中最具竞争力的实习薪。

---

## 2. 岗位画像

### 2.1 Backend Engineer Intern
- 技术栈：Java / Scala / Python / Go，Backend services 多基于 GCP，事件流以 Kafka 为核心，存储混用 Cassandra / BigQuery / PostgreSQL。
- 典型项目：歌单 / 推荐 / 元数据 / 创作者后台微服务、广告投放后台、ETL 数据管道、内部平台工具。
- 关键能力：分布式系统基础、面向对象/函数式设计、Backstage（Spotify 开源的 dev portal）相关概念加分。

### 2.2 Machine Learning Engineer Intern
- 技术栈：Python、TensorFlow / PyTorch、Spark / Beam、Kubeflow、BigQuery、Vertex AI / 自研 ML Platform。
- 典型项目：推荐召回/排序、内容理解（音频 embedding）、Search、Ads CTR/CVR、播客发现、A/B 实验框架。
- 招聘官博客指出实习"刻意保留探索性"——具体项目随团队 needs 演化，强调端到端思维 + 快速学习 AI。

### 2.3 Mobile（iOS / Android）Engineer Intern
- 技术栈：iOS 主要 Swift（仍有少量 Objective-C），Android 主要 Kotlin（部分 Java legacy）；模块化 monorepo、Backstage 工程平台、Bazel/ Gradle 构建。
- 典型项目：客户端某个 feature surface（如歌单、Home Feed、Now Playing）、UI 设计系统组件、性能优化、A/B 框架接入。
- 关键能力：扎实的语言基础（runtime / memory / concurrency）、UI 架构（MVVM / MVI / TCA-like）、能在 IDE 中真实写代码并解释设计取舍。

---

## 3. 面试流程

### 3.1 通用步骤
1. **Recruiter Screen**（30 min）— 背景、动机、反馈文化、签证 / 起始时间。
2. **Technical Phone Screen**（60 min）— 2 名工程师，简历过往项目深挖 + 1 道 LeetCode Easy/Medium 编程题。
3. **Final Loop**（4 轮 × 60 min，通常一天/两天打包）：
   - Values（行为面，对 Spotify 价值观如 ownership / collaboration / adaptability 严苛评分）
   - Algorithms & Data Structures（白板/CoderPad 中等题）
   - System Design（实习常以 high-level 题为主，例如设计 Playlist 服务、Recommendation 数据流）
   - Case Study / IDE Interview（Mobile 实习有 IDE round：在 Android Studio / Xcode 真机式写代码并 share screen）
4. **Hiring Manager + Offer 讨论**

### 3.2 通用题型/题目（来自 Glassdoor / 1Point3Acres / LeetCode Discuss / 媒体博客）

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
| --- | --- | --- | --- | --- | --- |
| 2024 H1 | Backend Engineer II / Stockholm | Recruiter → Tech Screen → 4-round Final | Tech Screen：项目深挖 + 1 道 LC Easy；Final：算法（中等）、系统设计（设计内部 metadata service）、Values、Case Study | 部分 candidate 反馈"通过电面后被 ghost"，是 Spotify Stockholm 常见痛点 | rampatra.com 博客 + Glassdoor Stockholm |
| 2024 | Backend Engineer II / Stockholm | 3 轮：phone screening with HM、tech screen with 2 engineers、4-round final | 项目讨论 + LeetCode easy；Final 含 Values / Algo & DS / System Design / Case Study | 收到 offer | Glassdoor 评价 |
| 2024 | ML Engineer / 多地 | 5 阶段：Recruiter → Tech Phone Screen → 4–5 onsite → Hiring Manager → Offer | Round 1 偏 SWE（设计模式 + DS&A + 技术栈问答）；Round 2 偏 ML（Feature engineering、模型选择、Scalability）；含 SQL 处理百万级 listening events + Recommender System case study | 流程 2–4 周 | Prepfully / InterviewQuery / Interviewing.io |
| 2024 | Android Engineer / Stockholm | Recruiter → Tech screen（Java/Kotlin） → 4 个 1h on-site：Behavioral、System Design、DS&A、IDE | IDE round：现场 Android Studio 写一个 feature，包含网络 + UI 渲染；过程中持续被追问设计选择 | -- | Glassdoor / lifeatspotify.com |
| 2023 后期 / 2024 | iOS Design System Engineer / London | 类似 4 轮 final | 包含 IDE round：实现 design system 组件；System Design：设计可复用 UI 框架；Values | 拿到 offer | Medium "the codelog" |
| 2023–2024 | Spotify Backend / 远程电面 | 1 + 2 轮 | 视频面：行为 + 1 道 Algo；第二轮：项目深挖 + System design 简单题 | 信息匮乏（部分中文面经只描述到中段） | 1Point3Acres（被 forum 限制访问）|
| 2024 | System Design 题（实习/初级常考） | Onsite | "Design Spotify 推荐系统"、"Design Spotify 播放器后端"、"Design Ads 投放平台"，要求覆盖 Collaborative + Content-based Filtering、Feature Store、批 + 实时管道、A/B Test 框架 | 实习多以高层设计为主，不强求落地细节 | educative.io / designgurus.io / systemdesignhandbook.com |

> 备注：Spotify 行为面权重显著高于一般大厂，"Values" 直接是评分项；HR / HM 阶段会反复问"对反馈文化（feedback culture）的态度"。

---

## 4. 补偿与福利

| 项目 | Stockholm Intern | London Intern | NYC Intern（对照） |
| --- | --- | --- | --- |
| 月薪 | ≈ USD 3,439（2024 Levels.fyi 数据，约 SEK 35k）| ≈ USD 4,625（2025）| ≈ USD 8,147（2025）|
| 时薪 | ≈ USD 19.84 | ≈ USD 26.68 | USD 47.0 |
| 餐补 / 其他 | 无明确公开；按 Spotify HQ 福利通常含办公室餐食、健身、心理咨询、parental support 等 | 类似伦敦 office 福利 | 每个工作日 USD 15 餐补 |
| 住房 | 不提供 housing stipend；Stockholm 公寓极紧张（Bostadsförmedlingen 排队制），建议靠 Blocket、Qasa、Samtrygg 等短租 | 不提供 housing；London 月租 £1.5–2.5k 单间 | 不提供，但薪资较高可自费 |
| 是否 sponsor 签证 | 否 | 否 | 否（但 NYC J-1 较多通过学校 CPT/OPT 解决） |
| 转正概率 | 历史上较好，但 2023–2024 裁员后 headcount 紧，转正率明显下降；ML / Personalization 团队仍保留少量返聘名额 | 同上 | 同上 |

> 国家差异：瑞典实习收入要扣 ~30% 综合税，到手净额需自行计算；英国实习若 ≤6 个月通常按 PAYE 缴税。

---

## 5. 签证与跨境工作

- **瑞典 Stockholm**：
  - 非欧盟在读学生：若已持有 *uppehållstillstånd för studier*（学生居留许可），通常允许在学期内全职/兼职工作，无小时上限；做 internship 须确保签证仍在有效期。
  - 海外申请者：Spotify 明确不为实习生 sponsor 工作签证；需走 *Internship/Trainee permit* 或学生身份转 *Work permit*，由 Migrationsverket 审批，周期 1–3 个月，Spotify 不主动提供材料支持。
  - 全职毕业生：需 Work permit，月薪须达到 Sweden 工会集体协议下限（2024 后约 SEK 28,480/月起，且 Spotify 实际开价远高于此）。
- **英国 London**：
  - Student visa（Tier 4）：学期内 ≤20h/周，假期可全职，与 10 周暑期实习兼容。
  - 海外申请：Spotify 不发起 Skilled Worker Sponsor for interns；Graduate visa 可覆盖毕业后 2 年。
- **跨境/远程**：Spotify 推行 "Work From Anywhere"，但实习一般绑定特定 office，跨国远程极少且需要法务/税务批准。

---

## 6. 申请策略 & 时间线

| 阶段 | 时间（北半球暑期） | 备注 |
| --- | --- | --- |
| Job posting 上线 | 上年 10–11 月 | Stockholm / London 通常同步上线，NYC 略晚 |
| Online application + Resume screen | 11–12 月 | 强烈建议同时投 backend / mobile / ML，多个 req 可同时挂着 |
| Recruiter screen | 12 月 – 次年 1 月 | 邮件回复速度直接影响后续节奏 |
| Tech screen | 1–2 月 | 通常 CoderPad |
| Final loop | 1 月底 – 3 月初 | 集中 1–2 天，跨时区可远程视频 |
| Offer | 2–3 月 | 1–2 周决定窗口 |
| Onboarding | 6 月初 | 集体入职 + 全公司 intern 项目活动 |

申请技巧：
- 招聘官博客明确强调：注重"learning agility + AI fluency"；CV 上展示对 LLM / 推荐系统 / 数据管道相关项目至关重要。
- Spotify Values（passionate, collaborative, innovative, sincere, playful）应该在简历 + 面试故事里能映射到具体经历。
- 同年若申请多个团队，被一个 squad 拒后仍可通过别的 manager 重新进入流程（"team match" 系统）。
- 2024 起 internal "AI for Productivity" 倡议明显，ML / GenAI 相关实习需求增多，且对 AI tooling 经验加分明显。

---

## 7. 中文社区 & 英文社区情报

| 来源 | 关键点 |
| --- | --- |
| 1Point3Acres | 帖子稀少，且新帖普遍 403 / 需登录；历史帖（2018–2020）多为 Stockholm Backend / Data Engineer 电面（行为 + 1 道 LC）。**信息匮乏** |
| Glassdoor Stockholm | Spotify Stockholm interviews 评分 3.5/5，"通过 phone screen 后被 ghost" 是高频抱怨；流程长（4–6 周）。 |
| Reddit r/cscareerquestionsEU & r/sweden | 直接搜索几乎无结果；偶尔在 "best tech companies Sweden" 综述中提及 Spotify 实习含金量高、转正难。**信息匮乏** |
| Blind | 仅有少量 senior level 帖子，实习相关讨论极少。 |
| Medium / 个人博客 | iOS Design System London、Backend Engineer II Stockholm 经验贴较详细，是最佳免费来源。 |
| 牛客 / 知乎 | 国内候选人主要关注 Spotify NYC，Stockholm 几乎无国人帖；"知乎 + Spotify 实习"基本无内容。**信息匮乏** |

---

## 8. 关键风险 / 提示

1. **裁员阴影**：2023–2024 大裁员后，Stockholm 实习名额收缩，转正机会变少；优先看 Personalization / ML / Marketplace 这种被点名为战略方向的组。
2. **不 sponsor 签证**：海外申请者需提前确认身份能合法在瑞典 / 英国工作；招聘流程中 recruiter 会反复确认。
3. **行为面权重高**：Values 一旦评低，技术再强也会出局；提前准备 STAR-format 故事，覆盖 ownership / feedback / collaboration / adaptability。
4. **流程拖延**：被 phone screen 后 ghost 是 Stockholm 高频痛点，需要主动 follow up，每 1–2 周邮件 recruiter。
5. **Mobile IDE round 难度**：实习 IDE round 难度接近正式工程师，需要熟练 IDE 快捷键、能从零搭一个 mini Android / iOS app；和"白板算法"完全不同的考察方向。
6. **AI / GenAI 内化**：2025 HR Blog 重申实习项目向 AI 时代转型，简历对 LLM / Agent / Embedding / 向量检索的项目有显著加分。

---

## 参考链接

- [Spotify HR Blog: Internship Program in a Time of Transformation and AI](https://hrblog.spotify.com/2025/06/27/spotifys-internship-program-in-a-time-of-transformation-and-ai)
- [Life at Spotify – Students](https://www.lifeatspotify.com/students)
- [Life at Spotify – How We Hire](https://www.lifeatspotify.com/how-we-hire/interview)
- [Levels.fyi Spotify SWE Intern](https://www.levels.fyi/internships/Spotify/Software-Engineer-Intern/)
- [Glassdoor Spotify Backend Engineer Interviews](https://www.glassdoor.com/Interview/Spotify-Backend-Engineer-Interview-Questions-EI_IE408251.0,7_KO8,24.htm)
- [Prepfully Spotify ML Engineer Guide](https://prepfully.com/interview-guides/spotify-machine-learning-engineer)
- [InterviewQuery Spotify ML Engineer](https://www.interviewquery.com/interview-guides/spotify-machine-learning-engineer)
- [System Design Handbook: Spotify](https://www.systemdesignhandbook.com/guides/spotify-system-design-interview/)
- [rampatra blog: Spotify Backend II Stockholm](https://blog.rampatra.com/spotify-interview-backend-engineer-ii)
- [Medium: Getting an Internship at Spotify](https://medium.com/design-bootcamp/getting-an-internship-at-spotify-b2d6063a11a6)
- [Medium: iOS Design System Engineer at Spotify](https://medium.com/the-codelog/interviewing-for-an-ios-design-system-engineer-role-at-spotify-6727ecb5bfdc)
- [Piktalent: Sweden Student Visa](https://piktalent.com/countries/sweden/student-internship-visa/)
