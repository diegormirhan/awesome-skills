# Awesome Skills

A curated collection of reusable skills for AI agents working on software, design, documentation, and research. Install the skills you need and give your agent focused guidance for the task at hand.

Browse the collection on [skills.sh](https://www.skills.sh/diegormirhan/awesome-skills).

## Get started

With Node.js available, use the [skills CLI](https://www.skills.sh/docs) to explore the collection:

```bash
npx skills add diegormirhan/awesome-skills --list
```

Install a specific skill:

```bash
npx skills add diegormirhan/awesome-skills --skill just-enough-engineering
```

Or run `npx skills add diegormirhan/awesome-skills` to choose skills interactively. The CLI will prompt you to select an agent and installation scope.

## Featured: Just Enough Engineering

[Just Enough Engineering](./skills/just-enough-engineering/SKILL.md) helps AI coding agents build and explain software with only the complexity each task requires. Use it to trim redundant code, documentation, repository research, integrations, MCP servers, agent graphs, loops, or architecture without losing required behavior, safety, or quality.

It builds on the idea behind Brian Lovin's [simplify](https://www.skills.sh/brianlovin/agent-config/simplify) skill, with independently written guidance that applies beyond a specific language or framework.

## Skills

| Skill | What it helps with |
| --- | --- |
| [animate](./skills/animate/SKILL.md) | Build purposeful interface animations. |
| [apple-design](./skills/apple-design/SKILL.md) | Apply Apple's interface and motion principles to the web. |
| [beautiful-article](./skills/beautiful-article/SKILL.md) | Turn source material into a shareable, single-file HTML article. |
| [clean-code](./skills/clean-code/SKILL.md) | Write, review, and refactor maintainable code. |
| [create-readme](./skills/create-readme/SKILL.md) | Write a clear project README. |
| [find-skills](./skills/find-skills/SKILL.md) | Discover installable skills. |
| [git-commit](./skills/git-commit/SKILL.md) | Stage changes and write conventional commits. |
| [grill-me](./skills/grill-me/SKILL.md) | Challenge a plan or design through focused questions. |
| [hallmark](./skills/hallmark/SKILL.md) | Build and review interfaces without generic AI aesthetics. |
| [impeccable](./skills/impeccable/SKILL.md) | Design, critique, and polish frontend interfaces. |
| [just-enough-engineering](./skills/just-enough-engineering/SKILL.md) | Choose the smallest sufficient solution without sacrificing essential quality. |
| [make-repo-contribution](./skills/make-repo-contribution/SKILL.md) | Follow a repository's contribution rules. |
| [rag-implementation](./skills/rag-implementation/SKILL.md) | Plan and implement retrieval-augmented generation. |
| [skill-creator](./skills/skill-creator/SKILL.md) | Create, evaluate, and improve agent skills. |
| [svg-logo-designer](./skills/svg-logo-designer/SKILL.md) | Create scalable SVG logos and variations. |

Each directory in [`skills/`](./skills) contains a `SKILL.md` with its instructions. Some skills also include supporting files, such as references, scripts, or evaluations. Browse a skill's files before installing it to see exactly what it does.
