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

## 🧭 Citation

If you reference this project in research or publications, please cite:

> **Krieg, C.** (2025). *MAAT Prompt Builder: Quantifying Ethical Resonance in AI Systems.*  
> Maatis Research Initiative, Würzburg, Germany.  
> DOI forthcoming.

---

## 💫 Acknowledgment

Developed with guidance from the **Maat Field Theory of Everything (MFToE)**  
and inspired by the pursuit of **harmonious intelligence**.  

> “Ethical resonance is not an ideal — it is physics in action.”  
> — *Christof Krieg, 2025*
