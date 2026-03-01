---
title: "The Rise of AI Power Users: From Prompting to Orchestrating"
date: 2025-02-24
# weight: 1
# aliases: ["/first"]
tags: ["AI"]
showToc: true
TocOpen: true
draft: false
ShowReadingTime: true
ShowWordCount: true
UseHugoToc: true
cover:
    image: "/img/the-great-rewrite-bangkok-cover.jpg" # image path/url
    # caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false # only hide on current single page
---

{{< figure align=center src="/img/the-great-rewrite-bangkok-cover.jpg" >}}

*How the best AI users are graduating from chat interfaces to programmatic systems and why you don't need to be a developer to join them*

*This expands on my talk at The Great Rewrite in Bangkok. In a 20-minute fireside chat I didn't have room for the frameworks and examples so this article is the follow-up.*

---

Earlier this month at The Great Rewrite in Bangkok, I asked a room full of AI professionals: "How many of you use AI daily?"

Almost every hand went up.

"Now keep it up if you feel like you've mastered it as a power user."

Half the room dropped.

That moment confirmed something I've been watching for months. There's a massive gap between using AI and using it well.

And it's not about which tools you have access to or how often you use them. In 2026, the dividing line is simpler: Most people use AI as a chat interface. Power users run AI as a system.

---

## The 2026 Inflection Point: From "Generates" to "Acts"

A year ago, the workflow looked like this:

1. Ask AI for output
2. Copy it into your tools
3. Debug the gaps yourself
4. Repeat tomorrow

Now the best tools can read files, run code, manage multi-step work, and execute inside workflows.

So the winning move isn't "write better prompts." It's:

Define outcomes. Build context once. Delegate execution. Review like a hawk.

The human role shifts from doing the steps to supervising the system.

---

## The Prerequisite Mindset: Own The Work First

Before any framework and tool, there's a prerequisite. And it's not technical.

Deep ownership of their own work is what would really separates a power user from an average user.

A random prompter asks AI for a competitive analysis. A power user knows:

- which competitors matter for their market
- which sources are reliable
- what "good" looks like inside their organization
- what the CEO cares about this quarter
- what the landmines are politically and operationally

AI can accelerate expertise. It can't replace it.

If someone's been coasting on shallow understanding, AI mostly helps them produce shallow work faster.

Your domain judgment is the moat.

The marketing coordinator who knows her brand voice instinctively, the strategy analyst who understands the real political dynamics behind a decision, the HR professional who knows why three people left in Q3 despite positive reviews — these people get 10x leverage from AI because they have institutional knowledge AI cannot replicate. They know what questions to ask, what to distrust, what's missing from a draft.

That knowledge doesn't come from AI. It comes from us doing the work, paying attention, and caring about it. Then, AI helps amplify expertise.

Compare these two prompts:

"Write a LinkedIn post about our product."

Versus:

```
Our audience is CFOs at mid-size companies in Southeast Asia.

Their mindset: skeptical of marketing claims, burned by overpromising vendors.

What they care about: ROI, implementation risk, regulatory compliance.

Brand voice: trusted advisor, not salesperson. Data-backed, not hype.

Task: 150 words showing how we saved Company X $200K in 6 months.

Format: Problem → Solution → Results.

Avoid: "revolutionize," "game-changing," "synergy."
```

The second prompt isn't longer because the task is more complicated. It's longer because it contains the institutional knowledge the first prompt left out.

---

## The 5-Stage Path to Becoming an AI Orchestrator (Power User)

Power users in 2026 shift how work is designed and operate as orchestrators. They define goals and supervise processes rather than executing each step manually.

Here's the progression I see most consistently:

### Stage 1: Outcome Definition

Stop asking "what should AI do?" and start specifying "what outcome should exist?"

Old approach: "Write a market research brief." You manage each step manually — research, synthesis, formatting, repeat next week. Total time: 6.5 hours.

Power user approach: "Every Monday: gather updates from our trusted sources, analyze using our strategy lens, update the tracking sheet, draft the exec brief in our format, and flag items needing my judgment."

You review Tuesday morning. You add the context only you have access to, for example, the conversation from last Friday, the thing the CFO mentioned offhand, the nuance that changes how to frame a finding. Then you approve.

Total time: 1.5 hours.

The shift is from executing steps to supervising a repeatable process.

### Stage 2: Building Context Architecture

In 2024 we re-explained context every chat. In 2026 that's wasted motion.

Power users write context once and let tools load it automatically.

A simple example is a project markdown file (e.g., `CLAUDE.md` / project instructions) that captures:

- audience & objections
- brand voice & banned words
- strategic constraints
- verification rules
- sources of truth

When context loads automatically, outputs stop sounding generic.

```
# My Work Context

## Audience

CFOs at mid-size companies in Southeast Asia

- Language: "ROI," "cost reduction," "risk mitigation"

- Objections: implementation time, change management

- Decision style: data-driven, risk-averse

## Brand Voice

- Tone: trusted advisor, not salesperson

- Always include: proof (data, case studies)

- Never use: "revolutionize," "game-changing," "synergy"

## Strategic Constraints

- We target enterprise clients, not SMBs

- CEO priorities: transparency, customer stories over features

## Verification Standards

- All statistics need sources

- Flag unusual claims for my review
```

Modern agents (such as Claude, Cursor) are trained to read these files before processing any request. You write your context once. It applies to every interaction in that project.

Start simple. Document your source of truth, your workflow, and your best practices. For marketers that means audience profiles, brand voice examples, and verification rules.

You probably already have this material somewhere in SharePoint, Google Docs, or Notion. AI can connect to those tools, but integrations pull whole documents rather than distilled context. Persistent markdown files are the cleaner approach: dense, structured, and loaded automatically before every session.

### Stage 3: The Quality Layer

This is where I disagree with old project management heuristics like "10-80-10" — says spending 10% of your time doing strategy and setup, 80% execution and autonomy, then 10% review and polish. That framework made sense when humans were doing most of the production work. You had limited time to strategize, limited time to check, and most of the effort went into output generation.

With agents, my default ratio looks closer to 30-10-60:

**First 30%: Planning and Setup.** This is front-loaded strategic work — defining the outcome precisely, loading the right context, setting quality standards, anticipating edge cases. AI's plan mode has made this faster; it breaks down complex goals well and surfaces things I would have missed. But I still own the direction entirely. Shortcutting this phase creates problems in the final 50% that are harder to fix than they would have been to prevent.

**Middle 10%: Execution handoff.** I let AI run. I read logs, approve decisions at key checkpoints, answer follow-up questions, unblock things the agent has flagged.

**Final 60%: Review and refinement.** This is where the work actually gets good. AI in 2026 works fast and makes autonomous micro-decisions. It saves me time but it requires me full attention on the review process. Because sometimes the direction shifts slightly based on intermediate feedback. Sometimes voice gets diluted. Sometimes it missed out some requests earlier.

Not always. Not for every task. But as a default: execution gets cheap, and judgment gets expensive.

The mistake most people make is trying to use agents to reduce the review phase. That's backwards. Agents increase output volume which increases the importance of review.

What I've noticed: my work quality has actually improved since I spend large amount of my time reviewing work and thinking how to make it better. The implication of 30-10-60 is that power users still spend time on their work but they spend it differently. Power users focus more on defining and planning, more on quality control, far less on production. The time savings are real, but they show up as higher output at higher quality, not as more leisure. At least in the beginning.

### Stage 4: Skill Engineering

Context files tell AI who you are and what you care about.

Skill files go further: they encode how you do things when you're at your best.

Your frameworks, SOPs, checklists, and standards become reusable "skills" any agent can load.

For example, this is what "building a library of expertise" looks like in practice:

**Ad Design Skill**

Imagine a marketing team that runs paid ads across multiple campaigns. The ad designer has developed strong instincts — which image ratios work for which platforms, what the brand's visual rules are, how to write a brief that actually gets executed well. Building a skill file means codifying those instincts:

```
# Ad Design Skill

## Brand Visual Standards
- Primary colors: #1A1A2E, #E94560 (never approximate — exact hex only)
- Typography: Montserrat Bold for headlines, Inter for body
- Logo placement: bottom-right, minimum 80px clear space around it
- Image style: real people over illustrations, warm lighting, Southeast Asian context

## Product Asset Library
- Location: /assets/product-images/ (organized by product line)
- Always use latest approved images — check the /approved/ subfolder
- Never use images older than 6 months without approval

## Platform Specifications
- Instagram Feed: 1080x1080px, text under 20% of frame
- LinkedIn: 1200x628px, professional context, no lifestyle imagery
- Facebook: 1200x628px, strong contrast for mobile scroll

## Brief Template
When given a campaign brief, always clarify:
1. Primary audience segment and their key objection
2. Single message this ad must communicate
3. Desired action (click, sign up, learn more)
4. Campaign dates and any regulatory constraints

## Quality Checklist Before Output
- Does this match brand colors exactly?
- Is the CTA visible in 3 seconds of viewing?
- Does the copy avoid banned words? (see brand-guidelines.md)
- Has this been tested at mobile size?

## Tools
- Connected to Canva MCP: use this to generate design files directly
- Output final files to /campaigns/[campaign-name]/ads/
```

An agent loaded with this skill doesn't need to be briefed on brand colors, or asked what format LinkedIn prefers, or reminded to check the asset library. It already knows. You give it a campaign brief and a deadline. It produces work that meets your standards from the first draft.

**Expanding to a full marketing workflow**

The real leverage is when you build a library of skills that cover the whole operation. A one-person marketing team running four parallel agents, each loaded with a purpose-built skill:

The **Research Skill** — connected to a Perplexity MCP for live search, a curated list of trusted industry sources, and a template for structuring competitive intelligence. An agent running this skill monitors trends, surfaces relevant competitor moves, and outputs a structured brief in your format.

The **Content Drafting Skill** — contains your brand voice guide, examples of your ten best-performing pieces, tone calibration for different audiences, and platform-specific formatting rules. An agent running this skill drafts in your voice, not a generic AI voice.

The **Ad Design Skill** — as described above. Connected to Canva, loaded with your visual standards, linked to your approved asset library.

The **Performance Reporting Skill** — connected to your analytics tools, contains your KPI definitions, knows which metrics matter to which stakeholders, and outputs reports in your standard format rather than making you reformat every time.

One person, four parallel agents, each operating as a specialist. A campaign that used to take a week — research, brief, design, copy, reporting — takes a focused morning. Not because the thinking was skipped, but because each agent was already trained in your standards before the campaign started.

This is what "building a library of expertise" actually means in practice. Not a collection of prompts. A set of codified capabilities that compound across every project you take on.

### Stage 5: Multi-Agent Orchestration

Once you have outcomes, context, skills, and quality gates, you can run multiple specialized agents in parallel.

**A product launch in one morning**

Maria runs marketing alone at a fintech startup. A product launch is scheduled for Friday. In 2024, she would have spent the week context-switching between research, copywriting, design briefs, and spreadsheets.

In 2026, she opens Claude Code on her laptop and types one instruction:

```
I have a product launch on Friday. I need:

1. Competitor pricing research for the three rivals in SOURCES.md

2. Three LinkedIn posts for launch week, in my brand voice (see BRAND.md)

3. Ad creative briefs for Instagram and LinkedIn formats

4. A performance tracking template for the first two weeks

Use the relevant skill files from my skills/ folder.

Flag anything that needs my input before proceeding.
```

Claude Code reads this, breaks it into four tasks, and spins up four agents. The research agent pulls live competitor data. The content agent drafts the LinkedIn posts using her brand voice skill. The ad brief agent follows her design skill file. A fourth agent builds the tracking template.

Before anything reaches Maria, a critic agent reviews the LinkedIn posts against her brand standards. It flags one post where the tone drifted toward generic. It surfaces that claim in one post that needs a source. Maria receives a folder with the outputs and a short list of issues to resolve.

She spends 90 minutes reviewing, adding the insight from a customer call last week that changes how she frames the launch, and approving.

---

## How to Apply It Right Away This Week

If you want to get started quickly, I recommend you do this:

Pick one recurring task you do every week.

1. Write the outcome as a recurring system ("Every Monday…")
2. Create one context file (audience, voice, constraints, verification)
3. Add one quality gate ("flag anything uncertain before proceeding")
4. Run it twice and refine the context based on what broke

That's enough to feel the shift.

Observe how the outputs change when context loads automatically instead of being re-explained each session. Start applying the 30-10-60 framework explicitly and notice where you're still spending time on execution you could delegate.

**Next Week:** Build your first skill file from an existing process you run regularly — a research methodology, a reporting format, a content framework.

**Next Few Weeks:** Try Stage 5 on one workflow: define what each "agent" role would handle and what decisions you'd retain.

---

I've thought about that room in the event in Bangkok since that night. The people who kept their hands up weren't necessarily more technical or better resourced. They had just stopped thinking about AI as a chat interface and started thinking about it as a system they run. That shift is what this whole article is trying to hand you. The framework exists. The tools exist. What's left is a decision to get started.

Where are you in the five stages? I would genuinely like to know.
