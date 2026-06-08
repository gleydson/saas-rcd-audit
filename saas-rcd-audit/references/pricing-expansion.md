# Pricing, monetization & expansion

> Price is the most under-used growth lever. **1% better price ≈ 8–11% more profit** (ProfitWell, typical SaaS margins) vs ≈2% from 1% better acquisition — the same 1% effort pays ~5× more. Yet when 1,500 execs were asked the most important growth lever, 70% chose acquisition (the lowest-return one). We value the opposite of where value lives.

**Contents:** [Pricing power](#pricing-power) · [Raising prices](#how-to-raise-prices) · [Decoy & the 3-plan architecture](#decoy--the-3-plan-architecture) · [Should you remove Free?](#should-you-remove-free) · [GBB](#gbb-goodbetterbest) · [Anchoring & build-from-the-middle](#anchoring--build-from-the-middle) · [Defaults](#defaults) · [Trial with or without card](#trial-with-or-without-card) · [Upgrade path](#upgrade-path) · [Price as filter & expansion](#price-as-filter--expansion-from-usage)

---

## Pricing power
Why founders avoid the 5× lever: acquisition is **visible** growth (a new lead shows on the dashboard, you can post "record signups"), while price gives you butterflies — touching it feels like it'll scare customers off, so nobody touches it. That's **loss aversion**: the fear of losing what you have shouts louder than the chance to earn more. So the founder hires another SDR, burns more on ads, fights for +1% top-funnel conversion, and leaves the lever that pays 5× more rusting in the garage. Acquisition matters — but if you've never sat down to price with method, your most powerful tool is idle.

## How to raise prices
- Check when you **last raised price** — if > 1 year and the product improved since, there's already a lag.
- Test the new price on **new clients only** (don't touch the existing base) and **measure conversion before deciding**: if the conversion drop is offset by the extra ticket, it's worth it.
- Consider **LTV impact**: users who pay more tend to churn *less* than those who paid cheap.
- Raise **small, anchored in value** — communicate what improved; don't throw the increase in the customer's face without context.
- **Forget A/B testing price** (you don't have the volume — ProfitWell is categorical on this). Do it **by segment** and by **willingness-to-pay survey**.

## Decoy & the 3-plan architecture
We decide by comparison; a clearly inferior option shifts choice toward the target (**decoy effect**). The Economist study (Ariely): adding a never-chosen print-only option at the same price as print+online pushed 84% to the bundle and added ~30–43% of subscription revenue (see `cognitive-biases.md`). Rules:
- The plan you want to sell most is the **middle**.
- The decoy must be **clearly inferior on one important attribute** (user limit, missing key integration, no priority support) — and not too close in price to the top plan, or the *top* plan wins by comparison.
- **Three plans** beat four or five — 4+ trips the paradox of choice; the user paralyzes and leaves.
- The **most expensive plan exists to anchor** — even if few buy Enterprise, it makes Pro look reasonable.
Most BR SaaS copy a competitor's pricing without understanding that each plan has a specific behavioral role. **Audit question:** what's the decoy of your plans today? If you can't answer, there probably isn't one, and your target plan is fighting the others instead of helping the user decide.

## Should you remove Free?
Listing **Free first anchors value at zero** — everything then looks expensive (anchoring). Pricing that converts shows the higher number first (a previous price, an Enterprise plan) so the target feels cheap. Instead of `Free / Pro R$99 / Enterprise` (user compares Free↔Pro), try `Starter R$79 (with irritating limits) / Pro R$99 / Enterprise` (user compares Starter↔Pro → Pro is obvious for +R$20). Documented tests show +10–20% conversion — not from changing the product, but from changing the comparison frame. With a Free plan, **you're competing against your own free plan, and losing.** (Caveat: at the right ICP, removing Free isn't always possible — judge by ICP.)

## GBB (Good/Better/Best)
A clean way to apply the decoy without overcomplicating:
1. **Good (the entry bait):** a simplified "budget" version. Role: a low-price anchor, but limited enough that the user feels "pain" and looks at the middle tier.
2. **Better (the target / core):** where you want ~80% of users to land. Role: maximize LTV; must look like a bargain vs Best and clearly superior to Good.
3. **Best (the value anchor):** fully loaded premium. Role: doesn't need to sell (great when it does) — it exists to make Better look cheap.
*Bicycle:* Good = aluminum frame, basic wheels; Better = aluminum frame, carbon wheels; Best = full carbon (3× the price). Without Best, Better seems expensive; with Best, Better seems like the smart choice.
**Golden rule of comparability:** never mix quantitative (10,000 tokens) with qualitative (priority support) — the brain can't compute that trade-off fast. Keep it linear: tokens vs tokens, support vs support. **Hick's Law:** 2–4 options max. **TLDR:** visual contrast (highlight Better with color/size/"Recommended" badge) + anchoring (an expensive plan frames the middle) + controlled comparison (choose the attributes that support *your* value, not your competitor's). **Stop letting the user do the math — do the math for them.**

## Anchoring & build-from-the-middle
The first number seen sets the reference. Jobs leaked iPad at $999, justified it, then revealed $499 — the audience felt a $500 *gain* (see `cognitive-biases.md`). In SaaS the anchor battle is your pricing table; every human decision is an if/else based on comparison.
- **Build pricing from the middle out.** The common error is designing the cheap plan and adding up. Invert it: design the **middle (ideal)** plan first — that's where unit economics close — then *remove* critical features to make the **Básico** (calculated pain/friction) and *add* premium features to make the **Anchor** (contrast).
- **Cross-modality anchoring:** a big benefit number ("10,000 fotos") next to a small price ("R$20/mês") makes the price feel smaller by cognitive osmosis.
- If your most expensive plan has no clear value-stacking logic, your anchor is styrofoam. Price design isn't about looking pretty — it's visual hierarchy of information to guide the decision.

## Defaults
Most people never change a setting; the default defines majority behavior (**status-quo bias** + cognitive-load reduction — deciding is expensive, the default is the lazy brain's easiest choice). Where to apply:
- **Default plan:** the pre-selected plan captures ~**60–80%** of choices — pre-select the one you want to sell.
- **Billing default annual:** switching the default from monthly to annual raises contracted MRR without changing price.
- **Default seat count** to the ICP's typical (e.g. start the selector at 5 if the median buys 5) — anchoring.
- **Reverse trial:** premium is the default, free is the opt-out — the user must actively give up what they already have.
Three rules: (1) the default must be **ethically defensible** — a checkbox trap becomes churn and a ReclameAqui/refund; (2) **smart defaults beat copy persuasion** — before rewriting a CTA, look at what's pre-selected on the critical screens; (3) a default acknowledges the user won't spend energy deciding what's trivial to you. You can spend your life optimizing copy, or change 5 defaults this weekend. (Reported: +60% average ticket and up to 4× LTV from default changes.)

## Trial with or without card
Trial-with-card converts ≈**31.4%** vs ≈**8.9%** without (Chartmogul 2026, US, 200 products) — 3×. But there's a hidden cost: asking for a card **reduces signups**, so you convert a higher % of *fewer* trials:
- No card: 1,000 visitors → 85 trials → ~7.5 payers (8.9%).
- Card: 1,000 visitors → 30 trials → ~9.4 payers (31.4%).
This is more evidence freemium is less effective than preached. **In Brazil, factor in PIX:** recurring-PIX customers tend to churn *more* than card customers. Don't ask which model converts most — ask which **attracts and retains the right ICP** (and some ICPs won't accept card-only).

## Upgrade path
A free user for 8 months who uses it weekly and recommends it but never upgrades is a **missing upgrade path**, not a product problem. The common strategies (usage limit, temporary discount, feature gate) all work but none works *well* without the right framing and a clear journey. Better levers:
- **Sunk cost:** remind them of accumulated investment — "You created 47 custom reports. On the free plan you lose access to 40." Now losing hurts.
- **Loss aversion:** "You'll lose access to 8 months of history" converts better than "Get unlimited history."
- **Limited access with correct timing:** gate at the imminence of a *known* result — "Your report is ready. To export as PDF, activate Pro." The work's done, the value is right in front of them, the barrier is minimal. **The timing/context of the gate matters more than the gate's existence.**
If upgrade rate is below ~5%, it's probably not price — it's the *way and timing* you're asking.

## Price as filter & expansion from usage
- **Price is a filter (RCD #9):** pricing decides who enters, how long they stay, and whether they expand; the wrong price attracts the wrong ICP. Make price visible early to filter unqualified leads (see `acquisition.md`).
- **Expansion is born from usage (RCD #8):** an upsell that interrupts creates resistance; an upgrade offered when the user hits a real limit converts without friction. Expansion follows perceived value, not a calendar.
