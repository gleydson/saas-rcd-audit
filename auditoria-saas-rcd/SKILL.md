---
name: auditoria-saas-rcd
description: Audit a SaaS product for conversion, activation, retention, and expansion using Revenue Centric Design (RCD) and behavioral science. Use when reviewing or improving a SaaS landing page, hero, pricing page/tiers, onboarding, empty states, dashboard, cancellation flow, lifecycle emails, feature adoption, or churn/activation/trial-conversion metrics; when asked to find improvement points, run a product/UX/growth/CRO audit, reduce churn, raise activation, fix pricing, or apply cognitive biases ethically to a product. Produces a prioritized, phase-aware audit with each finding tagged to a specific bias or principle.
license: MIT
---

# SaaS Audit — Revenue Centric Design (RCD)

Audit any SaaS so its design serves **user value AND revenue at the same time**. This skill turns a body of behavioral-design knowledge into a repeatable audit that surfaces concrete, prioritized improvement points — each tied to a named cognitive bias or principle, with a recommended fix.

> **Source & credit.** These frameworks synthesize public posts and articles by **Richard — "Design for startups" (@richardrx)**: Revenue Centric Design, the Swiss Knife Index, the 4 startup phases, GBB pricing, the feature filter, and more. The underlying science is credited to its originators (Kahneman & Tversky, Dan Ariely, Eugene Schwartz, Aronson & Mills, Nir Eyal, Fitts, Hick, Nielsen Norman Group). Apply persuasion **ethically** — see [Ethics gate](#ethics-gate).

## Core thesis

Neutral design is not "objective" — it is **omission**. An interface that does not deliberately guide attention makes the path to value longer and revenue harder. Good product design is never user-value *or* business-revenue; it is both, by construction. **Cognitive biases are the levers; the customer lifecycle is the map; the startup phase sets the priorities.**

## What this skill does

Given a SaaS (a URL, screenshots, a description, a codebase, or a specific surface like "our pricing page"), produce an **audit**: a prioritized list of improvement points, each with evidence, the bias/principle it violates, a concrete fix, and an effort×impact estimate. Works for a full audit or a focused one (just pricing, just onboarding…). For a focused request, still do Step 0–1 (phase + ICP) first — they reframe everything — then jump to the relevant stage.

## Audit workflow

Copy this checklist into your working notes and fill it in:

```
Audit progress:
- [ ] Step 0: Startup phase calibrated (ARR/MRR + priorities)
- [ ] Step 1: ICP clarity gated
- [ ] Step 2: Lifecycle walked (Acquisition → Activation → Retention → Monetization → Metrics)
- [ ] Step 3: 9 RCD principles scored
- [ ] Step 4: Master checklist run
- [ ] Step 5: Findings emitted in report template
```

### Step 0 — Calibrate to the startup phase → `references/startup-phases.md`
The most common failure is applying the wrong phase's advice (scale-stage growth loops on a survival-stage product). Establish ARR/MRR (or a best estimate) and set what matters:

| Phase | ARR band | Goal | Where design pays off |
|---|---|---|---|
| **Survival** | R$0–240k | Prove *someone pays* | Visual differentiation, trust layer, speed-to-value |
| **Traction** | R$240k–1.2M | *Luck or system?* | Behavioral: onboarding, TTV, value realization, upsell levers, churn control |
| **PMF** | R$1.2M–6M | *Prove scale* (users arrive, stay, refer) | Retention efficiency, margin |
| **Scale** | R$6M+ | Compete for *attention* | Continuous optimization + defensibility (network effects, data moat) |

### Step 1 — Gate on ICP clarity → `references/acquisition.md`
Everything downstream depends on a sharp, **underserved** ICP that: (a) feels the pain with real weight (the loss when unresolved is large), (b) is big enough (bottom-up TAM), (c) can pay the ticket your unit economics need, (d) has founder fit. A vague ICP ("anyone who wants the product") makes every later finding ambiguous and makes errors undiagnosable. **If the ICP is unclear, that is finding #1.**

### Step 2 — Walk the lifecycle
For each stage, read the matching reference + the matching checklist section, then record gaps.

| Stage | Read | Hunting for |
|---|---|---|
| Acquisition | `references/acquisition.md` | Hero fails the 5-sec test, jargon, generic CTA, no/weak proof, awareness mismatch, LP that doesn't qualify |
| Activation / Onboarding | `references/onboarding-activation.md` | No defined aha-moment, slow TTV, empty dashboard, passive tour, admin friction, journey gap |
| Retention / Churn | `references/retention-churn.md` | Expectation debt, jargon churn, dead cancellation flow, one-time-job model, reactive comms, low feature adoption, no habit loop, no moat |
| Monetization / Expansion | `references/pricing-expansion.md` | No decoy/anchor, >4 plans, free anchored at zero, bad defaults, weak upgrade path, upsell that interrupts instead of meeting a limit |
| Metrics / Experimentation | `references/metrics-experimentation.md` | Vanity metrics, underpowered A/B tests, blended LTV, inflated LTV:CAC, leaky-bucket math ignored |
| Product / Design strategy | `references/product-design-strategy.md` | Feature creep (Swiss Knife Index), no feature filter, cluttered dashboard, cosmetic-only refactors |

### Step 3 — Score the 9 RCD principles → `references/revenue-centric-design.md`
Rate each principle Pass / Partial / Fail with one sentence of evidence. This is the cross-cutting scorecard.

### Step 4 — Run the master checklist → `checklists/master-audit-checklist.md`
The comprehensive, phase-aware gap detector. Every concept from the corpus appears here. Each item is a yes/no check tagged with its bias/principle and a pointer to the reference for the fix.

### Step 5 — Emit findings → `assets/audit-report-template.md`
Fill the template: phase + ICP verdict, findings table (area · finding · evidence · bias/principle · severity · fix · effort×impact), top-5 quick wins, RCD scorecard.

## Navigation — which file answers which question

| Question | File |
|---|---|
| "What does each RCD principle mean and how do I check it?" | `references/revenue-centric-design.md` |
| "Which bias applies here / what's the study behind it?" | `references/cognitive-biases.md` |
| "Is the landing page / hero / copy / CTA / positioning right?" | `references/acquisition.md` |
| "Why do trials not activate? What onboarding pattern fits?" | `references/onboarding-activation.md` |
| "Why are people churning? How do I retain & build a moat?" | `references/retention-churn.md` |
| "How should pricing/tiers/defaults/upgrades be structured?" | `references/pricing-expansion.md` |
| "Is this metric or experiment trustworthy?" | `references/metrics-experimentation.md` |
| "Too many features? Cluttered dashboard? What to cut?" | `references/product-design-strategy.md` |
| "What should I prioritize at my stage?" | `references/startup-phases.md` |
| "Give me the full checklist." | `checklists/master-audit-checklist.md` |

## How to write recommendations

- **Be specific and quantified.** "Replace the hero headline 'A plataforma completa de produtividade' with one naming the ICP + outcome, e.g. 'Controle de comandas para oficina mecânica'" — not "improve the headline."
- **Tie every finding to a named bias or principle** (e.g. *Anchoring*, *Loss aversion*, *RCD #6 Defaults*). The "why" is what makes a recommendation persuasive and trustworthy.
- **Respect the phase.** Don't recommend scale-stage optimization to a survival-stage product. At survival, prioritize differentiation/trust/speed-to-value; at traction, behavioral onboarding & churn; later, retention efficiency & moat.
- **Prefer high-leverage fixes over cosmetics.** Pricing structure, defaults, and the onboarding sequence move metrics far more than button color. (1% better price ≈ 8–11% more profit vs ≈2% from 1% better acquisition — ProfitWell.) Flag "repaint" disguised as "refactor."
- **Quantify the leak when you can.** Use the leaky-bucket and cohort-LTV math in `references/metrics-experimentation.md` to translate a churn point into R$.

## Ethics gate

Persuasion here is for **clarity and momentum, not coercion**. Enforce these or the audit becomes a dark-pattern manual:
- **Defaults must be ethically defensible.** A pre-checked box that traps users into spend is churn bait and a ReclameAqui/refund risk — recommend defaults that match what an informed user of the ICP would choose.
- **Promise must equal proof** (RCD #4). Never recommend a claim the product can't demonstrate — that creates expectation debt and *causes* churn.
- **Scarcity/urgency must be real.** Recommend honest scarcity only (true limits, real deadlines), never fabricated countdowns.
- **Friction that qualifies ≠ friction that traps.** Add friction to qualify intent or deepen commitment; never to obstruct cancellation.

## Benchmarks quick-reference

Use as rough goalposts (mostly SaaS; some US data — adjust for the market). Sources in `references/`.

| Metric | Weak | OK | Strong | Note |
|---|---|---|---|---|
| Activation rate | <20% | 30–37% | 40%+ | <20% = structural onboarding/product problem |
| D7 retention | <10% | 10–15% | >30% | |
| Time-to-Value (TTV) | days | ~1d12h (median) | <5 min (top) | Userpilot, 547 cos. |
| NRR (B2B) | <100% | ~100% | >110% | Separates growth from leaky funnel |
| Trial→paid, card vs no-card | 8.9% (no card) | — | 31.4% (card) | Chartmogul 2026, US, 200 products |
| LTV:CAC | <3:1 | 3:1 | >3:1 | Recompute by cohort; blended overstates 30–50% |
| Swiss Knife Index | <0.3 | — | ≥0.3 | features used by >40% of actives/30d ÷ total |
| Pricing tiers | 1 or 5+ | — | 3 (2–4 max) | Hick's Law; decoy needs a middle plan |
| Reviews sweet spot | 5.0 (looks fake) | — | 4.2–4.5★ | Northwestern |

When citing a number, attribute the source and note it's a benchmark, not a guarantee.
