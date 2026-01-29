# temporal-interrater-reliability-annotation
Temporal inter-rater reliability using guideline-driven annotation with temporally separated rounds
# Temporal Inter-Rater Reliability in Human Annotation  
### A guideline-driven annotation project with temporally separated labeling

---

## Why this project exists

Human annotation sits at the core of clinical research datasets and medical AI systems.  
When labels depend on subjective interpretation (for example, symptom descriptions), inconsistency can quietly degrade data quality and downstream conclusions.

This project demonstrates a **small, transparent, and auditable annotation workflow** that focuses on:

- clear annotation rules  
- consistency over time  
- explicit handling of uncertainty  
- documentation of disagreement and resolution  

Rather than optimizing for scale, the emphasis is on **process quality**—the same principles expected in regulated or ethically sensitive settings.

---

## What this project shows

- How annotation guidelines reduce ambiguity  
- How consistency can be assessed even with a single annotator  
- How disagreements reveal weaknesses in rules (not “mistakes”)  
- How annotation workflows can align with established regulatory and ethical principles  

The workflow is conceptually aligned with:
- :contentReference[oaicite:0]{index=0} — Good Machine Learning Practice (GMLP)  
- :contentReference[oaicite:1]{index=1} — Ethics & Governance of AI for Health  
- :contentReference[oaicite:2]{index=2} — data quality and human-centered design principles  
- :contentReference[oaicite:3]{index=3} / :contentReference[oaicite:4]{index=4} — transparency in data generation  

No certification or formal compliance is claimed—only **methodological alignment**.

---

## Data overview

- **Type:** Short textual statements describing tiredness or low energy  
- **Source:** Synthetic or de-identified text  
- **Unit of annotation:** One sentence per item  
- **Size:** 30–50 items  

No personal identifiers or patient data are used.

---

## Labels used

Each sentence receives **one mutually exclusive label**:

| Label | Meaning |
|-----|--------|
| **F – Fatigue** | Persistent, non-situational tiredness with explicit duration or chronicity |
| **S – Stress-related tiredness** | Situational tiredness linked to lifestyle factors (e.g., work, exams, sleep loss) |
| **U – Unclear** | Insufficient or ambiguous information for confident classification |

A conservative rule is followed: **when in doubt, label as _Unclear_**.

---

## Annotation guidelines

All labeling is governed by a written **annotation style guide**, which defines:

- operational label definitions  
- inclusion and exclusion criteria  
- explicit decision rules  
- default handling of uncertainty  

The guidelines are **versioned** to ensure traceability.

Files:
