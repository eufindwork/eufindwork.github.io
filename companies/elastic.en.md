# Elastic Internship Intel

> **Language**: [中文](elastic.md) | English
>

> Update: 2026-05-26
> Information richness: ⭐⭐ (full-time interview experience OK, internship-specific info scarce, campus hiring volume extremely small)
> Company background: Elastic N.V. (NYSE: ESTC), parent company of open-source Elasticsearch / Kibana, registered in Amsterdam, actual HQ distributed (HQ nominally Amsterdam, CEO in SF)

---

## 1. Basic Info

- **Full company name**: Elastic N.V. (HQ on paper: Amsterdam, Keizersgracht 5)
- **Amsterdam Office**: 5 Keizers Building, Keizersgracht (opened 2019, city center along canal)
- **Business**: Elasticsearch (search / vector database), Kibana (visualization), Beats / Logstash, Observability, Security (SIEM)
- **Core tech**: Java (Elasticsearch core), TypeScript/Node/React (Kibana), Go (some agents), Lucene low-level
- **Stock**: ESTC (NYSE), 2024 revenue ~$1.4B, customers include Netflix, Uber, Slack, Microsoft, Walmart
- **Company culture**: **"Distributed by default"** — 90%+ employees remote, no mandatory office, Amsterdam office is more of a hub than engineering main force
- **Internship/early talent programs**:
  - **No standardized "annual internship cohort"** (drastically different from Booking / Databricks / Adyen)
  - Internships exist on a **case-by-case open** basis, typically through thesis / school partnership
  - Occasionally "Intern" / "Working Student" / "Apprentice" job tags appear on jobs.elastic.co
- **Internship duration**: 5-6 months (master thesis project) is most common mode; occasionally 3-month summer

---

## New Grad / Junior Roles

> Information richness: ⭐⭐ (Elastic is distributed-by-default company, no "annual grad cohort", occasionally Junior / Working Student released case-by-case; public data extremely thin, Levels.fyi NL data mostly in C6+ senior, lacks entry-level)
> Distinct from internship: internships almost don't exist as fixed programs; **Junior / SWE I** full-time can remote hire but more inclined toward candidates with existing legal status (vs. sponsoring new candidates); 2026 NL Glassdoor shows "No Jobs at Elastic in Netherlands" — even Amsterdam HQ has almost no NL-tagged openings [Source (search result): https://www.glassdoor.com/Jobs/Elastic-Netherlands-Jobs-EI_IE751551.0,7_IL.8,19_IN178.htm]

- **Common role names**: **Software Engineer I** / **Software Engineer II** / **Associate Software Engineer** / occasionally **Working Student** (DE legal framework, not grad); **No "Graduate Programme"** branding (historically LinkedIn showed "Elastigrad" but already discontinued) [Source (search result): https://uk.linkedin.com/jobs/view/elastigrad-graduate-software-engineer-at-elastic-3153062925]
- **European locations**:
  - **Amsterdam (NL, Keizersgracht 5)**: nominal HQ, but 2026-05 Glassdoor actual test 0 NL-tagged openings [Source (search result): https://www.glassdoor.com/Jobs/Elastic-Netherlands-Jobs-EI_IE751551.0,7_IL.8,19_IN178.htm]
  - **London (UK)**: business + small amount engineering, most realistic EMEA in-person hub
  - **Berlin / Munich (DE)**: historically had Working Student slots (university in-school part-time), not true full-time grad; Elastic DE job entry jobs.elastic.co/jobs/country/germany real-time open
  - **Madrid / Barcelona (ES)**: remote priority, small amount SE I full-time
  - **Remote (EU-wide / "Distributed")**: Elastic majority employees remote, junior full-time theoretically any EU country, but **practice requires already having work right** [Source (verified opened): https://jobs.elastic.co/jobs/city/distributed]
- **Independent Graduate Programme**: **No** — Elastic is distributed-first company, culture opposes cohort-based grad scheme; no batch hiring nor structured rotation. All entry-level go through standard SWE hiring
- **Non-EU visa (full-time)**:
  - Elastic N.V. registered in Amsterdam, theoretically is IND Sponsor, but **actual sponsor frequency extremely low** — "distributed by default" culture makes company **more inclined to hire remote candidates with existing work right** rather than process Kennismigrant
  - For Chinese new grads **almost closes off EU channel**, only feasible path: (1) already have EU residence / EU degree (2) through Amsterdam HQ in-person full-time (very few slots)
  - **UK Skilled Worker**: Elastic UK is licensed sponsor, but entry-level role SOC code salary threshold £38,700 usually not met (Elastic UK Junior generally £40-50K base, borderline)
  - **30% ruling (NL 2026)**: SE I starting salary needs to reach **€4,357/month <30 years = €52.3K/year** Kennismigrant threshold, Elastic NL Junior actual €60K-€75K estimate **meets**, but barely usable due to too few NL-based offers [Source (verified opened): https://www.jobbatical.com/blog/netherlands-highly-skilled-migrant-salary-thresholds-2026]
- **Salary range (base, gross/year, 2026-05 Levels.fyi NL data)**:
  - **Greater Amsterdam Area C6 (mid)**: **€120K-€212K total range, median €158K** (NL all-level median, skewed senior) [Source (verified opened): https://www.levels.fyi/companies/elastic/salaries/software-engineer/locations/greater-amsterdam-area]
  - **NL all-level**: **€123K-€176K** range [Source (search result): https://www.levels.fyi/companies/elastic/salaries/software-engineer/locations/netherlands]
  - **Amsterdam SE I (entry)**: public data extremely few, estimated by Amsterdam 2026 entry-level baseline **€60K-€75K base** + RSU [Source (search result): https://whatisthesalary.com/it-salaries/software-engineer-salary-amsterdam/]
  - **London SE I**: **£60K-£75K base** + RSU
  - **Berlin SE I**: **€60K-€75K base** + RSU
  - **US all-level Elastic SWE range**: $74.5K - $98.3K (median lower-end) [Source (search result): https://www.levels.fyi/companies/elastic/salaries/software-engineer]
  - **Equity**: ESTC (NYSE) RSU, 4-year vest (25-25-25-25, Y1 quarterly, Y2+ semi-annual); Junior usually $20K-$40K initial grant
- **Application window**: completely rolling, through jobs.elastic.co rolling open; no fall batch; watch Career portal "Software Engineer" + filter "Junior" / "I" / "Associate"; average hiring cycle 32 days [Source (search result): https://www.glassdoor.com/Interview/Elastic-Interview-Questions-E1166989.htm]
- **Interview process differences vs internship**:
  - Elastic has no standard "internship process", so can't directly compare; **Junior full-time process** almost same as Senior, just onsite cut from 5 rounds to 3-4 rounds
  - Process: Recruiter (45 min) → Tech Screen (1h) → 3 rounds Virtual Onsite (coding + occasional lite system design + behavioral); all video, distributed-first culture
  - **Domain knowledge testing important** — Elasticsearch / Lucene / inverted index / distributed raft / Kubernetes basics sometimes directly appear in Tech Screen, different from FAANG pure LeetCode mode
- **Selection competition**: Junior slots themselves extremely few (company doesn't actively hire entry-level), so **competition more like lottery** — every year EU-wide may only have 5-15 SE I spots open, application pool 1,000+, accept rate hard to estimate but actually < 1%; low international student friendliness (mainly for EU citizens / settled candidates with existing work right)
- **Key links**:
  - Elastic global Career entry: https://jobs.elastic.co/
  - Elastic NL job entry (2026 almost empty): https://jobs.elastic.co/jobs/country/netherlands
  - Elastic DE job entry (Working Student common): https://jobs.elastic.co/jobs/country/germany
  - Elastic Distributed (remote) jobs: https://jobs.elastic.co/jobs/city/distributed
  - Levels.fyi Elastic SWE Greater Amsterdam (2026-05 actually read C6 €120K-€212K): https://www.levels.fyi/companies/elastic/salaries/software-engineer/locations/greater-amsterdam-area
  - Glassdoor interview experience (closest to Junior entry-level): https://www.glassdoor.com/Interview/Elastic-Interview-Questions-E1166989.htm
  - Engineering blog (must read before interview, understand tech stack): https://www.elastic.co/blog/category/engineering

---

## 2. Visa & International Student Policy

- Elastic registered in Netherlands, but actual engineering team **globally distributed, doesn't concentrate on hiring NL local**
- **NL-based intern extremely few**: most internships / early roles happen in US / UK / India / Eastern Europe
- For NL Amsterdam intern, Elastic officially hasn't clearly published visa sponsor policy; because "distributed by default", company **more inclined to remote hire candidates with existing legal status** rather than process visas
- **Feasible paths**:
  - Non-EU students already in NL/EU institution → apply with study residence + Nuffic agreement
  - EU citizens → direct apply
  - Non-EU + non-EU institution → **basically can't go NL intern path**, suggest looking at other countries (US, India)
- **Full-time 30% ruling**: Amsterdam-based full-time conversion meets threshold applicable

---

## 3. Interview Process

Elastic has no public "internship-specific process"; below based on its **SWE full-time process** description, internship version usually has **1-2 fewer rounds**.

### Standard Process (4-5 weeks, 4-5 rounds)
1. **Recruiter Call** (30-45 minutes)
   - Experience + motivation + remote work adaptability + Elastic business (search/observability/security must do homework)
2. **Technical Screening** (1 hour, video, screen-sharing)
   - Algorithm + data structure + occasional live coding (LeetCode medium range)
   - Occasional domain questions: Elasticsearch / Lucene / inverted index / distributed / Kubernetes
3. **2-3 rounds technical onsite** (virtual, due to distributed culture)
   - **Coding**: live coding, usually 1-2 medium questions, emphasizes readability and testing thinking
   - **System Design** (senior mandatory, intern occasional): design search system / log aggregation / distributed queue
   - **Domain Deep Dive**: Elasticsearch internals (cluster, shard, segment, query DSL), Lucene basics, distributed consensus
4. **Hiring Manager Round** (45 minutes)
   - Project deep-dive + team fit + work style (remote collaboration ability is key)
5. **Senior Leadership Round** (occasional, more for senior)
   - Engineering Director / VP, culture + long-term goals

### Elastic Culture Keywords
- **"Source Code"** (Elastic's internal values collection, including: As One, Hungry & Humble, Be the Change, etc.)
- "Be passionate"
- Remote collaboration + cross-timezone communication + Slack / GitHub documentation culture

### Overall Difficulty
- Glassdoor difficulty: 2.89/5 (medium), lower than Booking / Databricks
- Hiring cycle: average 32 days (Glassdoor)
- Comprehensive positive review 54-60%

---

## 4. Real Interview Experiences

| Time | Role/City | Process | Question Types | Result | Source |
|------|----------|---------|----------|------|------|
| — | SWE (general) | Recruiter → Tech screen → Onsite (3 rounds) | LeetCode medium + Lucene/Elasticsearch concepts | — | [Glassdoor](https://www.glassdoor.com/Interview/Elastic-Software-Engineer-Interview-Questions-EI_IE751551.0,7_KO8,25.htm) |
| — | SWE comprehensive | Multiple technical + system design + behavioral | algorithms, data structures, system design; occasional K8s / distributed | — | [InterviewQuery](https://www.interviewquery.com/interview-guides/elastic-software-engineer) |
| Early blog | SWE (Duy Do) | Recruiter + multiple technical | Comprehensive algorithms + system design + Elastic-specific | — | [Medium Duy Do](https://medium.com/@duy.do/interview-at-elastic-e1081af8a0f6) |
| — | Internal sharing | — | "Be passionate, problem-solving willing to learn, mutual discovery" | — | [Elastic Official Blog](https://www.elastic.co/blog/tips-for-interviewing-at-elastic) |

**Amsterdam-specific intern interview experience**: **Information scarce** — 1point3acres / Reddit / Blind can't find specific interview experiences for Amsterdam intern

### Question Type Samples (Based on Full-Time SWE Comprehensive)
- **Algorithms**: arrays, strings, trees, graphs; occasionally trie (due to search engine background)
- **System design**:
  - Design a simplified Elasticsearch (inverted index + sharding + replication)
  - Log aggregation system (similar to ELK stack)
  - Full-text search + autocomplete
  - Distributed rate limiter
- **Domain questions** (Elastic specialty):
  - "Explain how Elasticsearch handles a search query end-to-end"
  - "What is a segment, refresh, flush, commit?"
  - "How does Lucene's inverted index work?"
  - "Discuss tradeoffs between sync / async replication in distributed search"
- **K8s / Cloud**: deployment, service mesh, observability stack
- **Behavioral interview**: emphasize distributed work, async communication, ownership

---

## 5. Offer Cases / Stipend

| City | Stipend | Notes | Time | Source |
|------|------|------|------|------|
| Amsterdam | — (no public data) | Intern data points almost zero | — | — |
| US (intern, general) | ~$26/hour (~$4,500/month) | North America data, reference only | 2024 | [Indeed (similar companies)](https://www.indeed.com/cmp/Elastic/salaries/Intern) |
| Amsterdam (full-time SWE converted) | Estimate €70-€100K base + RSU | Remote roles commonly use SF base adjustment | 2024 | [TechPays / Levels.fyi](https://www.glassdoor.com/Salary/Elastic-Amsterdam-Netherlands-Salaries-EI_IE751551.0,7_IL.8,29_IP2.htm) |

### Key Notes
- **Information scarce**: Elastic internship stipend in Amsterdam **has no reliable public data point**
- Company remote culture makes base less tied to specific cities, usually uses location-adjusted comp band
- Full-time remote SWE conversion treatment competitive (NYSE-listed, RSU substantial)

---

## 6. Application Channels & Tips

- **Official hiring main page**: https://www.elastic.co/careers
- **Full jobs portal**: https://jobs.elastic.co/
- **NL jobs**: https://jobs.elastic.co/jobs/country/netherlands
- **Amsterdam city filter**: https://jobs.elastic.co/jobs/city/amsterdam
- **Interview tips (official)**: https://www.elastic.co/blog/tips-for-interviewing-at-elastic

### Recommended Strategy
1. **Don't wait for "intern cohort"**: regularly (weekly) check if jobs.elastic.co has intern / working student roles
2. **Open-source contribution is strongest signal**: Elasticsearch / Kibana / Beats all active on GitHub, submitting a small PR (even typo or doc) to elastic/elasticsearch is extremely strong "I know you" signal
3. **Highlight remote collaboration experience**: cover letter should show async communication ability (open source, cross-timezone projects, strong documentation style)
4. **Elasticsearch / Lucene basics**: even shallow, at least understand inverted index, query DSL, sharding concepts
5. **K8s / Docker / Cloud-native** experience almost prereq at Elastic
6. **EuroPython / FOSDEM / KubeCon etc. conferences**: Elastic often sponsors and has booth, on-site talk + drinks getting referral more effective than mass apply

---

## 7. Pitfalls & Community Reviews

### Watch Points
- **Amsterdam intern slots almost don't exist**: Amsterdam office more like EU corporate registration, engineering team distributed globally
- **Remote culture "double-edged"**: intern remote may have insufficient mentorship; Elastic itself admits remote onboarding is challenging for junior
- **Not traditional campus hiring company**: doesn't have university recruiting team / campus fair / summer cohort like Databricks / Booking
- **2023-2024 layoff**: Elastic also experienced reorg, intern hiring budget affected
- **Visa sponsor not active**: distributed-first company inclined to "find legal candidates" rather than process visas
- **Chinese community info almost zero**: 1point3acres / Nowcoder / Zhihu Elastic interview experiences almost can't be found, equivalent volume Booking / Adyen info volume far more

### Pros
- **Remote friendly**: if you get offer, work location freedom high (NL residence, cross-Europe cross-continent team)
- **Open source + tech depth**: Elasticsearch / Lucene is world-top open source search infrastructure, resume endorsement strong (subsequent jumps to Confluent / Snowflake / Mongo all sweet)
- **work-life balance**: distributed culture + European labor law protection, stronger than FAANG-style
- **mission-driven**: open source + observability still infrastructure core in AI era

### Pros and Cons
- (+) Top tech depth, world-top open source influence
- (+) Remote flexibility
- (-) Internship pipeline almost doesn't exist, campus hiring volume too small
- (-) Amsterdam local intern probability extremely low
- (-) Information sources sparse, can't find veterans for guidance

---

## 8. Key Links Summary

- Official hiring main page: https://www.elastic.co/careers
- All jobs portal: https://jobs.elastic.co/
- NL jobs: https://jobs.elastic.co/jobs/country/netherlands
- Amsterdam city filter: https://jobs.elastic.co/jobs/city/amsterdam
- Interview tips (official): https://www.elastic.co/blog/tips-for-interviewing-at-elastic
- Amsterdam Office opening blog: https://www.elastic.co/blog/growing-at-the-roots-welcoming-the-new-elastic-amsterdam-office
- Glassdoor interview experience: https://www.glassdoor.com/Interview/Elastic-Software-Engineer-Interview-Questions-EI_IE751551.0,7_KO8,25.htm
- InterviewQuery process guide: https://www.interviewquery.com/interview-guides/elastic-software-engineer
- Distributed culture review: https://www.indexventures.com/perspectives/a-look-inside-elastics-distributed-people-first-culture/
- HelloInterview Elasticsearch system design deep-dive: https://www.hellointerview.com/learn/system-design/deep-dives/elasticsearch
- Open source core code: https://github.com/elastic/elasticsearch
- Levels.fyi Elastic SWE Greater Amsterdam (2026-05 actually read): https://www.levels.fyi/companies/elastic/salaries/software-engineer/locations/greater-amsterdam-area
- Levels.fyi Elastic SWE Netherlands range: https://www.levels.fyi/companies/elastic/salaries/software-engineer/locations/netherlands
- Elastic Distributed (remote) job entry: https://jobs.elastic.co/jobs/city/distributed
- Elastic DE country entry (Working Student): https://jobs.elastic.co/jobs/country/germany
- NL 2026 Kennismigrant threshold: https://www.jobbatical.com/blog/netherlands-highly-skilled-migrant-salary-thresholds-2026
