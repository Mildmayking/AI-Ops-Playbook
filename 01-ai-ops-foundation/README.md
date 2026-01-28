Module 01 — AI Ops Foundation
Purpose of This Module

This module establishes the foundational operating model for AI in IT Operations (AI Ops).
It defines what AI is allowed to do, what it is not allowed to do, and how humans remain accountable.

This module is intentionally principle-heavy.
All later modules (incident response, automation, governance, tooling) depend on the rules defined here.

How to Consume This Module

This module consists of:

Written documentation (this README) — authoritative reference

4 short videos — conceptual explanation and applied context

Diagrams — visual mental models used across the product

Rule:
Videos explain.
Documentation governs.

Module Videos


Video 01A — What AI Ops Is (and Is Not)
Conceptual framing and scope definition
https://share.synthesia.io/fc5bf771-3784-44e3-9e28-021c5e83f7a8

Video 01B — Human-in-the-Loop & Accountability
Why humans remain responsible in AI-assisted operations
https://share.synthesia.io/83062c5b-39a2-4a4f-bbb5-46ff3ed63e0e

Video 01C — AI Usage Risk Zones (Traffic-Light Model)
Operational safety boundaries for AI
https://share.synthesia.io/104a65d2-0871-4a15-8678-f580c95ed5e5

Video 01D — AI Ops Core Principles
The non-negotiable rules that govern every AI system
https://share.synthesia.io/35ac2298-3f7b-4bea-8827-7c89c3a9cba6


01.1 — What Is AI Ops (Correct Definition)

AI Ops is not autonomous IT.

AI Ops is the use of AI systems to assist, augment, and accelerate human operators across IT operations — while preserving human accountability, approval, and control.

AI Ops Is:

Pattern recognition across logs, metrics, and tickets

Decision support for incident response

Drafting scripts, runbooks, and remediation plans

Summarization of complex operational data

AI Ops Is Not:

Fully autonomous execution in production

Replacement for on-call engineers

A reason to weaken change control or access governance

Foundational rule:
AI can recommend and draft.
Humans decide and execute.

01.2 — Why AI Ops Requires a Different Operating Model

Traditional automation:

Executes deterministic logic

Fails predictably

Is fully auditable line-by-line

AI systems:

Are probabilistic

Can hallucinate

Can be confidently wrong

This introduces new classes of operational risk, including:

Silent misclassification

Over-trust in generated output

Drift between model behavior and business reality

Therefore: AI Ops must be governed differently than scripts or tools.

01.3 — Human-in-the-Loop Is Non-Negotiable

Every AI Ops system must define:

Where AI can suggest

Where humans must approve

Where AI is explicitly forbidden

There must always be:

A named human owner

A clear escalation path

A way to override or disable AI behavior

If no human is accountable, the system is unsafe.

01.4 — AI Usage Risk Zones (Traffic-Light Model)

This model defines where AI may operate and where it must never operate.

Traffic-Light Risk Zones for AI Usage
Zone	Risk Level	Description	Examples
Green	Low	Advisory only; human review required	Ticket summarization, log analysis, KB search
Yellow	Medium	AI drafts actions; no execution	Script drafting, remediation suggestions
Red	High	AI prohibited from acting	Access changes, prod deployments, firewall rules
Enforcement Rules

AI may recommend in Green and Yellow zones

AI may never execute in Red zones

Promotion between zones requires explicit governance approval

This table is referenced repeatedly in later modules and must remain unchanged.

01.5 — AI Ops Core Principles

These principles govern every AI-enabled operational system.

Principle 1 — Human Accountability

AI does not own outcomes.
Humans do.

Principle 2 — Explicit Boundaries

If AI’s allowed behavior is not written down, it is not allowed.

Principle 3 — Auditability

Every AI-generated output must be:

Traceable

Reviewable

Attributable

Principle 4 — Fail-Safe Defaults

If AI fails, the system must degrade safely — never silently.

Principle 5 — Reversibility

AI-driven recommendations must be reversible and overrideable.

01.6 — Foundational Architecture (Conceptual)

AI Ops architecture always includes:

Signal sources (logs, metrics, tickets)

AI reasoning layer

Human approval layer

Execution systems

Audit & feedback loop

AI never talks directly to production systems without human mediation.

(See diagram: ai-ops-foundation-architecture)

01.7 — What This Module Enables

After completing this module, you will be able to:

Design AI Ops systems safely

Explain AI risk to leadership

Set enforceable AI boundaries

Avoid over-automation failures

Prepare for governance and scale

01.8 — What Comes Next

Module 02 builds directly on these foundations and covers:

AI-assisted incident response

Decision support during outages

Preventing AI amplification during incidents

If Module 01 rules are ignored, Module 02 will fail.

Final Lock Statement

This module is authoritative.
Later modules do not redefine these rules — they apply them.
