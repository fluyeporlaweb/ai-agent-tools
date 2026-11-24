<p align="center"><img src=".github/assets/logo.png" width="128" alt="ai-agent-tools logo"></p>

# Agent Tools

**Open-source tools for AI agents: MCP servers, agent skills and scripts that Claude, Cursor, Windsurf and any compatible agent can use.** Built and maintained by [fluyeporlaweb](https://fluyeporlaweb.com).

English · [Español](README.es.md)

[![GitHub stars](https://img.shields.io/github/stars/fluyeporlaweb/ai-agent-tools?style=flat)](https://github.com/fluyeporlaweb/ai-agent-tools/stargazers)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## Contents

- [What this is](#what-this-is)
- [Tools](#tools)
- [Install](#install)
- [Sponsors](#sponsors)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## What this is

Agent Tools is the monorepo where [fluyeporlaweb](https://fluyeporlaweb.com) builds and publishes its tools for AI agents: MCP servers, agent skills and small scripts.

This is not an awesome list. Every entry here is a tool we build and maintain. Each one lives in its own folder under [`tools/`](tools/) with its own README, installation steps and usage notes.

## Tools

| Tool | Type | What it does | Status |
| --- | --- | --- | --- |
| [mcp-x-intelligence](https://github.com/fluyeporlaweb/mcp-x-intelligence) | MCP server | X/Twitter research for AI agents | Coming soon |

`mcp-x-intelligence` already exists as a standalone repository. It is the first tool planned for this monorepo. Until it lives here, use the standalone repo.

## Install

This is a monorepo: there is no single package to install. Each tool is installed on its own, using the instructions in its folder. See [`tools/`](tools/README.md) for the layout.

No tool is available in this monorepo yet. When `mcp-x-intelligence` lands here, installing it in an MCP client will follow the usual pattern. This is an example of the shape, not a published package:

```json
{
  "mcpServers": {
    "x-intelligence": {
      "command": "npx",
      "args": ["-y", "<package-name>"]
    }
  }
}
```

The exact package name and options will be documented in the tool's README when it ships.

## Sponsors

This project is free and open source. Brands that support the work appear here.

**[Your brand here](https://fluyeporlaweb.com/patrocina)**

## Contributing

Issues and pull requests are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening one, and follow the [Code of Conduct](CODE_OF_CONDUCT.md).

If you work on the repo with a coding agent, point it to [AGENTS.md](AGENTS.md).

## License

[MIT](LICENSE) © fluyeporlaweb

## Links

- Website: [fluyeporlaweb.com](https://fluyeporlaweb.com)
- X: [@fluyeporlaweb](https://x.com/fluyeporlaweb)
- Telegram: [t.me/fluyeporlaweb](https://t.me/fluyeporlaweb)
