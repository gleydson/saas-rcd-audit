# Metrics & experimentation

> Every interface change is a hypothesis; without a success metric you can't know what worked (RCD A1). But most early-stage tests can't prove anything — and most LTV math is computed in a way that lies.

**Contents:** [A/B testing pitfalls](#ab-testing-pitfalls) · [LTV by cohort](#ltv-by-cohort) · [LTV:CAC reality check](#ltvcac-reality-check) · [Vanity vs real metrics](#vanity-vs-real-metrics) · [The leaky bucket](#the-leaky-bucket-distribution-math) · [Cost of a churn point](#the-cost-of-a-churn-point)

---

## A/B testing pitfalls
Most A/B tests in small SaaS can't prove anything, yet the founder swaps the whole product on the result. To safely detect a 2% lift on an already-low conversion you need **thousands of visitors per variation** — traction-stage products rarely have that. They run a test for a week, see "variant B won by 12%," celebrate, and change everything. Two biases combine: **law of small numbers** (a tiny sample taken as representative) + **confirmation bias** (favoring what you already wanted to believe). ProfitWell is categorical that you should *not* A/B test price — never enough volume or context. How to treat tests:
- **Calculate required sample size before running** (free calculators exist). If you can't hit that floor in reasonable time, don't start.
- **Test big things** — headline, offer, pricing structure, onboarding. Big effects need less sample to appear.
- **Don't stop a test because the number looks pretty mid-way** (very common).
- **No volume → decide by qualitative research + judgment.** Five good interviews beat an underpowered A/B test.
**Audit question:** the last test that changed your product — did it have the sample to conclude, or did you swap everything on a week of noise?

## LTV by cohort
`ARPU / Churn` is the standard formula. It works for a mature product with stabilized churn — but in traction it **overstates LTV by 30–50%**. Churn in a young product is unstable: highest in the first ~90 days, falling as the base self-selects. Using the trailing-12-month average churn blends young cohorts (high churn) with mature ones (low churn), and that average describes *neither*. Example:
| | Churn | "LTV" |
|---|---|---|
| Blended formula (ARPU R$200, 8%) | 8% | **R$2,500** |
| Cohort 0–3 mo | 18% | R$1,111 |
| Cohort 3–6 mo | 10% | R$2,000 |
| Cohort 6+ mo | 5% | R$4,000 |
R$2,500 doesn't exist in your base — it's an average of different things shown as one. It matters because you use LTV to decide how much to spend on CAC; if it's inflated you authorize spend the business can't support (founder sees LTV:CAC 4:1 on the dashboard when it's really 2:1 by cohort). **Audit question:** does this LTV come from the general formula or from the last-6-months cohort? If it's the general formula on a product < 18 months old, recompute by cohort.

## LTV:CAC reality check
Target ≥ 3:1. Below it (recomputed by cohort), you're spending marketing money to push a product that doesn't stand on its own organically — fix retention before scaling acquisition. Measure **CAC by closed deal**, not by lead (see `acquisition.md`).

## Vanity vs real metrics
Measure the layer that predicts revenue, not the one that feels good (detail in `onboarding-activation.md`):
| Vanity | Real |
|---|---|
| Signups | Activation rate |
| Session time | Time to first useful action (+ repetition) |
| Onboarding completion | D7 retention |
| Feature clicks | Feature *adoption rate* (habit) |
| Lead count | CAC per closed deal |

## The leaky bucket (distribution math)
Building the product is the easy part; **distribution is the game.** To serve 2,500 customers/month you must capture that audience somewhere:
- At a 5% LP conversion (excellent — most sit at 1–2%) you need **50,000 visitors**.
- From ads at 3% creative CTR (excellent — most don't hit 1%) that's **1.6M impressions**.
- The part few calculate: at 20%/month churn, average lifetime is 5 months — you replace the whole base every 5 months. To hold 2,500 you lose 500/month, so you must replace **500/month just to stand still** = 10,000 visitors = ~333,000 impressions, every month, forever. And 20% churn at low ticket is optimistic; many operate at 40–50% — the bucket never fills.
To attract, convert, and retain at this level you must master non-obvious things at the intersection of dev, design, and marketing — none alone knows it all.

## The cost of a churn point
Few translate a churn point into accumulated LTV lost over 12 months. A finance SaaS at 25% monthly churn, ARPU R$120, 1,000 users needs **250 new users/month just to break even**; turn off paid traffic and it dies in ~4 months. Optimizing **5 points (25% → 20%) = ~R$72,000 more cash/year** — no price change, no extra acquisition. Work it without opening Figma:
1. Define the aha moment.
2. Measure time from signup to it (TTV).
3. Answer: how do I deliver it faster?
4. If you can't, break it into micro-wins.
5. Test, measure, repeat.
Use this math in audit findings to put a R$ figure on each leak.
