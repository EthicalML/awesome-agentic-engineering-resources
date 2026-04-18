# Curation methodology

This document explains how resources on this list are selected, placed and maintained so that contributors and readers share a common mental model.

## What belongs on this list

**In scope:** *resources* that help you learn, design, build, evaluate and operate agentic and LLM-powered systems — articles, books, courses, cookbooks, tutorials, papers, talks, podcasts, newsletters, benchmarks, reference implementations, and case studies.

**Out of scope:** pure tools, libraries or SaaS products. Those belong in the two sister lists:

- [awesome-production-agentic-systems](https://github.com/EthicalML/awesome-production-agentic-systems) — open-source agentic-system tools.
- [awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning) — open-source production ML tools.

A resource repo may appear here only if its primary value is *teaching* (cookbooks, reference implementations, annotated examples) rather than being a library you depend on.

## Quality bar

Every entry must be:

1. **Substantive** — a full guide, course, book, paper, talk, or cookbook. Not a tweet, not a 300-word marketing post.
2. **Canonical** — referenced by at least one authoritative third-party source (course syllabus, survey, canonical author's reading list, well-known practitioner's post).
3. **Primary** — the original source rather than an aggregator repost.
4. **Durable** — on a host likely to still exist in 2 years. Avoid Medium paywalls, dead personal domains and URL shorteners.
5. **Not duplicative** — substantially different from other entries in the same cell.

## Matrix-first placement

Resources are placed in a **single strongest-fit cell** in the resource-type × topic matrix documented in the README. Cross-referencing is reserved for the **Trending**, **Milestones Timeline**, and **Core & Foundations** sections.

When in doubt, pick the topic the reader would most plausibly *be searching for* when they'd want this resource, and place it in the resource-type that matches its primary format.

## One-line descriptions

Each entry is a single bullet of the form:

```
- [icons] [**Title**](url) — Author / Org. One sentence explaining what you'll learn or why it matters.
```

- **Icons** come from the Legend (⭐🆓💰📘🧑‍🎓🎥🎧📄🛠️📋🧪🏗️📰).
- The sentence is *informational*, not marketing. "A short course on RAG that covers retrieval, re-ranking and evaluation" is good; "Unlock the power of AI!" is bad.
- Prefer ⭐ sparingly — typically 1–2 editors' picks per cell.

## Curation cadence

- **Weekly**: review open PRs, triage issues.
- **Monthly**: review the Trending section, promote evergreen entries to their permanent cells, rotate in new candidates.
- **Quarterly**: full pass against the thoroughness checklist (see below).
- **Continuously**: `lychee` link-check workflow flags broken links; `awesome-lint` and `markdownlint` enforce structural hygiene.

## Thoroughness checklist (per section)

Before merging a section update we verify:

- Each populated cell has ≥ 3–4 entries.
- No cell over-indexes on a single vendor (≥ 2 distinct authors/orgs where possible).
- Each entry has a verified provenance trail (≥ 1 authoritative citation).
- Mix of classic + current (≤ 12 months) material where the topic is fast-moving.
- All links resolve (local `lychee` run).
- One-line descriptions are substantive.
- At least one external "AI canon" reference was cross-checked for omissions.
- No pure tool repos.

## Research inputs

Candidate discovery draws from:

- Canonical practitioner blogs (Anthropic / OpenAI / Google DeepMind / Meta AI engineering blogs; Chip Huyen, Eugene Yan, Hamel Husain, Shreya Shankar, Lilian Weng, Simon Willison, Sebastian Raschka, Jason Liu, Phillip Carter, swyx, Armin Ronacher, Steve Yegge, Maggie Appleton, Linus Lee).
- Conference proceedings (NeurIPS, ICML, ICLR, EMNLP, ACL, COLM, MLSys, CHI, USENIX Security).
- arXiv and Semantic Scholar citation graphs.
- GitHub trending with `stars:>1000` filters for reference implementations.
- Neighbouring awesome lists (cross-referenced rather than copy-pasted).
- Community signal (r/LocalLLaMA, r/MachineLearning, Hacker News, MLOps Community Slack, Latent Space Discord).

## How to propose a change

See [CONTRIBUTING.md](./CONTRIBUTING.md). File an issue (using the templates) for discussion before large restructuring PRs.
