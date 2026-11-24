# AGENTS.md

Instructions for coding agents working in this repository.

## What this repo is

`ai-agent-tools` is a public, bilingual awesome list of tools, APIs, MCP servers, SDKs and frameworks for AI agents, maintained by fluyeporlaweb. The main artifacts are `README.md` (English) and `README.es.md` (Spanish). They must stay in sync.

The maintainer is Pablo ([@fluyeporlaweb](https://x.com/fluyeporlaweb)). The project is MIT licensed. The sponsor page is https://fluyeporlaweb.com/patrocina.

This is not a monorepo of tools we invent on every commit. The directory `tools/` is reserved for tools that fluyeporlaweb itself builds and publishes. Most contributions are new or updated list entries.

## Repository layout

```
.
├── README.md            # main list, English
├── README.es.md         # same list, Spanish
├── AGENTS.md            # this file
├── CONTRIBUTING.md      # contribution rules, EN + ES
├── SECURITY.md          # vulnerability reporting
├── llms.txt             # short project summary for LLMs
├── tools/               # tools built by fluyeporlaweb (optional)
│   ├── README.md
│   ├── README.es.md
│   └── _template/       # starting point for a tool we publish
└── .github/             # issue and PR templates, logo
```

## Adding or changing a list entry

1. Add or edit the line in both `README.md` and `README.es.md`, in the same category, using the format `- [Name](url) - Description.`
2. Update the category count in the Contents / Índice of both files.
3. Do not invent facts. One sentence, no superlatives, no prices, no internal strategy.
4. Do not add your own affiliate query parameters. Existing affiliate entries use `https://fluyeporlaweb.com/go/<slug>/?p=github-readme` and are marked *affiliate* / *afiliado*.
5. Do not copy blocks from other awesome lists. Select, deduplicate and write our own descriptions.
6. Verify the URL (it should respond) before opening a pull request.

## Adding a tool that we build

1. Copy `tools/_template/` to `tools/<tool-name>/`. Use lowercase and hyphens.
2. Write `README.md` and `README.es.md` and keep them in sync.
3. Mention the tool in the "Built by fluyeporlaweb" / "Hecho por fluyeporlaweb" section of both root READMEs, and in `llms.txt`.
4. Keep `.env.example` free of real secrets.

## Conventions

- Public docs are written in English and Spanish. Spanish should read as Spanish of Spain, not as a literal translation.
- Do not commit secrets, tokens, `.env` files or API keys.
- Do not mention pricing, sponsorship packages, SEO tactics or internal decisions in public files.
- Leave the logo header (`logo.png` in `.github/assets/`) at the top of both READMEs.
