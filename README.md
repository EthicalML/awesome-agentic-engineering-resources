[![Awesome](https://awesome.re/badge.svg?cacheSeconds=86400)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/EthicalML/awesome-agentic-engineering-resources/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/EthicalML/awesome-agentic-engineering-resources?cacheSeconds=86400)](https://github.com/EthicalML/awesome-agentic-engineering-resources/commits/main)
[![Contributors](https://img.shields.io/github/contributors/EthicalML/awesome-agentic-engineering-resources?cacheSeconds=86400)](https://github.com/EthicalML/awesome-agentic-engineering-resources/graphs/contributors)
[![Link Check](https://github.com/EthicalML/awesome-agentic-engineering-resources/actions/workflows/link-check.yml/badge.svg)](https://github.com/EthicalML/awesome-agentic-engineering-resources/actions/workflows/link-check.yml)
[![X](https://img.shields.io/badge/X-%23000000?logo=X&logoColor=white)](https://twitter.com/EthicalML)

# Awesome Agentic Engineering Resources

> A curated list of high-signal resources — articles, books, courses, cookbooks, papers, playbooks, benchmarks, talks, podcasts, and newsletters — for agentic engineering and AI engineering.

This is a *resources* list, not a tools list. Open-source **tools** for building agentic systems live in the sister list [awesome-production-agentic-systems](https://github.com/EthicalML/awesome-production-agentic-systems); production ML tooling lives in [awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning). This list covers the *learning, design, and operational resources* that sit alongside those tools — including both:

- **Agentic engineering** — using AI agents to do software engineering (Copilot, Cursor, Claude Code, Aider, Cline, Windsurf, Codex; spec-driven development; context engineering; agent IDE rules and memory files; SWE benchmarks).
- **AI / agentic systems engineering** — building agentic and LLM-powered systems (architecture, RAG, memory, tool use & MCP, orchestration, multi-agent coordination, evaluation, observability, guardrails, safety, fine-tuning, inference, product/UX, economics, teams).

You can keep up to date by watching this repo for the monthly releases summarising newly added resources 🤩

This list was proposed in [EthicalML/awesome-production-machine-learning#709](https://github.com/EthicalML/awesome-production-machine-learning/issues/709) as a sister list focused on *resources* rather than tools.

## Legend

Resources are tagged with icons so you can scan and filter at a glance:

| Icon | Meaning |
|---|---|
| ⭐ | Editors' pick — start here |
| 🆓 | Free to access |
| 💰 | Paid |
| 📘 | Book |
| 🧑‍🎓 | Course |
| 🎥 | Video / talk |
| 🎧 | Audio / podcast |
| 📄 | Paper |
| 🛠️ | Hands-on cookbook / tutorial |
| 📋 | Playbook / design-pattern catalog |
| 🧪 | Benchmark / leaderboard |
| 🏗️ | Reference implementation / case study |
| 📰 | Newsletter |

## Quick links to sections on this page

|   |   |   |
|---|---|---|
| [⭐ Trending / What's New](#trending) | [🧭 Core & Foundations](#core) | [🗓️ Milestones Timeline](#milestones) |
| [👥 Communities](#communities) | [🧑‍🎓 Courses](#courses) | [📘 Books](#books) |
| [✍️ Articles & Essays](#articles) | [🛠️ Tutorials & Cookbooks](#tutorials) | [📋 Playbooks & Patterns](#playbooks) |
| [📄 Papers & Research](#papers) | [🧪 Benchmarks & Leaderboards](#benchmarks) | [🏗️ Reference Implementations](#references) |
| [🎥 Talks & Conferences](#talks) | [🎧 Podcasts](#podcasts) | [📰 Newsletters](#newsletters) |
| [🛡️ Governance, Safety & Responsible AI](#governance) | [🎨 Product, UX & Economics of AI](#product) | [🧑‍🤝‍🧑 Teams, Hiring & Org Design](#teams) |

## Topic Coverage Matrix

Resources are organised as a **matrix**: the top-level sections above (rows) are resource *types*, and each section is sub-divided by *topic*. The 21 topics, `T1`–`T21`, are shared across sections. This lets you read vertically ("what papers exist on RAG?") or horizontally ("where do I find resources on Coding Agents?").

**Topics:**

| # | Topic |
|---|---|
| T1 | Coding Agents & AI-Assisted Development (Copilot, Cursor, Claude Code, Aider, Cline, Windsurf, Codex) |
| T2 | Spec-Driven Development & Context Engineering (AGENTS.md, spec-kit, rules files) |
| T3 | Agent IDE Rules, Memory Files & Developer Workflows |
| T4 | SWE Benchmarks & Coding Evaluation |
| T5 | Autonomous Software Agents & Long-Horizon Engineering Tasks |
| T6 | LLM Application Architecture & System Design |
| T7 | Prompt Engineering |
| T8 | Retrieval-Augmented Generation (RAG) |
| T9 | Memory Systems & Long-Context |
| T10 | Tool Use, Function Calling & MCP |
| T11 | Orchestration, Planning & Design Patterns |
| T12 | Multi-Agent Systems & Coordination |
| T13 | Evaluation & Testing |
| T14 | Observability, Tracing & Debugging |
| T15 | Guardrails & Security (prompt injection, jailbreaks, red-teaming) |
| T16 | Safety, Alignment & Responsible AI |
| T17 | Fine-tuning, Post-training, RLHF & Reasoning Training |
| T18 | Inference, Serving, Cost & Latency |
| T19 | Voice, Multi-modal & Embodied Agents |
| T20 | Product, UX & Human-AI Interaction Design |
| T21 | Economics, Teams, Hiring & Org Design |

**Coverage** (`●` = populated, `○` = opportunistic / partial, `—` = out of scope for that row):

| Row \ Topic | T1 | T2 | T3 | T4 | T5 | T6 | T7 | T8 | T9 | T10 | T11 | T12 | T13 | T14 | T15 | T16 | T17 | T18 | T19 | T20 | T21 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Core & Foundations | ● | ● | ○ | ○ | ○ | ● | ● | ● | ○ | ● | ● | ○ | ● | ○ | ○ | ○ | ○ | ○ | ○ | ○ | ○ |
| Communities | ● | ○ | ○ | ○ | ○ | ● | ● | ● | ○ | ● | ● | ○ | ● | ● | ○ | ● | ● | ● | ○ | ● | ● |
| Courses | ● | ○ | ○ | ● | ○ | ● | ● | ● | ○ | ● | ● | ● | ● | ● | ● | ● | ● | ● | ○ | ○ | ○ |
| Books | ● | ○ | ○ | — | ○ | ● | ● | ● | ○ | ● | ● | ○ | ● | ○ | ● | ● | ● | ● | ○ | ● | ● |
| Articles & Essays | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● |
| Tutorials & Cookbooks | ● | ● | ● | ○ | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ○ | ● | ● | ● | ○ | — |
| Playbooks & Patterns | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ○ | ● | ○ | ● | ● |
| Papers & Research | ● | ○ | — | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ○ |
| Benchmarks | ● | — | — | ● | ● | ○ | ○ | ● | ○ | ● | ● | ● | ● | ○ | ● | ● | ○ | ● | ● | ○ | — |
| Reference Impls | ● | ● | ● | ● | ● | ● | ○ | ● | ● | ● | ● | ● | ● | ● | ● | ○ | ● | ● | ● | ● | ● |
| Talks & Conferences | ● | ● | ○ | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● | ● |
| Podcasts | ● | ○ | ○ | ○ | ● | ● | ● | ● | ○ | ● | ● | ● | ● | ● | ● | ● | ● | ● | ○ | ● | ● |
| Newsletters | ● | ○ | ○ | ○ | ○ | ● | ● | ● | ○ | ● | ● | ○ | ● | ● | ● | ● | ● | ● | ○ | ● | ● |

The **Trending / What's New**, **Milestones Timeline**, **Governance & Responsible AI**, **Product / UX / Economics**, and **Teams, Hiring & Org Design** sections collapse across topics and are presented as curated lists rather than matrix cells.

## Contributing to the list

Please review our [CONTRIBUTING.md](./CONTRIBUTING.md) before submitting a PR — it explains the one-line description style, how to pick the right row/topic cell, and the quality bar for inclusion. Thank you to the community for supporting the list's growth 🚀

## Want to receive recurrent updates on this repo and other advancements?

<table>
  <tr>
    <td width="30%">
         You can join the <a href="https://ethical.institute/mle.html">Machine Learning Engineer</a> newsletter. Join over 70,000 ML professionals and enthusiasts who receive weekly curated articles & tutorials on production Machine Learning.
    </td>
    <td width="70%">
        <a href="https://ethical.institute/mle.html"><img src="images/mleng.png"></a>
    </td>
  </tr>
  <tr>
    <td width="30%">
         Also check out <a href="https://github.com/EthicalML/awesome-production-agentic-systems">Awesome Production Agentic Systems</a> and <a href="https://github.com/EthicalML/awesome-production-machine-learning">Awesome Production Machine Learning</a>, the sister lists of open-source <em>tools</em> for agentic systems and production ML respectively.
    </td>
    <td width="70%">
        <a href="https://github.com/EthicalML/awesome-production-agentic-systems"><img src="images/list.jpg"></a>
    </td>
  </tr>
</table>

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="
      https://api.star-history.com/svg?repos=EthicalML/awesome-agentic-engineering-resources&type=Date&theme=dark
    "
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="
      https://api.star-history.com/svg?repos=EthicalML/awesome-agentic-engineering-resources&type=Date
    "
  />
  <img
    alt="Star History Chart"
    src="https://api.star-history.com/svg?repos=EthicalML/awesome-agentic-engineering-resources&type=Date"
  />
</picture>

# Main Content

<a name="trending"></a>
## ⭐ Trending / What's New

*Rotating pinned items: the most-discussed agentic & AI-engineering resources of the current cycle. Refreshed regularly — see [CONTRIBUTING.md](./CONTRIBUTING.md) for nomination criteria.*

<a name="core"></a>
## 🧭 Core & Foundations

*Canonical "what is agentic engineering / AI engineering" reading. Start here.*

<a name="milestones"></a>
## 🗓️ Milestones Timeline

*Dated, field-defining events that shaped agentic & AI engineering.*

<a name="communities"></a>
## 👥 Communities

*Discords, Slacks, forums, and meetups where practitioners gather.*

<a name="courses"></a>
## 🧑‍🎓 Courses

*Structured courses — free and paid, university and industry.*

<a name="books"></a>
## 📘 Books

*Published and in-progress books covering agentic & AI engineering.*

<a name="articles"></a>
## ✍️ Articles & Essays

*Long-form writing from canonical authors and engineering teams.*

<a name="tutorials"></a>
## 🛠️ Tutorials & Cookbooks

*Hands-on, code-first guides and official cookbooks from model providers and framework authors.*

<a name="playbooks"></a>
## 📋 Playbooks & Design-Pattern Catalogs

*Opinionated, prescriptive guides distilling design patterns and operational practices.*

<a name="papers"></a>
## 📄 Papers & Research

*Foundational papers, surveys, and benchmark papers. Includes a dated milestone-papers table.*

<a name="benchmarks"></a>
## 🧪 Benchmarks & Leaderboards

*Public benchmarks and leaderboards for coding agents, tool use, RAG, evaluation, and more.*

<a name="references"></a>
## 🏗️ Reference Implementations & Case Studies

*Public production write-ups and canonical reference repositories that teach by example.*

<a name="talks"></a>
## 🎥 Talks, Workshops & Conferences

*Recorded talks, workshops, and conference series worth watching.*

<a name="podcasts"></a>
## 🎧 Podcasts

*Recurring podcasts with strong agentic & AI-engineering coverage.*

<a name="newsletters"></a>
## 📰 Newsletters

*Weekly and monthly curated newsletters.*

<a name="governance"></a>
## 🛡️ Governance, Safety & Responsible AI

*Policy frameworks, safety research, red-teaming resources, and responsible-AI guidance.*

<a name="product"></a>
## 🎨 Product, UX & Economics of AI

*Going beyond engineering: designing for AI, human-AI interaction, and the economics of LLM applications.*

<a name="teams"></a>
## 🧑‍🤝‍🧑 Teams, Hiring & Org Design

*How organisations structure AI-engineering work, hire for it, and operate sustainably.*

---

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/) — To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

