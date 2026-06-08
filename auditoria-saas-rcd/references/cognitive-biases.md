# Cognitive biases catalog (the levers)

Each entry: **what it is** · *Study/example* (from the corpus) · **Apply in SaaS** · **Red flags** to look for in an audit. Tag every audit finding with the bias it exploits or violates.

> **Ethics:** these are levers for clarity and momentum, not coercion. See the SKILL ethics gate.

**Index**
- Pricing & choice: [Anchoring](#anchoring) · [Decoy effect](#decoy-effect) · [Paradox of choice / Hick's Law](#paradox-of-choice--hicks-law) · [Cognitive load / Fitts's Law](#cognitive-load--fittss-law) · [Diminishing marginal utility of money](#diminishing-marginal-utility-of-money) · [Status-quo bias & defaults](#status-quo-bias--defaults)
- Conversion & trust: [Loss aversion](#loss-aversion) · [Social proof](#social-proof) · [Scarcity](#scarcity) · [Framing effect](#framing-effect) · [Construal level theory](#construal-level-theory) · [Outcome bias](#outcome-bias) · [Processing fluency](#processing-fluency-easy-speech) · [Curse of knowledge](#curse-of-knowledge) · [Narrative bias](#narrative-bias) · [Mere-exposure effect](#mere-exposure-effect) · [Aesthetic-usability / credibility](#aesthetic-usability--credibility)
- Activation & habit: [Zeigarnik effect](#zeigarnik-effect) · [Endowed progress](#endowed-progress-effect) · [Peak-end rule](#peak-end-rule) · [Endowment / IKEA effect](#endowment--ikea-effect) · [Effort justification](#effort-justification) · [Variable rewards / dopamine](#variable-rewards--dopamine) · [Inattentional blindness](#inattentional-blindness)
- Retention & moat: [Sunk cost](#sunk-cost-effect) · [Social switching cost + network effect](#social-switching-cost--network-effect)
- Reasoning traps (for *your* decisions): [Law of small numbers](#law-of-small-numbers) · [Confirmation bias](#confirmation-bias) · [Cargo cult](#cargo-cult)

---

## Pricing & choice

### Anchoring
The first number seen sets the reference point for everything after.
*Example:* Jobs "leaked" iPad at $999, justified it on stage, then revealed $499 — the audience felt a $500 *gain*, not a $500 spend (Tversky & Kahneman). 
**Apply:** show the expensive plan/anchor first; don't list "Free" first (it anchors value at zero, making everything else feel expensive). Build pricing **from the middle out** (design the target plan; strip features to make the cheap plan, add to make the anchor). **Cross-modality:** a big benefit number ("10,000 photos") next to a small price ("R$20/mo") makes the price feel smaller.
**Red flags:** pricing in ascending order starting at Free; the most expensive plan has no clear value-stacking logic ("styrofoam anchor").

### Decoy effect
A clearly inferior option shifts choice toward the target option (we decide by comparison).
*Study:* Ariely, The Economist, 100 MIT students. A: online $59 → 16%; B: print $125 → 0%; C: print+online $125 → 84%. Remove the never-chosen B and C drops to 32% (A 68%). The decoy added ~30–43% subscription revenue.
**Apply:** the plan you want to sell is the **middle**; add a decoy that's clearly worse on one important attribute (fewer seats, no key integration, no priority support) near the target's price. The top plan anchors; the decoy makes the target obvious.
**Red flags:** no plan plays the decoy role; the "cheap" plan is too close in price to the top plan (then the top plan wins by comparison).

### Paradox of choice / Hick's Law
Decision time and effort rise with the number of options; too many options paralyze.
**Apply:** 3 plans work better than 4–5; keep options to **2–4 max**. 8 plans isn't freedom, it's anxiety → closed tab.
**Red flags:** 5+ tiers; long feature matrices mixing quantitative (tokens) with qualitative (support) attributes — keep comparisons like-with-like (tokens vs tokens).

### Cognitive load / Fitts's Law
Every element adds surface to process; target acquisition time is a function of distance and size (Fitts). The F-pattern (Nielsen Norman) governs where eyes go.
**Apply:** make the primary action bigger, higher-contrast, and where the eye already is; cut anything that competes. Clarity beats cleverness at the top of the funnel.
**Red flags:** primary CTA in the bottom-right dead zone or inside a dropdown; dense screens where everything has equal weight.

### Diminishing marginal utility of money
A benefit-in-kind often beats equivalent cash; cash makes a transaction feel transactional.
*Example:* Dropbox gave **500MB**, not $20 — and the reward deepened product usage.
**Apply:** referral/loyalty rewards as product value (storage, credits, features), not cash.
**Red flags:** "refer a friend, earn R$20" framed around the referrer (see Framing).

### Status-quo bias & defaults
People prefer the current state when the gain from changing seems small vs the cost of relearning; most never change a setting.
*Study:* opt-out organ donation ≈ **6×** more registered donors than opt-in (Science, 2003); Austria ~100% vs Germany ~12%. The difference is one pre-checked box.
**Apply:** pre-select the target plan (defaults capture ~60–80% of choices), default annual billing, default the seat count to the ICP's typical, consider a reverse trial (premium is default; free is opt-out). Also explains **redesign risk** (forcing relearning feels hostile) and **feature-adoption resistance**.
**Red flags:** target plan not pre-selected; monthly default when annual serves both; aggressive redesign of a heavily-used surface.

---

## Conversion & trust

### Loss aversion
Losing hurts about twice as much as the equivalent gain feels good (Kahneman).
*Examples:* Booking "only 1 room left"; cancellation "you'll lose 8 months of history with 476 clients"; upgrade "you'll lose access to 40 of your 47 reports."
**Apply:** frame retention and upgrades as avoiding loss, not gaining benefit; use honest scarcity.
**Red flags:** cancellation/upgrade copy that only describes gains; no surfacing of what the user would lose.

### Social proof
We infer correct behavior from others'.
*Data:* purchase probability peaks at **4.2–4.5★**, not 5.0 (5.0 looks fake — Northwestern); testimonials +34% conversion (VWO); 5+ reviews → 270% more likely to buy (Yotpo); 93% read reviews (BrightLocal); Booking showing sold-out hotels *raised* conversion.
**Apply:** specific, verifiable proof (named company + quantified result + real photo/video/link) beats generic 5-star cards.
**Red flags:** identical cards, first-name-only, generic avatars, "used by Company X" with no result.

### Scarcity
Limited availability raises perceived value and compresses the deliberation window.
**Apply:** real scarcity only (true stock, real deadlines).
**Red flags:** fabricated countdowns / fake "3 left" — dark pattern, remove.

### Framing effect
The same facts yield opposite conclusions depending on how they're presented.
*Examples:* Dropbox referral as "a gift from your friend" vs "your commission"; the Brazil-vs-Paraguay tables (pick indicators → either looks better); "lose" vs "gain" copy.
**Apply:** you are the designer of the comparison. In pricing, build your own comparison table choosing the attributes that support your value — if you don't frame it, the user compares you to "nothing" or your cheapest competitor.
**Red flags:** no controlled comparison on the pricing page; referral framed around the referrer's reward.

### Construal level theory
Concrete/near-term framing drives action more than abstract/distant.
**Apply:** make CTAs concrete — "Start free in 30s" simulates exactly what happens; "Sign up" leaves it abstract.
**Red flags:** vague CTAs; benefits described abstractly instead of as a concrete next moment.

### Outcome bias
We evaluate a decision by the outcome we expect from it; before clicking, the brain simulates "what happens."
**Apply:** a CTA should answer the 3 pre-click questions — *what happens, how long, what does it cost/commit.* Add a click-trigger beneath it ("14 days, no card").
**Red flags:** "Cadastrar"/"Submit" that answers none of the three.

### Processing fluency ("easy speech")
Simple, fluent language is trusted more and raises perceived competence.
**Apply:** plain language over jargon — it converts *and* retains.
**Red flags:** internal jargon in hero/product; clever-but-empty headlines.

### Curse of knowledge
You know too much and forget the user doesn't.
**Apply:** test copy with someone outside the team; remove insider terms.
**Red flags:** churn that looks like "missing feature" but is really "user never understood the value" — a *language* problem. Audit language before product/onboarding.

### Narrative bias
The brain craves stories and patterns; a ready-made story creates familiarity → trust → perceived value.
*Framework (Scartozzoni):* **Character → Desire → Obstacle → Transformation** (the customer is the hero, not you). *Ethics:* storytelling amplifies the truth but can't sustain a lie — Diletto invented a fake Italian grandfather, got caught (CONAR) and had to change everything; Do Bem built a true story and was acquired by Coca-Cola. In an OSINT/transparency era, fiction is a liability.
**Apply:** Build-in-Public turns your real day-to-day into the hero's journey and builds the hardest-to-copy moat: identification.
**Red flags:** no narrative (just feature lists); or a fabricated story the product can't back.

### Mere-exposure effect
Familiarity breeds preference; a familiar brand wins even when logically similar to rivals.
**Apply:** consistent presence (Build-in-Public, content) compounds into preference and an "illusion of superiority."
**Red flags:** zero owned audience/touchpoints; brand invisible between purchase moments.

### Aesthetic-usability / credibility
Polished visual design is read as trustworthy and competent; reduces perceived risk.
*Study:* **46%** of people judge a site's credibility by visual design (Stanford) — and the weight rises when money or sensitive data is involved.
**Apply:** at survival stage especially, a polished UI signals "if they cared about this, they cared about the rest." Trust signals (password rules, lock icon, social proof) on the first screen set the tone — a login/signup screen is a first impression, not a formality.
**Red flags:** sloppy first screen on a product handling money/PII; B2B product that looks like a weekend prototype.

---

## Activation & habit

### Zeigarnik effect
Started-but-unfinished tasks create mental tension until closed.
**Apply:** open small loops the user carries — complete profile, invite 3 colleagues, send first message; remind them they *started*. Keep loops small enough to feel closeable.
**Red flags:** onboarding with 14 steps and no perceived progress; no re-engagement when a user abandons mid-flow.

### Endowed progress effect
People finish what they perceive they've already started.
**Apply:** start the progress bar at ~20%, not 0% ("you already did the hard part — account + payment — 3 steps left").
**Red flags:** progress that starts at 0%; effort shown without crediting what's done.

### Peak-end rule
Experiences are judged by their emotional peak and their end, not the average (Kahneman).
*Example:* Stripe shows a **rising graph** at first transaction, not a number — progress → dopamine → emotional memory. Most products ship *confirmation* where they should ship *celebration*.
**Apply:** engineer a peak moment at the exact point of highest emotional vulnerability in activation.
**Red flags:** flat success states; no celebration at the first win.

### Endowment / IKEA effect
We value more what we own or helped build — up to ~3× for things we co-created.
**Apply:** let the user create/manipulate and see a result *before* asking for email/card; make the created object feel like "theirs."
**Red flags:** signup wall before any creation; empty state showing "0 data" instead of the user's own work-in-progress.

### Effort justification
Effort invested to obtain something raises its perceived value (Aronson & Mills, 1959).
*Examples:* trial-with-card filters intent; Superhuman's mandatory 30-min onboarding call; paid courses finish more than free ones; fraternity initiation; the queue that makes a restaurant seem better.
**Apply:** friction in the *right* place qualifies and deepens commitment (signup-trial friction hurts acquisition; onboarding friction *can* create activation; enterprise-demo friction qualifies pipeline).
**Red flags:** all friction treated as bad and removed everywhere; no qualification step where one would help.

### Variable rewards / dopamine
Dopamine fires on *anticipation* of reward, not the reward itself; predictable rewards habituate fast, variable rewards keep the loop alive (Hooked / mesolimbic system).
**Apply:** lifecycle messages that provoke curiosity ("your team hit a record you haven't seen yet") beat ones that merely inform ("see your performance"). Turn stale "validity" metrics into loss-aversion triggers ("sync in 24h or lose this week's benchmark").
**Red flags:** engagement emails the user can ignore at zero emotional cost; only predictable monthly reports.

### Inattentional blindness
Users don't see what they aren't looking for.
**Apply:** new features need contextual/triggered onboarding (surface the feature in the screen/empty-state where it's needed), not a login modal.
**Red flags:** "new feature!" modals at login; new features launched as a comms problem, not a design one; <10% adoption weeks after launch.

---

## Retention & moat

### Sunk-cost effect
We honor what we've already invested.
**Apply:** at upgrade/cancellation, remind the user of accumulated investment ("you created 47 custom reports; the free plan keeps 7").
**Red flags:** no surfacing of accumulated work; cancellation that lists nothing lost.

### Social switching cost + network effect
When a SaaS becomes the communication protocol between people/departments, cancelling becomes an org problem, not an IT one; accumulated shared data makes migration painful → negative churn by inertia.
**Apply:** design workflows where User A's work depends on User B; reports that aggregate across departments; multiplayer over single-player.
**Red flags:** single-player product (contract dies when one champion leaves); >30% of churned accounts had only 1 active user / 1 department — architectural vulnerability, not a market problem.

---

## Reasoning traps (about *your own* decisions)

### Law of small numbers
Treating a small sample as representative.
**Apply:** compute required sample size *before* an A/B test; if you can't reach it in reasonable time, don't start — decide by qualitative research instead.
**Red flags:** "variant B won by 12%" after one week of low traffic → whole product changed.

### Confirmation bias
Favoring evidence for what you already believe.
**Apply:** pre-register the success metric; don't stop a test early because the number looks good.
**Red flags:** tests stopped at a pretty mid-point; only favorable cuts reported.

### Cargo cult
Copying the visible form expecting the function (a fallacy, not a bias).
*Example:* cloning a high-converting landing page copies the cheap part (layout) and misses the expensive invisible part (customer research, objection order, ICP vocabulary) → 4% vs 0.6%.
**Apply:** ask "what here is a function of the product vs a function of the customer research behind each line?" Copy the research process, not the pixels.
**Red flags:** "we copied a page that works and it doesn't convert"; benchmarking competitors' surface without their underlying mechanism.
