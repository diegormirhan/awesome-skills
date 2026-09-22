# Awesome Skills

A practical collection of reusable skills for AI coding agents. The repository
focuses on software engineering, interface design, documentation, research, and
agent workflows.

## Summary

This collection helps agents produce clear, maintainable results with only the
complexity the task actually requires. It includes reusable guidance for code,
design, documentation, research, RAG, repository contribution, and agent
workflows.

## Just Enough Engineering

[`just-enough-engineering`](./skills/just-enough-engineering/SKILL.md) reduces
accidental complexity across code, documentation, repository exploration,
integrations, MCPs, agent graphs, loops, and architecture while preserving
required behavior and essential safeguards.

It expands the useful behavior-preserving idea behind Brian Lovin's
[`simplify`](https://www.skills.sh/brianlovin/agent-config/simplify) skill into a
language-agnostic, artifact-agnostic method for choosing the smallest sufficient
solution. Its instructions are independently written and avoid the original's
project-specific React and TypeScript conventions.

## Install

Replace `<owner>` with the GitHub account or organization that hosts this
repository:

```bash
npx skills add <owner>/awesome-skills --skill just-enough-engineering
```

List all discoverable skills before installing:

```bash
npx skills add <owner>/awesome-skills --list
```

## Included skills

| Skill | Purpose |
| --- | --- |
| `animate` | Design and implement purposeful interface motion. |
| `apple-design` | Apply Apple-inspired interface and motion principles to the web. |
| `beautiful-article` | Turn source material into a shareable single-file visual article. |
| `clean-code` | Write and refactor readable, maintainable code. |
| `create-readme` | Create a concise, useful project README. |
| `find-skills` | Discover and install skills from the open ecosystem. |
| `git-commit` | Stage changes and create conventional commits. |
| `grill-me` | Stress-test a plan or design through focused questioning. |
| `hallmark` | Build and review interfaces while avoiding generic AI aesthetics. |
| `impeccable` | Design, critique, and polish frontend interfaces. |
| `just-enough-engineering` | Reduce accidental complexity without removing essential quality. |
| `make-repo-contribution` | Follow repository-specific contribution rules. |
| `rag-implementation` | Plan and implement retrieval-augmented generation systems. |
| `skill-creator` | Create, evaluate, and improve agent skills. |
| `svg-logo-designer` | Design professional SVG logos and variations. |

## Repository layout

```text
awesome-skills/
└── skills/
    ├── just-enough-engineering/
    │   ├── SKILL.md
    │   └── evals/
    │       └── evals.json
    └── <skill>/
        └── SKILL.md
```

Each skill is a directory containing a `SKILL.md` with `name` and `description`
frontmatter. Supporting scripts, references, assets, or evaluations are included
only when they add concrete value.

## Publish on skills.sh

There is no separate registry submission command. To make the collection
discoverable:

1. Publish this repository publicly on GitHub.
2. Run the install command above at least once.
3. Visit `https://skills.sh/<owner>/awesome-skills/just-enough-engineering`
   after indexing.

skills.sh derives discovery and rankings from anonymous installation telemetry.
See the official [skills.sh documentation](https://www.skills.sh/docs) and the
[Agent Skills specification](https://agentskills.io/specification) for current
format and publishing requirements.

## Local validation

Validate a skill with the reference implementation before publishing:

```bash
skills-ref validate ./skills/just-enough-engineering
```

The draft evaluation prompts are in
[`skills/just-enough-engineering/evals/evals.json`](./skills/just-enough-engineering/evals/evals.json).
They cover code, documentation, and agent-workflow simplification.
