# Booking.com 实习情报

> 更新时间: 2026-05-26
> 信息丰富度: ⭐⭐⭐⭐⭐ (面经丰富, 公开信息透明度高)
> 公司背景: 全球最大 OTA (在线旅游平台), 母公司 Booking Holdings (Nasdaq: BKNG), HQ 位于阿姆斯特丹 Oosterdokseiland (中央车站旁)

---

## 1. 基本信息

- **公司全称**: Booking.com B.V. (Booking Holdings 旗下)
- **HQ**: Amsterdam, Netherlands (Oosterdokseiland 园区, 中央火车站旁)
- **其他工程办公室**: Manchester (UK), Shanghai (中国), Bengaluru, Tel Aviv
- **业务**: OTA / 酒店预订平台, 内部 ML/Personalization/Search/Pricing/Payments 团队庞大
- **股票**: BKNG (Nasdaq, 母公司 Booking Holdings); 2024 年净利润 ≈ $5.9B
- **实习岗位** (Compass 内部框架统一管理):
  - **Software Engineering Internship** (Amsterdam, 9 周)
  - **Machine Learning Internship / PhD ML Research Intern**
  - Data Engineer / Data Science Intern
  - Product / Business Analyst Intern
  - 同框架下还有 Compass Graduate Programme (毕业生项目)
- **实习时长**: SWE 实习 **9 周** (夏季); ML Research / PhD intern 通常 **3–6 个月**
- **申请时间窗**: 通常前一年秋 (9–11 月) 开放, 次年 1–3 月截止; 2026 年的 SWE 实习页面显示 "Applications closed", 需关注 2027 cohort 开放

---

## 2. 签证与国际学生政策

- **关键限制**: 2025/2026 的 Amsterdam SWE Internship **明确要求 "enrolled in a Dutch University" + "right to work in EEA"**
  - 这意味着非 EU 学生若已经在荷兰院校读 Bachelor/Master 且持有学习居留, 通常可以申请 (学习居留自带每年 16 小时/周 + 暑期全职打工权)
  - 不在荷兰院校的非 EU 学生 (例如 UK/德国/中国学校) **基本无法走 9 周暑期 SWE 实习路径**
- **替代路径**: PhD/Research Intern 通常更愿意走 GVVA (combined permit residence+work) 或 Nuffic 协议; 项目时长 3–6 个月时 IND 流程值得办
- **Recognised sponsor 状态**: Booking.com 是荷兰 IND 注册的**重点 sponsor 之一**, 处理 HSM/Kennismigrant 经验丰富, 全职转正走 Highly Skilled Migrant 路径
- **30% ruling**: 实习生**不适用**; 全职转正后视工资门槛而定 (2024 年规则被收紧, 5 年期降至 5 年但比例下调)
- **搬迁福利**: 2025 实习生官方提供单程机票 + 30 天 managed apartment, 之后自行找房

---

## 3. 面试流程

Booking.com 实习面试以 **HackerRank OA + 行为/案例 + 技术 + 文化** 为主线, 比同梯队公司更重视 **case study / A/B testing 思维**。

### SWE Internship (9-week, Amsterdam)
1. **CV 筛选** (转化率 < 10%)
2. **HackerRank OA**
   - 90 分钟 / 3–5 题 (主流报告是 4 题, 75–90 分钟)
   - 题型: LeetCode easy/medium + 偶有 SQL + 多选 (CS 基础)
   - **极强的"商业领域题"特征** — 题目背景多为 hotel review / hotel ID / booking data
   - 不只是 pass test cases, **time/space 复杂度也算分**
3. **Recruiter Call** (英语, 30 分钟, 动机/经历/期望)
4. **Hiring Manager / 技术 1v1** (45–60 分钟, pair programming on collaborative IDE, 数组 / hashmap 基础题)
5. **Assessment Day (2025 起合并)** — Zoom/Teams, 半天内连续进行:
   - 1× 技术 coding (medium LeetCode 难度)
   - 1× **Case Study / Business Case** (Booking 特色, 详见下方)
   - 1× **Culture fit / 行为面** (围绕 Booking values: "Learn Forever", "Own It", "Succeed Together" 等)

### ML Internship / ML Scientist 流程
1. HackerRank: 1 题 coding + 9 题 ML 多选 (概率/统计/经典模型)
2. Recruiter screen
3. Coding interview (Python, LeetCode graphs/trees)
4. System Design / ML System (推荐 / ranking 系统设计)
5. Case study (常见题: "How to identify good hotel deals?", 重点考 A/B testing 与 metric design)
6. HR 文化面

### Booking 特色: Case Study
- 部分流程会要求 **48 小时内准备一个 case 演讲**, 然后向多人评委 presentation
- Case 常涉及: pricing experiment, ranking algorithm trade-off, fraud detection metric, conversion funnel
- **A/B testing 几乎必考**: control vs treatment, statistical significance, sample size, novelty effect, network effect

### 接受率
- 公开报道实习接受率 **< 8%**, 实习生申请池每年数千份

---

## 4. 真实面经

| 时间 | 岗位/城市 | 流程概述 | 题目/题型 | 结果 | 来源 |
|------|----------|---------|----------|------|------|
| 2024-09 | ML Scientist / Amsterdam | Recruiter → 技术 case study | "How to identify good hotel deals?" 重点 A/B testing; 抱怨 interviewer 不在目标 team | No Offer (Neutral) | [JoinTaro](https://www.jointaro.com/interviews/companies/bookingcom/experiences/machine-learning-scientist-amsterdam-september-22-2024-no-offer-neutral-bf4e128b/) |
| 2022 | SDE-2 / Amsterdam | OA (90 min, sort+traverse) → 多轮技术 + 行为 | 排序遍历数组, 系统设计欺诈交易检测 | Offer | [LeetCode Discuss](https://leetcode.com/discuss/interview-experience/2086386/bookingcom-sde-2-amsterdam-2022-offer/) |
| 2022-02 | Backend Engineer / Amsterdam | HackerRank (3 题 / 90 min) → onsite 多轮 | Graph: 最近 K hotels; System design: fraud credit card booking | — | [LeetCode Discuss](https://leetcode.com/discuss/interview-experience/1810773/bookingcom-interview-experience-amsterdam-backend-engineer-february-2022/) |
| 2021-07 | Backend Dev / Amsterdam | HackerRank → 1st tech → onsite | Top K hotels by positive/negative review words | Offer | [LeetCode Discuss](https://leetcode.com/discuss/interview-experience/1395715/bookingcom-backend-developer-amsterdam-july-2021-offer/) |
| 2021-05 | OA | HackerRank | Hotel reviews positive/negative words 题 | — | [LeetCode Discuss](https://leetcode.com/discuss/interview-question/1245302/bookingcom-hacker-rank-test-may-2021/) |
| 多次报告 | OA | HackerRank | "Sort hotels by avg score (hotelId reviewScore 每行)" | — | [Glassdoor](https://www.glassdoor.com/Interview/HackerRank-Sort-hotels-by-average-score-Each-line-of-input-had-the-hotel-ID-and-a-review-score-E-g-1000-4-1000-QTN_2837477.htm) |
| 多次报告 | OA | HackerRank | "Award Top K Hotels": positive words +3, negative -1, 输出 top K | — | [LeetCode Discuss](https://leetcode.com/discuss/interview-question/1431676/Booking.com-Award-Top-K-Hotels-OA-HackerRank) |

### OA 高频题目模式
- **Hotel Reviews + Sorting**: 给定正/负面关键词列表和酒店评论, 按命中数排序输出 top K
- **Hotel Sort by avg score**: 多行 `hotelId score` 输入, 按平均分排序, 同分按 ID
- **String rotation / GCD / LCM / set intersection** (CS 基础题)
- **API/REST 实现题**: 给 GitHub repo + 要求实现指定 endpoint (常见于 senior, 实习偶尔出现)

---

## 5. Offer 案例

| 城市 | Stipend (gross/月) | Team | 时间 | 来源 |
|------|------|------|------|------|
| Amsterdam | **€2,500–€3,000** (普遍报告区间, SWE intern) | Various | 2024–2025 | [getsmartresume / Glassdoor](https://www.getsmartresume.com/article/booking-com-internship-program) |
| Amsterdam | 平均 **€16,500/年** (Glassdoor 多个数据点, 9 周项目按比例) | — | 2024 | [Glassdoor](https://www.glassdoor.com/Salary/Booking-com-Intern-Amsterdam-Salaries-EJI_IE256653.0,11_IC3064478.htm) |
| Amsterdam (Compass SE Grad) | 全职 €60–70K base 起 (转正参考) | SE | 2024–2025 | [TechPays](https://techpays.com/europe/netherlands/booking-com/amsterdam) |

### 关键备注
- Booking 实习官方不公开具体 stipend; 第三方报告区间 **€2,000–€3,000/月 gross**, 是 Amsterdam 实习市场偏上水平
- 9 周项目 + 单程机票 + 30 天住宿安排, 综合包对欧洲在校生很有竞争力
- 实习接收 return offer 的比例较高 (无公开数字, 但 Compass 框架设计意图就是 pipeline 到 Compass Graduate Programme)

---

## 6. 申请渠道与建议

- **官网**: https://careers.booking.com/early-careers/
- **Compass 项目页**: https://careers.booking.com/booking-com-compass-internship/
- **联系邮箱**: graduates@booking.com (官方早期人才邮箱)
- **校招活动**: TU Delft, UvA, VU Amsterdam, Erasmus Rotterdam, Eindhoven (TU/e) 几乎都有校园宣讲
- **推荐策略**:
  1. 提前 6 个月 准备 STAR 故事, 围绕 Booking values 准备 6–8 个核心故事
  2. **必须熟练 A/B testing**: power, significance, MDE, novelty effect, network effect, peeking
  3. LeetCode 刷 **Booking 公司 tag** (graph / hashmap / sorting), 重点关注 "Top K Hotels" 这类问题
  4. 业务背景熟悉度加分: 自己读一遍 Booking 工程博客 (booking.ai)
  5. 拿到 OA 后**全力优化**, 不要满足于 pass test cases

---

## 7. 踩坑与社区评价

### 警惕点 (来自 2023–2025 社区反馈)
- **2024 年裁员**: Booking Holdings 宣布全球裁 200–1000 人 (close to 1000), 母公司利润仍创新高 (净利 $5.9B 2024) 但运营开支增长过快, **部分申请者反馈被告知"由于内部变动无法继续"**
- **Case study 主观性强**: 多个 Glassdoor 报告 case study 评分依赖面试官个人偏好, 同样答案不同结果
- **HackerRank time pressure**: 4 题 / 15 分钟一题, 抱怨"读题/读 stdin 比写算法更花时间"
- **A/B testing 必考**: ML/DS 候选人若忽略 statistics 复习几乎稳挂

### 优点
- 项目 quality 高, mentorship 制度成熟, 9 周内有真实 production 任务
- Amsterdam 园区位置好 (Oosterdokseiland), 食堂/福利/远程工作政策友好
- Compass 框架对 intern→grad→junior→senior 路径设计明确

### 利与弊
- (+) 大流量平台 + tech 投入大 + ML/personalization 团队世界级
- (+) 荷兰 visa sponsor 经验丰富, 是 senior 转正最稳的 NL 大厂之一
- (-) 业务高度集中 OTA, 不及 FAANG 多元
- (-) 2024 裁员让部分组招聘 freeze, intern → return offer 比率被压

---

## 8. 关键链接汇总

- 官方早期职业页: https://careers.booking.com/early-careers/
- Compass Internship: https://careers.booking.com/booking-com-compass-internship/
- Compass SE Grad Amsterdam: https://careers.booking.com/booking-com-compass-se/
- 工程博客: https://booking.ai
- LeetCode 公司讨论: https://leetcode.com/discuss/interview-experience/?currentPage=1&orderBy=hot&query=booking.com
- Glassdoor 面经: https://www.glassdoor.com/Interview/Booking-com-Amsterdam-Interview-Questions-EI_IE256653.0,11_IL.12,21_IM1112.htm
- 1point3acres tag: https://www.1point3acres.com/bbs/tag/booking-1427-1.html
- JoinTaro 实习经验集: https://www.jointaro.com/interviews/companies/bookingcom/
- 2024 裁员: https://siliconcanals.com/booking-com-plans-job-cuts/
