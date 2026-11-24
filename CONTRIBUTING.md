# Contributing to Agent Tools

This project is bilingual. Public documentation is maintained in English and Spanish, so every tool ships a `README.md` and a `README.es.md`. You can contribute in either language.

---

## English

### Proposing a tool

Open a [tool proposal](https://github.com/fluyeporlaweb/ai-agent-tools/issues/new?template=tool-proposal.yml) and describe:

- What the tool does and who it is for.
- Whether it is an MCP server, an agent skill or a script.
- Any existing repo or prototype.
- Why it belongs in this monorepo instead of a standalone repo.

Wait for a maintainer to agree on the scope before writing code.

### Adding a tool

1. Copy `tools/_template/` to `tools/<tool-name>/`. Use lowercase and hyphens.
2. Write `README.md` and `README.es.md` with the same structure. English and Spanish must be published together.
3. Fill in `TOOL.md`.
4. Add the source under `src/`, or a `SKILL.md` for a skill.
5. Add the tool to the tables in the root `README.md` and `README.es.md`.
6. Add a row to `llms.txt`.
7. Include tests if the tool contains code, and document how to run them.

### Directory format

```
tools/<tool-name>/
├── README.md
├── README.es.md
├── TOOL.md
├── .env.example
└── src/
```

### Pull request checklist

- [ ] The tool is in its own directory under `tools/`.
- [ ] `README.md` and `README.es.md` are both complete and consistent.
- [ ] The root README tables and `llms.txt` mention the tool.
- [ ] No secrets, tokens, `.env` files or credentials are included.
- [ ] Tests pass, or the PR explains why there are none.
- [ ] The change is described in plain language.

### Code of conduct

Participation is covered by the [Code of Conduct](CODE_OF_CONDUCT.md). Report unacceptable behavior to the maintainers as described there.

---

## Español

### Proponer una herramienta

Abre una [propuesta de herramienta](https://github.com/fluyeporlaweb/ai-agent-tools/issues/new?template=tool-proposal.yml) y explica:

- Qué hace la herramienta y para quién es.
- Si es un servidor MCP, una skill o un script.
- Si ya existe un repositorio o un prototipo.
- Por qué encaja en este monorepo y no en un repositorio aparte.

Espera a que un maintainer acepte el alcance antes de escribir código.

### Añadir una herramienta

1. Copia `tools/_template/` en `tools/<nombre-herramienta>/`. Usa minúsculas y guiones.
2. Escribe `README.md` y `README.es.md` con la misma estructura. Los dos idiomas se publican juntos.
3. Rellena `TOOL.md`.
4. Añade el código en `src/`, o un `SKILL.md` si es una skill.
5. Añade la herramienta a las tablas del `README.md` y `README.es.md` de la raíz.
6. Añade una fila a `llms.txt`.
7. Incluye tests si la herramienta tiene código y documenta cómo ejecutarlos.

### Formato del directorio

```
tools/<nombre-herramienta>/
├── README.md
├── README.es.md
├── TOOL.md
├── .env.example
└── src/
```

### Lista de comprobación del pull request

- [ ] La herramienta está en su propia carpeta dentro de `tools/`.
- [ ] `README.md` y `README.es.md` están completos y son coherentes.
- [ ] Las tablas del README raíz y `llms.txt` mencionan la herramienta.
- [ ] No se incluyen secretos, tokens, ficheros `.env` ni credenciales.
- [ ] Los tests pasan, o el PR explica por qué no hay.
- [ ] El cambio se describe en lenguaje claro.

### Código de conducta

La participación se rige por el [Código de Conducta](CODE_OF_CONDUCT.md). Los comportamientos inaceptables se comunican a los maintainers como se indica allí.
