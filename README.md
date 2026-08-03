# Design High-Consideration Landing Pages

An agent skill for designing, reviewing, and rebuilding high-consideration landing pages for courses, memberships, communities, services, and founder-led products.

It helps an agent reason across product value, category and transformation, semantic hierarchy, decision paths, proof, authority, visual argument, mobile experience, and whole-page iteration. The goal is not a universal page formula. It is a stronger product decision and a page whose copy, evidence, design, and conversion path reinforce one another.

## Install

Clone this repository into your Codex skills directory:

```sh
git clone https://github.com/sunyuzheng/design-high-consideration-landing-pages.git ~/.codex/skills/design-high-consideration-landing-pages
```

Restart Codex after installing so the skill can be discovered.

## Use

Invoke it explicitly when useful:

```text
Use $design-high-consideration-landing-pages to review this landing page as a complete decision and brand experience. Identify what already works, the main bottleneck, and the highest-leverage changes.
```

It can also be used to create a page brief or guide an approved implementation. Production publishing and customer-visible edits still require the authorization rules of the active workspace.

## Repository Structure

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── field-notes.md
    └── sources.md
```

`SKILL.md` defines the job, output expectations, failure modes, acceptance criteria, and boundaries. `references/field-notes.md` contains longer case-study observations that should be loaded only when the task needs them.

## Public-Source Boundary

The field notes were abstracted from real revisions of [Stay Superlinear](https://stay.superlinear.academy) and [AI Builders 2027](https://ai-builders.com). They contain reusable reasoning and dated public examples, not private project files, member data, credentials, current product contracts, or permission to copy either product's brand language and page design.

## License

MIT
