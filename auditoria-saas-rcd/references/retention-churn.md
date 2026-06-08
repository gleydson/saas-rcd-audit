# Retention & churn

> Churn doesn't start when the user cancels — it starts when they read your landing page. It's solved by interventions that **anticipate** abandonment before it becomes intent, not by reactive Customer Success (RCD A3). NRR > 110% (B2B) separates sustainable growth from a leaky funnel.

**Contents:** [Churn starts at the LP](#churn-starts-at-the-lp-expectation-debt) · [Churn as a language problem](#churn-as-a-language-problem) · [30-day churn = onboarding](#30-day-churn--onboarding) · [Cancellation screen](#the-cancellation-screen) · [One-time-job churn (JTBD)](#one-time-job-churn-jtbd) · [Proactive comms & NRR](#proactive-communication--nrr) · [Feature adoption](#feature-adoption) · [Attention hierarchy](#attention-hierarchy-organize-vs-direct) · [Redesign risk](#redesign-risk) · [The habit loop & moat](#the-habit-loop--moat-cs-is-a-tax)

---

## Churn starts at the LP (expectation debt)
If the LP promises one thing and the product delivers another, you've created **expectation debt** that charges interest every day the user thinks "this isn't quite what I expected." Three common mismatches:
- **Result promised vs tool delivered:** "Aumente suas vendas em 30%" → a metrics dashboard. The user bought a result, got a colorful spreadsheet.
- **Simplicity promised vs complexity delivered:** "Configure em 5 minutos" → 47 fields, 3 integrations, 20-min tutorial.
- **Wrong ICP:** LP speaks to a 2-person startup; product was built for a 15-person team at scale.
In all three the product can be excellent and it won't matter — the disappointment was pre-programmed. **Signal: high 30-day churn + OK NPS → the problem is what you promised, not the product.**

## Churn as a language problem
A technical founder writes the product and the sales page in jargon without noticing. The ICP buys on a leap of faith, then inside the product hits more jargon, never perceives value, accumulates small disappointments, and cancels. On the dashboard it looks like a missing feature or bad onboarding — it was a **discourse-vs-understanding** mismatch.
- **Curse of knowledge:** you know too much and forget the other doesn't.
- **Processing fluency:** simple language conveys more confidence and raises perceived competence.
**Audit move:** before reviewing onboarding and product, review the *language*.

## 30-day churn = onboarding
Most early-stage churn is in the first 30 days → it's onboarding, not features (adding features only adds complexity). Three diagnostic questions:
1. **Time to first real result?** Not "watched the full tutorial" — a result. If the answer is "it depends" or > 1 day, you're losing people.
2. **Does the user know where they are?** Progress bar, checklist, "you are here, X left." (**Endowed progress:** a user at 30% finishes more than one at 0% — starting at 0% is a design error.)
3. **What happens when they abandon mid-flow?** Email? Push? Nothing? Most teams only design the happy path. Use **Zeigarnik**: an incomplete task occupies mental space — remind them they started.
Sub-30-day churn is fixed with a *sequence* of value-first micro-interactions, not features (unless you literally promised the feature on the LP).

## The cancellation screen
The most ignored page in the product and one of the most important — the last conversation with someone leaving, usually handled as a Stripe-default "Are you sure?" Do three things:
1. **Show what they lose (loss aversion):** "You'll lose access to relationship data for your 476 clients and 8 months of history." Concrete loss outweighs abstract benefit; they don't know how much they invested until you show them.
2. **Offer an alternative before goodbye:** "Pause for 30 days instead?" / "Try one more month free." (ChatGPT does this well.)
3. **Collect the reason usefully:** an open question — "What was missing for you to stay?" — beats a dropdown that rarely lists the real reason.
You invested to bring the user here; invest the last 30 seconds to keep them.

## One-time-job churn (JTBD)
A product 4.2★ on the App Store with positive NPS but rising churn isn't a satisfaction problem — it's a **billing-model vs job-to-be-done** mismatch. A user who loves it and still cancels often just *finished the job*. Products hired for a one-off problem generate **structural churn**: resume builders, contract/legal-doc generators, data-migration tools, pitch-deck makers, due-diligence platforms. TurboTax solved this by **anchoring to an event that already recurs in the user's life** (tax season) instead of faking off-season engagement — the product became a ritual because the event makes the use inevitable. **Audit question:** if your product's job is done, what event in the user's life justifies returning? If there's no answer, it's a business-model problem, not a product problem.

## Proactive communication & NRR
Reactive improvement comms is a sneaky churn vector: a vendor only offered the newer product when the customer called to *complain* — by then they'd already evaluated 4 competitors and were ready to switch. When support offers a migration at the moment of cancellation, the damage is done — you've converted a clean expansion opportunity into emergency retention. Ship **proactive comms of new features/migrations to the existing base** (the lever behind NRR > 110%). **Audit question:** when you shipped the last relevant feature/version, how many *active* clients were actually told? (Not release emails nobody reads, not an Instagram post.)

## Feature adoption
You launch a feature, do a changelog, email the base, add a "new" badge — 3 weeks later 9% opened it, 4% used it twice. The killer is **inattentional blindness** (the user doesn't see what they're not looking for; they run their usual path and leave) plus **status-quo bias** (relearning cost outweighs perceived benefit even when the new way is better). Adoption is a *design* problem, not a comms problem. What works:
- **Contextual announcement** — surface the feature in the screen where it's used, not a login modal.
- **Directing empty state** — when the user enters a screen where the feature applies, the empty state shows it.
- **Triggered onboarding** — a micro-onboarding per important feature, fired by the behavior that signals need (CRM user on a sales page → present the AI that breaks objections).
- **Feature-adoption-rate metric** — measure whether it became a *habit* (used at the appropriate frequency in compatible windows), not whether it was clicked once.
- **Continuity criterion** — a feature that doesn't clear an adoption threshold goes under review: badly designed, wrong place, or nobody needs it.

## Attention hierarchy (organize vs direct)
"My interface is fine but people don't use the main features." The diagnosis is rarely isolated feature visibility — it's that the product was built to **organize information** when it should **influence behavior**. A product that organizes delivers *access*; a product that directs delivers *activation*. Well-designed attention hierarchy makes the user use what *retains*; bad hierarchy makes them use what's most *salient* — rarely the same thing. The most important feature hidden behind three clicks is a feature the user never gives those clicks to.

## Redesign risk
A redesign can kill a working product. Snapchat's Feb 2018 redesign (separating friends from creators — sensible on paper) triggered a 1.2M-signature petition, Kylie Jenner's "does anyone else not open Snapchat anymore?", and a stock drop. The cause was behavioral: users had built a **cognitive map** (where everything is, which gesture does what) that was part of the product even though no one designed it intentionally (like Tinder's swipe). An aggressive redesign asks the user to pay the relearning cost (**status-quo bias**) and signals you know better than they do what they should want. **Audit question:** what part of the product is so used that touching it would feel hostile? That part stays; you improve *around* it.

## The habit loop & moat ("CS is a tax")
If you need an army of CSMs to stop cancellations, the product failed — CS should be growth, not a churn plug. Your real competitor isn't the other startup; it's **boredom**, and boredom has infinite CAC. Mobile games solve this in three phases:

**Phase 1 — Sudden death (TTV vs cognitive load).** A wizard ("click here, configure that") asks for work before delivering value; the brain marks hostile territory in ~10 seconds. Games use progressive disclosure — let the user create/manipulate/see a result *before* asking for email or card (**Zeigarnik + endowment**: people value ~3× what they helped build). The empty state must sell the dream. *Test:* open the product in an incognito tab, time 120 seconds — did you feel perceived value without clicking "Next" on a tutorial? If not, onboarding is killing retention.

**Phase 2 — Retention is biology (the habit loop).** Passive software only reacts to clicks; daily login isn't the customer's discipline, it's the product's failure to create dependency. Games are proactive and use **variable rewards** — dopamine fires on *anticipation*, so predictable rewards (your monthly report) habituate fast while variable ones ("we detected an anomaly yesterday") keep the loop alive (same mechanism as slot machines and feeds, applied ethically). Turn validity metrics into **loss-aversion** triggers: not "see your performance" but "your team hit a record you haven't seen yet"; "sync in 24h or lose this week's benchmark." *Test:* your last 5 engagement emails — do they *inform* (dopamine 0) or *provoke curiosity* (dopamine high)? If a user can ignore them at no emotional cost, rewrite.

**Phase 3 — Defensive moat (social switching cost + network effect).** Single-player products die when the champion leaves the company — you built dependency on a person, not an organization. Make it multiplayer + accumulate a **data debt**: workflows where User A's work blocks/depends on User B; reports that aggregate 3 departments; when cancelling requires a Sales+Ops+Finance alignment meeting, you've reached negative churn by bureaucratic inertia. *Test:* your last 10 churns — how many were accounts with only 1 active user / 1 department? If > 30%, you have an architectural vulnerability, not a market problem.

**Final diagnosis.** If LTV:CAC < 3:1 you're spending marketing money to push a product that doesn't stand on its own organically. Behavior signals: dropout between minute 2–8 of onboarding = dopamine bleed (Phase 1); avg login 1.3×/week when it should be ~4×7 = habit failure (Phase 2); churn that kills the whole account when one employee leaves = single-player architecture (Phase 3). Stop blaming the customer — in the attention game, boring is bankruptcy.
