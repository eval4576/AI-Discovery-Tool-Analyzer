# AI Discovery Interview Analyzer
### Extract Jobs-to-be-Done, pain point themes, and ranked opportunities from raw user interview notes

**Live Demo → [eval4576.github.io/ai-discovery-tool-analyzer](https://eval4576.github.io/ai-discovery-tool-analyzer/)**

---

## What It Does

Paste raw, messy user interview notes — bullet points, direct quotes, stream of consciousness — and get a structured discovery insight report in seconds:

- **Executive summary** — board-ready synthesis of what you learned and data confidence level
- **Jobs to Be Done (JTBD)** — extracted job statements in "When I... I want to... So I can..." format, with frequency rating, pain severity, and supporting evidence quotes
- **Pain point theme clustering** — groups related friction into named themes with mention counts, insight summaries, and representative quotes
- **Opportunity scoring** — each opportunity scored 1–10 with effort rating and prioritization rationale
- **Discovery signals** — green (positive), watch (uncertain), and red (critical concern) flags across the data set
- **PM recommendation** — a single sharp next step with rationale and 4 concrete actions

Output copies as clean Markdown for direct use in Notion, Confluence, or any PM tool.

---

## Why I Built This

User research is where great products are born — and where most teams fall short. The synthesis step is the bottleneck. PMs sit on pages of raw notes for days, insights go stale, patterns get missed, and the roadmap ends up reflecting whoever spoke loudest rather than what the data actually shows.

This tool eliminates that bottleneck. It doesn't replace the judgment of an experienced PM — it removes the grunt work so that judgment can be applied where it matters most: deciding what to build and why.

The Jobs-to-be-Done framework is the analytical backbone. JTBD cuts through surface-level feature requests to expose the underlying motivation — the real reason a user is struggling. That's the insight that drives durable product decisions.

Built as part of the **AI PM Toolkit** at [Motionova Labs](https://motionovalabs.com) — a series of AI tools designed around real PM workflows, not theoretical ones.

---

## Built With

- **Vanilla HTML / CSS / JavaScript** — zero dependencies, runs in any browser
- **Anthropic Claude API** (`claude-sonnet-4-20250514`) — JTBD extraction and structured insight generation
- **GitHub Pages** — zero-infrastructure deployment

---

## How to Run Locally

```bash
# Clone the repo
git clone https://github.com/eval4576/ai-discovery-analyzer.git

# Open directly in browser — no build step, no server needed
open index.html
```

The app calls the Anthropic API directly from the browser. No backend required.

---

## Example Use Cases

| Interview Subject | Domain | Discovery Goal |
|---|---|---|
| Ghost kitchen operators managing multiple delivery platforms | Multi-sided Marketplace | Identify unmet needs and friction points |
| Dealership service managers at enterprise accounts | Automotive SaaS | Understand workflow and process gaps |
| New B2B customers in first 60 days post-signup | B2B SaaS | Evaluate activation and onboarding gaps |
| Product managers at growth-stage startups | AI / Productivity | Prioritize roadmap opportunities |

---

## The PM Thinking Behind It

Most discovery tools ask you to structure your notes before you get insights. That's backwards. Real interviews are messy — people interrupt themselves, go off-topic, say one thing and mean another.

This tool is designed to work with raw, unstructured notes because that's what PMs actually have. The AI applies the structure after the fact, the way a senior PM would when reviewing a junior researcher's 
