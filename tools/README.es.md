# Herramientas

Cada herramienta de este monorepo vive en su propia carpeta dentro de `tools/`. Es autocontenida: tiene su README, sus pasos de instalación, su configuración y su código.

```
tools/
├── _template/       # punto de partida para una herramienta nueva
└── <nombre-herramienta>/
    ├── README.md
    ├── README.es.md
    ├── TOOL.md
    ├── .env.example
    └── src/
```

Las herramientas pueden ser servidores MCP (TypeScript), skills (`SKILL.md`) o scripts (Python o Bash). El tipo se indica en `TOOL.md` y en la tabla de herramientas del README raíz.

Para añadir una herramienta, copia `_template/` y sigue [CONTRIBUTING.md](../CONTRIBUTING.md). La versión en inglés está en [README.md](README.md).
