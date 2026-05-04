# business-model.md

## What This File Is For

How you make money, durably. The value the customer is actually buying (not the features they're paying for), your pricing logic, your unit economics on the back of a napkin, and the scenarios that break the model. Updated every time pricing or revenue logic changes.

---

## Interview Protocol

*Instructions for the interview agent.*

**Multi-file capture:** Feeds `positioning.md` (price reflects positioning), `constraints.md` (margin defines what you can spend), `stakeholder-pressure.md` (investors care about unit economics).

**Conversation flow:**

1. **The value the customer is buying.** "Forget your feature list. What's the one thing the customer is actually buying? Not the product — the outcome. In dollars or time saved or risk reduced."
   - If they describe features, push: "Features are what you ship. Value is what they pay for. If your product disappeared tomorrow and they had to recreate the outcome themselves, what would it cost them?"

2. **Pricing — what and why.** "What are you charging right now (or planning to)? How did you arrive at that number?"
   - Listen for cost-plus thinking ("we costed it out"), competitor-copy ("we matched X"), or value-based reasoning ("they pay $Y for the alternative, we save them $Z").
   - If cost-plus or competitor-copy, push: "Both of those leave money on the table or under-price the value. What's the value-based version of this number?"

3. **The pricing model.** "Per seat? Per use? Tiered? Outcome-based? Flat? What model and why does it match how customers buy?"

4. **The doubling and halving test.** "If you doubled the price tomorrow, what would happen? If you halved it, what would happen? What does that tell you about where your price actually is?"

5. **Unit economics on a napkin.** "Walk me through the back of the napkin. ARPU or LTV. Cost to serve. Gross margin. CAC if you've measured it (estimate if not). Payback period."
   - For pre-revenue founders: estimates are fine. Tag each as estimate vs. measured.

6. **What breaks this model.** "Name 3-5 scenarios where the pricing or unit economics fall apart. CAC higher than estimated. Churn faster than expected. Cost to serve doesn't drop with scale. Be specific."

**Stop condition:** You have a value hypothesis, a specific price + model + reasoning, a back-of-napkin unit economics view (with estimate vs. measured tagged), and 3+ named risks.

**Judgment-layer challenge:**
> *Pre-mortem lens. Ask: "It's 12 months out and the unit economics are upside down. What killed the margin — CAC, churn, cost to serve, or pricing? Which is most likely?"*

---

## Output Structure

```markdown
# Business Model

## Value Hypothesis
[What the customer is actually buying — the outcome, in dollars or time or risk reduced. One paragraph.]

## Pricing
- **Current price:** [Specific number + model]
- **Pricing model:** [Per seat / Per use / Tiered / Outcome-based / Flat / Other]
- **Reasoning:** [Why this number, why this model]

## Unit Economics (Back of Napkin)
- **ARPU / LTV:** [Number] — [estimate / measured]
- **Cost to serve:** [Number] — [estimate / measured]
- **Gross margin:** [%] — [estimate / measured]
- **CAC:** [Number] — [estimate / measured]
- **Payback period:** [Months] — [estimate / measured]

## What Breaks This Model
1. [Specific scenario + why it would break things]
2. [Specific scenario]
3. [Specific scenario]

## Doubling / Halving Test Results
- If we doubled the price: [What would happen]
- If we halved the price: [What would happen]
- What this tells us: [The implication]

## Confidence
- Value hypothesis: [Evidence / Faith / Untested]
- Price level: [Evidence / Faith / Untested]
- Pricing model fit: [Evidence / Faith / Untested]
- Unit economics: [Evidence / Faith / Untested]

## Open Questions
[What you need to test about value, price, or unit economics.]

## Last Refreshed
[Date]
```
