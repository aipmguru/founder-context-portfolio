# Getting Started

You're 60 minutes from having a strategic context portfolio that works with every AI tool you use.

## Before you start

You need:

- A working AI tool (Claude.ai, ChatGPT, Cursor, Claude Code, or similar)
- 60 minutes of focused time (or 3-4 sessions of 15-20 min if you'd rather chunk it)
- A real business or serious idea (this isn't hypothetical, you fill it with your actual context)

You don't need:
- Any coding experience
- Polish (messy truth beats polished fiction)
- All the answers (the interview surfaces what you don't know yet — that's part of the value)

## Path 1: Run the guided interview (recommended)

1. **Open your AI tool of choice.** I'd recommend Claude as a Project, but ChatGPT, Cursor, or anything that supports a custom system prompt will work.

2. **Load the agent system prompt.** Copy the contents of `interview-protocol/agent-system-prompt.md` into your tool. In Claude, paste it into the project's custom instructions. In ChatGPT, paste it into a custom GPT or the system message of a new chat.

3. **Drop the templates in.** Upload all 12 files from `templates/` so the agent has the structure to fill.

4. **Type:** `start interview`

5. **Answer the questions.** The agent will run a structured 5-phase interview (~60 min). It will challenge weak answers, push for specifics, and capture multi-file context as you go.

6. **Download your portfolio.** When done (or whenever you want to pause), the agent will hand back your 12 filled markdown files.

## Path 2: Fill in by hand

If you'd rather skip the interview and write directly:

1. Open each file in `templates/`
2. Read the *What This File Is For* section
3. Skip the *Interview Protocol* section (it's for the agent, not you)
4. Fill in the *Output Structure* section with your real content

This takes longer (probably 90+ min instead of 60) and you lose the judgment-sharpening of the interview, but it works.

## What the interview is like

The agent isn't a form. It's a sharp practitioner asking pointed questions and pushing back when you hand-wave.

Example exchange:

> **Agent:** Tell me about your business in one paragraph. What you do, who it's for, why it matters. Don't polish — say it like you'd tell a friend at a coffee shop.
>
> **You:** We help small businesses use AI to automate their operations.
>
> **Agent:** That's the elevator pitch. Drop the marketing layer. *Which* small businesses, doing *what* operations? If I asked your last paying customer, what would they say you did for them?

The interview surfaces specificity that founders skip when they're talking to themselves.

## After the interview

You'll have 12 filled markdown files. From here:

| What you can do | How |
|---|---|
| Use them with any AI tool | Drop the folder into Claude / ChatGPT / Cursor / Codex / Gemini and reference them |
| Plug into the Strategic PM OS | See `wiring/pm-os-integration.md` |
| Host as an MCP server | See `wiring/mcp-resource.md` |
| Re-run the interview later | Type `update interview` — the agent picks up where you left off and refreshes the files based on what's changed |

## How often to update

| Trigger | What to update |
|---|---|
| Every 90 days | Run `update interview` — refresh the portfolio across the board |
| After 5+ customer conversations | Update `market-and-customers.md`, `thesis-and-bets.md` |
| After a strategic pivot | Update `thesis-and-bets.md`, `decision-log.md`, possibly `positioning.md` |
| After a fundraise or new investor | Update `stakeholder-pressure.md`, possibly `goals.md` |
| After a pricing change | Update `business-model.md` |

The portfolio is a living document. Keep it fresh and your AI tools stay sharp.

## Common questions

**Do I have to use Claude?**
No. The portfolio works with any AI tool that reads markdown (which is all of them). Claude is recommended for the interview because the system prompt is tested there, but you can adapt it to ChatGPT, Gemini, or any LLM.

**Is this private?**
Yes — your portfolio stays on your laptop unless you choose to host it somewhere. The interview happens in your AI tool's context. Nothing is uploaded to me or anyone else.

**What if I don't know the answer to a question?**
Say so. The agent tags answers with confidence levels (Evidence / Faith / Untested). "I don't know yet" is a valid answer that gets logged as an open question — and the agent will suggest where to find out.

**Can I skip files?**
Technically yes, but the more files you fill, the more useful the portfolio. Some files (like `decision-log.md`) get more valuable over time as you log more decisions. Start with what you can answer today, leave thin files for later.

**What if I'm pre-launch?**
Even better. The interview is designed to handle "I haven't validated this yet" answers — it captures your hypothesis and tags it as Faith. You'll see exactly which assumptions you're betting on before you build.
