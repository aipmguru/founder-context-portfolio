# Founder Context Portfolio

*The strategic context every AI tool you use should know about your business. Built once. Portable forever.*

---

You're a founder making strategic calls every week. Who to build for. What to bet on. How to price it. Why it's defensible.

You've explained your business 50 times this year. To investors. To advisors. To ChatGPT. To your cofounder. Every time you open a new AI tool, you start over.

This is the system that ends that.

## What this is

Twelve markdown files that capture your founder context in a structured, machine-readable, portable format. Built through a guided interview with Claude (or any AI tool you prefer). Once filled, drop them into Claude Code, Cursor, Codex, Gemini, ChatGPT, or any agent you want to work with. They all read markdown.

The 12 files cover the strategic dimensions that actually drive founder decisions:

| # | File | What it captures |
|---|---|---|
| 1 | `identity.md` | Business in one paragraph + you in one paragraph |
| 2 | `founder-market-fit.md` | Your earned secret, why you, why now |
| 3 | `market-and-customers.md` | ICP, beachhead, real customer language |
| 4 | `thesis-and-bets.md` | What you believe + what you're betting on |
| 5 | `business-model.md` | Pricing, value hypothesis, unit economics |
| 6 | `positioning.md` | POV, competitive frame, category |
| 7 | `goals.md` | This week / month / quarter / year / company |
| 8 | `constraints.md` | Runway, time, team, ethical lines, refused-to-do |
| 9 | `stakeholder-pressure.md` | Investors, board, customers, advisors |
| 10 | `decision-log.md` | Strategic decisions taken + reasoning |
| 11 | `competitive-landscape.md` | Direct competitors, alternatives, threats, moat |
| 12 | `narrative-and-story.md` | Founding story, the version you tell, the version you don't |

## Why this matters

Three reasons it's worth 60 minutes of your time:

**1. The context-repetition tax kills quality.** Every time you re-explain your business to a new AI tool, you leave things out. The output gets shallower. Multiply that across 5+ tools and you're getting B-grade work everywhere.

**2. Portability beats lock-in.** These are markdown files. They work with everything. Switch tools without losing your context. No vendor can hold your business hostage.

**3. The interview itself sharpens your thinking.** The agent doesn't just record what you say. It pushes back when you're hand-waving. Founders consistently report the interview surfaces things they hadn't articulated yet.

## How to use it

**Path 1: Run the guided interview** (recommended, ~60 min)

1. Open Claude (or your AI tool of choice)
2. Load the agent system prompt from `interview-protocol/agent-system-prompt.md`
3. Have it interview you through the 12 files
4. Download your filled portfolio

**Path 2: Fill it in by hand**

Open each template in `templates/` and fill it in directly. Slower but works if you prefer.

**Path 3: Plug into the Strategic PM OS**

If you're using the [Strategic PM OS](https://pmos.founderwell.com/) (or attending the workshop), see `wiring/pm-os-integration.md` for how the 12 files feed into the OS skills.

## Design principles

| Principle | What it means |
|---|---|
| Markdown-first | Every AI tool reads markdown. No proprietary formats. |
| Modular, not monolithic | 12 separate files. Agents grab what they need. |
| Living, not static | The portfolio evolves. Re-run the interview every 90 days. |
| Confidence-tagged | Every captured fact is marked Evidence / Faith / Untested |
| Judgment-sharpening | The interview challenges weak answers, doesn't just record them |

## Lineage

Inspired by Nathaniel Whittemore's [Personal Context Portfolio](https://github.com/nlwhittemore/personal-context-portfolio). Adapted for founders building strategic AI operating systems.

What's different here:
- **Founder-strategic content** (not personal-general)
- **Multi-file capture** during the interview (one good answer feeds 3+ files at once)
- **Judgment-layer challenges** woven into the interview (not just neutral capture)
- **PM OS integration** (the 12 files are inputs to a working strategic system)

## License

MIT. Fork it. Customize it. Use it however you want.

## Built by

[Shaili Guru](https://www.linkedin.com/in/shailiguru/) — AI Product Manager. 12+ years at Amazon, Disney, Nike, T-Mobile. Lecturer at the University of Washington. Writer of [AIPMGURU Substack](https://aipmguru.substack.com).
