# Cohere (London) Internship Intelligence

> **Language**: [中文](cohere.md) | English
>
> Updated: 2026-10-10
>
> Cohere is a Canadian enterprise-grade LLM company, founder Aidan Gomez is one of the Transformer paper authors. **London is one of the core European offices**, mainly handling research + enterprise sales. 2024-2025 company revenue tripled, completed Paris office expansion (40 people). **ML/AI Intern interview bar extremely high, Research Intern requires PhD in progress + top venue papers**; non-PhD candidates may also enter via Engineering Intern channel, but still need solid ML engineering experience.

## 1. Company Snapshot

| Item | Content |
|---|---|
| HQ | Toronto + San Francisco (main) |
| European offices | London + Paris (Paris as European hub, 40 people) |
| Valuation | ~$5.5B (2024 Series D) |
| Main business | Enterprise-grade LLM (Command series), Embed, Rerank, Aya multilingual research |
| Tech stack | Python, PyTorch / JAX, Triton, MLIR, Megatron / DeepSpeed |
| Internship duration | 4-8 months (Co-op mode) or 12 weeks Summer |
| Application window | Rolling open; Summer cohort 1-2 month; Fall cohort 5-7 month |
| Visual signal | Top LLM employer, same tier as OpenAI / Anthropic |

## New Grad / Junior Roles

> Checked: 2026-10-10 (live WebFetch + Ashby API; this session's WebSearch quota was exhausted) | Information density: ⭐⭐⭐⭐ (basis: Levels.fyi London read directly on 2026-10-10, 57 samples + official newsroom + full Ashby posting list)
> **2027 intake status**: **No programme (new grad); Cohere Labs Scholars = Upcoming** — no new grad / junior title, newcomers go through the MTS track; Scholars Program currently closed: "We are currently evolving the Research Scholars program. Applications are expected to open in Fall 2026" (not yet open on 2026-10-10) [Source (verified opened): https://cohere.com/research/scholars-program]
> **2026 H2 news**: 2026-09-16 definitive business combination agreement with Aleph Alpha — dual HQ Berlin + Toronto, Heidelberg kept as a research centre, >1,000 people combined, subject to regulatory approval, expected to close this year [Source (verified opened): https://cohere.com/blog/cohere-and-aleph-alpha-sign-agreement]; 2026-10-05 PwC partnership, 2026-08-06 University of Waterloo talent partnership (Canada) [Source (verified opened): https://cohere.com/newsroom]; (H1 context) 2026-06-15 new London office at 100 New Oxford Street, 14,000+ sq ft, up to 100 people, growing AI engineering / applied ML / infrastructure / customer deployment [Source (verified opened): https://cohere.com/blog/cohere-triples-uk-footprint-with-new-london-office-to-support-r-and-d-growth]

- **Role names**: Member of Technical Staff (Modeling / Post-Training / Pre-Training Data / Multilingual / Agent Code / RL Environments / Training Infra etc.), Software Engineer, Integrations, Forward Deployed Engineer (Europe / UK Public Sector / France); on 2026-10-10 Ashby has 119 postings, 46 include a European location (London 30 / Paris 16 / "Europe" 13 / UK 11 / Berlin 5 / Munich 3 / Brussels 2 etc.), 0 new grad / junior titles (full Ashby API parse via curl: https://api.ashbyhq.com/posting-api/job-board/cohere)
- **Eligibility**: most MTS JDs state no years requirement (MTS Multilingual requires a PhD or equivalent experience); public-sector roles need UK security clearance or French citizenship (France TPM / CSM); some UK sales roles say "Existing right to work in the UK"; language: France public-sector roles require French, engineering roles English only
- **European locations**: London (core research + engineering, new office 2026-06), Paris, Berlin (listed as a key office in postings; one of the dual HQs after the Aleph Alpha combination), Munich / Frankfurt / Brussels / Edinburgh (multi-location FDE postings), Heidelberg (research centre, pending close)
- **Programme structure**: no cohort / rotation, newcomers join as L3 MTS with the same title as experienced staff (lowest public Levels.fyi London level = L3 "Member of Technical Staff"); Scholars Program = remote-first, full-time paid research programme (no relocation, no publication record required), length / stipend not stated on the page
- **Non-EU visa (full-time)**: **UK**: Cohere UK Ltd on the official register = Worker (A rating), Skilled Worker [Source (verified opened): https://www.gov.uk/government/publications/register-of-licensed-sponsors-workers — 2026-10-09 CSV downloaded and searched] (previously only a search result); threshold £41,700 (£33,400 in specific cases) [Source (verified opened): https://www.gov.uk/skilled-worker-visa/your-job]. **FR**: Passeport Talent salarié qualifié €39,582 only for a master's obtained in France → non-French degrees use EU Blue Card €59,373 [Source (verified opened): https://www.service-public.gouv.fr/particuliers/vosdroits/F16922] (previous: "≥ €43,243", 2026-05). **DE (Berlin)**: Blue Card €50,700 / shortage occupations €45,934 (⚠️ Pending web verification: official pages blocked by Radware / 404, repo baseline values used). Scholars FAQ "Will Cohere Labs sponsor work permits?" → answered with remote-first, "no requirement to relocate" (no explicit sponsorship commitment). **NL student visa / zoekjaar**: no NL office, zoekjaar does not apply; Scholars is remote-first → may be doable remotely from NL (inferred, employment form to be confirmed)
- **Pay range (gross/year)**: **Levels.fyi London SWE (2026-10-10, 57 entries)**: median £177K (exact £176,929), average £183,886, highest £261,527, range £82,900 – £177,000+; L3 MTS row: total £236K / base £152K / stock £25.3K / bonus £0 (sample 5 yrs experience; columns are the values Levels.fyi shows and need not add up) [Source (verified opened): https://www.levels.fyi/en-gb/companies/cohere/salaries/software-engineer/locations/london-metro-area] (previous: L3 base ~£135K / total £172K, 2026-05-27). Official postings only publish Canada / US ranges: MTS (Multilingual etc.) base CA$295K – CA$535K (Toronto/Montreal) / CA$250K – CA$460K (Canada) / $205K – $380K (US CA/NY/WA); SWE Integrations CA$215K – CA$270K / $180K – $225K; no GBP / EUR ranges. Paris MTS has no Levels data (previous estimate €90-115K, unverified)
- **Application window**: full-time rolling; Scholars expected to open Fall 2026 (not open as of 2026-10-10); Winter 2027 internships (SWE / ML / Research) posted 2026-05, still open on 2026-10-10, incl. London/UK/Europe [Source (verified opened): https://jobs.ashbyhq.com/cohere/8c035d3d-081d-4c8a-914a-72f4efaad254]
- **Interview process difference vs internship**: MTS has 1-2 more rounds than internship (5-7 vs 4-5): Research MTS adds 1-2 paper deep-dive rounds, system design mandatory (serving / training pipeline / multi-tenant inference); coding same as internship (Colab + ML implementation tasks) (compiled 2026-05, no new reports found this round)
- **Competition**: extremely high, pass rate estimated 5-10% (inferred); a paper or OSS work is close to a hard requirement; public-sector roles (clearance / citizenship) not feasible for non-EU candidates
- **Key links**: Careers https://cohere.com/careers (verified opened) · Scholars https://cohere.com/research/scholars-program (verified opened) · Levels.fyi London (see above) · Aleph Alpha combination https://cohere.com/blog/cohere-and-aleph-alpha-sign-agreement (verified opened)

## 2. Internship Roles & Directions

| Role category | Main requirements | Notes |
|---|---|---|
| **ML Intern / Co-op** | Final year undergrad or master's, solid PyTorch | Engineering-leaning — model training tools, pipeline, infra |
| **Research Intern** | **PhD in progress** (ML / NLP / AI), top venue (NeurIPS/ICML/ICLR/ACL/EMNLP/COLING) papers strong signal | Lean toward research output; exceptional non-PhD also accepted |
| **SWE Intern** | CS undergrad final year, general engineering | LLM platform, API, infra |
| **ML Engineering Intern** | Between ML and SWE | Production ML, training optimization |

## 3. Application Requirements & Visa

- **Education**: SWE Intern penultimate year undergrad; ML / Research Intern prefer master/PhD
- **Technical hard conditions**:
  - Python + PyTorch / JAX proficient
  - At least one ML-related project / paper / internship
  - Distributed training (Distributed Data Parallel, Megatron, ZeRO) plus
  - Triton / CUDA / MLIR plus (System ML)
- **Visa**: **Cohere UK Ltd is Skilled Worker licensed employer** (Home Office register), London internship OK for international students, Student Visa usable
- **Salary**:
  - SWE Intern North America ~$59/hr (Levels.fyi); London estimated £4,000-£5,500 monthly salary
  - Stipend + $2,000 learning stipend + workplace stipend
  - Aidan Gomez publicly stated: **"We're happy to pay extremely high salaries"**

## 4. Interview Process

```
1. Recruiter Screen (30 min, background + motivation + résumé review)
2. OA / Take-home (Colab notebook form, self-contained questions → code + report)
   - SWE Intern: algorithm + ML concepts
   - ML Intern: implement top-k decoding, attention layer, tokenization, etc.
3. Coding Interview (45 min Live, Google Colab + real-time explanation)
4. Project / Manager Deep Dive
   - Résumé project deep dive (30-60 min, asks down to code details)
   - Team introduction + candidate interest alignment
5. ML Design / System Design (for ML Intern)
   - Design ChatGPT-class system / training pipeline / inference serving
6. (Optional) Paper discussion — Research Intern mandatory
```

Total duration **4-6 weeks**, Pass rate medium-low (~20-30%).

## 5. Interview Experience Excerpts

| Time | Role/City | Process Overview | Questions/Types | Result | Source |
|---|---|---|---|---|---|
| 2024 mid | MLE VO / general signal | Colab coding + ML design | Implement top-k LLM token decoding + ML design (ChatGPT class) | / | 1point3acres |
| 2024 mid | OA / Internship | Colab notebook | Attention / tokenization implementation + write report | / | 1point3acres |
| 2024 | Research Intern (Fall) | Resume → paper discussion + technical | Paper deep dive + Transformers implementation details | / | Cohere job listing |
| 2025 | General interview discussion | 4 rounds | Industry / LLM knowledge → narrow to specific concepts | / | Blind |
| 2024 | Non-PhD ML Intern | Coding + project | Emphasize "clear interest / existing projects" | / | Glassdoor |

## 6. Culture & Reputation

- **Positive**:
  - **Cohere Labs (research dept) strong academic atmosphere**, lots of open-source community interaction (Aya project, C4AI)
  - Salary industry top (CEO explicitly endorses "high pay")
  - Founder Aidan Gomez is Transformer author → interns have chance to access top scientists
  - Diverse + open research culture
- **Challenges**:
  - **Extremely high bar**: ML Intern also often required PhD in progress or top venue paper
  - Toronto / SF centralized → London team relatively small, accessible projects may be limited
  - Intense competition with OpenAI / Anthropic / DeepMind, top talent scarce
  - Glassdoor rating 4.0+ (relatively small sample)

## 7. Key Preparation Checklist

### ML / Research Intern direction
1. **Must-read papers**: "Attention Is All You Need" (Aidan one of authors); BERT/GPT series; LoRA, QLoRA; RLHF; Chinchilla scaling
2. **Must-run code**:
   - Implement Multi-head Attention + RoPE from scratch
   - Implement top-k / nucleus / beam search decoding
   - Fine-tune an open-source LLM (LLaMA / Mistral / Cohere Command-R)
3. **Distributed training**: ZeRO, Tensor Parallelism, Pipeline Parallelism
4. **Efficiency optimization**: FlashAttention, KV cache, quantization (GPTQ / AWQ)

### SWE Intern direction
1. LC Medium + algorithm basics
2. Python performance (asyncio, multiprocessing)
3. Kubernetes / Docker / API design

### Behavioral
1. "Why Cohere (not OpenAI / Anthropic)" — must be sincere, talk about enterprise LLM differentiation
2. Project deep dive preparation — each résumé project must be able to discuss code details

## 8. Summary Rating

| Dimension | Rating | Notes |
|---|---|---|
| Information density | Medium-high | Overseas interview experiences abundant, London-targeted slightly fewer but process clear |
| Application threshold | Extremely high | LLM research + engineering dual high bar |
| Offer conversion expectation | Low | Pass rate 20-30%, Research Intern even lower |
| Recommendation index | Strongly recommended (for ML direction) | Top LLM employer, brand value and future channel excellent |

> **Suggestion**: ML / research direction students must apply. Preparation time at least 2-3 months, paper + code dual cultivation. Résumé must have ML project + GitHub public implementation. Getting interview is already top proof.

## Information Sources

- [Cohere Careers](https://cohere.com/careers)
- [Cohere Research Internship Fall 2025 - Built In](https://builtinlondon.uk/job/research-internship-fall-2025/4808713)
- [Cohere SWE Intern Job Ashby](https://jobs.ashbyhq.com/cohere/8c035d3d-081d-4c8a-914a-72f4efaad254)
- [Cohere ML Intern Spring/Summer 2026 - Jobright](https://jobright.ai/jobs/info/69698998f25a380066982e96)
- [Levels.fyi Cohere Intern Salary](https://www.levels.fyi/internships/Cohere-ai/Software-Engineer-Intern/)
- [Cohere ML Intern Interview Questions Glassdoor](https://www.glassdoor.com/Interview/Cohere-Machine-Learning-Intern-Interview-Questions-EI_IE6413613.0,6_KO7,30.htm)
- [1point3acres Cohere OA](https://www.1point3acres.com/bbs/thread-1059251-1-1.html)
- [1point3acres Cohere MLE VO](https://www.1point3acres.com/bbs/thread-1065950-1-1.html)
- [Cohere UK Ltd Sponsor Status](https://immigrationgpt.co.uk/company/Cohere-UK-Ltd)
- [Cohere European Expansion - Sifted](https://sifted.eu/articles/aidan-gomez-cohere-interview)
- [Cohere Labs Research](https://cohere.com/research)
- [Blind Cohere Interview Discussion](https://www.teamblind.com/company/Cohere/posts/cohere-interview)
- [Cohere AI Researcher Interview Guide](https://www.datainterview.com/blog/cohere-ai-researcher-interview)
- [Levels.fyi - Cohere London SWE 2026-05](https://www.levels.fyi/en-gb/companies/cohere/salaries/software-engineer/locations/london-metro-area)
- [Levels.fyi - Cohere SWE UK all](https://www.levels.fyi/companies/cohere/salaries/software-engineer/locations/united-kingdom)
- [UK Skilled Worker 2026 £41,700 threshold - Jobbatical](https://www.jobbatical.com/blog/uk-skilled-worker-visa-minimum-salary-41700-threshold-employer-guide)
- [Glassdoor - Cohere MTS Salaries (US)](https://www.glassdoor.com/Salary/Cohere-Member-Of-Technical-Staff-Salaries-E6413613_D_KO7,32.htm)
- [6figr - Cohere Salaries 2026](https://6figr.com/us/salary/cohere)
- [Blind - AI scientist / MTS comp Mistral vs Cohere London](https://www.teamblind.com/post/ai-scientist-member-of-technical-staff-compensation-for-mistralcohere-london-7x2nc1m1)
