# Confluent (London) Internship Intel

> **Language**: [中文](confluent.md) | English
>
> Updated: 2026-10-10
>
> Confluent is the commercial parent of Apache Kafka, founded by the original Kafka authors. European operations are centered in London, with a focus on distributed stream processing, the Kafka platform, and "Data in Motion" infrastructure. A top-tier brand for interns aiming at distributed systems.

## 1. Company Snapshot

| Item | Content |
|---|---|
| HQ / European core | Mountain View, USA / London (Europe) |
| European hiring sites | Primarily London, with some roles extending to Northern Ireland and Spain |
| Main business | Kafka commercialization, Confluent Cloud, Flink, Stream Governance |
| Tech stack | Java/Scala (Kafka core), Go, Kubernetes, AWS/GCP/Azure, Rust (new engine) |
| Internship length | 12-week summer or 12-month placement (FTC) |
| Application window | Opens autumn (Sep-Nov), rolling review |
| Internship / brand reputation | Strong engineering, Kafka core community, high distributed systems intensity |

## New Grad / Junior Roles

> Checked: 2026-10-10 (live WebSearch + WebFetch + ATS API) | Information richness: ⭐⭐⭐ (basis: SEC 8-K + acquisition / layoff reporting + Ashby job API + UK sponsor register + Levels.fyi direct read; missing: careers.confluent.io blocked (HTTP 429), no 2025-26 European new-grad interview reports)
> **2027 intake status**: **No programme / no open roles** — Confluent's own Ashby job board has 17 jobs on 2026-10-10, all in North America / India, none in Europe and none new grad / intern / junior [Source (verified opened): https://api.ashbyhq.com/posting-api/job-board/confluent]
> **2026 news (major)**: IBM completed the acquisition on 2026-03-17 ($31/share cash, EV ~$11B), CFLT delisted; after closing there were unofficial reports of cuts "as high as 800", with no official statement from IBM / Confluent [Source (verified opened): https://factorhouse.io/articles/what-the-ibm-confluent-acquisition-means-for-kafka-users/]; reported 2026-08-14: CEO Jay Kreps stepped back, CPO Shaun Clowes took over [Source (verified opened): https://www.sdxcentral.com/news/ibm-in-new-software-blow-as-confluent-ceo-exits/]

- **Role names**: previously recorded "Software Engineer, New Grad" / "Software Engineer I (L2)", no standalone graduate programme; no entry-level role open in 2026-10; whether Confluent has a separate graduate channel inside IBM: no public data
- **Eligibility**: no live postings to check; no public data
- **European locations**: London is the main EMEA engineering hub (previous record); no European role on the Ashby board in 2026-10 (same source); earlier Belfast / Madrid team info not verified this round
- **Programme structure**: no cohort-based grad scheme (previous record); start month / cohort size: no public data
- **Non-EU visa (full-time)**: UK: Confluent Europe Ltd holds **Skilled Worker + GBM Senior or Specialist Worker (A rating)** (gov.uk register, 2026-10-09 edition) [Source (verified opened): https://sponsorlist.co.uk/visa-sponsorship/confluent-europe-ltd/ , https://www.gov.uk/government/publications/register-of-licensed-sponsors-workers]; Skilled Worker general threshold **£41,700** or the going rate, whichever is higher [Source (verified opened): https://www.gov.uk/skilled-worker-visa/your-job] (previous: £38,700, 2026-05); new-entrant threshold **£33,400** / 70% of going rate, if under 26 at application or on a UK Student / Graduate visa within the last 2 years, etc. [Source (verified opened): https://www.gov.uk/skilled-worker-visa/when-you-can-be-paid-less] — someone coming from NL study / zoekjaar qualifies only via the under-26 rule, otherwise £41,700 applies; NL: no Confluent entity on the IND recognised-sponsor register [Source (verified opened): https://ind.nl/en/public-register-recognised-sponsors/public-register-regular-labour-and-highly-skilled-migrants]
- **Pay (TC, gross/yr)**: Levels.fyi UK L2 (entry) **£106K = £69.4K base + £34.3K stock + £2.3K bonus**, median £168K (2026-10) [Source (verified opened): https://www.levels.fyi/en-gb/companies/confluent/salaries/software-engineer/locations/united-kingdom] — data mostly submitted pre-acquisition (inferred); single Blind data point £70K base ≈ £120K TC [Source (search results): https://www.teamblind.com/post/confluent-london-salary-ty8nxfgh]
- **Equity**: the merger agreement (2025-12-07) converts unvested employee RSUs into IBM RSUs with unchanged vesting; options cash-settled at the $31 spread [Source (verified opened): https://www.sec.gov/Archives/edgar/data/1699838/000110465925119081/tm2532777d2_8k.htm] (previous: "CFLT (Nasdaq) RSU", now obsolete); equity form in new offers: no public data
- **Application window**: earlier "opens Aug-Oct each year" was unsourced; 2027 cycle: no postings, no announcement
- **Interview process vs internship**: previous record: Recruiter → OA → coding → concurrency → system design (Kafka-related) → HM, interns usually skip system design (see §4); whether the process changed under IBM: no public data
  > ⚠️ **Pending web verification**: unsourced earlier items, not verifiable this round — London new-grad acceptance ~2-3%, applicant pool 3,000-5,000, relocation ~£5K-£10K, Belfast / Madrid base, 4-week bootcamp, home office £400/month; do not use for pay / deadline decisions until re-checked.
- **Competition**: European entry-level hiring essentially paused in 2026 (basis: no open roles + layoff reports; inferred)
- **Key links**: Ashby job API (verified opened, above); Early Talent page https://careers.confluent.io/early-talent (returned HTTP 429 on 2026-10-10, could not open); Levels.fyi UK / UK register / SEC 8-K (verified opened, above)

---

## 2. Internship Roles and Directions

| Role Category | Main Teams | Tech Stack |
|---|---|---|
| Software Engineering Intern (12 weeks) | Confluent Cloud, Connect, Kafka Core, Schema Registry | Java, Go, Kubernetes |
| Software Engineer Intern - 12 month FTC | Stream Processing (Flink), Networking, Storage | Java, Scala, Rust |
| Site Reliability / Platform Intern | SRE, Observability | Go, Terraform, Prometheus |
| Security Intern | Security Engineering, SOC | Python, Go |

## 3. Application Requirements and Visa

- **Education**: Penultimate or second-year undergrad / master's in progress
- **Technical requirements**: Strong DSA fundamentals + at least one systems language (Java / Go / C++); distributed systems / networking / OS coursework is a plus
- **Visa**: Confluent UK Ltd is a Skilled Worker licensed sponsor; interns mainly use Student Visa work permissions (20h/wk during term, full-time during vacation); for non-Tier-4 students, 12-month FTC uses GAE/T5 temporary work visa
- **Salary**: London internship not publicly disclosed; industry comparable range is approximately £3,200-£3,800/month + housing allowance + round-trip flights reimbursed

## 4. Interview Process

```
Apply → Recruiter chat (15-30 min)
     → OA / coding test (HackerRank or CoderPad, LC Medium)
     → Tech round 1: Data structures + algorithms (45-60 min)
     → Tech round 2: Concurrency / systems programming (often tests thread-safe LRU, WindowedMap, atomic data structures)
     → Tech round 3 / final: System design (Kafka-related: stream ingestion, config propagation, expired email service, etc.)
     → Hiring Manager + behavioral
```

Note that Confluent's signature is: **very heavy on concurrency, parallelism, and memory model assessment**, not pure LeetCode patterns. Interns usually skip one round of system design.

## 5. Interview Experience Highlights

| Time | Role/City | Process Overview | Questions/Types | Result | Source |
|---|---|---|---|---|---|
| 2025-04 | SWE Intern / Austin (signals same as London) | OA + 1 tech round | LC Hard "Number of Atoms" | No offer / positive feedback | Jointaro |
| 2024 | SDE campus hire (general signals) | OA + 4-5 VO rounds | Function Signature Matcher (varargs method dispatch), LRU+TTL, Sudoku Solver | Offer | GeeksforGeeks |
| 2024 | Senior SWE | 5 rounds | WindowedMap (TTL key-value), concurrent thread-safe LRU, stream processing system design | Offer | LeetCode Discuss |
| 2025 | SSE first round (signals same as London) | First round | Stream-related SSE question, map iteration deadlock prevention | / | LeetCode Discuss |

> Public London internship interview experiences are scarce; US-region interview signals for the same role are consistent with London (same panel/same hiring bar).

## 6. Culture and Reputation

- **Positive**: Engineering rigor, Kafka founding team still present, working on real distributed infrastructure; mentor system is solid, internship projects lean production
- **Challenges**: Concurrency/atomicity assessment is brutal; internship projects may involve on-call shadow, requires high maturity
- **Glassdoor rating**: Overall ~3.8/5, good engineering culture reputation, but rumors of hiring cuts in last two years due to stock price fluctuations

## 7. Key Preparation Checklist

1. **Kafka basics**: Topics / Partitions / Consumer Groups / ISR / Exactly-Once Semantics — must be able to explain clearly
2. **Concurrent programming**: Java `synchronized` / `ReentrantLock` / `ConcurrentHashMap` internals; Go's channel + mutex
3. **LRU / LFU design**: Both single-threaded and thread-safe versions
4. **System design (Junior version)**: Rate limiter, simplified message queue, unique ID generator
5. **Behavioral questions**: "Why Confluent" — must have reasons, ideally having touched Kafka / Pulsar / Flink

## 8. Summary Rating

| Dimension | Rating | Notes |
|---|---|---|
| Information richness | Medium | Public interview experiences mainly US-region, less London-specific material |
| Application bar | High | Strong requirements in concurrency and distributed practice |
| Offer conversion expectation | Medium-low | Single panel difficulty high, but hiring bar consistent with FAANG |
| Recommendation index | Strongly recommended | Top choice for distributed systems track |

> **Recommendation**: Actively play with Kafka before applying (run producer/consumer + Connect locally via docker-compose), write a blog or GitHub project — significant boost during interviews.

## Sources

- [Confluent Early Talent](https://careers.confluent.io/early-talent)
- [Confluent SWE Intern Job](https://careers.confluent.io/job-description/7322e3ab-d31d-5ba3-8960-819a133854cf/)
- [12 month FTC Posting](https://uk.linkedin.com/jobs/view/software-engineer-intern-12-month-ftc-at-confluent-4368657879)
- [Jointaro Interview Experience](https://www.jointaro.com/interviews/companies/confluent/experiences/swe-intern-austin-tx-april-30-2025-no-offer-positive-5472a4fd/)
- [LeetCode Discuss - Confluent SSE](https://leetcode.com/discuss/interview-question/5494972/Confluent:-SSE-Interview-Q/)
- [GeeksforGeeks Interview Experience](https://www.geeksforgeeks.org/interview-experiences/confluent-interview-experience-for-sde-on-campus/)
- [TechPrep Interview Process Guide](https://www.techprep.app/blog/confluent-interview-process)
- [Glassdoor Confluent Interviews](https://www.glassdoor.com/Interview/Confluent-Software-Engineer-Interview-Questions-EI_IE1048428.0,9_KO10,27.htm)
- [Levels.fyi Confluent SWE UK 2026-05 verified read](https://www.levels.fyi/en-gb/companies/confluent/salaries/software-engineer/locations/united-kingdom)
- [Levels.fyi Confluent Greater London SWE median £192K](https://www.levels.fyi/companies/confluent/salaries/software-engineer/locations/london-metro-area)
- [Blind Confluent London salary post (£70K base + RSU)](https://www.teamblind.com/post/confluent-london-salary-ty8nxfgh)
- [Confluent UK Careers live entry](https://careers.confluent.io/search/jobs/in/country/united-kingdom)
- [Glassdoor Confluent London 13 open roles 2026-05](https://www.glassdoor.co.uk/Job/london-confluent-jobs-SRCH_IL.0,6_IC2671300_KO7,16.htm)
