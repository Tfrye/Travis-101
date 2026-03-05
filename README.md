# Travis 101 — A Working with Me Guide

**Live site:** https://tfrye.github.io/Travis-101

---

## What this is

A personal operating manual built to help teammates, managers, and collaborators understand how I work best — how I take action, how I communicate, where I thrive, and where I have blind spots.

The guide is built on two behavioral frameworks:

- **KOLBE A™ Index** — measures natural instincts and how a person takes action (not personality, not intelligence)
- **DISC** — measures how a person communicates, engages with others, and responds to their environment

My results: **Fact Finder 7 · Follow Thru 8 · Quick Start 2 · Implementor 3 · DISC Supporter (S)**

---

## Why I built this

A few honest reasons:

1. **To get comfortable with AI-assisted development** — this project was built entirely through conversation with Claude (Anthropic's AI assistant) using Claude.ai.

2. **To re-familiarize myself with GitHub** — I wanted a small project to use as a reason to get back into version control, GitHub Pages, and the basics of shipping something to the web.

---

## How it was built

- **Tool:** [Claude.ai](https://claude.ai) (Claude Sonnet) — conversational prompting, no manual coding
- **Stack:** Single-file HTML using React (via CDN) + Babel standalone — no build tools, no npm, no frameworks
- **Hosting:** GitHub Pages
- **Design:** Custom — navy/teal/gold palette, Playfair Display + DM Sans typography, animated with CSS keyframes

---

## Want to build your own?

If you'd like to create a personal operating manual like this one, here's the prompt I used to get started with Claude:

---

### 🤖 Starter Prompt

> I want to build a personal operating manual as a single-page interactive web app — something I can share with teammates and collaborators so they understand how I work.
>
> It should be styled like a polished mobile-first experience with dark background, elegant typography, and animated transitions between screens. Each screen should cover a different aspect of how I operate.
>
> I'll be basing it on my **KOLBE A™ Index** and **DISC** assessment results. Here are my scores:
>
> - **KOLBE:** Fact Finder: [X], Follow Thru: [X], Quick Start: [X], Implementor: [X]
> - **DISC profile:** [e.g. Supporter / High S / Dominance / etc.]
>
> Write all content in **third person** (he/she/they) so it reads as a briefing document for others, not a self-description.
>
> Include the following screens:
> 1. Cover — name, tagline, "Begin" button
> 2. KOLBE breakdown — all 4 action modes with scores, bars, and tap-to-expand detail
> 3. DISC profile — key traits and what they mean in practice
> 4. Blind spots — shadows of each strength, with antidotes (tap to expand)
> 5. The Connector — how this person builds relationships
> 6. User Manual — tabbed guide: Projects / Feedback / Disagreement / Meetings
> 7. The Decoder — tap behaviors to reveal what they mean and how to respond
> 8. Cheat Sheet — what energizes vs. frustrates this person
> 9. Closing screen — a summary statement
>
> Make it a single self-contained HTML file using React via CDN (no build tools), so it can be dropped directly into GitHub Pages and shared via URL.

---

Swap in your own scores, adjust the tone, and iterate from there. The best results come from pushing back on anything that doesn't feel accurate and asking Claude to refine it.

---

## Credits

Built with [Claude](https://claude.ai) by Anthropic · Hosted on [GitHub Pages](https://pages.github.com)
