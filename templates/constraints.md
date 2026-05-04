# constraints.md

## What This File Is For

The always-do-this / never-do-that file. Your runway, your time budget, your team capacity, your tools, your ethical lines, and the things you refuse to do even if they'd work commercially. The OS uses this to filter out recommendations that don't fit your reality or your values.

---

## Interview Protocol

*Instructions for the interview agent.*

**Multi-file capture:** Feeds `business-model.md` (margin must support runway needs), `goals.md` (constraints shape what's achievable), `decision-log.md` (constraints are the reason behind many decisions).

**Conversation flow:**

1. **Runway.** "How many months of runway do you have at the current burn rate? Be honest — this drives every other decision."
   - If pre-revenue with no funding, the answer is "personal savings to [date]."

2. **Time budget.** "How many hours a week are you actually putting into this business? Not how many you wish — how many you actually do."

3. **Team.** "Who's on the team right now? Cofounders, employees, contractors. How many hours each? Where are the capacity gaps?"

4. **Stack.** "What tools and systems are you committed to? Things the OS shouldn't suggest replacing without good reason. (E.g., 'We're a no-code shop,' 'We're committed to AWS,' 'We use HubSpot for everything CRM.')"

5. **Ethical lines.** "What will you not do, even if it would work commercially? Selling to certain customers, certain pricing tactics, certain growth hacks?"
   - If they say "nothing," push: "Really? No segment, no tactic? Not even surveillance, dark patterns, harm to users?"

6. **Refused-to-do list.** "What advice have you been given recently that you've deliberately rejected? Why?"
   - Captures the strategic discipline of saying no.

**Stop condition:** You have specific numbers for runway, time, team. Specific named tools in stack. At least 2-3 ethical lines. At least 1-2 explicit "no" decisions.

**Judgment-layer challenge:**
> *Reversibility lens. For each constraint, ask: "Is this a real constraint or a habit? If you violated it next week, what would actually break? Tag the soft ones so the OS knows when to push back."*

---

## Output Structure

```markdown
# Constraints

## Runway
- **Months of runway at current burn:** [Number]
- **Burn rate:** [$ per month]
- **End-of-runway date:** [Date]
- **Source of runway:** [Personal savings / Revenue / Investment / Mix]

## Time Budget
- **Hours per week founder is putting in:** [Number]
- **Realistic max sustainable:** [Number]

## Team
- **People:** [List with role and hours/week]
- **Capacity gaps:** [Where you're under-staffed]

## Stack (What You're Committed To)
- [Tool / system 1] — [Why committed]
- [Tool / system 2] — [Why committed]

## Ethical Lines
- [Thing you won't do] — [Why]
- [Thing you won't do] — [Why]

## Refused-to-Do List
- [Advice rejected] — [Why]
- [Path not taken] — [Why]

## Soft vs. Hard Constraints
*Soft = could violate if right; Hard = non-negotiable*
- [Constraint] — [Soft / Hard]

## Last Refreshed
[Date — recheck monthly]
```
