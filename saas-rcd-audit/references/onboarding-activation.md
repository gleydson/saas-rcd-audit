# Onboarding & activation

> Most early-stage churn happens in the first 30 days — which means it's an **onboarding** problem, not a product problem. ~90% of users abandon in week 1 if they don't reach clear value. They don't cancel or complain; they silently disappear and you never learn their name. Adding features makes this *worse* (more complexity).

**Contents:** [Measure the right things](#measure-the-right-things) · [The aha moment](#the-aha-moment) · [Active vs passive](#active-vs-passive-onboarding) · [Empty states](#empty-states) · [9 onboarding patterns](#9-onboarding-patterns--how-to-choose) · [Declarative vs administrative friction](#declarative-vs-administrative-friction) · [Friction in the right place](#friction-in-the-right-place) · [Sell the outcome](#onboarding-sells-the-outcome-not-the-mechanics) · [Trial conversion = journey](#trial-conversion-is-a-journey-problem) · [The journey gap](#the-journey-gap)

---

## Measure the right things
Technical founders measure the wrong layer:
- **Activation rate, not signups.** Signup is the door; activation is the user actually using the product for real. Avg SaaS activation 30–37%, top quartile 40%+, **below 20% = serious structural problem** in onboarding and/or product.
- **Time to first useful action (and its repetition), not session time.** Session time includes a lost user hunting for what to do.
- **D7 retention, not onboarding completion.** Completing an 8-step tour means the user was *obedient*, not that they understood value. D7 says whether they came back (avg 10–15%, >30% strong).
- **TTV (time-to-value):** the time from signup to clear value. Median ≈ **1 day 12h 23m** (Userpilot, 547 companies); top performers **< 5 minutes.**

## The aha moment
The exact instant the user feels the product solves something they had. Before it, they're just exploring; after it, they integrate the product into a routine. **Find it empirically:** take your paying customers and look at what they all did in week 1 that the churned users did *not*. That — not what you assume — is your aha moment. For most SaaS it involves doing something **with a collaborator** (invite, share, comment); even a light network creates a retention effect.
- *Slack:* teams exchanging **2,000 messages** had a 93% probability of staying. That number became the activation north star.
- *Facebook:* **7 friends in 10 days.** The whole company optimized for it.
Audit question: how long between signup and aha? If you can't answer, you're not measuring what matters.

## Active vs passive onboarding
- **Passive** (tooltips, guided tour, docs — "learn if you want"): assumes the user will explore. They won't — they have 47 tabs and WhatsApp pinging; yours is one of them.
- **Active** (a designed sequence of actions; each action delivers value, each value triggers the next): assumes you know the shortest path to value and you remove friction to guarantee they reach it. Slack drops you into a channel and makes you send a message — you've *used* the product, and using it is understanding it. **Learning by doing beats learning by reading.**
- Design question: not "what's the minimum the user must do," but **"what's the smallest action that delivers the most value in the least time?"**

## Empty states
An empty dashboard on first login kills trials (tumbleweed rolling by) — the user is at peak curiosity and you hand them a blank screen; they think "I'll come back" and never do. The empty state should **sell the dream**, never show "0 data" or blank templates. Make it:
- **One obvious, immediate first action** ("Importe sua primeira planilha" / "Conecte sua conta") — one, not eight, not a 12-step tour.
- **Sample / example data** so they see the destination before starting (reduces uncertainty), or an interactive populated demo simulating "day 30 of use."
- **Visible progress from the first click** — a progress bar starting at ~20%, not 0% (endowed progress).
The user doesn't buy the tool; they buy the vision of themselves succeeding with it.

## 9 onboarding patterns & how to choose
A toolbox — pick the pattern(s) that deliver value before asking for effort, fit to your product type:
1. **Welcome measurement** — instrument the welcome so you can see where users drop.
2. **Wizard / product tour** — guided setup; use sparingly, only if setup is genuinely required.
3. **Contextual tooltips** — just-in-time hints at the point of need (not a front-loaded tour).
4. **Empty state that sells** — see above; the highest-leverage pattern.
5. **Personalization** — adapt the path to a declared intent (see declarative friction).
6. **Checklists** — small, closeable loops with visible progress (Zeigarnik + endowed progress).
7. **Goal definition** — have the user state the outcome they want; customizes the journey.
8. **Sample data** — pre-populate so the product looks alive immediately.
9. **Rewards / wins** — celebrate the first real result (peak-end).
**Choosing:** map your aha moment, then choose the fewest patterns that get the user there fastest; prefer active (do) over passive (read).

## Declarative vs administrative friction
A BR payments platform cut time-to-first-sale from **24.2 days to 2.5 days** — not by removing onboarding steps, but by *adding* one: a ~30-second step where the user declares **what they sell and their long-term goal**, placed between signup and product. Two effects:
- **Operational:** the journey afterward becomes specific (infoproduct vs physical → different tutorials, next actions).
- **The real one:** a **micro-commitment** — the user is no longer exploring a platform, they're executing a plan they just described.
Audit each onboarding step: is it collecting **data** (administrative — delays the user, buys nothing → candidate for removal) or making the user **declare intent** (declarative — delays slightly, buys commitment + customization → expandable)?

## Friction in the right place
Friction isn't universally bad (see effort justification in `cognitive-biases.md`). Right-placed friction qualifies and retains:
- **Trial with card** filters intent (≈31% vs ≈9% conversion) — but lowers signups; choose by ICP, not just conversion.
- **Mandatory onboarding before the dashboard** (Superhuman's 30-min call; Linear forcing team name + first issue) makes power users faster.
- **Enterprise demo form (6–8 fields)** lowers lead volume but raises close rate — the SDR stops burning hours on leads that would never buy.
Rule: friction at trial signup *hurts* acquisition; friction in onboarding *can* create activation; friction at the enterprise demo *qualifies* pipeline. Same tool, different places, opposite results.

## Onboarding sells the outcome, not the mechanics
Nobody wants to learn the product; they want the result you promised in the hero.
- Dev onboarding: "1. create your first project 2. add a member 3. configure integrations" → boring.
- Converting onboarding: "1. in 2 minutes you'll see your first report 2. let's start with the data you already have 3. done — this is the insight your competitors pay consultants for."
Use **endowed progress** ("you already did the hard part — 3 steps left") and **Zeigarnik** (small, closeable loops). Don't ask "which plan?" — pre-select the best fit from what you learned and offer an upgrade ("want more? +R$20/mo gets you X"). The gap between 5% and 15% trial conversion lives in these micro-decisions, not in features or price.

## Trial conversion is a journey problem
Trial is a test of value; if it's not proven, it won't convert — and that's rarely a pricing problem. Three ways users get lost:
1. **Empty dashboard** → didn't know what to do first → "I'll come back" → never did. *Fix:* obvious, immediate first step; skip "explore our product."
2. **Lost before value** → did a bunch of "nothing," never thought "this solves my problem." *Fix:* install a session-replay tool (e.g. Clarity), watch where they stall before value, optimize that click.
3. **Lost in life** → liked it, but life happened and forgot. *Fix:* an email that shows *their* progress ("you created 3 reports, your team logged in 12 times, you're in the top 20%") — not a generic "your trial is ending."
The longest trial in the world doesn't save bad onboarding.

## The journey gap
The founder describes a 12-step journey; the user executes 4. The founder's journey is top-down (what they want the user to do: Onboarding → Activation → First project → Expansion → Advocacy); the user's is bottom-up (the specific problem they had when they opened the tab — everything else is friction). They rarely coincide, and the gap is invisible to the founder because he lives the *creator's* journey, never the newcomer's. Map it in 3 steps, no Figma:
1. Write your assumed user journey in numbered steps.
2. Open **5 session replays** of real users in their first 7 days; note what each actually does, in order, with timing, and what they try and abandon.
3. Put the two lists side by side — the report is in the differences. What % execute the happy path you designed? If you don't know, it's tomorrow's research session. **The journey is what shows up in session replay; what's in Figma/Excalidraw is a hypothesis.**
