# Mistral AI (Paris) — Internship Intel

> **Language**: [中文](mistral.md) | English
>
> France's top homegrown large model company, valuation ~€6-14B (2024-2025), team ~100 people rapidly expanding to 200+. Extremely high hiring bar, usually requires NeurIPS/ICML-level paper or top conference first author; Master interns need to be from "Tier 1" engineering schools.

---

## 1. Company Snapshot

| Dimension | Info |
|---|---|
| HQ | Paris (France) — main office, also London/Palo Alto/Singapore |
| Founded | April 2023, founded by Arthur Mensch, Guillaume Lample, Timothée Lacroix |
| Valuation/size | ~USD 14B (2025), ~100-200 employees, planning to hire 125 more |
| Business | Open-source + closed-source LLM (Mistral 7B, Mixtral, Codestral, Large 2), API, Le Chat |
| Tech stack | PyTorch, JAX, Megatron-LM, Slurm/K8s on thousands of GPUs, Rust inference |
| Work style | Engineer-driven, flat structure, fast ship, open-source first, Paris-first |
| Glassdoor rating | ~4.7/5 recommendation rate 100% (small sample); WLB 3.8/5 |

---

## New Grad / Junior Roles

> Information richness: ⭐⭐⭐ (Mistral 2026 public data shows obvious expansion — Levels.fyi L2 Paris data out + jobsbyculture detailed leveling + 164 active reqs; but standalone "Graduate" named reqs for new grads still few, mainly via PhD/Master internship + CIFRE conversion)
> Distinct from internship: full-time entry-level (0-2 years experience); Mistral **2026 has expanded to 1,000+ employees** (far above 2025 100-200 scale) [Source (verified opened): https://jobsbyculture.com/blog/mistral-compensation-2026]; hiring senior-skewed but L1/L2 entry is public

- **Common role names**: Software Engineer (L1 Entry / L2 / L3 Lead), ML Research Engineer, Research Scientist, Applied AI Engineer, Forward Deployed ML Engineer; hiring page rarely tags "Graduate" — prefers 1-2 years large-model experience / PhD in-progress / new PhD
- **European locations**: main base **Paris (9th arr.)** — most employees [Source (verified opened): https://jobsbyculture.com/blog/mistral-compensation-2026]; growth in **London + San Francisco**; Junior / new grad roles almost default Paris onsite
- **Independent Graduate Programme**: **No** — no named cohort, but two entry pathways:
  - **CIFRE (French doctoral-corporate joint training) → Full-time Research Engineer**: Mistral in AI Scientist Internship JD **explicitly states support for CIFRE renewal** [Source (verified opened): https://www.indexventures.com/startup-jobs/mistral/ai-scientist-paris-internship-phd/ via search]; main entry for PhD students
  - **Master internship → full-time Software Engineer L1/L2**: Applied AI / Forward Deployed Engineer internship is direct channel for Master / M2
- **Non-EU visa (full-time)**:
  - **France Passeport Talent (Salarié Qualifié)**: monthly salary ≥ 2x SMIC (~€3,494/month gross), Mistral Software Engineer L1 starting salary €70-90k well above threshold [Source (verified opened): https://jobsbyculture.com/blog/mistral-compensation-2026]
  - **EU Blue Card (France)**: 2026 threshold ~€54-55k/year, Mistral L1 borderline / L2+ safely meets
  - **APS (Autorisation Provisoire de Séjour)**: M2 France graduation 12 + 24 months job-seeking, main path for China / India candidates
  - jobsbyculture article doesn't explicitly write sponsor policy, but Mistral's overseas hiring is obvious → actually sponsors (especially top-conference ML candidates)
- **Salary range (Levels.fyi 2026-05-28 + jobsbyculture data, Greater Paris Area)**:
  - **L1 (Software Engineer, Entry / Junior)**: base €70K-€90K, +BSPCE equity, TC €90K-€130K [Source (verified opened): https://jobsbyculture.com/blog/mistral-compensation-2026]
  - **L2 (Software Engineer)**: TC median ~€78.6K, Levels.fyi USD data base $85.5K + stock $5.7K = TC $91.2K (~€85K) [Source (verified opened): https://www.levels.fyi/companies/mistral-ai/salaries/software-engineer/locations/greater-paris-area]; jobsbyculture mid-level €90K-€120K base + equity → TC €130K-€180K
  - **L3 (Lead Software Engineer)**: TC median ~€134K (Levels.fyi $156K), jobsbyculture senior €120K-€165K base + €180K-€250K+ TC
  - **Research Scientist (Mid / Staff)**: TC ~$490K (mid) / $700K-$950K (staff) [Source (verified opened): https://jobsbyculture.com/blog/mistral-compensation-2026]
  - **Equity structure**: **BSPCE** (French startup options) — 4-year vest + 1-year cliff + **12.8% flat tax** (vs CA 40-50%); illiquid until IPO / acquisition
  - Compared to French local (Criteo / Doctolib) Mistral full-time base 30-50% higher, plus equity has huge upside
- **Application window**: **Rolling year-round**, no fixed deadline; **2026-05 active 164 reqs (significant expansion)** across research / engineering / infrastructure, mainly Paris [Source (verified opened): https://jobsbyculture.com/blog/mistral-compensation-2026]; no cohort batch. **2026-09-26 re-check**: official careers page's ATS has moved from Lever to Ashby (jobs.ashbyhq.com/mistral.ai) [Source (verified opened): https://mistral.ai/careers]; the old Lever page is still reachable and currently lists AI Scientist Internship (PhD) — Paris, AI Scientist Internship (PhD) — Palo Alto, and Applied AI Engineer, Use-case (Internship) — Paris, all rolling with no stated deadline [Source (verified opened): https://jobs.lever.co/mistral]
- **Interview process differences vs internship**:
  - Internship 5-6 rounds (HR → Team Lead → LLM Quiz → Coding → System Design → Fit), full-time **same 5-6 rounds each round depth increasing**
  - **Implementing attention from scratch is still high-frequency test point**, full-time adds multi-GPU training / inference optim / distributed training
  - System Design: full-time asks inference serving (vLLM-style), KV cache management, batch scheduling, multi-tenant serving
  - Founder round appears more frequently in full-time process
- **Acceptance competition**: Mistral publicly "hire only the best", Master internship hit rate < 5%, full-time entry-level L1 similarly strict; international student friendliness medium-high (after 1,000+ scale sponsor process more familiar); top-conference first-author paper / large open-source PR is entry ticket; vs Hugging Face / Criteo AI Lab still hardest
- **Key links**:
  - Mistral Careers: https://mistral.ai/careers
  - **Ashby Mistral Jobs (main link on official site as of 2026-09-26) [Source (verified opened): https://mistral.ai/careers]**: https://jobs.ashbyhq.com/mistral.ai
  - Lever Mistral Jobs (legacy link, still reachable 2026-09-26, 3 open internships) [Source (verified opened): https://jobs.lever.co/mistral]: https://jobs.lever.co/mistral
  - **Levels.fyi Mistral Paris (2026-05-28)**: https://www.levels.fyi/companies/mistral-ai/salaries/software-engineer/locations/greater-paris-area
  - Levels.fyi Mistral France all levels: https://www.levels.fyi/companies/mistral-ai/salaries/software-engineer/locations/france
  - **JobsByCulture Mistral Compensation 2026 (incl. BSPCE / leveling)**: https://jobsbyculture.com/blog/mistral-compensation-2026
  - Mistral AI Scientist PhD Internship (incl. CIFRE renewal statement): https://www.indexventures.com/startup-jobs/mistral/ai-scientist-paris-internship-phd/
  - Welcome to the Jungle Mistral: https://www.welcometothejungle.com/en/companies/mistral-ai/jobs
  - startup.jobs Mistral active req: https://startup.jobs/company/mistral-ai
  - Glassdoor Mistral AI Interviews: https://www.glassdoor.com/Interview/Mistral-AI-Interview-Questions-E9945031.htm

---

## 2. Internship Role Types

| Role name | Degree requirement | Team | Keywords |
|---|---|---|---|
| AI Scientist Internship (Master) | M2, Tier 1 school (Math/Physics/ML) | Science Team | LLM design, NLP research, model optimization |
| AI Scientist Internship (PhD) | PhD in-progress, top conference publication bonus | Science Team | Frontier research, free topic choice, publish papers |
| Applied Scientist / Research Engineer (Intern) | M2 or PhD | Applied AI | Customer scenario customized models, multimodal (text/image/voice) |
| Applied AI, Forward Deployed ML Engineer (Intern) | M2 (CS/Math/ML) | Applied Engineering | Customer LLM deployment, fine-tuning, RAG, eval |
| ML Research Engineer (sometimes opens internship) | M2/PhD | Research Engineering | Pre-training/post-training pipelines, thousand-card clusters |

**Locations**: mainly Paris; some roles Paris/London/Zurich/Warsaw three-way choice. Some support CIFRE (French PhD+enterprise joint training) renewal.

**Duration**: 3-6 months (6 months best), tends toward last internship before graduation.

---

## 3. Application Eligibility (Hard Requirements + Bonus)

| Item | Content |
|---|---|
| Education | M2 / PhD in-progress. Master roles explicitly require "Tier 1 engineering schools or universities" — Chinese students roughly equivalent to Tsinghua/Peking/HKUST / EPFL / Polytechnique / ENS / Cambridge / Oxford level |
| Language | English primary, French not required but bonus |
| Programming | Python mandatory, PyTorch/TF, bonus: contribution to large open-source codebase |
| Research | NLP/LLM/Transformer related publication strongly bonus; PhD role almost essential |
| Mathematics | Linear algebra, probability, optimization solid |
| Engineering | Familiar with distributed training (FSDP/DeepSpeed/Megatron), GPU profiling bonus |
| Timing | Tends toward "about to graduate" candidates, can convert (especially CIFRE path) |

> **Important warning**: Mistral is extremely picky at the Master internship level. On 1point3acres/Reddit you can hardly find cases of non-top-school non-paper backgrounds getting interviews. If your CV doesn't have top conference/journal first author, no large open-source PR, no EPFL/Polytechnique/ENS/MIT-level school, hit rate < 5%. This is an honest assessment, not discouragement, but recommendation to **also apply to Hugging Face, Criteo AI Lab, Kyutai and other more accessible choices**.

---

## 4. Hiring Process (based on Glassdoor / interviewquery / datainterview)

Mistral process averages ~15 days, 5-6 rounds:

| Round | Content | Duration | Format |
|---|---|---|---|
| 1. HR Screen | Background, motivation, timeline, expectations | 30 min | Phone/Google Meet |
| 2. Team Lead Screen | Resume deep dive, project/paper details | 30-45 min | Video |
| 3. LLM Quiz | Transformer architecture, attention, KV cache, RAG, fine-tuning, embedding retrieval, scaling laws | 45-60 min | Strict Q&A format (not discussion), seeking specific answers |
| 4. Coding / Tech | LeetCode medium; may also require **implementing multi-head self-attention from scratch** (incl. causal mask, batch) | 60-90 min | Shared editor |
| 5. System Design / Take-home Panel | Training system design, inference service architecture; or take-home + defense | 60-90 min | Video |
| 6. Fit / Founder Round | Talk with founder or senior member about vision and match | 30-45 min | Video |

**Features**:
- Process **emphasizes LLM depth** > classical ML breadth. KV cache, embedding, RAG pipeline all high-frequency test points.
- Coding requires **ability to implement attention from scratch**, not just calling API.
- "Rigid Q&A" style — interviewer is looking for specific knowledge points you say, not open discussion.

---

## 5. Interview Experience Summary

| Date | Role/City | Process overview | Question type | Result | Source |
|---|---|---|---|---|---|
| 2024-2025 | Applied AI Engineer (Paris) | HR → Tech Manager → LLM Quiz → Coding → Take-home → Fit | LLM Quiz: KV cache, embedding retrieval, RAG; coding: multi-head attention from scratch | Difficulty 2.56-3/5 (Glassdoor), 11.1% positive | [Glassdoor Mistral Interviews](https://www.glassdoor.com/Interview/Mistral-AI-Interview-Questions-E9945031.htm) |
| 2024-2025 | Applied AI Engineer | 6 rounds: HR / Team Lead / Business Case / Tech (LLM+SysDesign) / Take-home Panel / Fit | Business case oriented toward customer use scenarios | Info scarce | [Mistral AI Engineer Guide - datainterview](https://www.datainterview.com/blog/mistral-ai-engineer-interview) |
| 2024 | Software Engineer | ~5-6 rounds, ~15 days | LeetCode medium, system design focused on inference/training stack | — | [Mistral AI SWE Interview - interviewquery](https://www.interviewquery.com/prep-guides/mistral-ai-software-engineer) |
| — | LLM Engineer | LLM Quiz heavy | Transformer arch, fine-tuning, RAG | — | [Glassdoor LLM Engineer](https://www.glassdoor.com/Interview/Mistral-AI-LLM-Engineer-Interview-Questions-EI_IE1133892.0,7_KO8,23.htm) |

> Chinese community (1point3acres/Nowcoder/Zhihu) specific interview experiences about Mistral internship are nearly zero. **Info scarce**, recommend looking at Glassdoor / Reddit r/MachineLearning directly.

---

## 6. Compensation and Benefits

| Item | Value/description |
|---|---|
| Full-time SWE salary (Paris) | €78.6K - €134K+ (Levels.fyi); senior role €108-142K+ |
| Intern stipend | Limited public info. French stage legal minimum **€4.35/hour (2025)**, ~€600+/month; **Mistral generally clearly above legal**, industry estimate €1,500-2,500/month; overseas channels mention USD 8-11K/month (this number may target US roles, Paris internship not necessarily so) — **based on offer** |
| Benefits | Meal vouchers (titre-restaurant), Gympass monthly subsidy, mobility pass, private health insurance, learning budget, full-time can take stock options |
| Convention de stage | Required. School issues tripartite agreement. >2 months mandatory gratification |
| Visual certification | Non-EU students need valid carte de séjour étudiant (French school registration gives directly); overseas hiring needs to consider visa stagiaire (APS not applicable to internship) |

---

## 7. Culture, Work Environment, Soft Intel

- **Pace**: Weekly reports/Slack/very few meetings, engineers highly self-driven. Early employees describe "everyone wears many hats".
- **Open-source culture**: Model weights and code largely open; your visible contributions on GitHub/HF (vLLM, transformers, llama.cpp etc. PRs) are real bonus points.
- **WLB**: Glassdoor 3.8/5. Not 996, but ship pace fast, pressure before deadline.
- **Office**: Paris 9th arr./center. Multi-lingual, working language English.
- **Conversion**: PhD internship → CIFRE/Full-time research engineer channel relatively clear; Master internship conversion difficulty high but has precedent.
- **Risk points**: Team size rapidly expanding (100 → 200+), early-employee dividend diminishing; internal mentorship not as structured as big tech.

---

## 8. Application Strategy and Timeline Recommendations

| Step | Recommendation |
|---|---|
| 1. Build OSS credit | Submit at least 1-2 substantive PRs (>50 lines, merged) to HuggingFace / vLLM / transformers / candle / mistral.rs |
| 2. Find one publicly visible LLM project | GitHub repo + a short blog explaining design choices (fine-tuning, RAG, eval). This is far better than coursework |
| 3. CV adjustment | Publication / top conference first author on top; if no paper, put open-source PR + key ML projects on first screen |
| 4. Time window | M2 stage usually starts Mar-Sep / Sep-Feb two periods; **4-6 months in advance** apply on jobs.lever.co/mistral, earlier the better |
| 5. Referral | Find referral via French alumni groups (X-Polytechnique, ENS, MVA, IP Paris); many Mistral employees come from MVA program |
| 6. Prepare deep LLM | Focus on KV cache, paged attention, FlashAttention, RAG (BM25 + ANN), DPO/RLHF/PPO, scaling laws, MoE; read Anthropic/OpenAI/Meta surveys from past 2 years |
| 7. Coding preparation | LeetCode Medium + **able to implement Transformer block from scratch in 45 min** (PyTorch, naked) |
| 8. Alternatives | Also apply to Hugging Face, Kyutai (Paris, same root as Mistral), Cohere, Anthropic, Meta FAIR Paris, Adept |

---

## Sources

- [Mistral AI Careers](https://mistral.ai/careers)
- [Lever - Mistral Jobs](https://jobs.lever.co/mistral)
- [Mistral AI - AI Scientist Master Internship](https://jobs.lever.co/mistral/292397f0-4ac7-4309-a0e8-63c97761a2cb)
- [Mistral AI - Applied AI Forward Deployed ML Engineer Internship](https://jobs.lever.co/mistral/881941e1-2741-48e2-8767-12866965fac5)
- [Glassdoor - Mistral AI Interview Questions](https://www.glassdoor.com/Interview/Mistral-AI-Interview-Questions-E9945031.htm)
- [Glassdoor - Mistral AI Applied AI Engineer Interview](https://www.glassdoor.com/Interview/Mistral-AI-Applied-AI-Engineer-Interview-Questions-EI_IE9945031.0,10_KO11,30.htm)
- [interviewquery - Mistral AI SWE](https://www.interviewquery.com/prep-guides/mistral-ai-software-engineer)
- [datainterview - Mistral AI Engineer Guide 2026](https://www.datainterview.com/blog/mistral-ai-engineer-interview)
- [datainterview - Mistral AI Researcher Guide](https://www.datainterview.com/blog/mistral-ai-researcher-interview)
- [Levels.fyi - Mistral AI Salaries](https://www.levels.fyi/companies/mistral-ai/salaries)
- [Glassdoor - Working at Mistral AI](https://www.glassdoor.com/Overview/Working-at-Mistral-AI-EI_IE9945031.11,21.htm)
- [Welcome to the Jungle - Mistral AI Jobs](https://www.welcometothejungle.com/en/companies/mistral-ai/jobs)
- [PropelGrad - Mistral AI Jobs & Internships](https://propelgrad.com/ai-jobs/at-mistral)
- [Levels.fyi Mistral SWE Greater Paris Area 2026-05](https://www.levels.fyi/companies/mistral-ai/salaries/software-engineer/locations/greater-paris-area)
- [Levels.fyi Mistral SWE France All Levels](https://www.levels.fyi/companies/mistral-ai/salaries/software-engineer/locations/france)
- [JobsByCulture Mistral Compensation 2026 Breakdown](https://jobsbyculture.com/blog/mistral-compensation-2026)
- [startup.jobs Mistral AI April 2026](https://startup.jobs/company/mistral-ai)
- [Index Ventures: Mistral AI Scientist Paris Internship (PhD CIFRE)](https://www.indexventures.com/startup-jobs/mistral/ai-scientist-paris-internship-phd/)
- [a16z Jobs - Mistral AI Careers](https://jobs.a16z.com/jobs/mistral-ai)
