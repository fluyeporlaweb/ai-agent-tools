<p align="center"><img src=".github/assets/logo.png" width="128" alt="ai-agent-tools logo"></p>

# Agent Tools

**Un directorio curado de herramientas open source para agentes de IA**, pensado para equipos de marketing y crecimiento técnico: **frameworks de agentes**, **agentes de código y CLIs**, **servidores y clientes MCP**, automatización de navegador y sandboxes, memoria y RAG, observabilidad, y **flujos de prospección y SEO**. Lo construye y mantiene [fluyeporlaweb](https://fluyeporlaweb.com?src=github). Cada enlace se comprueba; las entradas se eligen, no se vierten a lo loco.

[English](README.md) · Español

[![GitHub stars](https://img.shields.io/github/stars/fluyeporlaweb/ai-agent-tools?style=flat)](https://github.com/fluyeporlaweb/ai-agent-tools/stargazers)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Enlaces comprobados cada semana](https://img.shields.io/badge/links-checked%20weekly-blue.svg)](.github/workflows/link-check.yml)

## Índice

- [Qué es esto](#qué-es-esto)
- [Protocolos y estándares](#protocolos-y-estándares) (8)
- [Frameworks y SDKs de agentes](#frameworks-y-sdks-de-agentes) (34)
- [Agentes de código e IDEs](#agentes-de-código-e-ides) (28)
- [SDKs, registro y herramientas MCP](#sdks-registro-y-herramientas-mcp) (18)
- [Servidores MCP](#servidores-mcp) (38)
- [Clientes y hosts MCP](#clientes-y-hosts-mcp) (12)
- [Navegador, computer use y sandboxes](#navegador-computer-use-y-sandboxes) (24)
- [APIs de datos, scraping y búsqueda](#apis-de-datos-scraping-y-búsqueda) (14)
- [Memoria, RAG y bases vectoriales](#memoria-rag-y-bases-vectoriales) (19)
- [Observabilidad, evals y trazas](#observabilidad-evals-y-trazas) (16)
- [APIs de LLM, routers y runtimes](#apis-de-llm-routers-y-runtimes) (27)
- [Flujos de trabajo y orquestación](#flujos-de-trabajo-y-orquestación) (14)
- [Voz, habla y tiempo real](#voz-habla-y-tiempo-real) (15)
- [Guardrails y seguridad](#guardrails-y-seguridad) (12)
- [Skills de agentes y marketplaces de tools](#skills-de-agentes-y-marketplaces-de-tools) (13)
- [Marketing, SEO y prospección](#marketing-seo-y-prospección) (10)
- [Hecho por fluyeporlaweb](#hecho-por-fluyeporlaweb) (2)
- [Visto en nuestros vídeos](#visto-en-nuestros-vídeos)
- [Patrocinadores](#patrocinadores)
- [Más de fluyeporlaweb](#más-de-fluyeporlaweb)
- [Listas relacionadas](#listas-relacionadas)
- [Contribuir](#contribuir)
- [Licencia](#licencia)
- [Enlaces](#enlaces)

## Qué es esto

Esta es una lista tipo awesome de **herramientas open source para agentes de IA, pensada para equipos de marketing y crecimiento**: frameworks y SDKs, agentes de código, servidores y clientes MCP, runtimes de navegador y sandbox, APIs de datos y búsqueda, memoria y RAG, observabilidad, pasarelas de LLM, flujos de trabajo, voz, guardrails, skills de agentes, y herramientas de prospección y SEO.

No es un volcado de cada repositorio que menciona “agent”. Cada entrada tiene una línea de explicación y un enlace que responde. También hay una sección pequeña para las herramientas [hechas por fluyeporlaweb](#hecho-por-fluyeporlaweb).

Algunas entradas usan [enlaces de afiliado](https://fluyeporlaweb.com/legal/afiliacion/?src=github) que pasan por `fluyeporlaweb.com/go/`. Van marcadas con *afiliado*. El precio que pagas no cambia. Si quieres que tu marca aparezca en esta lista, mira [Patrocinadores](#patrocinadores).

## Protocolos y estándares

- [Model Context Protocol](https://modelcontextprotocol.io) - Estándar abierto para que las apps de IA hablen con herramientas, fuentes de datos y servicios a través de una interfaz común.
- [MCP specification](https://github.com/modelcontextprotocol/modelcontextprotocol) - Especificación oficial del protocolo MCP y su documentación, mantenida por el grupo directivo del proyecto.
- [Agent Skills](https://agentskills.io) - Formato abierto para empaquetar instrucciones y scripts reutilizables que los agentes de código cargan en un repositorio.
- [Agent2Agent (A2A)](https://a2a-protocol.org) - Protocolo abierto nacido en Google para que agentes de distintos fabricantes se descubran entre sí y colaboren.
- [AG-UI](https://docs.ag-ui.com) - Protocolo abierto para conectar backends de agentes con aplicaciones de usuario mediante un flujo de eventos estándar.
- [llms.txt](https://llmstxt.org) - Propuesta de estándar para un fichero /llms.txt que indica a los modelos de lenguaje cómo leer un sitio o proyecto.
- [OpenTelemetry GenAI](https://opentelemetry.io/docs/specs/semconv/gen-ai/) - Convenciones semánticas para trazar aplicaciones de IA generativa y agentes con OpenTelemetry.
- [Agent Communication Protocol (ACP)](https://agentcommunicationprotocol.dev) - Protocolo abierto que permite a los agentes descubrirse y comunicarse mediante un formato de mensajes compartido (`Open Source`).

## Frameworks y SDKs de agentes

- [LangChain](https://www.langchain.com) - Framework muy usado para componer apps de LLM, herramientas y agentes en Python y JavaScript.
- [LangGraph](https://www.langchain.com/langgraph) - Framework de orquestación de bajo nivel para agentes con estado y persistencia, ciclos y supervisión humana.
- [LlamaIndex](https://www.llamaindex.ai) - Framework para conectar LLMs a tus datos, con agentes, workflows y un kit completo de RAG.
- [CrewAI](https://www.crewai.com) - Framework en Python para equipos de varios agentes con roles, tareas y un motor de workflows.
- [AutoGen](https://microsoft.github.io/autogen/) - Framework multiagente de Microsoft para agentes conversacionales por eventos, ahora dentro de la línea Agent Framework.
- [Microsoft Agent Framework](https://learn.microsoft.com/en-us/agent-framework/overview/) - SDK unificado de Microsoft para construir y ejecutar sistemas multiagente en .NET y Python, documentado en Microsoft Learn.
- [Semantic Kernel](https://learn.microsoft.com/semantic-kernel/) - SDK de Microsoft para integrar agentes de IA y plugins en aplicaciones C#, Python y Java.
- [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/) - SDK oficial de OpenAI para construir agentes con herramientas, traspasos, guardrails y trazas.
- [Google Agent Development Kit (ADK)](https://google.github.io/adk-docs/) - Kit de Google, orientado a código, para construir, evaluar y desplegar agentes, también sobre Vertex AI.
- [PydanticAI](https://ai.pydantic.dev) - Framework de agentes en Python con tipos seguros del equipo de Pydantic, con E/S estructurada e independiente del modelo.
- [Agno](https://github.com/agno-agi/agno) - Framework Python rápido para agentes con memoria, conocimiento, herramientas y bucle de razonamiento integrados.
- [Haystack](https://haystack.deepset.ai) - Framework de deepset, open source, para pipelines de RAG y agentes con herramientas, con editor visual de pipelines.
- [Mastra](https://mastra.ai) - Framework en TypeScript para agentes, workflows y RAG, con evals y un playground local.
- [VoltAgent](https://voltagent.dev) - Framework en TypeScript para construir y orquestar agentes de IA, con memoria, herramientas y observabilidad.
- [smolagents](https://github.com/huggingface/smolagents) - Librería mínima en Python de Hugging Face para agentes que escriben y ejecutan código para usar herramientas.
- [Letta](https://www.letta.com) - Framework y plataforma para agentes con memoria a largo plazo, nacidos de la investigación de MemGPT.
- [Dify](https://dify.ai) - Plataforma open source para construir y operar apps y agentes de LLM, con estudio visual y pipeline de RAG.
- [Langflow](https://www.langflow.org) - IDE visual open source del ecosistema LangChain para construir agentes y flujos de RAG.
- [Vercel AI SDK](https://ai-sdk.dev) - Toolkit en TypeScript para interfaces de IA en streaming y agentes con muchos proveedores de modelos.
- [Spring AI](https://docs.spring.io/spring-ai/reference/) - API del proyecto Spring para construir apps y agentes de IA en Java, con soporte portable de modelos y herramientas.
- [Strands Agents](https://github.com/strands-agents/sdk-python) - SDK open source de AWS, dirigido por el modelo, para construir y desplegar agentes de IA.
- [DSPy](https://dspy.ai) - Framework para programar LLMs con firmas optimizables en lugar de prompts, que los agentes pueden usar como módulos.
- [Claude Agent SDK](https://platform.claude.com/docs/en/agent-sdk/overview) - SDK de Anthropic para construir agentes con Claude, herramientas y el mismo harness que usa Claude Code.
- [Google Gen AI SDK](https://ai.google.dev) - SDK oficial de Google para Gemini, con function calling, thinking y APIs en vivo y multimodales.
- [AstrBot](https://github.com/AstrBotDevs/AstrBot) - Framework de código abierto para asistentes de IA que se integran con plataformas de mensajería como Telegram y Discord, con LLMs y plugins.
- [learnharness](https://github.com/amosblomqvist/learnharness) - Un harness de agentes pensado para aprender temas difíciles, con un bucle nativo de agente en lugar de un tutor estático.
- [TradingAgents](https://github.com/TauricResearch/TradingAgents) - Framework multiagente de LLM que modela una mesa de trading, con agentes que debaten y analizan mercados financieros.
- [CopilotKit](https://www.copilotkit.ai) - SDK para añadir copilotos de IA a aplicaciones, con hooks y componentes de interfaz para asistentes integrados (`Open Source`).
- [Flowise](https://flowiseai.com) - Constructor visual para ensamblar cadenas de LLM y agentes con nodos conectados, útil para prototipos rápidos (`Open Source`).
- [CAMEL](https://www.camel-ai.org) - Framework para investigación con múltiples agentes y escenarios de roles, usado para estudiar cómo cooperan en tareas (`Open Source`).
- [Langroid](https://langroid.github.io/langroid/) - Framework que convierte las interacciones con LLM en agentes orientados a tareas, con mensajes y uso de herramientas (`Open Source`).
- [mcp-agent](https://github.com/lastmile-ai/mcp-agent) - Biblioteca para crear agentes que combinan servidores MCP y herramientas con un modelo de orquestación claro (`Open Source`).
- [Suna](https://github.com/kortix-ai/suna) - Agente abierto y generalista que gestiona tareas de investigación, datos y navegador desde una conversación (`Open Source`).
- [BeeAI Framework](https://github.com/i-am-bee/bee-agent-framework) - Framework para crear y ejecutar flujos multiagente con agentes portátiles y herramientas (`Open Source`).

## Agentes de código e IDEs

- [Claude Code](https://code.claude.com/docs/en/overview) - Agente de código de Anthropic pensado para terminal, con soporte MCP, skills y workflows conscientes del repo.
- [Cursor](https://cursor.com) - Editor de código nativo de IA con modo agente, contexto del repo, soporte MCP y ediciones en línea.
- [GitHub Copilot](https://github.com/features/copilot) - Asistente y agente de código de GitHub, disponible en VS Code, Visual Studio, la CLI y github.com.
- [Windsurf](https://windsurf.com) - IDE agéntico de Codeium con flujos en cascada, soporte MCP y contexto profundo del repositorio.
- [Aider](https://aider.chat) - Agente de código open source para terminal que edita tu repo, hace commits y funciona con muchos LLMs.
- [Continue](https://www.continue.dev) - Asistente y agente de código open source para VS Code y JetBrains, con MCP y contexto personalizable.
- [Cline](https://github.com/cline/cline) - Agente de código open source para VS Code que puede usar el navegador, la terminal y herramientas MCP.
- [OpenCode](https://opencode.ai) - Agente de código open source para terminal que funciona con muchos proveedores de modelos, incluidos locales.
- [Goose](https://block.github.io/goose/) - Agente de código y operaciones de Block, open source y local-first, con un ecosistema extensible de tools y MCP.
- [Codex](https://openai.com/codex/) - Agente de código de OpenAI, disponible como CLI, extensión de IDE y dentro de ChatGPT.
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Agente de línea de comandos open source de Google para Gemini, con soporte MCP y herramientas integradas.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - Agente de desarrollo open source (antes OpenDevin) capaz de editar código, ejecutar comandos y navegar.
- [Roo Code](https://github.com/RooCodeInc/Roo-Code) - Agente de código open source para VS Code (fork de Cline) con modos, MCP y una comunidad muy activa.
- [Sourcegraph Amp](https://sourcegraph.com/amp) - Agente de código de Sourcegraph, construido sobre la misma inteligencia de código que impulsan Cody y su buscador.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/) - Asistente y agente de código de AWS para IDE, CLI y consola, con herramientas que entienden de AWS.
- [Zed](https://zed.dev) - Editor open source y rápido, con panel de agente y soporte de cliente MCP.
- [Warp](https://www.warp.dev) - Terminal agéntica capaz de ejecutar workflows, editar comandos y usar servidores MCP.
- [Grok Bot](https://grok.com) - Agente de código y operaciones de xAI que puede usar herramientas, navegar y trabajar con apps conectadas.
- [Devin](https://devin.ai) - Ingeniero de software autónomo de Cognition: un agente en la nube que planifica, programa y abre pull requests.
- [Augment Code](https://www.augmentcode.com) - Agente de código y motor de contexto diseñado para bases de código grandes, con integraciones de IDE y Slack.
- [t3code](https://github.com/pingdotgg/t3code) - Control remoto para Claude Code, Codex y otros agentes de código, para dirigirlos desde cualquier ordenador o teléfono.
- [Crush](https://github.com/charmbracelet/crush) - Agente de programación en terminal que edita archivos, ejecuta comandos y ayuda con el trabajo en repositorios desde la línea de comandos (`Open Source`).
- [Tabby](https://tabby.tabbyml.com) - Asistente de código autoalojado que completa y explica código dentro del editor mientras trabajas (`Open Source`).
- [Void](https://voideditor.com) - Editor de código abierto pensado para programar con IA, con chat y ediciones en línea en el mismo espacio de trabajo (`Open Source`).
- [Qwen Code](https://github.com/QwenLM/qwen-code) - Agente de programación por línea de comandos que lee un repositorio y ayuda a implementar cambios con asistencia del modelo (`Open Source`).
- [JetBrains AI](https://www.jetbrains.com/ai/) - Asistencia de IA integrada en los IDE de JetBrains para completar código, refactorizar y chatear dentro del editor (`Freemium`).
- [Factory](https://factory.ai) - Espacio de trabajo de programación con IA donde los agentes gestionan tareas de software desde una interfaz compartida y el contexto del repositorio (`Freemium`).
- [Plandex](https://github.com/plandex-ai/plandex) - Agente de programación que planifica cambios en varios archivos y los aplica con pasos revisables en la terminal (`Open Source`).

## SDKs, registro y herramientas MCP

- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - SDK oficial en TypeScript para construir servidores y clientes MCP.
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) - SDK oficial en Python para construir servidores y clientes MCP.
- [MCP Go SDK](https://github.com/modelcontextprotocol/go-sdk) - SDK oficial en Go para servidores y clientes MCP, mantenido junto a Google.
- [MCP Java SDK](https://github.com/modelcontextprotocol/java-sdk) - SDK oficial en Java para MCP, mantenido junto al equipo de Spring AI.
- [MCP Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) - SDK oficial en Rust para el Model Context Protocol.
- [MCP C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) - SDK oficial en C# para servidores y clientes MCP, en colaboración con Microsoft.
- [MCP Kotlin SDK](https://github.com/modelcontextprotocol/kotlin-sdk) - SDK oficial en Kotlin para MCP, mantenido junto a JetBrains.
- [MCP PHP SDK](https://github.com/modelcontextprotocol/php-sdk) - SDK oficial en PHP para MCP, mantenido junto a The PHP Foundation.
- [MCP Swift SDK](https://github.com/modelcontextprotocol/swift-sdk) - SDK oficial en Swift para MCP, mantenido junto a Apple.
- [MCP Ruby SDK](https://github.com/modelcontextprotocol/ruby-sdk) - SDK oficial en Ruby para servidores y clientes MCP.
- [FastMCP](https://github.com/jlowin/fastmcp) - Framework de alto nivel en Python (y TypeScript) para escribir servidores MCP con el mínimo código de andamiaje.
- [MCP Registry](https://github.com/modelcontextprotocol/registry) - Servicio de registro oficial de la comunidad para descubrir y publicar servidores MCP.
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) - Herramienta visual oficial para probar y depurar servidores MCP.
- [MCPB](https://github.com/modelcontextprotocol/mcpb) - Formato de Desktop Extensions para empaquetar e instalar servidores MCP con un clic en apps de escritorio.
- [Reference MCP servers](https://github.com/modelcontextprotocol/servers) - Monorepo oficial de servidores MCP de referencia (filesystem, memory, everything y más).
- [Smithery](https://smithery.ai) - Registro y herramientas para encontrar y ejecutar servidores MCP con una configuración coherente (`Freemium`).
- [PulseMCP](https://www.pulsemcp.com) - Directorio de servidores y clientes MCP que ayuda a descubrir integraciones y seguir los cambios del ecosistema (`Free`).
- [Glama MCP](https://glama.ai/mcp) - Catálogo de servidores MCP con reseñas y detalles, útil para comparar las integraciones disponibles (`Free`).

## Servidores MCP

- [GitHub MCP Server](https://github.com/github/github-mcp-server) - Servidor MCP oficial de GitHub para repos, issues, pull requests y Actions.
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - Servidor MCP oficial de Microsoft que permite a los agentes navegar y automatizar páginas con Playwright.
- [Cloudflare MCP Server](https://github.com/cloudflare/mcp-server-cloudflare) - Servidor MCP oficial de Cloudflare para Workers, KV, R2, D1, Observability y más.
- [Stripe Agent Toolkit](https://github.com/stripe/agent-toolkit) - Toolkit oficial de Stripe con MCP y otras integraciones de agentes para pagos.
- [Notion MCP](https://github.com/makenotion/notion-mcp-server) - Servidor MCP oficial de Notion para leer y escribir páginas y bases de datos de Notion.
- [Linear MCP](https://linear.app/docs/mcp) - Servidor MCP oficial de Linear para issues, proyectos y workflows de equipo.
- [Sentry MCP](https://github.com/getsentry/sentry-mcp) - Servidor MCP oficial de Sentry para que los agentes consulten errores, issues y trazas.
- [Supabase MCP](https://github.com/supabase-community/supabase-mcp) - Servidor MCP oficial de Supabase para proyectos, base de datos, auth y edge functions.
- [Prisma MCP](https://www.prisma.io/mcp) - Servidor MCP de Prisma para hablar con Prisma Postgres y tu esquema desde un agente.
- [Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp) - Servidor MCP oficial de Chrome DevTools para inspeccionar y depurar páginas en vivo.
- [Browserbase MCP](https://github.com/browserbase/mcp-server-browserbase) - Servidor MCP que da a los agentes un navegador en la nube vía Browserbase y Stagehand.
- [Firecrawl MCP](https://github.com/firecrawl/firecrawl-mcp-server) - Servidor MCP para rastrear, hacer scraping y buscar en la web con Firecrawl.
- [Context7](https://fluyeporlaweb.com/go/context-dev/?p=github-readme) - Servidor MCP que trae documentación actualizada y por versión de librerías a tu agente de código. *(afiliado)*
- [Apify MCP](https://fluyeporlaweb.com/go/apify/?p=github-readme) - Forma oficial de ejecutar Actors y herramientas de Apify desde agentes compatibles con MCP. *(afiliado)*
- [Zernio MCP](https://fluyeporlaweb.com/go/zernio/?p=github-readme) - Servidor MCP alojado para programar, publicar y gestionar cuentas sociales y de mensajería desde un agente. *(afiliado)*
- [Monid](https://fluyeporlaweb.com/go/monid/?p=github-readme) - Pasarela con más de 2.800 herramientas para agentes (lo llaman el OpenRouter de las tools de agentes), con MCP, skill y CLI. *(afiliado)*
- [Atlassian MCP](https://www.atlassian.com/platform/remote-mcp-server) - Servidor MCP remoto oficial de Atlassian para Jira y Confluence.
- [Figma MCP](https://developers.figma.com/docs/figma-mcp-server/) - Integración MCP oficial de Figma para que los agentes lean el contexto de diseño de los ficheros.
- [MongoDB MCP](https://github.com/mongodb-js/mongodb-mcp-server) - Servidor MCP oficial de MongoDB para consultar y gestionar clusters.
- [Neon MCP](https://neon.tech/docs/ai/neon-mcp-server) - Servidor MCP oficial de Neon para gestionar Postgres serverless desde un agente.
- [Hugging Face MCP](https://huggingface.co/settings/mcp) - Servidor MCP oficial de Hugging Face para modelos, datasets, Spaces y papers.
- [Slack MCP](https://docs.slack.dev/ai/slack-mcp-server/) - Servidor MCP oficial de Slack para buscar y publicar en workspaces.
- [Zapier MCP](https://zapier.com/mcp) - Zapier MCP que expone miles de acciones de apps como herramientas para agentes.
- [n8n MCP](https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/) - Servidor MCP oficial de n8n para que los agentes busquen, ejecuten y construyan workflows.
- [Exa MCP](https://github.com/exa-labs/exa-mcp-server) - Servidor MCP para la búsqueda web neuronal y la API de contenidos de Exa.
- [Tavily MCP](https://docs.tavily.com/documentation/mcp) - Servidor MCP para las APIs de búsqueda y extracción de Tavily, pensadas para agentes.
- [Brave Search MCP](https://github.com/brave/brave-search-mcp-server) - Servidor MCP oficial de Brave Search para búsqueda web, de imágenes, noticias y vídeo.
- [Qdrant MCP](https://github.com/qdrant/mcp-server-qdrant) - Servidor MCP oficial de Qdrant para almacenar y recuperar memorias semánticas.
- [AWS MCP Servers](https://github.com/awslabs/mcp) - Colección de servidores MCP que conectan agentes con servicios de AWS y flujos de infraestructura (`Open Source`).
- [Terraform MCP Server](https://github.com/hashicorp/terraform-mcp-server) - Servidor MCP que permite a los agentes trabajar con configuraciones de Terraform y definiciones de infraestructura (`Open Source`).
- [Redis MCP](https://github.com/redis/mcp-redis) - Servidor MCP que da a los agentes acceso a Redis para caché, claves y operaciones de datos (`Open Source`).
- [Pipedream MCP](https://mcp.pipedream.com) - Interfaz MCP para integraciones de aplicaciones, de modo que los agentes puedan disparar acciones en herramientas SaaS conectadas (`Freemium`).
- [Serena](https://github.com/oraios/serena) - Servidor MCP que aporta a los agentes de código comprensión semántica de un codebase mediante servidores de lenguaje (`Open Source`).
- [Browser MCP](https://browsermcp.io) - Servidor MCP que permite a los agentes manejar un navegador real para hacer clics, rellenar formularios y leer páginas (`Open Source`).
- [21st.dev Magic MCP](https://21st.dev/magic) - Servidor MCP que aporta componentes de interfaz y fragmentos de diseño a los agentes de código cuando los piden (`Freemium`).
- [PostgreSQL MCP](https://github.com/crystaldba/postgres-mcp) - Servidor MCP que permite a los agentes consultar e inspeccionar bases de datos PostgreSQL mediante un conjunto definido de herramientas (`Open Source`).
- [Microsoft MCP servers](https://github.com/microsoft/mcp) - Servidores MCP de Microsoft para conectar agentes con productos, documentación y servicios de desarrollo (`Open Source`).
- [Docker MCP Catalog](https://docs.docker.com/ai/mcp-catalog-and-toolkit/) - Catálogo de servidores MCP distribuidos a través de Docker para facilitar la instalación y mantener ejecuciones coherentes (`Open Source`).

## Clientes y hosts MCP

- [Claude Desktop](https://claude.ai/download) - App de escritorio de Anthropic, uno de los primeros hosts MCP, con soporte de servidores locales y remotos.
- [VS Code](https://code.visualstudio.com/docs/copilot/chat/mcp-servers) - Host MCP de Visual Studio Code, usado por GitHub Copilot y otros agentes de chat.
- [LibreChat](https://www.librechat.ai) - Interfaz open source estilo ChatGPT con MCP, agentes y muchos proveedores de modelos.
- [Open WebUI](https://openwebui.com) - Interfaz web autoalojada para modelos locales y remotos, con soporte de MCP y herramientas.
- [Cherry Studio](https://github.com/CherryHQ/cherry-studio) - Cliente de escritorio open source para muchos proveedores de LLM, con soporte MCP.
- [OpenBot](https://github.com/CopilotKit/OpenBot) - Workspace autoalojable para compañeros de trabajo de IA, como app de escritorio o en Kubernetes: los agentes usan el navegador y las herramientas, y esperan tu visto bueno antes de actuar.
- [Jan](https://jan.ai) - Cliente de IA local que ejecuta modelos en tu máquina y admite integraciones con herramientas y MCP (`Open Source`).
- [AnythingLLM](https://anythingllm.com) - Cliente para chatear con tus propios documentos y conectarlos con herramientas y agentes (`Open Source`).
- [DeepChat](https://github.com/ThinkInAIXYZ/deepchat) - Cliente de chat extensible que admite varios proveedores, herramientas y conexiones MCP en una sola interfaz (`Open Source`).
- [5ire](https://5ire.app) - Cliente de IA que reúne varios modelos, herramientas y un mercado MCP en una aplicación de escritorio (`Open Source`).
- [TypingMind](https://www.typingmind.com) - Interfaz de chat para reunir tus claves de modelo, prompts y herramientas en un solo lugar (`Freemium`).
- [Raycast](https://www.raycast.com) - Lanzador que se amplía con un directorio de aplicaciones, comandos de IA y acciones basadas en MCP (`Freemium`).

## Navegador, computer use y sandboxes

- [Playwright](https://playwright.dev) - Librería de automatización de navegador de Microsoft, base de muchas tools de navegador y servidores MCP.
- [Puppeteer](https://pptr.dev) - Librería de Node del equipo de Chrome para manejar Chromium, muy usada aún en scraping y agentes.
- [Stagehand](https://github.com/browserbase/stagehand) - SDK de automatización de navegador de Browserbase pensado para IA, con servidor MCP y API tipo Playwright.
- [Browser Use](https://github.com/browser-use/browser-use) - Librería open source en Python que permite a los agentes manejar un navegador real con acciones de alto nivel.
- [Browserbase](https://www.browserbase.com) - Navegadores en la nube para agentes: modo sigiloso, sesiones, Stagehand y un servidor MCP oficial.
- [E2B](https://e2b.dev) - Sandboxes seguras en la nube para que los agentes ejecuten código, instalen paquetes y usen escritorio o navegador.
- [Steel](https://steel.dev) - Infraestructura de navegador open source y alojada, hecha para agentes de IA.
- [Kernel](https://www.kernel.sh) - Plataforma de navegador en la nube para agentes, con modo sigiloso, sesiones y API/MCP.
- [Crawl4AI](https://github.com/unclecode/crawl4ai) - Crawler open source hecho para pipelines de LLM y agentes, con salida en markdown limpio.
- [Skyvern](https://skyvern.com) - Agente de navegador open source y alojado que completa workflows a partir de un objetivo o definición.
- [Daytona](https://www.daytona.io) - Infraestructura segura y rápida para ejecutar código generado por IA y agentes de código en workspaces aislados.
- [Modal](https://modal.com) - Cómputo serverless para ejecutar cargas de agentes, sandboxes y trabajos de GPU desde Python.
- [Firecrawl](https://www.firecrawl.dev) - API y MCP para convertir sitios web en markdown limpio o datos estructurados para agentes.
- [Computer Use (Anthropic)](https://platform.claude.com/docs/en/agents-and-tools/computer-use) - Capacidad oficial de computer use de Anthropic: Claude maneja un escritorio mediante capturas y acciones.
- [Scrapybara](https://scrapybara.com) - Escritorios y navegadores Ubuntu en la nube que los agentes controlan a través de un SDK.
- [agent-browser](https://github.com/vercel-labs/agent-browser) - CLI de automatización de navegador de Vercel, hecha para agentes de IA, para que hagan clic, escriban e inspeccionen páginas desde la terminal.
- [Crawlee](https://crawlee.dev) - Biblioteca para rastrear y extraer datos web de forma fiable, con colas y reintentos integrados (`Open Source`).
- [Browserless](https://www.browserless.io) - Servicio de automatización de navegador que ofrece una instancia remota de Chrome sin gestionar infraestructura (`Freemium`).
- [Hyperbrowser](https://www.hyperbrowser.ai) - Infraestructura de navegador para agentes que necesitan sesiones headless, extracción y automatización a escala (`Freemium`).
- [Lightpanda](https://lightpanda.io) - Navegador headless ligero centrado en automatización rápida y bajo consumo de recursos para agentes (`Open Source`).
- [WebContainers](https://webcontainers.io) - Tecnología que ejecuta un entorno de desarrollo completo dentro del navegador para demos y entornos aislados de agentes (`Open Source`).
- [Vercel Sandbox](https://vercel.com/docs/vercel-sandbox) - Entorno aislado para ejecutar código no fiable procedente de agentes con límites definidos y arranque rápido (`Freemium`).
- [Dagger](https://dagger.io) - Motor de integración continua programable que permite a los agentes definir y ejecutar pipelines reproducibles como código (`Open Source`).
- [Selenium](https://www.selenium.dev) - Framework de automatización de navegador para probar aplicaciones web en distintos navegadores, plataformas y tamaños de pantalla (`Open Source`).

## APIs de datos, scraping y búsqueda

- [Apify](https://fluyeporlaweb.com/go/apify/?p=github-readme) - Plataforma y tienda de Actors de scraping y navegador que los agentes ejecutan vía API o MCP. *(afiliado)*
- [DataForSEO](https://fluyeporlaweb.com/go/dataforseo/?p=github-readme) - API de pago por uso con datos de SERP, keywords, backlinks y visibilidad en LLMs que los agentes pueden consultar. *(afiliado)*
- [Tavily](https://tavily.com) - API de búsqueda y extracción diseñada para agentes, con servidor MCP oficial.
- [Exa](https://exa.ai) - API de búsqueda web neuronal y contenidos, con servidor MCP oficial para agentes.
- [Jina AI](https://jina.ai) - APIs de lectura, búsqueda y embeddings que convierten páginas web y ficheros en contexto apto para LLMs.
- [SerpAPI](https://serpapi.com) - API alojada en tiempo real para resultados de Google y otros buscadores.
- [Bright Data](https://brightdata.com) - Plataforma de datos web con desbloqueo, APIs de scraping y datasets orientados a agentes.
- [Perplexity API](https://docs.perplexity.ai) - API Sonar para respuestas web fundamentadas y con citas que los agentes usan como herramienta de investigación.
- [Scrapling](https://github.com/D4Vinci/Scrapling) - Framework de web scraping en Python que cubre descarga, parseo y casos anti-bot en un solo kit que un agente puede usar.
- [Scrapy](https://scrapy.org) - Framework de Python para rastrear sitios y extraer datos estructurados de páginas a escala (`Open Source`).
- [Serper](https://serper.dev) - API de búsqueda que devuelve resultados de Google en un formato fácil de usar dentro de agentes (`Freemium`).
- [Brave Search API](https://brave.com/search/api/) - API de búsqueda que ofrece resultados web y de noticias para agentes y aplicaciones que necesitan contexto actualizado (`Freemium`).
- [Oxylabs](https://oxylabs.io) - API de recopilación de datos con proxies y analizadores para páginas extraídas que deben mantenerse fiables (`Freemium`).
- [Parallel](https://parallel.ai) - API de búsqueda y extracción que convierte páginas web en datos estructurados para flujos con LLM (`Freemium`).

## Memoria, RAG y bases vectoriales

- [Mem0](https://mem0.ai) - Capa de memoria para agentes de IA: extrae, guarda y recupera memorias a largo plazo de usuarios y agentes.
- [Zep](https://www.getzep.com) - Memoria y grafo de conocimiento para agentes, con contexto temporal y SDK en Python y TypeScript.
- [Chroma](https://www.trychroma.com) - Base de datos de embeddings open source popular para RAG local y en producción en apps de agentes.
- [Qdrant](https://qdrant.tech) - Base de datos vectorial open source con un filtrado muy capaz y servidor MCP oficial.
- [Pinecone](https://www.pinecone.io) - Base de datos vectorial gestionada que sirve de backend de recuperación a muchos agentes en producción.
- [Weaviate](https://weaviate.io) - Base de datos vectorial open source con búsqueda híbrida, colecciones y versión en la nube.
- [Milvus](https://milvus.io) - Base de datos vectorial open source y escalable de Zilliz, con la versión ligera Milvus Lite.
- [pgvector](https://github.com/pgvector/pgvector) - Extensión de PostgreSQL para búsqueda por similitud vectorial, opción por defecto en muchas pilas RAG autoalojadas.
- [LanceDB](https://lancedb.com) - Base de datos vectorial embebida y multimodal construida sobre Lance, útil para memoria local de agentes.
- [Graphiti](https://github.com/getzep/graphiti) - Framework open source de Zep para construir grafos de conocimiento en tiempo real y con conciencia temporal para agentes.
- [claude-mem](https://github.com/thedotmack/claude-mem) - Memoria persistente para agentes de código: captura lo que hace el agente, lo comprime e inyecta el contexto relevante en las sesiones siguientes.
- [GraphRAG](https://github.com/microsoft/graphrag) - Técnica que construye grafos de conocimiento sobre documentos para que los agentes respondan preguntas conectando ideas (`Open Source`).
- [RAGFlow](https://github.com/infiniflow/ragflow) - Plataforma de recuperación que prepara documentos y embeddings para responder preguntas sobre tu propio contenido (`Open Source`).
- [LightRAG](https://github.com/HKUDS/LightRAG) - Framework RAG ligero que indexa documentos y recupera contexto relevante para las respuestas de los agentes (`Open Source`).
- [Cognee](https://www.cognee.ai) - Capa de memoria que convierte datos y conversaciones en un grafo de conocimiento que los agentes pueden consultar con el tiempo (`Open Source`).
- [txtai](https://github.com/neuml/txtai) - Biblioteca que combina embeddings, búsqueda y flujos de trabajo para crear aplicaciones semánticas sobre datos de texto (`Open Source`).
- [FAISS](https://github.com/facebookresearch/faiss) - Biblioteca de búsqueda rápida de similitud sobre vectores, usada para recuperar pasajes relevantes en sistemas RAG (`Open Source`).
- [Vespa](https://vespa.ai) - Motor de búsqueda e inferencia que atiende consultas vectoriales, de texto y estructuradas a escala para agentes (`Open Source`).
- [MongoDB Atlas Vector Search](https://www.mongodb.com/products/platform/atlas-vector-search) - Búsqueda vectorial sobre documentos en Atlas, útil para basar las respuestas de los agentes en tus propios datos (`Freemium`).

## Observabilidad, evals y trazas

- [LangSmith](https://www.langchain.com/langsmith) - Plataforma de LangChain para trazar, evaluar y monitorizar agentes y apps de LLM.
- [Langfuse](https://langfuse.com) - Plataforma de ingeniería de LLM open source: trazas, prompts, evals y métricas, autoalojada o en la nube.
- [Arize Phoenix](https://phoenix.arize.com) - Herramienta open source de trazas, evaluación y playground para apps de LLM y agentes.
- [Braintrust](https://www.braintrust.dev) - Plataforma de evaluación y observabilidad para productos de IA, con un flujo de experimentos sólido.
- [Helicone](https://www.helicone.ai) - Pasarela y observabilidad de LLM open source: logs, costes, caché y gestión de prompts.
- [Promptfoo](https://www.promptfoo.dev) - Evals y red-teaming open source para prompts, agentes y RAG, ejecutables en CI.
- [DeepEval](https://github.com/confident-ai/deepeval) - Framework open source de evaluación para salidas de LLMs y agentes, con muchas métricas incluidas.
- [Ragas](https://docs.ragas.io) - Kit open source de evaluación centrado en pipelines de RAG y agentes.
- [Weights & Biases Weave](https://wandb.ai/site/weave) - W&B Weave para trazar, evaluar e iterar aplicaciones de LLM y agentes.
- [Portkey](https://portkey.ai) - Pasarela de IA con observabilidad, guardrails, enrutado y una API unificada entre proveedores.
- [Opik](https://www.comet.com/site/products/opik/) - Plataforma para trazar llamadas a LLM, evaluar resultados y depurar el comportamiento de los agentes a lo largo del tiempo (`Open Source`).
- [LangWatch](https://langwatch.ai) - Espacio de observabilidad y evaluación para equipos que lanzan funciones con LLM y supervisan su calidad (`Freemium`).
- [AgentOps](https://www.agentops.ai) - Herramienta que registra sesiones, llamadas a herramientas y fallos de los agentes para poder repetir y depurar cada ejecución (`Freemium`).
- [TruLens](https://www.trulens.org) - Biblioteca para evaluar la calidad de recuperación y generación con funciones de feedback e inspección de trazas (`Open Source`).
- [OpenLLMetry](https://www.traceloop.com) - Trazas basadas en OpenTelemetry para aplicaciones y agentes con LLM, compatibles con stacks de observabilidad existentes (`Open Source`).
- [Giskard](https://www.giskard.ai) - Biblioteca de pruebas que analiza aplicaciones con LLM en busca de vulnerabilidades, sesgos y regresiones antes del lanzamiento (`Open Source`).

## APIs de LLM, routers y runtimes

- [OpenAI API](https://platform.openai.com/docs) - API oficial para GPT, razonamiento, computer use, voz y el Agents SDK.
- [Anthropic API](https://docs.anthropic.com) - API oficial de Claude, con tool use, computer use, ficheros, conectores MCP y el Agent SDK.
- [Google AI Studio / Gemini API](https://ai.google.dev) - API oficial de Gemini, con function calling, thinking y funciones multimodales en vivo.
- [xAI API](https://docs.x.ai) - API oficial de los modelos Grok, con tool use y búsqueda en vivo.
- [Groq](https://groq.com) - API de inferencia muy rápida para modelos abiertos, usada a menudo como backend de agente barato y de baja latencia.
- [Together AI](https://www.together.ai) - Inferencia, fine-tuning y endpoints para modelos abiertos, con API compatible con OpenAI.
- [Fireworks AI](https://fireworks.ai) - Plataforma de inferencia rápida para modelos abiertos y de IA compuesta.
- [Mistral AI](https://mistral.ai) - Laboratorio europeo de modelos con API para chat, Codestral, embeddings y agentes.
- [Cohere](https://cohere.com) - API para los modelos Command, embeddings, rerank y tool use al estilo agente.
- [DeepSeek](https://www.deepseek.com) - API de los modelos chat y reasoner de DeepSeek, muy usada como cerebro de agente con buen coste.
- [OpenRouter](https://openrouter.ai) - API unificada que enruta a cientos de modelos de muchos proveedores con una sola clave.
- [LiteLLM](https://www.litellm.ai) - Proxy y SDK de Python open source que habla formato OpenAI con más de 100 proveedores de modelos.
- [Ollama](https://ollama.com) - La forma más sencilla de ejecutar modelos abiertos en local, con una API que muchos agentes ya entienden.
- [vLLM](https://github.com/vllm-project/vllm) - Servidor de inferencia open source de alto rendimiento para alojar modelos que tus agentes pueden llamar.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - Runtime estándar en C/C++ para ejecutar modelos GGUF en local, con servidor y bindings.
- [LM Studio](https://lmstudio.ai) - App de escritorio y servidor local para descubrir y ejecutar modelos, incluso como endpoint compatible con OpenAI.
- [Hugging Face Inference](https://huggingface.co/docs/inference-providers) - API de inferencia unificada y proveedores para ejecutar modelos abiertos del Hugging Face Hub.
- [Azure OpenAI](https://azure.microsoft.com/products/ai-services/openai-service/) - Modelos de OpenAI alojados en Azure, con redes, identidad y opciones regionales de empresa.
- [Amazon Bedrock](https://aws.amazon.com/bedrock/) - API gestionada de AWS para muchos modelos fundacionales, además de Bedrock Agents y Guardrails.
- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) - Inferencia y bindings de IA que se ejecutan en el edge, junto a Workers y Agents.
- [Cerebras](https://www.cerebras.ai) - API de inferencia de altísimo rendimiento, útil cuando el bucle de un agente necesita baja latencia.
- [SGLang](https://github.com/sgl-project/sglang) - Framework de servicio para LLM con generación estructurada e inferencia rápida en aplicaciones de alto rendimiento (`Open Source`).
- [LocalAI](https://localai.io) - Servidor de inferencia local que ejecuta modelos abiertos en tu hardware con una API compatible con OpenAI (`Open Source`).
- [Text Generation Inference](https://github.com/huggingface/text-generation-inference) - Servidor de inferencia de Hugging Face optimizado para servir modelos de lenguaje grandes con eficiencia (`Open Source`).
- [LMDeploy](https://github.com/InternLM/lmdeploy) - Kit de inferencia y servicio para LLM con compresión y kernels rápidos para despliegue (`Open Source`).
- [MiniMax API](https://platform.minimax.io) - API de modelos para tareas de texto, voz y multimodal, usada cuando un agente necesita generación alojada (`Freemium`).
- [SambaNova](https://sambanova.ai) - Plataforma de inferencia para ejecutar modelos abiertos en hardware especializado mediante una API (`Freemium`).

## Flujos de trabajo y orquestación

- [n8n](https://n8n.io) - Automatización de workflows open source con nodos de IA, agentes y servidor MCP oficial. Autoalojado o en la nube.
- [Make](https://www.make.com) - Plataforma de automatización visual que conecta apps y ejecuta pasos de IA y escenarios que disparan agentes.
- [Zapier](https://zapier.com) - Plataforma de automatización con un catálogo enorme de apps y un servidor MCP que expone acciones a agentes.
- [Temporal](https://temporal.io) - Plataforma de ejecución durable que suele ser la columna vertebral de workflows de agentes de larga duración.
- [Inngest](https://www.inngest.com) - Funciones durables y workflows por eventos en TypeScript, un harness habitual para pasos de agentes.
- [Prefect](https://www.prefect.io) - Orquestador de workflows en Python para programar, reintentar y observar pipelines de agentes y datos.
- [Pipedream](https://pipedream.com) - Plataforma de integración y workflows con un catálogo enorme de APIs y tools orientadas a MCP.
- [Trigger.dev](https://trigger.dev) - Trabajos en segundo plano y workflows durables open source para apps TypeScript, incluidas ejecuciones de agentes.
- [Activepieces](https://www.activepieces.com) - Plataforma de automatización sin código con un conjunto creciente de conectores para crear flujos asistidos por agentes (`Open Source`).
- [Windmill](https://www.windmill.dev) - Plataforma de flujos orientada a desarrolladores para ejecutar scripts como tareas, interfaces y automatizaciones programadas (`Open Source`).
- [Kestra](https://kestra.io) - Plataforma de orquestación que define flujos de datos y agentes como código con historial de ejecución visible (`Open Source`).
- [Apache Airflow](https://airflow.apache.org) - Plataforma de flujos para programar y supervisar pipelines, muy usada en ingeniería de datos (`Open Source`).
- [Dagster](https://dagster.io) - Orquestador de datos que hace visibles activos, dependencias y fallos en todos tus pipelines (`Open Source`).
- [Gumloop](https://www.gumloop.com) - Constructor visual de automatizaciones para equipos que quieren encadenar pasos de IA con herramientas habituales (`Freemium`).

## Voz, habla y tiempo real

- [OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime) - API oficial de OpenAI para agentes de voz a voz y multimodales de baja latencia.
- [Gemini Live](https://ai.google.dev/gemini-api/docs/live) - API multimodal en vivo de Gemini para agentes de voz y vídeo en tiempo real.
- [ElevenLabs](https://elevenlabs.io) - Texto a voz con voces de gran calidad, además de clonación de voz y agentes conversacionales de voz para tus proyectos.
- [Deepgram](https://deepgram.com) - APIs de voz a texto en streaming y de agentes de voz con baja latencia.
- [AssemblyAI](https://www.assemblyai.com) - APIs de voz a texto y comprensión de audio, con streaming para agentes de voz.
- [Pipecat](https://www.pipecat.ai) - Framework open source en Python para construir agentes de voz y multimodales en tiempo real.
- [LiveKit](https://livekit.io) - Stack de medios en tiempo real open source, con Agents para voz, vídeo y avatares.
- [Vapi](https://vapi.ai) - Plataforma para construir y alojar agentes de voz por teléfono y web.
- [Retell AI](https://www.retellai.com) - Plataforma para agentes de teléfono y voz, con LLM, TTS y telefonía ya conectados.
- [Cartesia](https://cartesia.ai) - Modelos y APIs de voz de latencia ultrabaja para agentes de voz en tiempo real.
- [Whisper](https://github.com/openai/whisper) - Modelo de voz a texto open source de OpenAI, aún el STT local por defecto para muchos agentes.
- [faster-whisper](https://github.com/SYSTRAN/faster-whisper) - Biblioteca optimizada de voz a texto que transcribe audio en local con menor consumo de recursos que modelos comparables (`Open Source`).
- [Piper](https://github.com/rhasspy/piper) - Motor local de texto a voz rápido con voces descargables para aplicaciones sin conexión y productos integrados (`Open Source`).
- [Gladia](https://www.gladia.io) - API de voz que transcribe y comprende audio, útil para añadir entrada por voz a productos (`Freemium`).
- [Daily](https://www.daily.co) - Infraestructura de vídeo y audio en tiempo real para añadir llamadas y salas de voz a aplicaciones (`Freemium`).

## Guardrails y seguridad

- [Guardrails AI](https://www.guardrailsai.com) - Validadores open source y comerciales que estructuran y limitan las salidas de LLMs y agentes.
- [NeMo Guardrails](https://github.com/NVIDIA-NeMo/Guardrails) - Toolkit open source de NVIDIA para añadir raíles programables alrededor de aplicaciones de LLM.
- [LLM Guard](https://github.com/protectai/llm-guard) - Escáner open source para inyección de prompts, datos personales y contenido tóxico o sensible.
- [Presidio](https://microsoft.github.io/presidio/) - Detección y anonimización de datos personales open source de Microsoft, útil como filtro previo o posterior de un agente.
- [Lakera Guard](https://www.lakera.ai) - Plataforma de seguridad centrada en inyección de prompts y protección en tiempo de ejecución de apps de IA.
- [Amazon Bedrock Guardrails](https://aws.amazon.com/bedrock/guardrails/) - Filtros de contenido gestionados, temas prohibidos y comprobaciones de fundamentación para modelos en Bedrock.
- [Invariant](https://invariantlabs.ai) - Capa de seguridad y políticas para agentes: inspecciona trazas, limita herramientas y detecta inyección de prompts.
- [SkillSpector](https://github.com/NVIDIA/SkillSpector) - Escáner de seguridad de NVIDIA para skills de agentes: busca vulnerabilidades, patrones maliciosos, inyección de prompts y riesgo de cadena de suministro antes de instalarlas.
- [garak LLM scanner](https://github.com/NVIDIA/garak) - Escáner que prueba aplicaciones con LLM en busca de inyección de prompts, fugas y otras debilidades habituales (`Open Source`).
- [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) - Framework para evaluar modelos de IA con tareas estructuradas, puntuadores y registros reproducibles (`Open Source`).
- [PyRIT](https://github.com/Azure/PyRIT) - Kit de herramientas para pruebas de seguridad ofensiva en sistemas de IA generativa con prompts adversarios automatizados (`Open Source`).
- [LangKit](https://github.com/whylabs/langkit) - Kit de herramientas para supervisar entradas y salidas de LLM con métricas de seguridad, relevancia y calidad (`Open Source`).

## Skills de agentes y marketplaces de tools

- [anthropics/skills](https://github.com/anthropics/skills) - Agent Skills oficiales de Anthropic: el formato, la documentación y un conjunto de skills de referencia para Claude.
- [obra/superpowers](https://github.com/obra/superpowers) - Colección de skills muy usada que da a los agentes de código una forma estructurada de planificar y entregar trabajo.
- [vercel-labs/skills](https://github.com/vercel-labs/skills) - CLI y registro (npx skills) para instalar Agent Skills en un proyecto.
- [Composio](https://composio.dev) - Marketplace gestionado de tools y SDK para que los agentes llamen a miles de APIs de terceros con la autenticación resuelta.
- [Arcade](https://arcade.dev) - Plataforma de herramientas y autenticación para agentes, con catálogo de integraciones y runtime compatible con MCP.
- [impeccable](https://github.com/pbakaus/impeccable) - Un vocabulario de diseño para agentes de código: skills para orientar el acabado y la crítica, y para pillar el trabajo genérico hecho por IA antes de publicarlo.
- [hallmark](https://github.com/Nutlope/hallmark) - Una skill de diseño que ayuda a Claude Code, Cursor y Codex a evitar interfaces con aspecto genérico de IA.
- [claude-seo](https://github.com/AgriciDaniel/claude-seo) - Skill de agente para auditorías de SEO técnico y de visibilidad en buscadores de IA (GEO/AEO), con sub-skills de schema, citas, preparación para agentes e informes.
- [Cloudflare security-audit-skill](https://github.com/cloudflare/security-audit-skill) - Skill oficial de Cloudflare para auditorías de seguridad en varias fases, con hallazgos verificados de forma independiente y legibles por máquinas.
- [instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill) - Conjunto de skills de agente para gestionar una cuenta de Instagram: investigación, ganchos, textos y un tono de publicación más humano.
- [last30days-skill](https://github.com/mvanhorn/last30days-skill) - Skill de agente que investiga un tema en Reddit, X, YouTube, Hacker News, Polymarket y la web, y redacta un resumen con fuentes.
- [ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) - Herramientas locales de FFmpeg con un contrato legible por máquinas y un servidor MCP, para que los agentes corten, subtitulen y exporten vídeo sin claves de API.
- [mcp.so](https://mcp.so) - Directorio de servidores MCP que ayuda a encontrar conectores para herramientas y fuentes de datos antes de crear los tuyos (`Free`).

## Marketing, SEO y prospección

APIs y plataformas que los flujos de agentes usan para encontrar leads, enriquecer cuentas e investigar demanda de búsqueda. Las herramientas open source conviven con productos muy usados que tienen una página pública a la que enlazar.

- [Clay](https://www.clay.com) - Espacio de enriquecimiento de datos y prospección para crear listas de contactos a partir de varias fuentes en un mismo flujo (`Freemium`).
- [Apollo.io](https://www.apollo.io) - Plataforma de prospección con datos de contactos y secuencias para equipos de ventas y crecimiento (`Freemium`).
- [Hunter](https://hunter.io) - Herramienta para encontrar y verificar direcciones de correo profesionales de un dominio durante la prospección (`Freemium`).
- [PhantomBuster](https://phantombuster.com) - Herramienta de automatización para redes sociales que ayuda a captar contactos y ejecutar tareas repetitivas de prospección (`Freemium`).
- [Instantly](https://instantly.ai) - Plataforma de prospección para gestionar secuencias de correo en frío, seguimientos y respuestas desde varias bandejas (`Freemium`).
- [Ahrefs](https://ahrefs.com) - Plataforma SEO para investigar palabras clave, analizar enlaces y seguir la visibilidad en buscadores con el tiempo (`Freemium`).
- [Screaming Frog](https://www.screamingfrog.co.uk/seo-spider/) - Rastreador que audita sitios web en busca de enlaces rotos, redirecciones y problemas de página antes del lanzamiento o durante el mantenimiento (`Freemium`).
- [AlsoAsked](https://alsoasked.com) - Herramienta que mapea preguntas relacionadas en los resultados de búsqueda para planificar contenidos según la intención real (`Freemium`).
- [BuiltWith](https://builtwith.com) - Herramienta que revela las tecnologías detrás de un sitio web, útil para investigación de mercado y prospección (`Freemium`).
- [People Data Labs](https://www.peopledatalabs.com) - Proveedor de datos de empresas y personas usado para enriquecer flujos de prospección y CRM (`Freemium`).

## Hecho por fluyeporlaweb

- [prospectforge](https://github.com/fluyeporlaweb/prospectforge) - Pipeline open source de leads B2B: descubre contactos, los cualifica contra tu ICP y redacta el primer mensaje. Por defecto va en dry-run y nunca envía correos.
- [Apify — fluyeporlaweb actors](https://fluyeporlaweb.com/go/apify-fluyeporlaweb/?p=github-readme) - Actors abiertos que publicamos en Apify (empleo, RSS, BOE, licitaciones) que un agente puede ejecutar vía API o MCP de Apify. *(afiliado)*

## Visto en nuestros vídeos

Hacemos reviews en vídeo de webs poco conocidas, repos de GitHub y web apps. Los artículos y los enlaces están en [fluyeporlaweb.com](https://fluyeporlaweb.com?src=github). Síguenos en [X](https://x.com/fluyeporlaweb) y en [Telegram](https://t.me/fluyeporlaweb).

## Patrocinadores

Este proyecto es gratuito y de código abierto. Las marcas que quieran aparecer aquí o colaborar pueden escribir a [colab@fluyeporlaweb.com](mailto:colab@fluyeporlaweb.com) o visitar [fluyeporlaweb.com/patrocina](https://fluyeporlaweb.com/patrocina?src=github).

**[Tu marca aquí](https://fluyeporlaweb.com/patrocina?src=github)**

## Más de fluyeporlaweb

- [awesome-design-stack](https://github.com/fluyeporlaweb/awesome-design-stack) — recursos de diseño web curados, en inglés y en español.
- [prospectforge](https://github.com/fluyeporlaweb/prospectforge) — pipeline open source de prospección B2B. Dry-run por defecto. Nunca envía correo.
- Web: [fluyeporlaweb.com](https://fluyeporlaweb.com?src=github)

## Listas relacionadas

Este directorio se curó a partir de fuentes primarias y de estas listas, entre otras. No las copiamos: seleccionamos, deduplicamos y reescribimos las descripciones.

- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - Un directorio grande y bien mantenido de servidores MCP.
- [punkpeye/awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients) - La lista complementaria de clientes y hosts MCP.
- [e2b-dev/awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) - Un recuento temprano e influyente de proyectos de agentes de IA.
- [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) - Aplicaciones LLM de código abierto, sistemas RAG y ejemplos de agentes.
- [kyrolabs/awesome-langchain](https://github.com/kyrolabs/awesome-langchain) - Un catálogo curado del ecosistema LangChain.
- [tensorchord/Awesome-LLMOps](https://github.com/tensorchord/Awesome-LLMOps) - Herramientas para servir, observar y operar sistemas LLM.
- [modelcontextprotocol](https://github.com/modelcontextprotocol) - La organización oficial de MCP: especificación, SDKs, registro e inspector.

## Contribuir

Las sugerencias y los pull requests son bienvenidos. Lee [CONTRIBUTING.md](CONTRIBUTING.md) antes de abrir uno y respeta el [Código de Conducta](CODE_OF_CONDUCT.md).

Si trabajas en este repo con un agente de código, indícale [AGENTS.md](AGENTS.md).

## Licencia

[MIT](LICENSE) © fluyeporlaweb

## Enlaces

- Web: [fluyeporlaweb.com](https://fluyeporlaweb.com?src=github)
- X: [@fluyeporlaweb](https://x.com/fluyeporlaweb)
- Telegram: [t.me/fluyeporlaweb](https://t.me/fluyeporlaweb)
- Correo: [colab@fluyeporlaweb.com](mailto:colab@fluyeporlaweb.com)
