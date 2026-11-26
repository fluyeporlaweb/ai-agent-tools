# Contributing to Agent Tools

This project is bilingual. Public documentation is maintained in English (`README.md`) and Spanish (`README.es.md`). Both files must stay in sync. You can contribute in either language.

---

## English

### What belongs here

This repository is a curated awesome list of **tools, APIs, MCP servers, SDKs, frameworks and runtimes for AI agents**. An entry is accepted when it meets **all** of these:

1. **Useful for building or running agents.** Frameworks, SDKs, MCP servers, coding agents, data/search APIs, memory, observability, gateways, workflows, voice, guardrails or agent skills.
2. **Real and alive.** The URL responds, and the product or repo is maintained (activity in the last ~12 months), unless it is a canonical standard or specification.
3. **Curated, not dumped.** One entry per product. No link farms, no SEO-bait directories, no copies of other awesome lists.
4. **A clear one-line description.** Say what it does, not that it is "the best".

Paid products are welcome when they are widely used by people who build agents and have a public page we can link. Official vendor tools belong here; unofficial wrappers are accepted only when they are the usual way to use that product.

### Entry format

One line per entry, in the right category, in both READMEs:

```md
- [Name](https://example.com) - One-line description that says what it is and why an agent builder would use it (`Open Source`).
```

Rules:

- Description: one line, starts with a capital letter, ends with a period. English in `README.md`, Spanish of Spain in `README.es.md`.
- Optional tag at the end of the description, in backticks: `Open Source`, `Free` or `Freemium`. Use only one, and only when it helps.
- No marketing superlatives ("the best", "ultimate", "revolutionary").
- Do not add affiliate parameters or tracking codes of your own. Maintainer-managed affiliate links already go through `https://fluyeporlaweb.com/go/` and are marked *affiliate* / *afiliado*.
- Keep both files in sync: an entry added to one must be added to the other in the same pull request.
- Update the count in the Contents / Índice list for that category.

### Categories

If a new entry does not fit any existing category, open an issue first and propose a new one. New categories should start with at least five entries.

### How to contribute

**Easiest:** open an issue using the "Suggest an entry" template. The maintainer will verify the link and add it.

**By pull request:**

1. Fork the repository.
2. Add the entry to `README.md` and `README.es.md` in the right category, in alphabetical order within the section when it is practical, otherwise next to related tools.
3. Update the category count in the contents list of both files.
4. Check the link:

   ```sh
   curl -s -o /dev/null -w "%{http_code}" -L -A "Mozilla/5.0" "https://your-url.example"
   ```

   A `200`–`399` response is expected. Some sites block bots with `403`; mention that in the PR.

   If you have [lychee](https://github.com/lycheeverse/lychee) installed, also run it on both READMEs and `llms.txt` (this is what the Link Check workflow runs on every pull request):

   ```sh
   lychee --no-progress README.md README.es.md llms.txt
   ```

   If lychee fails in CI, the pull request cannot be merged until the link is fixed or replaced.

5. Open the pull request using the template.

Please do not send a PR that only copies a block from another awesome list.

### Reporting a broken link

Open an issue titled `Broken link: <name>` with the URL and what you see (404, redirect, parked domain). A PR that removes or replaces the entry in both READMEs is also welcome.

### Tools built by fluyeporlaweb

Source for tools we publish ourselves still lives under `tools/`. If you are proposing a tool *we* should build, open a discussion or an issue and wait for a maintainer before sending code. Public contributions to the list itself (this README) do not require that.

### Code of conduct

Participation is covered by the [Code of Conduct](CODE_OF_CONDUCT.md). Report unacceptable behavior to the maintainers as described there. Entries that point to harassment, hate, gambling, crypto-pump or adult content will be rejected.

---

## Español

### Qué encaja aquí

Este repositorio es una lista tipo awesome de **herramientas, APIs, servidores MCP, SDKs, frameworks y runtimes para agentes de IA**. Una entrada se acepta cuando cumple **todo** esto:

1. **Sirve para construir o ejecutar agentes.** Frameworks, SDKs, servidores MCP, agentes de código, APIs de datos o búsqueda, memoria, observabilidad, pasarelas, flujos, voz, guardrails o skills.
2. **Es real y está viva.** La URL responde y el producto o el repo se mantiene (actividad en los últimos ~12 meses), salvo que sea un estándar o una especificación de referencia.
3. **Está curada, no volcada.** Una entrada por producto. Nada de granjas de enlaces, directorios cebo ni copias de otras listas awesome.
4. **Tiene una descripción de una línea.** Qué hace, no que es "la mejor".

Los productos de pago caben si los usa mucha gente que construye agentes y tienen una página pública que podamos enlazar. Las herramientas oficiales del fabricante encajan; los wrappers no oficiales solo si son la forma habitual de usar ese producto.

### Formato de la entrada

Una línea por entrada, en la categoría correcta, en los dos README:

```md
- [Nombre](https://example.com) - Una línea que dice qué es y por qué le sirve a quien construye agentes (`Open Source`).
```

Normas:

- Descripción: una línea, empieza con mayúscula y termina con punto. Inglés en `README.md`, español de España en `README.es.md`.
- Etiqueta opcional al final de la descripción, entre backticks: `Open Source`, `Free` o `Freemium`. Solo una, y solo cuando aporte contexto.
- Sin superlativos de marketing ("the best", "ultimate", "revolucionario").
- No añadas parámetros de afiliado ni códigos de seguimiento por tu cuenta. Los enlaces de afiliado que mantiene el proyecto pasan por `https://fluyeporlaweb.com/go/` y van marcados con *affiliate* / *afiliado*.
- Los dos ficheros van a la par: si añades una entrada en uno, va en el otro en el mismo pull request.
- Actualiza el recuento del índice de esa categoría.

### Categorías

Si una entrada nueva no encaja en ninguna categoría, abre una issue y propone una categoría nueva. Una categoría nueva debería nacer con al menos cinco entradas.

### Cómo contribuir

**Lo más fácil:** abre una issue con la plantilla "Suggest an entry". El maintainer comprobará el enlace y la añadirá.

**Por pull request:**

1. Haz un fork del repositorio.
2. Añade la entrada en `README.md` y `README.es.md`, en la categoría correcta.
3. Actualiza el recuento de esa categoría en el índice de los dos ficheros.
4. Comprueba el enlace con `curl` o `lychee` (véase la sección en inglés). Se espera un `200`–`399`. El CI de Link Check corre en cada PR y, si falla, no se puede fusionar.
5. Abre el pull request con la plantilla.

No envíes un PR que solo copie un bloque de otra lista awesome.

### Enlaces rotos

Abre una issue con el título `Broken link: <nombre>` y la URL, o un PR que quite o sustituya la entrada en los dos README.

### Herramientas hechas por fluyeporlaweb

El código de las herramientas que publicamos nosotros sigue viviendo en `tools/`. Si propones una herramienta *que deberíamos construir*, abre una issue y espera a un maintainer antes de enviar código. Contribuir a la lista (el README) no exige eso.

### Código de conducta

La participación se rige por el [Código de Conducta](CODE_OF_CONDUCT.md). Los comportamientos inaceptables se comunican a los maintainers como se indica allí.
