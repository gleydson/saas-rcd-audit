# auditoria-saas-rcd

> An Agent Skill that audits a SaaS for **conversion, activation, retention, and expansion** using **Revenue Centric Design (RCD)** and behavioral science — and returns a prioritized, phase-aware list of improvement points, each tied to a named cognitive bias or principle.

Point it at a landing page, a pricing page, an onboarding flow, a dashboard, a cancellation screen, or a whole product, and it produces an audit: what's wrong, *why* (the bias/principle), a concrete fix, and an effort×impact estimate — anchored by a comprehensive checklist that covers every concept it knows.

## Install

Via [skills.sh](https://skills.sh) / the Agent Skills CLI (works with Claude Code, Cursor, Copilot, Codex, and more):

```bash
npx skills add gleydson/auditoria-saas-rcd
```

Or manually (Claude Code, personal skills):

```bash
git clone git@github.com:gleydson/auditoria-saas-rcd.git
ln -s "$(pwd)/auditoria-saas-rcd/auditoria-saas-rcd" ~/.claude/skills/auditoria-saas-rcd
```

## Use

The skill triggers on requests like:

- "Audit our SaaS / run a product/UX/growth/CRO audit and find improvement points."
- "Why is our trial not converting?" · "Reduce our churn." · "Raise activation."
- "Review our landing page / hero / pricing tiers / onboarding / dashboard / cancellation flow."
- "Help me design pricing that converts."

It runs a 6-step workflow: calibrate to the **startup phase** → gate on **ICP** → walk the **lifecycle** (Acquisition → Activation → Retention → Monetization → Metrics) → score the **9 RCD principles** → run the **master checklist** → emit findings in a report template.

## What's inside

```
auditoria-saas-rcd/
├── SKILL.md                         # workflow, navigation, benchmarks, ethics gate
├── references/
│   ├── revenue-centric-design.md    # the 9 RCD principles as audit lenses
│   ├── cognitive-biases.md          # ~28 biases: study · SaaS application · red flags
│   ├── acquisition.md               # ICP, hero/5-sec test, awareness stages, CTA, trust, PLG
│   ├── onboarding-activation.md     # TTV, aha moment, empty states, friction, journey gap
│   ├── retention-churn.md           # expectation debt, cancellation, JTBD, habit loop, moat
│   ├── pricing-expansion.md         # pricing power, decoy, GBB, anchoring, defaults, upgrades
│   ├── metrics-experimentation.md   # A/B sample size, cohort LTV, leaky bucket
│   ├── product-design-strategy.md   # Swiss Knife Index, feature filter, dashboards
│   └── startup-phases.md            # the 4-phase contextual lens
├── checklists/
│   └── master-audit-checklist.md    # the comprehensive, phase-aware gap detector
└── assets/
    └── audit-report-template.md     # the output format
```

## Frameworks covered

Revenue Centric Design (9 principles) · Swiss Knife Index & the 2-layer feature filter · the 4 startup phases · GBB (Good/Better/Best) pricing · the decoy effect & anchoring (build-from-the-middle) · the 5 stages of awareness · the habit loop & defensive moat · cohort LTV & the leaky bucket · and a catalog of ~28 cognitive biases applied to SaaS.

## Credit & sources

The frameworks here **synthesize the public posts and articles of [Richard — "Design for startups" (@richardrx)](https://x.com/richardrx)**, who originated Revenue Centric Design, the Swiss Knife Index, the 4 startup phases, the feature filter, and the GBB articulation used here. Please follow and credit the original author.

Underlying behavioral science is credited to its researchers: Kahneman & Tversky (loss aversion, anchoring, peak-end), Dan Ariely (decoy effect), Eugene Schwartz (stages of awareness), Aronson & Mills (effort justification), Nir Eyal (Hooked / variable rewards), Fitts, Hick, and the Nielsen Norman Group. Benchmarks cite ProfitWell, Chartmogul, Userpilot, Northwestern, VWO, Yotpo, BrightLocal, and Stanford as noted in the reference files.

Apply the persuasion techniques **ethically** — the skill enforces an ethics gate (defaults must be defensible, promises provable, scarcity real, friction must qualify rather than trap).

## License

[MIT](LICENSE) for this synthesis and packaging. The underlying ideas belong to their original authors (see above).
