# Revenue Centric Design (RCD) — the 9 principles

> RCD is the spine of this audit. The premise: design must deliver **value to the user AND revenue to the business at the same time** — not one at the expense of the other. Score each principle **Pass / Partial / Fail** with one line of evidence; the result is your cross-cutting scorecard.

Originated by Richard (@richardrx). The list below is the canonical 9, followed by three auxiliary principles from the earlier draft that are worth checking too.

---

## 1. Neutrality is omission
**An interface that doesn't deliberately direct attention hurts conversion.** "Neutral" / "we just show the options objectively" is a decision *not* to guide — and the path to value gets longer. Every screen has a primary action; if it competes with six other elements, it's invisible.
- **Check:** Does every key screen have ONE visually dominant primary action? Is the most important thing also the most salient (size, contrast, position)?
- **Fail signs:** primary CTA buried in a dropdown or bottom-right dead zone; dashboards where everything has equal weight.
- **Fix → `acquisition.md` (contrast/layout), `product-design-strategy.md` (attention hierarchy, dashboards).**

## 2. Who speaks to everyone convinces no one (ICP)
**A product without a defined ICP creates generic value; generic value is worth less and retains worse.** Pivoting the product is cheaper than pivoting the base — choose a niche deliberately.
- **Check:** Can you name the underserved ICP in one sentence? Does the product/copy speak its native language?
- **Fail signs:** "for any business," generic category claims, feature lists instead of an audience.
- **Fix → `acquisition.md` (ICP gate).**

## 3. Value before the ask (value before doubt)
**The promise is fulfilled over time, but proof of value must arrive before the user questions whether they chose right.** Deliver a win, then ask for effort/payment.
- **Check:** How many seconds/steps from signup to first real value? Does onboarding teach mechanics or deliver an outcome?
- **Fail signs:** empty dashboard on first login; "explore our product"; payment/effort demanded before any win.
- **Fix → `onboarding-activation.md`.**

## 4. Promise is the size of the proof
**The market believes what you demonstrate, not what you claim.** Any promise is allowed *if* you can prove it (testimonial, published number, unique-mechanism logic). Over-promising creates **expectation debt** that compounds into churn.
- **Check:** Does each headline claim have visible proof near it? Does the product deliver what the LP promised (result vs tool, simple vs complex, right ICP)?
- **Fail signs:** "increase sales 30%" backed only by a metrics dashboard; "setup in 5 minutes" that takes 47 fields.
- **Fix → `acquisition.md` (proof), `retention-churn.md` (expectation debt).**

## 5. Same competes on price; different competes by category
**With a unique angle you compete by category and keep margin. Without contrast, you compete on price.** Contrast can live in the mechanism, the narrative, or the experience — not only the feature set.
- **Check:** What is the single contrast that makes this not-a-commodity? Is it legible on the LP and in the product?
- **Fail signs:** positioning identical to competitors; the only lever left is discounting.
- **Fix → `acquisition.md` (positioning, narrative), `pricing-expansion.md`.**

## 6. A default is a decision you made for the user
**Most people never change settings; the initial state defines majority behavior.** Defaults beat copy persuasion — the lazy brain takes the path you set.
- **Check:** What's pre-selected on pricing (plan? annual vs monthly?), seats, notifications, trial type? Do defaults serve the user *and* the business?
- **Fail signs:** target plan not pre-selected; monthly billing default when annual is better for both; no reverse trial considered.
- **Ethics:** defaults must be defensible (see SKILL ethics gate).
- **Fix → `pricing-expansion.md` (defaults), `cognitive-biases.md` (status-quo bias).**

## 7. Retention is built, not asked
**Show users what they've accumulated; perceived loss retains more than promised benefit.** Don't beg with reactive CS — engineer accumulated value (data, customizations, history, light network) that makes leaving feel like loss.
- **Check:** Does the product surface accumulated value ("you created 47 reports")? Is there a switching cost the user can *feel*?
- **Fail signs:** no sense of sunk investment; cancellation that lists nothing the user would lose.
- **Fix → `retention-churn.md` (loss framing, moat), `cognitive-biases.md` (endowment, sunk cost).**

## 8. Expansion is born from usage
**Upsell that interrupts creates resistance; an upgrade offered at the moment the user hits a real limit converts without friction.** Expansion follows perceived value, not a calendar.
- **Check:** Is the upgrade prompt triggered by usage/limit (e.g. "your report is ready — export PDF on Pro") or pushed at random?
- **Fail signs:** modal upsells unrelated to current action; discounts as the only upgrade lever.
- **Fix → `pricing-expansion.md` (upgrade path, expansion).**

## 9. Price is a filter
**Pricing decides who enters, how long they stay, and whether they expand. Wrong price attracts the wrong ICP.** Price is the most under-used growth lever (1% better price ≈ 8–11% more profit).
- **Check:** Was price set with method (value/segment/willingness-to-pay) or copied from a competitor? Is price visible early to filter unqualified leads?
- **Fail signs:** price set by gut or competitor-matching; hidden price that wastes sales calls on unqualified leads.
- **Fix → `pricing-expansion.md` (pricing power, price-as-filter).**

---

## Auxiliary principles (from the earlier RCD draft — also worth checking)

- **A1. Everything is a hypothesis.** Each interface change is a hypothesis; without a success metric you can't know if it worked. → `metrics-experimentation.md`.
- **A2. Remember the Swiss Knife.** Every added feature raises the learning curve, cognitive load, and maintenance cost; past a peak, each new feature *reduces* perceived utility. Find your ideal. → `product-design-strategy.md`.
- **A3. Cancellation begins after signup.** Churn isn't solved by reactive Customer Success; it's solved by interventions that anticipate abandonment before it becomes intent. → `retention-churn.md`.

## Using the scorecard
For the audit report, render a 9-row table: principle · Pass/Partial/Fail · one-line evidence · top fix. A product can have a beautiful UI and still fail RCD (e.g. neutral, ICP-less, proof-less) — that's exactly the gap this skill exists to expose.
