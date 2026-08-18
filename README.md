# Meridian

> **The Operating System for AI Agents.**  
> **El Sistema Operativo de los Agentes de IA.**

[![Community](https://img.shields.io/badge/community-open%20to%20builders-334FB4?style=flat-square)](https://github.com/christiandejesus320-droid/Meridian-Open-Source/discussions)
[![Documentation](https://img.shields.io/badge/docs-coming%20soon-c0c0c0?style=flat-square)](https://github.com/christiandejesus320-droid/Meridian-Open-Source)
[![License](https://img.shields.io/badge/license-Apache--2.0-111111?style=flat-square)](LICENSE)

Meridian is a community-driven initiative to make AI agents useful beyond the chat window: organized, permission-aware, connected to real systems, and capable of turning intent into accountable execution.

Meridian es una iniciativa impulsada por la comunidad para llevar los agentes de IA más allá de la ventana de chat: organizados, conscientes de los permisos, conectados a sistemas reales y capaces de convertir la intención en ejecución verificable.

---

## English

### Vision

AI should not be another application people have to manage. It should become an operating layer for work: a place where people, agents, knowledge, workflows, and decisions can operate together without losing context or control.

Meridian is being shaped as that operating layer. It brings structured workspaces, agent capabilities, governed automations, and human approval into one coherent system. The goal is not to replace people. The goal is to give people a higher-leverage interface for thinking, building, and operating.

> **Meridian is where AI agents gain context, boundaries, memory, and a path to action.**

### What We Are Building

Meridian explores a modular platform for agent-native workspaces:

| Layer | Purpose |
|---|---|
| Workspaces | Organize pages, projects, tasks, knowledge, and decisions in one operating context. |
| Agent Runtime | Give agents explicit capabilities, scoped access, and auditable actions. |
| Knowledge Layer | Connect structured data, documents, blocks, and operational context. |
| Integration Layer | Use MCP and secure connectors to reach the tools teams already use. |
| Governance Layer | Keep humans in control through permissions, approvals, logs, and safe defaults. |

### Tech Stack

Meridian is designed around an open, composable stack. The public repository documents the architecture and community contracts; it does **not** contain the private engine or production source code.

| Technology | Role in the Meridian architecture |
|---|---|
| Supabase | Auth, Postgres data, storage, realtime primitives, and secure project infrastructure. |
| Prisma | Typed data access, schema discipline, migrations, and safe domain boundaries. |
| MCP | A connector protocol for giving agents structured access to tools and services. |
| TypeScript | Shared contracts across the product, agent capabilities, and integrations. |
| Next.js | Product surfaces, documentation experiences, and server-rendered application boundaries. |
| GitHub + Vercel | Community collaboration, continuous delivery, previews, and public project visibility. |

### Roadmap 2026

| Quarter | Focus | Community outcome |
|---|---|---|
| Q1 | Public architecture | Publish the Meridian mental model, core terminology, and contribution pathways. |
| Q2 | Agent capabilities | Define capability contracts, permission scopes, tool boundaries, and evaluation practices. |
| Q3 | MCP ecosystem | Build connector patterns and reference integrations for agent-native workflows. |
| Q4 | Community network | Launch public experiments, contributor programs, showcases, and a Silicon Valley-facing demo narrative. |

The roadmap is directional. We will prioritize durable primitives, transparent decisions, and useful demonstrations over vanity features.

### How to Join the Movement

You do not need access to the private engine to contribute to Meridian. The public community is where we develop the ideas, standards, experiments, documentation, integrations, and feedback loops that make the system stronger.

Start by reading the documentation, opening a discussion, proposing a use case, improving terminology, sharing an MCP integration pattern, or helping us test an agent workflow. If you are a builder, researcher, designer, product thinker, security practitioner, or operator, there is a place for your perspective.

1. **Watch the repository** to follow the public roadmap.
2. **Start a Discussion** with a use case, question, or architecture proposal.
3. **Open an issue** only when the problem is specific, reproducible, and documented.
4. **Read `CONTRIBUTING.md`** before submitting a pull request.
5. **Respect the Zero-Code Exposure policy:** do not request, publish, infer, or reconstruct private engine code, credentials, production configuration, or user data.

### Zero-Code Exposure

This repository is the **Public Face** of Meridian. It exists to attract builders and make the vision legible without exposing the proprietary engine.

The public surface may contain documentation, architectural concepts, community standards, examples that are intentionally self-contained, issue templates, and non-sensitive diagrams. It must never contain private application source, secrets, production environment variables, database dumps, customer data, internal URLs, credentials, or copied files from private repositories.

Security reports should be handled privately according to the process described in `SECURITY.md` when that file is published.

---

## Español

### Visión

La IA no debería ser otra aplicación que las personas tienen que administrar. Debería convertirse en una capa operativa para el trabajo: un espacio donde personas, agentes, conocimiento, flujos y decisiones puedan funcionar juntos sin perder contexto ni control.

Meridian se está construyendo como esa capa operativa. Reúne espacios de trabajo estructurados, capacidades de agentes, automatizaciones gobernadas y aprobación humana en un sistema coherente. El objetivo no es reemplazar a las personas, sino ofrecerles una interfaz de mayor apalancamiento para pensar, construir y operar.

> **Meridian es el lugar donde los agentes de IA obtienen contexto, límites, memoria y un camino seguro hacia la acción.**

### Qué estamos construyendo

Meridian explora una plataforma modular para espacios de trabajo nativos de agentes:

| Capa | Propósito |
|---|---|
| Espacios de trabajo | Organizar páginas, proyectos, tareas, conocimiento y decisiones en un mismo contexto operativo. |
| Runtime de agentes | Dar a los agentes capacidades explícitas, acceso limitado y acciones auditables. |
| Capa de conocimiento | Conectar datos estructurados, documentos, bloques y contexto operacional. |
| Capa de integraciones | Usar MCP y conectores seguros para llegar a las herramientas que los equipos ya utilizan. |
| Capa de gobernanza | Mantener a las personas en control mediante permisos, aprobaciones, registros y valores seguros por defecto. |

### Stack tecnológico

Meridian está diseñado alrededor de un stack abierto y componible. El repositorio público documenta la arquitectura y los contratos de comunidad; **no contiene el motor privado ni el código fuente de producción**.

| Tecnología | Función en la arquitectura Meridian |
|---|---|
| Supabase | Autenticación, datos en Postgres, almacenamiento, primitivas realtime e infraestructura segura. |
| Prisma | Acceso tipado a datos, disciplina de esquema, migraciones y límites de dominio seguros. |
| MCP | Protocolo de conectores para dar a los agentes acceso estructurado a herramientas y servicios. |
| TypeScript | Contratos compartidos entre producto, capacidades de agentes e integraciones. |
| Next.js | Superficies de producto, experiencias de documentación y límites server-rendered. |
| GitHub + Vercel | Colaboración comunitaria, entrega continua, previews y visibilidad pública del proyecto. |

### Roadmap 2026

| Trimestre | Enfoque | Resultado para la comunidad |
|---|---|---|
| T1 | Arquitectura pública | Publicar el modelo mental de Meridian, su terminología y las vías de contribución. |
| T2 | Capacidades de agentes | Definir contratos de capacidades, scopes de permisos, límites de herramientas y prácticas de evaluación. |
| T3 | Ecosistema MCP | Crear patrones de conectores e integraciones de referencia para flujos de trabajo nativos de agentes. |
| T4 | Red comunitaria | Lanzar experimentos públicos, programas para contribuidores, showcases y una narrativa de demo orientada a Silicon Valley. |

El roadmap es orientativo. Priorizaremos primitivas duraderas, decisiones transparentes y demostraciones útiles por encima de funcionalidades de vanidad.

### Cómo unirse al movimiento

No necesitas acceso al motor privado para contribuir a Meridian. La comunidad pública es el lugar donde desarrollamos las ideas, estándares, experimentos, documentación, integraciones y ciclos de feedback que hacen más fuerte al sistema.

Empieza leyendo la documentación, abriendo una discusión, proponiendo un caso de uso, mejorando la terminología, compartiendo un patrón de integración MCP o ayudándonos a probar un flujo de agentes. Si eres desarrollador, investigador, diseñador, estratega de producto, especialista en seguridad u operador, tu perspectiva tiene un lugar.

1. **Sigue el repositorio** para recibir el roadmap público.
2. **Abre una Discussion** con un caso de uso, una pregunta o una propuesta de arquitectura.
3. **Abre un issue** solo cuando el problema sea específico, reproducible y esté documentado.
4. **Lee `CONTRIBUTING.md`** antes de enviar un pull request.
5. **Respeta la política Zero-Code Exposure:** no solicites, publiques, infieras ni reconstruyas código privado del motor, credenciales, configuración de producción o datos de usuarios.

### Zero-Code Exposure

Este repositorio es la **fachada pública** de Meridian. Existe para atraer programadores y hacer legible la visión sin exponer el motor propietario.

La superficie pública puede contener documentación, conceptos de arquitectura, estándares de comunidad, ejemplos autocontenidos de forma intencional, plantillas de issues y diagramas no sensibles. Nunca debe contener código privado de la aplicación, secretos, variables de entorno de producción, volcados de base de datos, datos de clientes, URLs internas, credenciales ni archivos copiados desde repositorios privados.

Los reportes de seguridad deben manejarse de forma privada según el proceso descrito en `SECURITY.md` cuando ese archivo sea publicado.

---

## Public-Face principles

Meridian-Open-Source is a documentation-first repository. It is intentionally separate from the private application repository. A strong public community does not require exposing the engine; it requires making the vision, boundaries, contribution paths, and technical vocabulary clear.

Meridian-Open-Source es un repositorio orientado primero a la documentación. Está separado intencionalmente del repositorio privado de la aplicación. Una comunidad pública sólida no requiere exponer el motor; requiere hacer clara la visión, los límites, las vías de contribución y el vocabulario técnico.

## License

Apache License 2.0. See [`LICENSE`](LICENSE).

## References

- [Model Context Protocol](https://modelcontextprotocol.io/)
- [Supabase](https://supabase.com/)
- [Prisma](https://www.prisma.io/)
- [Next.js](https://nextjs.org/)
- [GitHub Discussions](https://docs.github.com/en/discussions)
