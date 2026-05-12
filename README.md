# Founder Context Portfolio

*The strategic context every AI tool you use should know about your business. Built once. Portable forever.*

---

You're a founder making strategic calls every week. Who to build for. What to bet on. How to price it. Why it's defensible.

You've explained your business 50 times this year. To investors. To advisors. To ChatGPT. To your cofounder. Every time you open a new AI tool, you start over.

This is the system that ends that.

---

## What this is

Twelve markdown files that capture your founder context in a structured, portable, machine-readable format. Built through a guided interview that runs in Claude Code (or any AI tool that reads markdown). Once filled, drop them into Claude, Cursor, ChatGPT, Gemini, or any agent you work with. They all read markdown.

## Who this is for

- **Solo founders** making 30+ product decisions a week without a PM, cofounder, or strategic team
- **Cofounder duos** who want to align on a single, shared strategic context document
- **Pre-seed and seed-stage founders** trying to clarify their value, positioning, and beachhead before they hard-commit
- **Founders using AI heavily** who are tired of re-explaining their business every time they open a new tool
- **Anyone who has built a business by gut and wants a written strategic system** to test their judgment against

This is **NOT for:**
- Idea-stage founders with no traction or customers (you don't have enough to test against)
- Large-company PMs (the OS-on-top product is a better fit)
- Founders who want pure tactical execution help (this is for strategic clarity, not project management)

## What you'll get

After ~60–90 minutes of structured interview, you'll walk away with:

1. **12 filled markdown files** covering identity, market, customers, business model, positioning, thesis, bets, goals, constraints, decisions, competition, and narrative
2. **Confidence tags** on every claim (Evidence / Faith / Untested) — so you know what's real, what's belief, and what's a guess
3. **A list of open questions** the interview surfaced — your "what to test next" list
4. **A portable strategic context document** you can drop into any AI tool and have it work like a senior strategic partner instead of a stranger
5. **A baseline** to refresh every 90 days as your business evolves

## Why this works

The same reason most AI-for-founders interactions disappoint: AI tools mirror your thinking instead of challenging it. If your strategy is fuzzy, you get fuzzy answers in return.

This system is different in three ways:

**1. The interview challenges weak answers.** It pushes back when you hand-wave. It asks for specifics. It tags every claim as Evidence, Faith, or Untested — so you can't quietly slip assumptions past yourself.

**2. The output is portable and persistent.** Plain markdown. Works with every AI tool. Travels with you across tools, accounts, devices, years. No vendor lock-in.

**3. The 12-file structure forces strategic completeness.** You can't accidentally skip "constraints" or "stakeholder pressure" or "competitive landscape." If a file is empty, that's the signal you haven't thought about that dimension yet.

> [!IMPORTANT]
> This is not a system that agrees with you. It's a system that interrogates you. The discomfort *is* the value.

---

# Quick Start

> [!NOTE]
> Recommended setup: **Claude Code Desktop** (the AI tool that reads and writes files on your computer). It's the smoothest path. If you'd rather use Claude.ai web or another AI tool, see [Alternative paths](#alternative-paths) at the bottom.

## Step 1 — Get your own private copy of this template

Click the green **Use this template** button at the top of this page.

<!-- SCREENSHOT: The green "Use this template" button at the top right of the GitHub repo page. Add a red arrow pointing to it. -->

Click **Create a new repository**.

<!-- SCREENSHOT: The dropdown after clicking "Use this template," showing "Create a new repository." -->

On the next screen:
- **Owner:** your GitHub account
- **Repository name:** `my-context-portfolio` (or whatever name you want)
- **Privacy:** select **Private** ✓ (your business context is not for public eyes)
- Leave everything else as default
- Click **Create repository**

<!-- SCREENSHOT: The "Create a new repository" form with Owner, Repository name, and Private radio button highlighted. -->

> [!TIP]
> "Private" means only you (and people you explicitly invite) can see it. This is the right setting for your business context.

You now have your own copy of the template at `github.com/[your-username]/my-context-portfolio`.

---

## Step 2 — Install Claude Code Desktop

If you don't already have Claude Code, install it now.

1. Go to **claude.ai/download**
2. Download Claude Code for your operating system (Mac or Windows)
3. Open the installer and follow the prompts
4. Sign in with your Claude account

<!-- SCREENSHOT: The claude.ai/download page showing the download button. -->

> [!NOTE]
> Claude Code is different from the regular Claude chat at claude.ai. Claude Code is the one that can read and write files on your computer. You need this version for the template to work properly.

---

## Step 3 — Get the repo onto your computer

Two options — pick whichever you're more comfortable with.

### Option A — Download ZIP (easiest, no terminal required)

1. Go to your new repo (`github.com/[your-username]/my-context-portfolio`)
2. Click the green **Code** button (top right of the file list)
3. Click **Download ZIP**
4. Unzip the downloaded file into a folder you can find easily — Documents, Desktop, wherever you keep important files

<!-- SCREENSHOT: The green "Code" button on the GitHub repo page with the dropdown open, showing "Download ZIP" highlighted. -->

### Option B — Clone with Git (terminal users)

```bash
git clone https://github.com/[your-username]/my-context-portfolio.git
cd my-context-portfolio
```

### Then: open the folder in Claude Code

1. Open Claude Code
2. Click **Open Folder** (or File → Open Folder)
3. Navigate to where you saved or unzipped your repo
4. Select the folder

<!-- SCREENSHOT: The Claude Code app's Open Folder dialog or the initial state with the file tree visible. -->

> [!NOTE]
> You should now see the folder structure on the left side of Claude Code: `templates/`, `interview-protocol/`, plus README.md and other docs.

---

## Step 4 — Start the interview

In the Claude Code chat window, type this and press Enter:

```
start interview
```

<!-- SCREENSHOT: The Claude Code chat input with "start interview" typed in it, ready to send. -->

Claude Code reads the file at `interview-protocol/agent-system-prompt.md` and begins the structured interview.

> [!TIP]
> If "start interview" doesn't work, paste this instead:
> *"Read the file at interview-protocol/agent-system-prompt.md and follow those instructions to interview me about my business."*

---

## Step 5 — Answer the interview

The interview runs in 5 phases. ~60–90 minutes total. You can pause and pick up later.

| Phase | What you'll cover | Time |
|---|---|---|
| 1 | Identity + Founder-Market Fit | ~10 min |
| 2 | Market and Customers + Competitive Landscape | ~20 min |
| 3 | Business Model + Decision Log | ~20 min |
| 4 | Positioning + Thesis and Bets | ~15 min |
| 5 | Goals + Constraints + Stakeholder Pressure + Narrative | ~20 min |

### How to answer well

> [!IMPORTANT]
> The interview will push back when you hand-wave. Don't fight it. The pushback is the value.

- **Be specific.** "Mid-market SaaS companies" is hand-wave language. "Series A SaaS companies, 50–200 employees, fintech vertical, fighting PCI compliance" is real.
- **Don't polish.** Write the messy version. The interview will sharpen it.
- **It's okay to say "I don't know."** The agent tags it as Untested. Better than making something up.
- **Use the confidence tags.** When asked, label each claim:
  - **Evidence:** you have real data backing this
  - **Faith:** you believe it but haven't proven it
  - **Untested:** you assume it but haven't even tried to validate

> [!WARNING]
> Don't try to do all 5 phases in one sitting if you're rushed. The work is sharper when you take breaks. The agent saves progress between phases.

---

# Testimonials

<!-- INSERT TESTIMONIAL FROM JENN HERE 
     Format: 
     > "Quote in their words. Direct, specific, what they got out of it."
     > 
     > **— Jenn [Last Name], [Their business / role]**
-->

<!-- INSERT TESTIMONIAL FROM MATTHEW HERE (with permission)
     Format:
     > "Quote in their words."
     > 
     > **— Matthew [Last Name OR "founder of [redacted]"]**
-->

*More testimonials from current users will appear here as the portfolio rolls out.*

---

# Next Steps

You've built the portfolio. Here's where to go from here.

### Run the Strategic PM OS on top of it — Cohort starts May 30

Building the portfolio is step one. Running an operating system that uses it to make ongoing strategic decisions is step two.

The **Strategic PM OS** is 9 structured skills that read your portfolio and walk you through every major strategic decision: customer thesis, problem validation, bet selection, positioning, business model, coherence-checking. Each skill produces a decision memo you can defend to your board, your cofounder, or yourself.

The next cohort is **2 Saturdays — May 30 and June 6, 2026.** 4 hours each. Virtual. **15 seats only.** Co-taught with Jenn.

**[Reserve your seat → https://pmos.founderwell.com/](https://pmos.founderwell.com/)**

### Get more thinking like this — Subscribe to AIPMGURU on Substack

Weekly essays on AI product management, strategic thinking for founders, and the operating systems behind better decisions. 5,700+ founders, AI PMs, and operators already read it.

**[Subscribe → https://aipmguru.substack.com](https://aipmguru.substack.com)**

### Stuck on a specific decision? Book a working session

Have a strategic call you're stuck on right now? Book a 60-minute 1:1 session. Bring your portfolio (or build it together live). Walk out with a written decision memo.

**[Book a session → CALENDLY LINK TBD]**

<!-- TODO: Replace "CALENDLY LINK TBD" with your actual Calendly URL (e.g., https://calendly.com/shailiguru/strategic-session). -->

---

# FAQ

> [!NOTE]
> **Do I need to be technical to use this?**
> No. If you can install an app and answer questions about your business, you can do this. The optional Git workflow (Step 3 Option B) is for people who already know Git — everyone else uses Download ZIP.

> [!NOTE]
> **How long does this take?**
> 60–90 minutes for the full interview. You can do it in one sitting or split across 2–3 sessions. The agent saves progress between phases.

> [!NOTE]
> **Is my data private?**
> Yes, if you set your repo to **Private** in Step 1 (which is what we recommend). GitHub private repos are visible only to you and people you explicitly invite. Claude Code runs on your computer and reads files locally — your business context never leaves your machine unless you push it to GitHub.

> [!NOTE]
> **What if my business changes? Do I have to redo this?**
> Re-run the interview every 90 days (set a calendar reminder now). Push to GitHub. The old versions stay in your repo's commit history, so you can see how your thesis has evolved over time.

> [!NOTE]
> **Can I share this with my cofounder?**
> Yes. Invite your cofounder as a collaborator on your private repo (Repo Settings → Collaborators → Add people). They can read and edit your portfolio.

> [!NOTE]
> **What if "start interview" doesn't work?**
> Try the longer version: *"Read the file at interview-protocol/agent-system-prompt.md and follow those instructions to interview me about my business."* If still stuck, open the agent prompt file directly and paste its contents into a new conversation.

> [!NOTE]
> **I don't know the answer to a question.**
> Tag it as **Untested** and move on. Don't make something up. The portfolio is meant to surface what you don't know yet, not paper over it.

> [!NOTE]
> **I have multiple businesses. Which one do I do?**
> Pick the one you're most stuck on. You can build a separate portfolio for the others later — each one lives in its own repo.

> [!NOTE]
> **My answers feel obvious and not worth writing down.**
> If they're obvious to you, they're not obvious to a new AI tool, a new advisor, or your future self in 6 months. Write them down.

> [!NOTE]
> **Claude Code can't find the file `agent-system-prompt.md`.**
> Make sure you opened the folder, not a single file. The folder should show `templates/`, `interview-protocol/`, README.md, etc. on the left side panel.

---

# Alternative paths

If you don't want to use Claude Code Desktop, two other options:

### Use Claude.ai web (no install needed)

1. Click **Use this template** to create your private repo (same as Step 1 above)
2. Go to **claude.ai** (the web version)
3. Start a new Project
4. Upload these files into the Project's knowledge: `interview-protocol/agent-system-prompt.md` + all 12 files in `templates/`
5. In the chat, type: *"Use the agent system prompt to interview me about my business."*
6. Answer the questions
7. Copy each completed file from Claude's responses and save manually to your local folder

**Tradeoff:** more manual file management; no filesystem persistence between sessions.

### Use ChatGPT, Cursor, Gemini, or another AI tool

Same idea. Open `interview-protocol/agent-system-prompt.md` and paste its full contents into your AI tool. Then say: *"Interview me about my business using this system prompt."* Save completed files manually.

**Tradeoff:** you lose the structured prompts inside each template file unless you also paste those one at a time.

---

# Design principles

| Principle | What it means |
|---|---|
| Markdown-first | Every AI tool reads markdown. No proprietary formats. |
| Modular, not monolithic | 12 separate files. Agents grab what they need. |
| Living, not static | The portfolio evolves. Re-run the interview every 90 days. |
| Confidence-tagged | Every captured fact is marked Evidence / Faith / Untested |
| Judgment-sharpening | The interview challenges weak answers, doesn't just record them |

---

# Lineage

Inspired by Nathaniel Whittemore's [Personal Context Portfolio](https://github.com/nlwhittemore/personal-context-portfolio). Adapted for founders building strategic AI operating systems.

What's different here:
- **Founder-strategic content** (not personal-general)
- **Multi-file capture** during the interview (one good answer feeds 3+ files at once)
- **Judgment-layer challenges** woven into the interview (not just neutral capture)
- **PM OS integration** (the 12 files are inputs to a working strategic system)

---

# License

MIT. Fork it. Customize it. Use it however you want.

---

# Built by

[Shaili Guru](https://www.linkedin.com/in/shailiguru/) is an AI Product Manager with 12+ years at Amazon, Disney, Nike, T-Mobile. Lecturer at the University of Washington. Writer of [AIPMGURU Substack](https://aipmguru.substack.com).
