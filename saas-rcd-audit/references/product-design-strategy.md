# Product & design strategy

> Every feature that enters, stays — and charges rent forever. The strategic question is never "is this feature good?" but **"does it deserve the permanent cost it will charge the product?"**

**Contents:** [Swiss Knife Index](#swiss-knife-index) · [The feature filter](#the-feature-filter-2-layers) · [Design drivers](#design-drivers-tactical--organizational--strategic) · [Refactor vs repaint](#refactor-vs-repaint) · [Dashboard design](#dashboard-design)

---

## Swiss Knife Index
Answers one question: **how many of your features are actually used?** List every feature, count those used by **>40% of active users in a 30-day window**, and divide by the total. **Below 0.3 → you have a Swiss army knife** — 100 tools, barely fits in your pocket, slow to find and open the one you need. Technical founders (especially now, with AI) love building features; the roadmap becomes a user wishlist believed to magically raise LTV and pull in users. But every feature increases the product's **surface area**: more code to maintain, more UI to design, more cognitive load (the user takes longer to learn) — and worse, it **dilutes the perception of what the product is for** (feature creep). How to fix:
1. **Quarterly audit** — feature list vs real usage; data, not team opinion.
2. **Hide, don't delete** — low-use features move to advanced settings: still there for the 3% who need them, gone for the other 97%.
3. **Criterion for the next feature:** "what existing feature will I kill to make cognitive room for this?"
Easy pull: *what feature would I show first if I had 30 seconds to sell the product?* Everything else should be invisible until it's needed.

## The feature filter (2 layers)
A feature must pass **both** layers.

**Layer 1 — does the feature deserve to exist?** Four criteria:
1. **Cognitive load** — every feature increases the contact surface → more learning, more decision time (Hick's Law), higher chance the user doesn't find what they wanted, gets frustrated, and later cancels.
2. **ICP specificity** — does it serve your *real* niche or a generic one that looks like yours? A generic CRM stays generic; a CRM for facial-aesthetics clinics charges 5×. Specificity is an unfair advantage over generic players.
3. **Operational cost** — not the build cost, the cost to *maintain, support, document, train support on, and update* when the stack changes. Long-term the product gets heavy and needs ever more resources — and more attack surface.
4. **Strengthens the main claim** — if the LP promises X, every feature must pull toward X. A feature that disperses the claim dilutes value *and* creates a communication problem (doing everything feels good, but you'll never have the space/time to communicate it).

**Layer 2 — build it now?** Two axes:
1. **Easily rejectable?** Is there a clear "no"? If the "no" is obvious, discard fast and move on. If the "no" needs a 3-hour meeting, the feature is ill-defined or you lack criteria.
2. **Easily implementable?** The real cost to a *first* version — not the dream version, the version that validates.
Crossing the axes reveals the **no-brainer zone**: passed Layer 1, easily implementable, obvious "go." **Build here first, always.** Most teams do the opposite — build the hard thing that looks strategic and ignore the no-brainer that moves a metric this week.

**Applying it:** for each roadmap feature — passes all 4 of Layer 1? where does it fall on the 2 axes? Pass 4 + no-brainer → build. Pass 4 but hard → schedule with criteria. Fail any of the 4 → kill without guilt.

## Design drivers: tactical → organizational → strategic
The three drivers of design, in order of leverage. The paradox: **tactical** is the base and theoretically the lowest-leverage — but because everyone outsourced aesthetics to the same UI kit the AI uses, it became the most **under-explored** opportunity. The lowest-value-in-theory became the highest-return-in-practice, simply because nobody looks.
- Aesthetics *and* function live at the tactical level — and so does **cost**: Johnnie Walker's square bottles cut breakage and logistics cost; the smaller iPhone box fit more units per container → margin. Small details, direct margin impact.
- Aesthetics can differentiate and build brand: **Resend** dressed its ICP and gave a commodity a visual that talks directly to its audience — differentiating a product that sells a commodity.
- Cautionary tale: the Ferrari Luce (first EV, designed by Jony Ive) had the worst brand reception in the company's recent history — wiped billions in 48h, stock ≈ −8% — by failing exactly where Ferrari was always strongest (the visual).
The bar is low today; the minimum care you put in already generates results. See design as **strategic**, but remember aesthetics sits at the base and makes a huge difference.

## Refactor vs repaint
The designer's infinite loop: *looks great → could be better → got better → repeat forever.* We refactor UI like we refactor code, and confuse two different things:
- **Real refactor:** wait for user feedback and change what *solves a problem* (e.g. attacking an old, annoying sector pain — clients not trusting a workshop's repair quote).
- **Repaint:** repainting the wall because the old color got boring — a week of pixel-perfect nobody asked for.
**Audit flag:** is a proposed redesign solving a user problem (refactor) or scratching an aesthetic itch (repaint)? Only the use will tell whether it got *better* or just *prettier*. (See also redesign risk in `retention-churn.md`.)

## Dashboard design
"Your dashboard is a data cemetery and it will kill your LTV." Most founders trust the dashboard as a universal data-viz solution; usually it just creates a *sense* of productivity without delivering value — the user glances at the tangle of cards, doesn't find what matters, and gives up. The complexity fallacy is why an expensive watch with many complications is hard to read the time on: more functions, harder to use. More information on the screen = longer to scan = harder for the important thing to happen. Principles:
1. **Define the "who" (ICP)** — list your user's 3 most-used features + the 3 main returns the product delivers, then combine them; that's what the dashboard should foreground.
2. **Cut the cognitive tax** — every pixel that doesn't communicate information is noise. *Less view = more signal.*
3. **Insights > raw data** — data is a commodity; the user wants intelligence. Turn raw numbers into value-associated insight.
4. **The "so what?" test** — each metric must imply an action. If a number doesn't suggest a next step, it's decoration.
5. **Color & contrast guide the eye** — use contrast to lead the eye to what matters, not more colors.
6. **Round the numbers** — R$50.752,46 → R$50k for cognitive ease.
7. **Group by business context**, not by chart type.
8. **Size & position create hierarchy** — the important number is bigger; a North Star metric is the beacon of the screen.
9. **Make it for humans** — a good dashboard isn't cold and corporate; it reflects the brand and reinforces the user's wins (habit/positive behavior).
