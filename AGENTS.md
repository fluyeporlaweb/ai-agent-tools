# AGENTS.md

Instructions for coding agents working in this repository.

## What this repo is

`ai-agent-tools` is the public monorepo where fluyeporlaweb builds and publishes tools for AI agents: MCP servers, agent skills and scripts. It is documentation-first: the root README and every tool README are written for humans and for agents.

The maintainer is Pablo ([@fluyeporlaweb](https://x.com/fluyeporlaweb)). The project is MIT licensed.

## Repository layout

```
.
├── README.md            # main README, English
├── README.es.md         # Spanish README, same structure
├── AGENTS.md            # this file
├── CONTRIBUTING.md      # contribution rules, EN + ES
├── SECURITY.md          # vulnerability reporting
├── tools/
│   ├── README.md        # how the monorepo is laid out
│   ├── README.es.md
│   ├── _template/       # starting point for a new tool
│   └── <tool-name>/     # one directory per tool
├── .github/             # issue and PR templates
├── llms.txt             # short project summary for LLMs
└── SEO.md               # GitHub repository listing proposal
```

## Adding a tool

1. Copy `tools/_template/` to `tools/<tool-name>/`. Use lowercase and hyphens for the directory name.
2. Fill in `README.md` and `README.es.md`. Both are required and must stay in sync. Do not publish one language and leave the other as a placeholder.
3. Update `TOOL.md` with the tool type and a one-line description.
4. Put the code in `src/`. Add tests if the tool contains code. If it is a skill, keep the `SKILL.md` in the tool directory.
5. Add the tool to the table in the root `README.md` and `README.es.md`, and to `llms.txt`.
6. Keep `.env.example` free of real values. Only document the variable names the tool needs.

## Conventions

- Public docs are written in English and Spanish. English is the source of truth for the main README; the Spanish version should read naturally, not as a literal translation.
- Use MIT for new code. Do not add a different license without asking the maintainer.
- Never commit secrets, tokens, API keys, `.env` files or credentials. `.env` is gitignored; `.env.example` is not.
- Do not invent tools, packages, badges or links that are not part of the project.
- Keep the tone concrete and short. Avoid superlatives and marketing filler.
- Do not add prices or internal planning notes to public files.
- If you change a tool's behavior, update its README and, when present, its tests.
- Run the tool's own tests and linters before proposing a change. There is no root-level build yet; each tool is responsible for its own setup.

## Status markers

`Coming soon` / `Próximamente` in the tools table is valid for tools that are announced but not yet in the monorepo. Do not add placeholder code for a tool that is still marked as coming soon.
