# stakeholder-pressure.md

## What This File Is For

Who's exerting strategic pressure on you and what they expect. Not an org chart. A pressure map. Investors pushing for ARR. Boards pushing for hires. Key customers pushing for features. Advisors pushing for direction. The OS uses this to flag when a recommended bet conflicts with stakeholder expectations — so you can decide whether to align or push back.

---

## Interview Protocol

*Instructions for the interview agent.*

**Multi-file capture:** Feeds `goals.md` (stakeholder expectations often shape goals), `decision-log.md` (many decisions are stakeholder-driven), `coherence-check` triggers (when bets conflict with expectations).

**Conversation flow:**

1. **The stakeholder list.** "Who has strategic pressure on you right now? Investors, board members, advisors, key customers, cofounders. List them by name or role."

2. **For each: what they expect.** "What does each one expect from you in the next 90 days? Be specific — revenue numbers, hires, product launches, fundraises, board meetings."

3. **For each: what pressure they exert.** "What's the pressure they put on you when you're not on track? How does it land — emails, calls, board meetings, withheld support?"

4. **Where expectations conflict with your strategy.** "Where does any of this pressure pull you in a direction that doesn't match your thesis or current bets? Be specific. Investor wants ARR but your thesis says go free for 6 months? Cofounder wants a hire but your runway says no?"

5. **The explicit conflicts.** "Of the conflicts you just named — which ones are you actively managing right now? Which ones are you avoiding?"

**Stop condition:** You have a named list of stakeholders, their expectations, the pressure each exerts, and at least 1-2 explicit conflicts between expectations and strategy.

**Judgment-layer challenge:**
> *Pre-mortem lens. Ask: "12 months from now, you've followed stakeholder pressure instead of your thesis, and the business failed. What was the moment you should have pushed back? Capture it as a watch item."*

---

## Output Structure

```markdown
# Stakeholder Pressure

## Stakeholder Map

### [Name / Role 1]
- **Relationship:** [Investor / Board / Advisor / Key Customer / Cofounder / Other]
- **What they expect (next 90 days):** [Specific expectations]
- **Pressure they exert:** [How it shows up — emails, calls, board meetings, withheld support, public statements]
- **Their priority order:** [What they care most about, in order]

### [Name / Role 2]
[Same structure]

[Add more as needed]

## Conflicts Between Expectations and Strategy

### Conflict 1
- **What stakeholder wants:** [Specific]
- **What your thesis / current bet says:** [Specific]
- **Status:** [Actively managing / Avoiding / Resolved]
- **How you're handling it:** [Approach]

[Add more conflicts]

## Watch Items (from Pre-Mortem)
[Where stakeholder pressure could pull you off the right strategy. Specific triggers to watch for.]

## Last Refreshed
[Date]
```
