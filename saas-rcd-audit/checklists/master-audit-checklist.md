# Master audit checklist

The comprehensive gap detector. **Every item is phrased so that a "No" is a finding.** Each carries a `[bias/principle]` tag and a → pointer to the reference with the fix. Work top-down: foundations first (they reframe everything), then the lifecycle, then the RCD scorecard.

**How to use:** mark each ✅ / ⚠️ / ❌. For every ❌ or ⚠️, write a finding in `assets/audit-report-template.md` (evidence · bias/principle · fix · effort×impact). Don't treat every section equally — use the phase key.

### Phase-priority key (focus where it pays at this stage)
| Phase | Lead with sections |
|---|---|
| **Survival** (R$0–240k) | 0 Foundations · 1 Acquisition (esp. trust) · 2 (value-before-ask part) |
| **Traction** (R$240k–1.2M) | 2 Activation · 3 Retention · 4 Pricing · 5 Metrics |
| **PMF** (R$1.2M–6M) | 3 Retention · 5 Metrics (cohort) · 6 Product · 4 Expansion |
| **Scale** (R$6M+) | 5 Experimentation · 3 Moat · 6 Optimization |

---

## 0. Foundations — phase & ICP
- [ ] **Startup phase identified** (ARR/MRR known) and priorities set to it? `[Phases]` → startup-phases.md
- [ ] **ICP nameable in one sentence** — a specific, underserved niche, not "everyone who wants it"? `[RCD #2]` → acquisition.md
- [ ] ICP **feels the pain with real weight** (large loss when unresolved)? `[ICP]`
- [ ] ICP has **enough size** (bottom-up TAM closes)? `[ICP]`
- [ ] ICP **can pay** the ticket your unit economics need? `[ICP / RCD #9]`
- [ ] **Founder fit / domain advantage** present? `[ICP]`
- [ ] Errors are **diagnosable** (you can tell product vs copy vs channel vs price vs audience apart)? `[ICP]`

## 1. Acquisition & landing
- [ ] Hero passes the **5-second test** (what / for whom / why care)? `[Cognitive load]` → acquisition.md
- [ ] Headline says **what it does in the customer's language** (no jargon)? `[Processing fluency]`
- [ ] Subheadline nails **ICP + concrete result**? `[Specificity]`
- [ ] **Problem-first**, not feature-first? `[Construal level]`
- [ ] **Specific over generic** ("comandas pra oficina" not "gestão")? `[Specificity]`
- [ ] **Real product screenshot** (not a generic illustration)? `[Aesthetic-usability]`
- [ ] **Immediate, specific, verifiable social proof** above the fold? `[Social proof]`
- [ ] Ratings in the **4.2–4.5 sweet spot** (not suspiciously perfect)? `[Social proof]`
- [ ] Message **matches incoming traffic's awareness stage**? `[5 stages of awareness]`
- [ ] **CTA answers the 3 pre-click questions** + has a click-trigger? `[Outcome bias]`
- [ ] **Primary action visually dominant** (contrast/size/position, within the F-pattern)? `[RCD #1 / Fitts]`
- [ ] **Trust layer on the first/login screen** (signals of security)? `[Aesthetic-usability]`
- [ ] **LP qualifies before the form** (specific copy / visible price / qualification)? `[CAC-as-filter]`
- [ ] **Price visible** early enough to filter unqualified leads? `[RCD #9]`
- [ ] **CAC measured per closed deal**, not per lead? `[Metrics]`
- [ ] A **single clear differentiator** (mechanism / narrative / experience)? `[RCD #5]`
- [ ] A **truthful narrative** (Character→Desire→Obstacle→Transformation)? `[Narrative bias]`
- [ ] **Not cargo-culting** a competitor's page (research, not pixels)? `[Cargo cult]`
- [ ] If claiming **PLG**, do the 4 preconditions actually hold? `[PLG]`
- [ ] First ~10 users **charged / validated with real payment**? `[First-10]`

## 2. Activation & onboarding
- [ ] **Aha moment defined empirically** (what payers did that churned users didn't)? `[Aha]` → onboarding-activation.md
- [ ] **TTV measured** and trending toward minutes, not days? `[TTV]`
- [ ] Measuring **activation rate** (not signups)? `[Vanity metrics]`
- [ ] Measuring **time-to-first-useful-action** (not session time)?
- [ ] Measuring **D7 retention** (not onboarding completion)?
- [ ] Onboarding is **active** (learn by doing), not a passive tour/docs? `[Active onboarding]`
- [ ] **First action obvious, immediate, single** (not 8, not a 12-step tour)? `[RCD #3]`
- [ ] **Empty state sells the dream** (sample/demo data, never "0 data")? `[Endowment]`
- [ ] **Progress visible, starts at ~20%**, not 0%? `[Endowed progress]`
- [ ] **Open loops + re-engagement** when the user abandons mid-flow? `[Zeigarnik]`
- [ ] A **peak/celebration at the first real win** (not just confirmation)? `[Peak-end]`
- [ ] Onboarding **sells the outcome, not the mechanics**? `[RCD #3]`
- [ ] **Declarative friction** (intent declaration) present; administrative friction removed? `[Effort justification]`
- [ ] Friction placed where it **qualifies** (trial card / demo), not where it obstructs? `[Effort justification]`
- [ ] Plan **pre-selected/personalized** from collected info (not "which plan?")? `[RCD #6]`
- [ ] **Journey gap mapped** (assumed journey vs 5 session replays)? `[Journey gap]`
- [ ] Trial-conversion losses diagnosed (empty dashboard / lost-before-value / lost-in-life)?
- [ ] Aha involves a **light network action** (invite/share/comment) where possible? `[Network]`

## 3. Retention & churn
- [ ] LP **promise == product delivery** (no expectation debt)? `[RCD #4]` → retention-churn.md
- [ ] **Language/jargon audited** (ICP understands inside the product)? `[Curse of knowledge]`
- [ ] 30-day churn treated as an **onboarding sequence**, not "more features"?
- [ ] Cancellation screen **shows what's lost**? `[Loss aversion]`
- [ ] Cancellation **offers an alternative** (pause / extra month) before goodbye?
- [ ] Cancellation **collects the reason as an open question**?
- [ ] If a one-time-job product: a **recurring life-event anchor** (ritual) exists? `[JTBD]`
- [ ] **Proactive comms** of new features/migrations to the active base? `[NRR]`
- [ ] **NRR tracked and > ~110%** (B2B)? `[Metrics]`
- [ ] Feature adoption driven by **design (contextual/triggered)**, not login modals? `[Inattentional blindness]`
- [ ] **Feature-adoption-rate** measured as habit + a continuity criterion in place?
- [ ] **Accumulated value surfaced** to the user ("you created 47…")? `[RCD #7 / sunk cost]`
- [ ] A **felt switching cost / data debt** exists? `[Endowment]`
- [ ] **Multiplayer/network workflows** (not single-player champion-leaves risk)? `[Social switching cost]`
- [ ] **< 30% of churn** is single-user / single-department accounts? `[Moat]`
- [ ] Attention hierarchy **directs to what retains** (not just organizes)? `[RCD #1]`
- [ ] **Heavily-used surfaces protected** from hostile redesign? `[Status quo]`
- [ ] Habit loop uses **variable/curiosity rewards** (not ignorable info emails)? `[Variable rewards]`
- [ ] **Behavior signals watched** (min 2–8 dropout; login frequency; account-killing churn)?

## 4. Pricing, monetization & expansion
- [ ] Price set **with method** (value/segment/WTP), not gut or competitor-copy? `[RCD #9]` → pricing-expansion.md
- [ ] **Last price increase < ~1 year** ago given product improvements? `[Pricing power]`
- [ ] **3 plans (2–4 max)**, not 1 or 5+? `[Paradox of choice / Hick]`
- [ ] A **defined decoy** makes the target (middle) plan obvious? `[Decoy]`
- [ ] An **anchor (top) plan** with clear value-stacking? `[Anchoring]`
- [ ] Pricing **not anchored at zero** (Free listed first)? `[Anchoring]`
- [ ] Pricing **built from the middle out**? `[Anchoring]`
- [ ] Comparisons **like-with-like** (no quantitative vs qualitative mix)? `[GBB golden rule]`
- [ ] **Target plan visually highlighted** ("Recommended")? `[RCD #1]`
- [ ] **Controlled comparison table** (attributes that support your value)? `[Framing]`
- [ ] **Cross-modality anchoring** used (big benefit # next to small price)? `[Anchoring]`
- [ ] **Target plan pre-selected** as default? `[RCD #6]`
- [ ] **Billing default = annual** (where it serves both)? `[Defaults]`
- [ ] **Seat/quantity default = ICP typical**? `[Anchoring]`
- [ ] **Reverse trial considered** (premium default, free opt-out)? `[Defaults]`
- [ ] Defaults **ethically defensible** (no checkbox traps)? `[Ethics]`
- [ ] Trial model (**card / no-card / PIX**) chosen by ICP fit + retention, not just conversion? `[Effort justification]`
- [ ] Upgrade path uses **sunk-cost / loss-aversion** framing? `[Sunk cost / loss aversion]`
- [ ] Gates **timed at the moment of a known result**? `[Loss aversion]`
- [ ] Upsell **triggered at a real usage limit** (not interrupting)? `[RCD #8]`
- [ ] **Upgrade rate ≥ ~5%** (else fix framing/timing, not price)?

## 5. Metrics & experimentation
- [ ] Each interface change has a **success metric** (it's a hypothesis)? `[RCD A1]` → metrics-experimentation.md
- [ ] A/B tests **sized before running** (sample-size floor)? `[Law of small numbers]`
- [ ] Tests **not stopped early** on pretty mid-points? `[Confirmation bias]`
- [ ] **Big things tested** (headline/offer/pricing/onboarding), not button color?
- [ ] **Qualitative research** used when volume is low (5 interviews > weak test)?
- [ ] **LTV computed by cohort** (not blended ARPU/Churn) for products < 18 mo? `[Cohort LTV]`
- [ ] **LTV:CAC ≥ 3:1** recomputed by cohort? `[Metrics]`
- [ ] **Real metrics over vanity** (activation / D7 / value realization)?
- [ ] **Leaky-bucket math known** (replacement need at current churn)?
- [ ] **Each churn point translated to R$** (to prioritize)?

## 6. Product & design strategy
- [ ] **Swiss Knife Index ≥ 0.3** (features used by >40%/30d ÷ total)? `[Swiss Knife]` → product-design-strategy.md
- [ ] New features pass the **2-layer feature filter**? `[Feature filter]`
- [ ] **"What will I kill to make room?"** asked for each new feature? `[Swiss Knife]`
- [ ] Low-use features **hidden (not deleted)**, kept for the 3%?
- [ ] Could you **name the one feature** to show in a 30-second sell?
- [ ] **Tactical/aesthetic layer cared for** (not the default AI UI-kit)? `[Design drivers]`
- [ ] Redesigns are **refactors** (solve a problem), not **repaints**? `[Refactor vs repaint]`
- [ ] Dashboard: defined "who" · cut cognitive tax · insights>raw · "so what?" test · contrast guides eye · rounded numbers · grouped by context · size/position hierarchy · human tone? `[Dashboard]`

## 7. RCD principles scorecard
- [ ] **#1 Neutrality is omission** — the interface deliberately directs attention?
- [ ] **#2 ICP** — speaks to a specific underserved niche?
- [ ] **#3 Value before the ask** — proof of value before effort/payment?
- [ ] **#4 Promise = proof** — every claim is demonstrated?
- [ ] **#5 Differentiate by category** — clear contrast, not price-only?
- [ ] **#6 Defaults** — initial state set intentionally and ethically?
- [ ] **#7 Retention is built** — accumulated value surfaced?
- [ ] **#8 Expansion from usage** — upsell at the limit?
- [ ] **#9 Price is a filter** — price set with method, filters the ICP?
- [ ] **A1** everything is a hypothesis · **A2** Swiss Knife respected · **A3** cancellation anticipated?

## Ethics gate (must all hold)
- [ ] Defaults defensible · promises provable · scarcity real · friction qualifies (never traps)? → SKILL ethics gate
