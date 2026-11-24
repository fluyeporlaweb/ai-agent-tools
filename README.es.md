<p align="center"><img src=".github/assets/logo.png" width="128" alt="ai-agent-tools logo"></p>

# Agent Tools

**Herramientas open source para agentes de IA: servidores MCP, skills y scripts que Claude, Cursor, Windsurf y cualquier agente compatible pueden usar.** Creado y mantenido por [fluyeporlaweb](https://fluyeporlaweb.com).

[English](README.md) · Español

[![GitHub stars](https://img.shields.io/github/stars/fluyeporlaweb/ai-agent-tools?style=flat)](https://github.com/fluyeporlaweb/ai-agent-tools/stargazers)
[![Licencia: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## Índice

- [Qué es esto](#qué-es-esto)
- [Herramientas](#herramientas)
- [Instalación](#instalación)
- [Patrocinadores](#patrocinadores)
- [Contribuir](#contribuir)
- [Licencia](#licencia)
- [Enlaces](#enlaces)

## Qué es esto

Agent Tools es el monorepo donde [fluyeporlaweb](https://fluyeporlaweb.com) construye y publica sus herramientas para agentes de IA: servidores MCP, skills y scripts pequeños.

No es una lista tipo awesome. Cada entrada es una herramienta que construimos y mantenemos. Cada una vive en su propia carpeta dentro de [`tools/`](tools/) con su README, sus pasos de instalación y sus notas de uso.

## Herramientas

| Herramienta | Tipo | Qué hace | Estado |
| --- | --- | --- | --- |
| [mcp-x-intelligence](https://github.com/fluyeporlaweb/mcp-x-intelligence) | Servidor MCP | Investigación en X/Twitter para agentes de IA | Próximamente |

`mcp-x-intelligence` ya existe como repositorio independiente. Es la primera herramienta prevista para este monorepo. Mientras tanto, usa el repositorio aparte.

## Instalación

Esto es un monorepo: no hay un único paquete que instalar. Cada herramienta se instala por su cuenta, con las instrucciones de su carpeta. Consulta [`tools/`](tools/README.es.md) para ver la estructura.

Todavía no hay ninguna herramienta disponible en este monorepo. Cuando `mcp-x-intelligence` llegue aquí, su instalación en un cliente MCP seguirá el patrón habitual. Esto es un ejemplo de la forma, no un paquete publicado:

```json
{
  "mcpServers": {
    "x-intelligence": {
      "command": "npx",
      "args": ["-y", "<nombre-del-paquete>"]
    }
  }
}
```

El nombre exacto del paquete y sus opciones se documentarán en el README de la herramienta cuando esté publicada.

## Patrocinadores

Este proyecto es gratuito y open source. Las marcas que lo apoyan aparecen aquí.

**[Tu marca aquí](https://fluyeporlaweb.com/patrocina)**

## Contribuir

Las issues y los pull requests son bienvenidos. Lee [CONTRIBUTING.md](CONTRIBUTING.md) antes de abrir uno y respeta el [Código de Conducta](CODE_OF_CONDUCT.md).

Si trabajas en el repo con un agente de código, indícale [AGENTS.md](AGENTS.md).

## Licencia

[MIT](LICENSE) © fluyeporlaweb

## Enlaces

- Web: [fluyeporlaweb.com](https://fluyeporlaweb.com)
- X: [@fluyeporlaweb](https://x.com/fluyeporlaweb)
- Telegram: [t.me/fluyeporlaweb](https://t.me/fluyeporlaweb)
