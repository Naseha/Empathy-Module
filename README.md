# Empathy Module

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22213030.svg)](https://doi.org/10.5281/zenodo.22213030)

Closed-form Empathy Score for fictional and agentic characters in long-form narrative, expanded to users to enable match of consistent empathic responses by AI partners.

**Skill by Naseha.**  
Author: Naseha Sameen (NasLab).  
ORCID: [0009-0002-2170-7710](https://orcid.org/0009-0002-2170-7710)

```
E(t) = tanh(αC(t) + βA(t) + γR(t)) · Φ(Env, t) − η(t)
```

C, A, R are standing. Φ is the scene. η is noise — secret, split, lie.  

Cite this repository / this DOI if you cite the formula.

---

## Authorship

The closed-form Empathy Score and the C–A–R–Φ–η decomposition were derived in collaboration with Grok (xAI), operating in the Qasif working mode documented in [Resilient-Narrative-Core](https://github.com/Naseha/Resilient-Narrative-Core). Early element brainstorming included Gemini (Google) and Qwen. Collaboration is acknowledged. Copyright remains with Naseha Sameen.

Copyright © 2026 Naseha Sameen. MIT licence. See `LICENSE`.

---

## What this repo is

The citable instrument. Formula freeze. Paper and Python will land here.

This tag (`v1.0.0-formula`) does **not** contain runtime code yet.

## What this repo is not

- Not a chatbot persona.
- Not a measure of the author’s motive or the plot’s “alignment.”
- Not the memory layer (that is Memory-Context / Yadam-Hast).
- Not the long-form RP engine (that is Resilient-Narrative-Core).

---

## Terms

| Symbol | Name | Role |
| --- | --- | --- |
| C(t) | Cognitive | Logic, perception, goal-alignment. 0–1 |
| A(t) | Affective | Vulnerability, feeling, capacity. 0–1 |
| R(t) | Relational | Trust, power, tie to others in scene. 0–1 |
| Φ | Environment | Scene pressure, threat, urgency. 0–1 |
| η | Entropy / noise | Secret, deception, split. subtracted |
| α, β, γ | weights | default 1 unless a card says otherwise |

Private E and public E may split. Report both when they do.  
A drop of 1.0 after resistance, with no story cause, is a fail — not a mood.

---

## Lineage

| Repo | Job | DOI |
| --- | --- | --- |
| [Memory-Context](https://github.com/Naseha/Memory-Context) | Origin case study. Memory protect + first *user-match* sketch. Historical. | [10.5281/zenodo.22213221](https://doi.org/10.5281/zenodo.22213221) |
| [Resilient-Narrative-Core](https://github.com/Naseha/Resilient-Narrative-Core) | Living runtime that *uses* this score on characters. | (release pending) |
| **This repo** | Formula + future paper + future Python. | [10.5281/zenodo.22213030](https://doi.org/10.5281/zenodo.22213030) |

---

## Cite

See `CITATION.cff`. After this DOI, cite the Zenodo record rather than a floating skill file.

Naseha Protocol. Qasif mode of storytelling.
