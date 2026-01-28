# Module 02 — AI in Incidents & Tickets

In **Module 02**, we explore how AI interacts with incidents and ticket workflows.  
This module teaches **safe integration of AI into operational processes**, ensuring that automation aids teams without introducing new risks.

---

## Table of Contents

1. [Introduction](#introduction)  
2. [Video Lessons](#video-lessons)  
3. [AI-Assisted Incident Workflows](#ai-assisted-incident-workflows)  
4. [Decision Support Models](#decision-support-models)  
5. [Failure Modes & Guardrails](#failure-modes--guardrails)  
6. [Diagrams](#diagrams)  
7. [Next Steps](#next-steps)

[⬅ Return to Module Index](../MODULE_INDEX.md)

---

## Introduction

AI can provide **incredible value during incidents**, but without defined guardrails:

- Signals may be misinterpreted  
- Automation may act unsafely  
- Teams can develop over-reliance

This module focuses on **decision support**, not decision replacement.

---

## Video Lessons

### 🎥 Video 02A — AI’s Role During Incidents

[▶ Watch Video 02A](https://share.synthesia.io/4bff33c0-6885-4e0f-aafa-6a985ac08b09)

**Diagram cue:** `ai-incident-lifecycle.png`  
> Observe where AI can safely interact in incident detection and resolution.

---

### 🎥 Video 02B — AI-Assisted Signal Triage

[▶ Watch Video 02B](https://share.synthesia.io/7134abf9-205f-41e3-a7ea-295e9466b940)

**Key Points:**

- Prioritize signals automatically  
- Flag anomalies for human review  
- Avoid full automation of critical incident escalation

**Diagram cue:** `ai-ticket-handling-flow.png`

---

### 🎥 Video 02C — Decision Support, Not Decision Making

[▶ Watch Video 02C](https://share.synthesia.io/b2c90503-811a-4a9b-9166-1a54a7daf24e)

**Principles:**

- AI provides probabilities, not guarantees  
- Humans remain the final decision authority  
- Define clear escalation points

**Diagram cue:** `documentation-feedback-loop.png`

---

### 🎥 Video 02D — Failure Modes & Guardrails

[▶ Watch Video 02D](https://share.synthesia.io/5dc8b3c6-33c3-4628-8351-7fbd31e8d879)

**Key concepts:**

- Recognize drift and bias in AI outputs  
- Implement friction for safe automation  
- Maintain logging, monitoring, and auditing of AI actions

**Diagram cue:** `ai-governance-operating-model.png`

---

## AI-Assisted Incident Workflows

- **Signal Detection:** AI monitors logs & metrics  
- **Ticket Creation:** AI drafts tickets for review  
- **Prioritization:** AI ranks incidents by impact  
- **Human Validation:** Humans approve AI’s suggested actions

> Diagram: `ai-ticket-handling-flow.png`

---

## Decision Support Models

- Advisory AI → generates recommendations  
- Execution AI → triggers automation **only within boundaries**  
- Human review is mandatory for high-risk actions

> Diagram: `ai-automation-boundary-flow.png`

---

## Failure Modes & Guardrails

| Mode | Risk | Guardrail |
|------|------|----------|
| Drift | AI output diverges from desired outcome | Review & rotate models |
| Overconfidence | AI automates too early | Human-in-loop approvals |
| Blind trust | Teams over-rely on AI | Continuous audit & feedback |

---

## Diagrams

All diagrams for this module are located in `diagrams/`:

- `ai-incident-lifecycle.png`  
- `ai-ticket-handling-flow.png`  
- `documentation-feedback-loop.png`  
- `ai-automation-boundary-flow.png`  
- `ai-governance-operating-model.png`  

> Click diagram name to view full-size images.

---

## Next Steps

After completing Module 02:

1. Proceed to [Module 03 — AI Automation & Autonomy](../MODULE_03_AI_AUTOMATION/README.md)  
2. Use diagrams alongside videos for better understanding  
3. Return to Module Index anytime: [⬅ Return to Module Index](../MODULE_INDEX.md)

