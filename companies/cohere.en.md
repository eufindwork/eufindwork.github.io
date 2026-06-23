# Cohere (London) Internship Intelligence

> **Language**: [中文](cohere.md) | English
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

> Information density: ⭐⭐⭐⭐ (Levels.fyi London SWE 2026-05-27 verified has specific L3 MTS data points; Glassdoor UK MTS data sample relatively small, US data abundant, **London median £172K total / base ~£135K**)
> Difference from internship: full-time entry-level (0-2 years experience) — Cohere is centered on "Member of Technical Staff" (MTS), internally graded L3/L4/L5 but title doesn't distinguish

- **Common role names**: Member of Technical Staff (Research / Engineering), Machine Learning Engineer, Software Engineer, Research Engineer; **no "Junior" / "New Grad" explicit title** — new hires enter as L3 MTS, share same title with experienced candidates
- **European locations**: London (core research + engineering hub, same as internship) + Paris (40-person new office, 2024 expansion, lean research + enterprise sales support); very few fully remote European roles
- **Standalone Graduate Programme**: **No** — Cohere ~400 people, doesn't run cohort grad pipeline; everything goes through MTS channel, same as OpenAI / Anthropic model (paper + code > degree label)
- **Non-EU visa (full-time)**:
  - **London**: Cohere UK Ltd is **Skilled Worker licensed sponsor** (Home Office register confirmed [Source (search result): https://immigrationgpt.co.uk/company/Cohere-UK-Ltd]); can issue CoS to non-UK new grad
  - **Key update**: UK Skilled Worker minimum base raised from £38,700 to £41,700 from 2025-07-22 (still effective 2026) [Source (search result): https://www.jobbatical.com/blog/uk-skilled-worker-visa-minimum-salary-41700-threshold-employer-guide]; also New Entrant discount line £33,400; Cohere London L3 base ~£135K far exceeds
  - **Paris**: Passeport Talent (salarié qualifié) available, base needs ≥ €43,243 (2026 SMIC × 1.8), Cohere Paris MTS base estimated €90K+ fully meets
  - Completely different from internship (Student Visa / carte de séjour étudiant) path, **full-time more stable**
- **Salary range (base, gross/year)**:
  - **London MTS L3 median 2026-05-27 verified**: **base ~£135K ($176K USD) / total £172K ($230K USD) / stock ~£42K ($54.1K) / bonus 0** — Levels.fyi L3 median (median 4 years experience, 2 years tenure, slightly higher than pure new grad) [Source (verified opened): https://www.levels.fyi/en-gb/companies/cohere/salaries/software-engineer/locations/london-metro-area]
  - **London SWE range**: £82.3K-£171K+ (Levels.fyi 2026-05 range) → **pure new grad L3 estimated falls in £100-130K base**
  - **Glassdoor UK MTS average**: £44K base (sample extremely small, biased report, severely inconsistent with Levels.fyi — use Levels as standard) [Source (search result, WebFetch 403): https://www.glassdoor.co.uk/Salary/Cohere-Member-Of-Technical-Staff-Salaries-E6413613_D_KO7,32.htm]
  - **US MTS average**: $240K base (Glassdoor US, 25-75 percentile $190K-$308K) — Europe London 0.7-0.75 discount roughly matches Levels.fyi data
  - **Paris MTS L3** (estimated, no Levels data): €90-115K base + equity (higher than Mistral L3 €70-80K, on par with OpenAI Paris)
  - **CEO Aidan Gomez publicly committed "extremely high salaries"** — same tier as Anthropic/OpenAI verified by Levels.fyi
- **Application window**: rolling — open year-round, Ashby recruiting page continuously updated [Source (search result): https://cohere.com/careers]; **after paper deadlines (ICML / NeurIPS) Research MTS** roles released in batches
- **Interview process difference vs internship**:
  - One more round: **Paper Bar significantly heavier** (Research MTS must have 1-2 rounds paper deep dive, internship occasionally has)
  - **System Design mandatory** (internship only ML Intern has): ChatGPT-class serving / training pipeline / multi-tenant inference
  - Coding bar same as internship (Colab + ML implementation questions), but **total rounds 1-2 more** (5-7 rounds vs internship 4-5 rounds)
  - OSS / paper at least one is **hard requirement** — Cohere For AI (C4AI) team especially values Aya / multilingual NLP contributions
- **Acceptance competition**: Extremely high — Pass rate estimated 5-10% (vs internship 20-30%); competing for same batch as OpenAI / Anthropic / DeepMind; **international student OK** but needs paper or OSS hard currency, school brand is plus but not deciding
- **Key links**:
  - Official careers page: [cohere.com/careers](https://cohere.com/careers)
  - Levels.fyi Cohere London SWE: [levels.fyi Cohere London](https://www.levels.fyi/en-gb/companies/cohere/salaries/software-engineer/locations/london-metro-area) (verified opened, 2026-05-27 data)
  - Cohere UK Ltd Skilled Worker status: [immigrationgpt.co.uk](https://immigrationgpt.co.uk/company/Cohere-UK-Ltd)
  - UK Skilled Worker 2026 £41,700 threshold: [Jobbatical](https://www.jobbatical.com/blog/uk-skilled-worker-visa-minimum-salary-41700-threshold-employer-guide)
  - Cohere Paris expansion: [Sifted - Aidan Gomez interview](https://sifted.eu/articles/aidan-gomez-cohere-interview)
  - Blind Cohere discussion: [teamblind.com/Cohere](https://www.teamblind.com/company/Cohere/posts/cohere-interview)
  - Cohere Labs (research vs engineering distinction): [cohere.com/research](https://cohere.com/research)

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
