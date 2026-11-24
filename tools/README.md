# Tools

Each tool in this monorepo lives in its own directory under `tools/`. A tool is self-contained: it has its own README, install steps, configuration and code.

```
tools/
├── _template/       # starting point for a new tool
└── <tool-name>/
    ├── README.md
    ├── README.es.md
    ├── TOOL.md
    ├── .env.example
    └── src/
```

Tools can be MCP servers (TypeScript), agent skills (`SKILL.md`) or scripts (Python or Bash). The type is recorded in `TOOL.md` and in the root tools table.

To add a tool, copy `_template/` and follow [CONTRIBUTING.md](../CONTRIBUTING.md). See the Spanish version in [README.es.md](README.es.md).
