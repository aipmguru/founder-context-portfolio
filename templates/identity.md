# identity.md

## What This File Is For

The dinner-party explanation of who you are and what you do. The single file an AI agent should read if it can only read one. Short, dense, no padding.

---

## Interview Protocol

*Instructions for the interview agent. Skip this section if you're filling in by hand.*

**Multi-file capture:** This phase also seeds early content for `market-and-customers.md` (industry signal), `narrative-and-story.md` (origin hint), and `founder-market-fit.md` (prompts the next interview).

**Conversation flow:**

1. **Name and current role.** Capture verbatim.

2. **Business / organization name + stage.** "What's your business called and where is it in its life — pre-launch, early revenue, growing, established?"

3. **The dinner party explanation.** "If you sat next to someone at dinner who's smart but doesn't know your industry, how would you describe your business in one paragraph?"
   - Self-reflect first. Don't offer examples.
   - If they give the polished elevator pitch, push: "Drop the marketing layer. *Which* customers, doing *what*? If I asked your last paying customer what you do for them, what would they say?"

4. **What you're known for.** "What do people seek you out for? Not what you wish they sought you out for. What they actually do."
   - If they give a generic skill ("strategy"), push: "Specifically. The thing they Slack you about at 11pm because they trust your judgment on it."

**Stop condition:** You have a one-paragraph business description that names a real customer and a real outcome, plus 1-3 sentences on what the founder is sought out for.

**Judgment-layer challenge** (apply once before drafting):
> *Read what the founder said back to them and ask: "If a stranger read just this paragraph, would they know exactly what your business does — or could it be 10 different businesses? Tighten until it could only be yours."*

---

## Output Structure

```markdown
# Identity

## Founder
- **Name:** [Full name]
- **Role:** [Founder / Co-founder / Solo operator]
- **Background (one line):** [Where you came from before this]

## Business
- **Name:** [Business name]
- **Stage:** [Idea / Pre-revenue / Early revenue / Growing / Established]
- **Industry:** [The space you play in]

## What You Do (one paragraph)
[The dinner-party explanation. One paragraph, plain English. Names a specific customer and a specific outcome. No marketing language, no "leveraging synergies."]

## What You're Known For
[1-3 sentences. The thing people seek you out for. Specific.]

## Confidence
- One-paragraph description: [Evidence: customers told me this / Faith: I think this is true / Untested: I haven't checked]
```
