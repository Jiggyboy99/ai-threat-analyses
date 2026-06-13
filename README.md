# AI Threat Analyses

A growing collection of real-world AI/ML security incident breakdowns — each one documenting how the attack worked, mapping it to industry threat frameworks (NIST, OWASP LLM Top 10, MITRE ATLAS), and outlining the defenses that apply.

The goal: study how AI systems actually get attacked in the wild, and build the habit of analyzing each incident the way a security professional would.

---

## 📂 Analyses

| # | Incident | Year | Threat Class | Frameworks |
|---|----------|------|--------------|------------|
| 01 | [Bing Chat "Sydney" Prompt Leak](./01-bing-chat-sydney-prompt-injection) | 2023 | Prompt Injection → System Prompt Leakage | OWASP LLM01 / LLM07 · MITRE AML.T0051.000 |

*More analyses added regularly.*

---

## 🧭 How each analysis is structured

Every write-up follows the same professional format:

- **Incident at a glance** — the facts in one table
- **Timeline** — how the event unfolded
- **What happened** — plain-English summary
- **How the attack worked** — the technical mechanism, with diagrams
- **Threat mapping** — NIST family + OWASP LLM code + MITRE ATLAS technique
- **Impact** — who was affected and how
- **Defenses & mitigations** — what stops it
- **Sources** — every claim is referenced

---

## 🛠️ Frameworks referenced

- **NIST** adversarial ML attack families — Evasion, Poisoning, Privacy, Abuse
- **OWASP Top 10 for LLM Applications (2025)**
- **MITRE ATLAS** — Adversarial Threat Landscape for Artificial-Intelligence Systems

---

<div align="center">
<sub>Independent security research · for educational and portfolio purposes</sub>
</div>
