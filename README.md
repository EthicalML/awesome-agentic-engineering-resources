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

- ⭐ 🆓 [**Building effective agents**](https://www.anthropic.com/engineering/building-effective-agents) — Anthropic (2024). The most-cited reference for agent design patterns (augmented LLM, prompt chaining, routing, parallelisation, orchestrator-workers, evaluator-optimiser, autonomous agents). Start here before any other agent reading.
- ⭐ 🆓 [**How we built our multi-agent research system**](https://www.anthropic.com/engineering/built-multi-agent-research-system) — Anthropic (2025). Production retrospective on Claude's multi-agent research mode: orchestrator/subagent split, prompt engineering for agents, evaluation and failure modes.
- ⭐ 🆓 [**A practical guide to building agents**](https://cdn.openai.com/business-guides-and-resources/a-practical-guide-to-building-agents.pdf) — OpenAI (2025). 30-page PDF covering when (and when not) to build agents, tool design, guardrails, and human-in-the-loop patterns.
- ⭐ 🆓 [**The bitter lesson of AI agents**](https://lucumr.pocoo.org/2025/6/12/agentic-coding/) / [**Agentic Coding: The Future of Software Development with Agents**](https://lucumr.pocoo.org/) — Armin Ronacher (2025). Widely-shared essays on what it actually feels like to ship with agentic coding tools day-to-day.
- 🆓 [**Claude Code: Best practices for agentic coding**](https://www.anthropic.com/engineering/claude-code-best-practices) — Anthropic (2025). CLAUDE.md, slash-commands, headless mode, custom permissions — the canonical how-to-use-Claude-Code reference.
- 🆓 [**How to build an agent**](https://ampcode.com/how-to-build-an-agent) — Thorsten Ball / Amp (2025). Viral step-by-step implementation of a tool-using coding agent in ~400 lines of Go, demystifying "what is an agent" in code.
- 🆓 [**The new code**](https://www.latent.space/p/new-code) — Sean Grove / OpenAI on Latent Space (2025). Specs-as-code: the spec is the new artefact, models are the compiler. Heavily cited in the AGENTS.md / spec-kit discussion.
- 🆓 [**AGENTS.md**](https://agents.md/) — Community standard (2025) for per-repo agent instructions, now read by Claude Code, Codex, Aider, Cursor, Cline, Windsurf and others.

<a name="core"></a>
## 🧭 Core & Foundations

*Canonical "what is agentic engineering / AI engineering" reading. Start here.*

### T1 · Coding Agents & AI-Assisted Development

- ⭐ 🆓 [**Building effective agents**](https://www.anthropic.com/engineering/building-effective-agents) — Anthropic. The reference taxonomy of agent design patterns (workflows vs. agents).
- ⭐ 🆓 [**Claude Code: Best practices for agentic coding**](https://www.anthropic.com/engineering/claude-code-best-practices) — Anthropic. CLAUDE.md, tools, slash-commands, headless mode.
- 🆓 [**How to build an agent**](https://ampcode.com/how-to-build-an-agent) — Thorsten Ball. A working coding agent in ~400 lines; the clearest "agents are not magic" walkthrough.
- 🆓 [**Here's how I use LLMs to help me write code**](https://simonwillison.net/2025/Mar/11/using-llms-for-code/) — Simon Willison. Grounded, practice-first account of daily LLM-assisted development.

### T2 · Spec-Driven Development & Context Engineering

- ⭐ 🆓 [**The new code**](https://www.latent.space/p/new-code) — Sean Grove (OpenAI) on Latent Space. The canonical "specs are the new code" essay.
- 🆓 [**AGENTS.md**](https://agents.md/) — Community standard for per-repo agent instructions.
- 🆓 [**spec-kit**](https://github.com/github/spec-kit) — GitHub's toolkit and essay set on spec-driven development with coding agents.
- 🆓 [**The rise of "context engineering"**](https://blog.langchain.com/the-rise-of-context-engineering/) — LangChain. Why prompt engineering became context engineering.

### T6 · LLM Application Architecture & System Design

- ⭐ 📘 💰 [**AI Engineering**](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) — Chip Huyen (O'Reilly, 2025). The textbook for building LLM applications end-to-end.
- ⭐ 🆓 [**Patterns for Building LLM-based Systems & Products**](https://eugeneyan.com/writing/llm-patterns/) — Eugene Yan. Evaluation, RAG, fine-tuning, caching, guardrails, defensive UX, collecting feedback — the reference pattern catalogue.
- 🆓 [**Emerging Architectures for LLM Applications**](https://a16z.com/emerging-architectures-for-llm-applications/) — a16z. The widely-shared reference diagram for the LLM app stack.
- 🆓 [**What We Learned from a Year of Building with LLMs**](https://applied-llms.org/) — Yan, Bensal, Bhawal, Husain, Shankar (2024). Tactical, operational, and strategic lessons distilled from shipping.

### T7 · Prompt Engineering

- ⭐ 🆓 [**Prompt Engineering**](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/) — Lilian Weng (OpenAI). The systematic taxonomy.
- 🆓 [**Prompt Engineering Guide**](https://www.promptingguide.ai/) — DAIR.AI. Continuously updated, with per-technique deep-dives.
- 🆓 [**OpenAI: Prompt engineering**](https://platform.openai.com/docs/guides/prompt-engineering) — OpenAI official guide.
- 🆓 [**Anthropic: Prompt engineering overview**](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) — Anthropic's practical guide for Claude.

### T8 · Retrieval-Augmented Generation (RAG)

- ⭐ 📄 🆓 [**Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks**](https://arxiv.org/abs/2005.11401) — Lewis et al. (2020). The original RAG paper.
- ⭐ 🆓 [**Advanced RAG Techniques**](https://www.pinecone.io/learn/advanced-rag-techniques/) / [**Pinecone Learn**](https://www.pinecone.io/learn/) — Pinecone. The hub for RAG primers and patterns.
- 🆓 [**Retrieval-Augmented Generation for LLMs: A Survey**](https://arxiv.org/abs/2312.10997) — Gao et al. (2023). The reference survey.
- 🆓 [**RAG is more than just embedding search**](https://jxnl.co/writing/2024/06/11/rag-is-more-than-just-embedding-search/) — Jason Liu. Systems-view RAG: query understanding, tool routing, evaluation.

### T10 · Tool Use, Function Calling & MCP

- ⭐ 🆓 [**Introducing the Model Context Protocol**](https://www.anthropic.com/news/model-context-protocol) — Anthropic (2024). The canonical introduction to MCP.
- ⭐ 🆓 [**Model Context Protocol — Specification**](https://modelcontextprotocol.io/) — Open protocol docs and SDKs.
- 📄 🆓 [**Toolformer: Language Models Can Teach Themselves to Use Tools**](https://arxiv.org/abs/2302.04761) — Schick et al. (2023). The foundational tool-use paper.
- 🆓 [**Function calling guide**](https://platform.openai.com/docs/guides/function-calling) — OpenAI. The canonical reference for structured tool calls.

### T11 · Orchestration, Planning & Design Patterns

- ⭐ 🆓 [**Building effective agents**](https://www.anthropic.com/engineering/building-effective-agents) — Anthropic. The orchestration pattern taxonomy.
- 🆓 [**LLM Powered Autonomous Agents**](https://lilianweng.github.io/posts/2023-06-23-agent/) — Lilian Weng. The canonical deep-dive on planning, memory, and tool use in agent loops.
- 📄 🆓 [**ReAct: Synergizing Reasoning and Acting in Language Models**](https://arxiv.org/abs/2210.03629) — Yao et al. (2022). The foundational reason+act loop.
- 📄 🆓 [**The Rise and Potential of LLM Based Agents: A Survey**](https://arxiv.org/abs/2309.07864) — Xi et al. (2023). Survey of agent architectures and components.

### T13 · Evaluation & Testing

- ⭐ 🆓 [**Your AI Product Needs Evals**](https://hamel.dev/blog/posts/evals/) — Hamel Husain. The most-cited essay on why and how to build evals for LLM products.
- 🆓 [**Task-Specific LLM Evals that Do & Don't Work**](https://eugeneyan.com/writing/evals/) — Eugene Yan. A pragmatic survey of eval techniques per task type.
- 📄 🆓 [**Judging LLM-as-a-Judge**](https://arxiv.org/abs/2306.05685) — Zheng et al. (2023). The foundational LLM-as-judge paper (MT-Bench, Chatbot Arena).
- 🆓 [**Who Validates the Validators? Aligning LLM-Assisted Evaluation of LLM Outputs with Human Preferences**](https://arxiv.org/abs/2404.12272) — Shankar et al. (2024). How to make LLM-judges trustworthy.

<a name="milestones"></a>
## 🗓️ Milestones Timeline

*Dated, field-defining events that shaped agentic & AI engineering.*

| Date | Event | Reference |
|---|---|---|
| 2017-06 | Transformer architecture introduced | [Attention Is All You Need](https://arxiv.org/abs/1706.03762) |
| 2020-05 | GPT-3 shows in-context learning at scale | [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) |
| 2020-05 | RAG framework introduced | [RAG for Knowledge-Intensive NLP](https://arxiv.org/abs/2005.11401) |
| 2021-06 | GitHub Copilot preview launches — first mainstream AI coding assistant | [GitHub blog](https://github.blog/news-insights/product-news/introducing-github-copilot-ai-pair-programmer/) |
| 2022-01 | Chain-of-Thought prompting | [Wei et al.](https://arxiv.org/abs/2201.11903) |
| 2022-03 | InstructGPT / RLHF | [Ouyang et al.](https://arxiv.org/abs/2203.02155) |
| 2022-10 | ReAct: reasoning + acting agent loop | [Yao et al.](https://arxiv.org/abs/2210.03629) |
| 2022-11 | ChatGPT release — mainstream adoption inflection | [OpenAI](https://openai.com/index/chatgpt/) |
| 2023-03 | GPT-4 release | [OpenAI](https://openai.com/index/gpt-4/) |
| 2023-03 | HuggingGPT / Toolformer-era tool use | [Toolformer](https://arxiv.org/abs/2302.04761) |
| 2023-03 | LangChain & LlamaIndex hit mainstream | — |
| 2023-05 | Voyager: open-ended agents in Minecraft | [Voyager](https://arxiv.org/abs/2305.16291) |
| 2023-06 | Simon Willison coins "prompt injection" as a durable threat category | [SW blog](https://simonwillison.net/series/prompt-injection/) |
| 2023-10 | SWE-bench released — real-world coding eval | [SWE-bench](https://www.swebench.com/) |
| 2023-12 | Mixture-of-experts open models (Mixtral) | [Mistral](https://mistral.ai/news/mixtral-of-experts/) |
| 2024-03 | Devin demo — autonomous software agent pitch | [Cognition](https://cognition.ai/blog/introducing-devin) |
| 2024-05 | GPT-4o: native multi-modal + realtime voice | [OpenAI](https://openai.com/index/hello-gpt-4o/) |
| 2024-06 | Anthropic's "Building effective agents" publishes | [Anthropic](https://www.anthropic.com/engineering/building-effective-agents) |
| 2024-07 | SWE-bench Verified launched | [OpenAI](https://openai.com/index/introducing-swe-bench-verified/) |
| 2024-09 | o1 reveals reasoning-model era | [OpenAI](https://openai.com/index/learning-to-reason-with-llms/) |
| 2024-11 | Model Context Protocol (MCP) announced | [Anthropic](https://www.anthropic.com/news/model-context-protocol) |
| 2025-02 | Claude Code general availability | [Anthropic](https://www.anthropic.com/claude-code) |
| 2025-05 | AGENTS.md published as cross-agent standard | [agents.md](https://agents.md/) |
| 2025-06 | GitHub spec-kit / "new code" essays formalise spec-driven dev | [spec-kit](https://github.com/github/spec-kit) |

<a name="communities"></a>
## 👥 Communities

*Discords, Slacks, forums, and meetups where practitioners gather.*

- 🆓 [**MLOps Community**](https://mlops.community/) — Slack + podcast + meetups; the biggest practitioner community at the ops/engineering intersection. Active agent and LLM-ops channels.
- 🆓 [**LangChain Discord**](https://discord.gg/langchain) — Heavy day-to-day Q&A on agent orchestration, RAG, evaluation, MCP.
- 🆓 [**LlamaIndex Discord**](https://discord.gg/dGcwcsnxhU) — RAG-centric builder community with active reference-impl discussion.
- 🆓 [**r/LocalLLaMA**](https://www.reddit.com/r/LocalLLaMA/) — The definitive open-weights / local-inference forum; fastest signal for new models, quantisation, and serving.
- 🆓 [**r/MachineLearning**](https://www.reddit.com/r/MachineLearning/) — Academic and practitioner mix; where new papers and threads get dissected.
- 🆓 [**Hacker News**](https://news.ycombinator.com/) — Filter for "LLM", "agent", "Claude", "Cursor" — where engineering-side essays trend.
- 🆓 [**EleutherAI Discord**](https://discord.gg/zBGx3azzUn) — Open research community; strong training/interpretability discussion.
- 🆓 [**Hugging Face Discord & Forums**](https://huggingface.co/join/discord) — Transformers, TRL, PEFT, model-hub discussions.
- 🆓 [**AI Engineer World's Fair / Latent Space Discord**](https://discord.gg/latent-space) — Practitioner community anchoring the AI Engineer conference series.
- 🆓 [**Cursor Community Forum**](https://forum.cursor.com/) — User-driven forum for Cursor rules, MCP, and workflows.
- 🆓 [**Anthropic Discord**](https://www.anthropic.com/discord) — Official Claude / Claude Code / MCP community.

<a name="courses"></a>
## 🧑‍🎓 Courses

*Structured courses — free and paid, university and industry.*

### T1 · Coding Agents & AI-Assisted Development

- ⭐ 🧑‍🎓 🆓 [**AI Python for Beginners**](https://www.deeplearning.ai/short-courses/ai-python-for-beginners/) — DeepLearning.AI (Andrew Ng). Gateway to AI-assisted coding.
- 🧑‍🎓 🆓 [**Pair Programming with a Large Language Model**](https://www.deeplearning.ai/short-courses/pair-programming-llm/) — DeepLearning.AI + Google.
- 🧑‍🎓 🆓 [**GitHub Copilot Fundamentals**](https://learn.microsoft.com/en-us/training/paths/copilot/) — Microsoft Learn. Official training path.

### T4 · SWE Benchmarks & Coding Evaluation

- 🧑‍🎓 🆓 [**Evaluating and Debugging Generative AI**](https://www.deeplearning.ai/short-courses/evaluating-debugging-generative-ai/) — DeepLearning.AI + W&B. Covers coding-eval mechanics.
- 🧑‍🎓 🆓 [**Mastering LLMs: Evals**](https://maven.com/parlance-labs/evals) — Hamel Husain & Shreya Shankar (Maven). Companion evals-for-LLMs curriculum.
- 🧑‍🎓 🆓 [**SWE-bench tutorial**](https://www.swebench.com/lite.html) — Princeton NLP. Free, self-paced walk-through of running and scoring coding evals.

### T6 · LLM Application Architecture & System Design

- ⭐ 🧑‍🎓 🆓 [**LLM Bootcamp**](https://fullstackdeeplearning.com/llm-bootcamp/) — Full Stack Deep Learning. Free 2-day bootcamp on building LLM apps end-to-end.
- 🧑‍🎓 🆓 [**Building Systems with the ChatGPT API**](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/) — DeepLearning.AI + OpenAI.
- 🧑‍🎓 🆓 [**CS25: Transformers United**](https://web.stanford.edu/class/cs25/) — Stanford. Seminal deep-dive seminar series.

### T7 · Prompt Engineering

- ⭐ 🧑‍🎓 🆓 [**ChatGPT Prompt Engineering for Developers**](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) — Andrew Ng & Isa Fulford (OpenAI).
- 🧑‍🎓 🆓 [**Anthropic Prompt Engineering Interactive Tutorial**](https://github.com/anthropics/prompt-eng-interactive-tutorial) — Anthropic. Hands-on, notebook-based.
- 🧑‍🎓 🆓 [**Prompt Engineering Guide (DAIR.AI)**](https://www.promptingguide.ai/) — Self-paced, continuously updated.

### T8 · Retrieval-Augmented Generation (RAG)

- 🧑‍🎓 🆓 [**Advanced Retrieval for AI with Chroma**](https://www.deeplearning.ai/short-courses/advanced-retrieval-for-ai/) — DeepLearning.AI.
- 🧑‍🎓 🆓 [**Building and Evaluating Advanced RAG Applications**](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/) — DeepLearning.AI + LlamaIndex + TruEra.
- 🧑‍🎓 🆓 [**LangChain Chat with Your Data**](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/) — DeepLearning.AI + LangChain.
- 🧑‍🎓 💰 [**Systematically Improving RAG Applications**](https://maven.com/applied-llms/rag-playbook) — Jason Liu on Maven.

### T10 · Tool Use, Function Calling & MCP

- 🧑‍🎓 🆓 [**Functions, Tools and Agents with LangChain**](https://www.deeplearning.ai/short-courses/functions-tools-agents-langchain/) — DeepLearning.AI + LangChain.
- 🧑‍🎓 🆓 [**MCP: Build Rich-Context AI Apps with Anthropic**](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/) — DeepLearning.AI + Anthropic.
- 🧑‍🎓 🆓 [**Introduction to MCP**](https://modelcontextprotocol.io/quickstart) — Anthropic official quickstart.

### T11 · Orchestration, Planning & Design Patterns

- 🧑‍🎓 🆓 [**AI Agents in LangGraph**](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/) — DeepLearning.AI + LangChain.
- 🧑‍🎓 🆓 [**AI Agentic Design Patterns with AutoGen**](https://www.deeplearning.ai/short-courses/ai-agentic-design-patterns-with-autogen/) — DeepLearning.AI + Microsoft.
- 🧑‍🎓 🆓 [**Hugging Face Agents Course**](https://huggingface.co/learn/agents-course) — Hugging Face. Free, certifying course on agent fundamentals.

### T12 · Multi-Agent Systems

- 🧑‍🎓 🆓 [**Multi AI Agent Systems with crewAI**](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/) — DeepLearning.AI + crewAI.
- 🧑‍🎓 🆓 [**Practical Multi AI Agents and Advanced Use Cases with crewAI**](https://www.deeplearning.ai/short-courses/practical-multi-ai-agents-and-advanced-use-cases-with-crewai/) — DeepLearning.AI.
- 🧑‍🎓 🆓 [**Building Agentic RAG with LlamaIndex**](https://www.deeplearning.ai/short-courses/building-agentic-rag-with-llamaindex/) — DeepLearning.AI + LlamaIndex.

### T13 · Evaluation & Testing

- ⭐ 🧑‍🎓 💰 [**AI Evals For Engineers & PMs**](https://maven.com/parlance-labs/evals) — Hamel Husain & Shreya Shankar on Maven. The industry-standard evals cohort course.
- 🧑‍🎓 🆓 [**Quality and Safety for LLM Applications**](https://www.deeplearning.ai/short-courses/quality-safety-llm-applications/) — DeepLearning.AI + WhyLabs.
- 🧑‍🎓 🆓 [**Automated Testing for LLMOps**](https://www.deeplearning.ai/short-courses/automated-testing-llmops/) — DeepLearning.AI + CircleCI.

### T14 · Observability, Tracing & Debugging

- 🧑‍🎓 🆓 [**LLMOps**](https://www.deeplearning.ai/short-courses/llmops/) — DeepLearning.AI + Google Cloud.
- 🧑‍🎓 🆓 [**Evaluating LLMs with Arize**](https://arize.com/llm-evaluation/) — Arize course hub.
- 🧑‍🎓 🆓 [**LangSmith Academy**](https://academy.langchain.com/) — LangChain. Free self-paced LangSmith courses covering tracing and evals.

### T15 · Guardrails & Security

- 🧑‍🎓 🆓 [**Red Teaming LLM Applications**](https://www.deeplearning.ai/short-courses/red-teaming-llm-applications/) — DeepLearning.AI + Giskard.
- 🧑‍🎓 🆓 [**Safe and Reliable AI via Guardrails**](https://www.deeplearning.ai/short-courses/safe-and-reliable-ai-via-guardrails/) — DeepLearning.AI + Guardrails AI.
- 🧑‍🎓 🆓 [**Prompt Injection Attacks (Learn Prompting)**](https://learnprompting.org/docs/prompt_hacking/injection) — Learn Prompting. Open course covering injection/jailbreak taxonomies.

### T16 · Safety, Alignment & Responsible AI

- 🧑‍🎓 🆓 [**AI Safety Fundamentals**](https://aisafetyfundamentals.com/) — BlueDot Impact. The standard entry curriculum.
- 🧑‍🎓 🆓 [**ARENA (Alignment Research Engineer Accelerator)**](https://www.arena.education/) — Hands-on alignment / interpretability.
- 🧑‍🎓 🆓 [**Intro to AI Safety, Remastered**](https://course.aisafetyfundamentals.com/alignment) — Richard Ngo / BlueDot. Free reading curriculum.

### T17 · Fine-tuning, Post-training & RLHF

- ⭐ 🧑‍🎓 🆓 [**Finetuning Large Language Models**](https://www.deeplearning.ai/short-courses/finetuning-large-language-models/) — DeepLearning.AI + Lamini.
- 🧑‍🎓 🆓 [**Reinforcement Learning from Human Feedback**](https://www.deeplearning.ai/short-courses/reinforcement-learning-from-human-feedback/) — DeepLearning.AI + Google Cloud.
- 🧑‍🎓 🆓 [**Hugging Face NLP Course (incl. RLHF chapter)**](https://huggingface.co/learn/nlp-course) — Hugging Face.

### T18 · Inference, Serving, Cost & Latency

- 🧑‍🎓 🆓 [**Efficiently Serving LLMs**](https://www.deeplearning.ai/short-courses/efficiently-serving-llms/) — DeepLearning.AI + Predibase.
- 🧑‍🎓 🆓 [**Quantization Fundamentals with Hugging Face**](https://www.deeplearning.ai/short-courses/quantization-fundamentals-with-hugging-face/) — DeepLearning.AI + HF.
- 🧑‍🎓 🆓 [**CUDA Mode lectures**](https://github.com/cuda-mode/lectures) — Community lectures on GPU inference internals.

<a name="books"></a>
## 📘 Books

*Published and in-progress books covering agentic & AI engineering.*

### T1 · Coding Agents & AI-Assisted Development

- ⭐ 📘 💰 [**AI-Assisted Programming**](https://www.oreilly.com/library/view/ai-assisted-programming/9781098164555/) — Tom Taulli (O'Reilly, 2024). Practical coverage of Copilot/Cursor/Claude workflows.
- 📘 💰 [**Prompt Engineering for Generative AI**](https://www.oreilly.com/library/view/prompt-engineering-for/9781098153427/) — James Phoenix & Mike Taylor (O'Reilly, 2024). Includes heavy coverage of code-generation prompting patterns.

### T6 · LLM Application Architecture & System Design

- ⭐ 📘 💰 [**AI Engineering: Building Applications with Foundation Models**](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) — Chip Huyen (O'Reilly, 2025). The reference textbook for the field.
- 📘 💰 [**Designing Machine Learning Systems**](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) — Chip Huyen (O'Reilly, 2022). The prior-generation canonical ML-systems text; still essential for data/infra context.
- 📘 💰 [**Generative AI on AWS**](https://www.oreilly.com/library/view/generative-ai-on/9781098159214/) — Chris Fregly, Antje Barth, Shelbee Eigenbrode (O'Reilly, 2023).

### T7 · Prompt Engineering

- 📘 🆓 [**Prompt Engineering for LLMs**](https://www.oreilly.com/library/view/prompt-engineering-for/9781098156145/) — John Berryman & Albert Ziegler (O'Reilly, 2024). From Copilot's original tech-lead.
- 📘 💰 [**The Prompt Report**](https://arxiv.org/abs/2406.06608) — Schulhoff et al. (2024). A 76-page survey that effectively functions as a book-length prompting reference.

### T8 · RAG

- 📘 💰 [**Building LLM Apps**](https://www.wiley.com/en-us/Building+LLM+Apps%3A+Create+Intelligent+Apps+and+Agents+with+Large+Language+Models-p-9781394250202) — Valentina Alto (Wiley, 2024). RAG-heavy application text.
- 📘 🆓 [**RAG-Driven Generative AI**](https://www.packtpub.com/en-us/product/rag-driven-generative-ai-9781836200918) — Denis Rothman (Packt, 2024).

### T10 · Tool Use & MCP

- 📘 💰 [**Building Intelligent Apps with OpenAI**](https://www.oreilly.com/library/view/building-intelligent-apps/9781098159450/) — Olivier Caelen & Marie-Alice Blete (O'Reilly, 2024). Heavy function-calling coverage.

### T11 · Orchestration & Design Patterns

- 📘 💰 [**Generative AI with LangChain**](https://www.packtpub.com/en-in/product/generative-ai-with-langchain-9781835083468) — Ben Auffarth (Packt, 2023). Orchestration patterns end-to-end.

### T13 · Evaluation

- 📘 💰 [**Prompt Engineering for Generative AI**](https://www.oreilly.com/library/view/prompt-engineering-for/9781098153427/) — Phoenix & Taylor (O'Reilly, 2024). Chapter-length eval coverage.

### T15 · Guardrails & Security

- 📘 💰 [**The Developer's Playbook for Large Language Model Security**](https://www.oreilly.com/library/view/the-developers-playbook/9781098162191/) — Steve Wilson (O'Reilly, 2024). OWASP LLM Top 10 project lead's book.
- 📘 💰 [**Generative AI Security**](https://link.springer.com/book/10.1007/979-8-8688-0277-1) — Ken Huang et al. (Apress, 2024).

### T16 · Safety, Alignment & Responsible AI

- 📘 💰 [**Human Compatible**](https://people.eecs.berkeley.edu/~russell/hc.html) — Stuart Russell (2019). The foundational alignment argument.
- 📘 💰 [**The Alignment Problem**](https://brianchristian.org/the-alignment-problem/) — Brian Christian (2020). The canonical popular-press primer.

### T17 · Fine-tuning & Post-training

- ⭐ 📘 💰 [**Build a Large Language Model (From Scratch)**](https://www.manning.com/books/build-a-large-language-model-from-scratch) — Sebastian Raschka (Manning, 2024). The reference hands-on text.
- 📘 💰 [**Hands-On Large Language Models**](https://www.oreilly.com/library/view/hands-on-large-language/9781098150952/) — Jay Alammar & Maarten Grootendorst (O'Reilly, 2024).

### T18 · Inference & Serving

- 📘 💰 [**Efficient Processing of Deep Neural Networks**](https://link.springer.com/book/10.1007/978-3-031-01766-7) — Sze et al. (Morgan & Claypool). Hardware/inference reference.

### T20 · Product & UX

- 📘 💰 [**Designing Machine Learning Systems**](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) — Chip Huyen. Includes pragmatic product/UX chapters.
- 📘 💰 [**Human-AI Interaction Design**](https://www.interaction-design.org/literature/topics/ai-interaction-design) — IxDF topic hub.

### T21 · Economics, Teams & Org

- 📘 💰 [**Managing Machine Learning Projects**](https://www.manning.com/books/managing-machine-learning-projects) — Simon Thompson (Manning).
- 📘 🆓 [**The Pragmatic Engineer's AI coverage**](https://newsletter.pragmaticengineer.com/) — Gergely Orosz. Regularly-updated editorial that functions as a rolling book on AI-engineering org design.

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

