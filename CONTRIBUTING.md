# Contribution Guidelines

Thank you for contributing to **Awesome Agentic Engineering Resources**! 🚀

This list is a *resources* list, not a tools list. Open-source tools for building agentic systems belong in the sibling list [awesome-production-agentic-systems](https://github.com/EthicalML/awesome-production-agentic-systems); production ML tools belong in [awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning). Please submit pure-tool entries to the appropriate sibling list.

## Ensure your suggestion is a good fit

Every entry should be:

- **Substantive** — a full article, essay, book, course, paper, cookbook, playbook, talk, podcast, benchmark, or reference implementation. Tweet threads, marketing pages, and short announcement posts do not qualify.
- **Canonical** — repeatedly cited by multiple independent authorities (canonical authors, course syllabi, survey papers, widely-read engineering blogs), or clearly destined to become so.
- **Primary source** — link to the original publication, not an aggregator or reposted copy.
- **Durable** — hosted on a stable domain. Avoid paywalled Medium posts, personal domains that frequently move, and link shorteners.
- **Not already listed** — search the README before opening a PR.
- **Not a pure tool** — if the resource is primarily an open-source library, submit it to the sibling tool lists instead.

## Choosing the right place for your entry

This README is structured as a matrix:

- **Row** = the *type* of resource (Core & Foundations, Courses, Books, Articles, Tutorials & Cookbooks, Playbooks, Papers, Benchmarks, Reference Implementations, Talks, Podcasts, Newsletters, etc.).
- **Topic** (T1–T21) = the *subject area* (Coding Agents, RAG, Memory, Evaluation, Observability, Guardrails, and so on). The topic list is in the [Topic Coverage Matrix](./README.md#topic-coverage-matrix).

Pick the single **strongest-fit row and topic** for your resource. Each entry belongs to **one** cell; cross-references are reserved for the Trending, Milestones, and Core & Foundations sections.

## Entry format

Entries are one-line bullet points, sorted alphabetically within their cell:

```markdown
* [Resource title](https://example.com/resource) 🛠️ 🆓 — One short, informative sentence that explains what the reader will learn or why it matters (author / organisation, year where relevant).
```

Guidelines:

- **Icon tags** — use the icons from the [Legend](./README.md#legend). Combine tags where useful (e.g., `🧑‍🎓 💰` for a paid course, `📄 🧪` for a paper accompanying a benchmark).
- **Description** — one sentence, informative not promotional. Explain *why* this resource matters.
- **No trailing punctuation clutter** — end the sentence with a single period.
- **Author or org** in parentheses at the end is encouraged for articles, papers, talks, and books.
- **Do not** include tracking parameters or affiliate links in URLs.
- **GitHub repositories** that double as a resource (e.g., a cookbook repo) may include a stars shield: `![](https://img.shields.io/github/stars/OWNER/REPO.svg?cacheSeconds=86400)`.

### Good example

```markdown
* [Building LLMs for Production](https://www.towardsai.net/book) 📘 💰 — End-to-end guide to designing, fine-tuning, and deploying LLM applications, covering RAG, evaluation, and observability (Louis-François Bouchard & Louie Peters, 2024).
```

### Bad examples

```markdown
* Check out this amazing new tool I built!                  ← marketing, no link
* [My Blog](https://mysite.com) — Great content            ← not substantive, vague
* [LangChain](https://github.com/langchain-ai/langchain)    ← a tool, belongs in sibling list
```

## PR checklist

Before opening a PR:

- [ ] The resource is substantive, canonical, primary-source, and durable.
- [ ] I searched the README and confirmed this entry is not already listed.
- [ ] I chose the strongest-fit row × topic cell.
- [ ] My entry follows the one-line format with appropriate icon tags.
- [ ] The link resolves (no 404, no redirect chain).
- [ ] My entry is alphabetically sorted within its cell.
- [ ] This is not a pure tool (those belong in the sibling lists).

## Opening an issue

Prefer an issue over a PR when:

- You want to **propose a new topic** (a new `T` cell in the matrix).
- You want to **nominate a resource for the Trending section**.
- You found a **broken link** but are not submitting a replacement.

Issue templates are available under **New Issue** for each of these.

## Code of Conduct

Please read our [Code of Conduct](./CODE_OF_CONDUCT.md). We expect all contributors to uphold it.

## License

By contributing, you agree that your contributions will be released under the same [CC0-1.0](./LICENSE) terms as this repository.
