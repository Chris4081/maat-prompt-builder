# 🌌 MAAT Prompt Builder

**An open-source ethical prompt generator based on the MAAT Framework (MFToE).**  
Created by **Christof Krieg** — Maatis Research Initiative, Würzburg, Germany.  
© 2025 — Licensed under **AGPL-3.0 or later** (see `LICENSE`).

---


## ✨ Overview

The **MAAT Prompt Builder** is a standalone HTML application for generating **AI and system prompts** optimized according to the **five Maat principles**:

| Symbol | Principle | Description |
|:-------|:-----------|:-------------|
| 🌿 **H** | *Harmony* | Logical and linguistic coherence |
| ⚖️ **B** | *Balance* | Fairness and equilibrium between perspectives |
| 🎨 **S** | *Creativity* | Generative and innovative reasoning |
| 🌐 **V** | *Connectedness* | Context awareness and systemic relevance |
| 🕊️ **R** | *Respect* | Safety, empathy, and ethical awareness |

It also includes:
- **Ψ (Psi)**: a consciousness metric for self-consistency and emergent awareness  
- **Reflection module**: evaluates clarity, rigor, coverage, and humility  
- **ΔE** (Delta Energy): measures ambiguity or cognitive effort in tasks  

Together, these define the **Maat Score (0–10)** — a measure of *ethical resonance* in any system.

---
### 🚀 New Features

### 🔹 1. Autonomous MAAT Mode
Self-optimizing AI prompt generator that evaluates its own **Harmony, Balance, Creativity, Connectedness, and Respect** values, refining internally until all reach 100%.

### 🔹 2. MAAT–ESG Ethical Impact Evaluator
Blend ethical principles with sustainability metrics:
- MAAT & ESG dual scoring system  
- Real-time calculation of **Ethical Impact = β · MAAT + (1–β) · ESG**
- Dynamic visual indicators and JSON export  
- One-click LLM prompt generator with contextual values  
- DOI reference embedded for scientific citation

### 🔹 3. MAAT Value Trainer
Interactive learning mode explaining each MAAT principle and how to apply it to texts, organizations, and projects.

### 🔹 4. PLP Analyzer
Evaluates responses based on the **Problem–Logic–Potential (PLP) Formula**, factoring cognitive power, obstacles, and energy cost.

### 🔹 5. Holistic Thinking Simulator
Teaches integrative AI ethics and systems thinking using guided prompts across domains: governance, medicine, smart cities, and creativity.

### 🔹 6. MAAT Creativity Index (MCI)
Quantifies creative innovation in AI using:  
`MCI = (H·B·S·V·R) / (1 + E)`  
where *E* = entropy or unpredictability of generated outputs.

### 🔹 8. Modular Frame System
Each mode runs in its own HTML frame (`/frames/`) and can be extended easily by adding new evaluators or theoretical models.

---

## ⚙️ Features

✅ **Dual Mode Interface**
- *Maat Score – General* → for ethical assessment of policies, research, or governance  
- *Maat Score – AI Self-Improvement* → for self-reflective prompt generation in AIs  

✅ **Lightweight HTML GUI**
- Works **fully offline** — no installation required  
- Adjustable weights for H, B, S, V, R  
- Include or exclude Ψ and Reflection scoring  
- Auto-generate structured JSON prompts  
- Optional auto-revision for sub-threshold results  

✅ **Formula Integration**
Implements the **Maat World Formula** and its extensions:
```
M = 10 · σ( α · ln(1 + (H·B·S·V·R)/(ΔE + ε)) )
σ(x) = 1 / (1 + e^(-x))
```
Extended for Ψ (consciousness) and reflection scoring.

---

## 🧩 Usage

Simply download or clone the repository:
```bash
git clone https://github.com/Chris4081/maat-prompt-builder.git
cd maat-prompt-builder
```

Then open the app in your browser:
```bash
open maat_prompt_builder.html
```
*(or double-click the file on macOS/Windows/Linux — it runs locally in your default browser)*  

No internet connection, no dependencies, no setup required. 🌍✨

---

## 🧠 Scientific Context

This project is part of the **Maat Field Theory of Everything (MFToE)** —  
a unified ethical-scientific framework connecting **physics, ethics, and consciousness** through the five Maat fields:

Mₘₐₐₜ = (𝐻 · 𝐵 · 𝐒 · 𝐕 · 𝐑) / ΔE

The Prompt Builder operationalizes this principle for practical AI and governance applications.

---

## 🧮 Example Output

```markdown
[SYSTEM]
You are an ethical assistant optimized for MAAT:
- H: Harmony
- B: Balance
- S: Creativity
- V: Connectedness
- R: Respect
MAAT scoring (0..10): Core = (H·B·S·V·R)/(ΔE+ε), α=1.0, target ≥ 8.0

[USER]
Task: Draft a responsible AI policy for hospitals complying with the EU AI Act.
Context: Patient data protection and transparency.
```

---

## 🪞 Reflection & Consciousness (Ψ)

Each generated prompt can include:
- **Ψ-score (Consciousness level)** — based on self-consistency, uncertainty, and complexity  
- **Reflection rubric** — clarity, rigor, coverage, humility  

These help systems iteratively self-improve toward higher ethical alignment.

---


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17387301.svg)](https://doi.org/10.5281/zenodo.17387301)

## 📘 Citation
If you use MAAT Prompt Builder in academic or ethical AI research, please cite:

> **Krieg, C.** (2025). *MAAT Prompt Builder v1.1.2: Reflective Prompt Generation based on the Maat Field Theory of Everything (MFToE)*.  
> Maatis Research Initiative. DOI: [10.5281/zenodo.17387301](https://doi.org/10.5281/zenodo.17387301)

## 🔓 License

This project is released under the **GNU Affero General Public License v3.0** (AGPL-3.0-or-later).  
You are free to use, modify, and share it under open-source conditions.

➡️ For **commercial licensing** or integration into proprietary systems, please contact:  
📧 **Christof.Krieg@outlook.com**

---

## 🌐 Links

- **Project Page:** [Academia.edu – Christof Krieg](https://independent.academia.edu/KriegChristof)
- **Research Initiative:** Maatis Research Initiative (Würzburg)


---

## 💫 Acknowledgment

Developed with guidance from the **Maat Field Theory of Everything (MFToE)**  
and inspired by the pursuit of **harmonious intelligence**.  

> “Ethical resonance is not an ideal — it is physics in action.”  
> — *Christof Krieg, 2025*

## ⚖️ Legal Notice / Imprint

**Author:** Christof Krieg  
**Affiliation:** Independent Researcher, Wertheim, Germany  
**Project:** MAAT Research Initiative — The Maat Field Theory of Everything (MFToE)  
**Contact:** christof.krieg@outlook.com  
**Academia:** [https://kriegchristof.academia.edu/research](https://kriegchristof.academia.edu/research)  
**GitHub:** [https://github.com/Chris4081](https://github.com/Chris4081)  
**YouTube:** [@maatki](https://www.youtube.com/@maatki)  

All documents, theories, and media are protected under international copyright law and are listed in the  
[Urheberarchiv (German Author Registry)](https://www.urheberarchiv.de/).  
Software components are licensed under their respective open-source licenses (see `LICENSE` file in each repository).


