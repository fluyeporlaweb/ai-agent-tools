# Tool template

A tool in this monorepo is one of:

- an MCP server, usually written in TypeScript;
- an agent skill, with a `SKILL.md` in the tool directory;
- a script, in Python or Bash.

To start a new tool:

1. Copy this directory to `tools/<tool-name>/` and use lowercase and hyphens.
2. Fill in `README.md` and `README.es.md` with the same structure. Both are required.
3. Update this file with the tool type and a one-line description.
4. Put the code in `src/`, or the `SKILL.md` in the tool directory for a skill.
5. Add the tool to the tables in the root `README.md` and `README.es.md`, and to `llms.txt`.
6. Keep `.env.example` free of real values. Never commit `.env` or any secret.
