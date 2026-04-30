# Nicolás Orefice

AI Lead en un equipo de desarrollo enterprise. Trabajo en cómo el equipo opera con AI como parte del flujo, no como un atajo individual.

Mi laboratorio cotidiano es [Encuentra.io](https://encuentra.io), una plataforma Java multi-tenant de WMS e integraciones con clientes enterprise en 5 países. Ese contexto — código con años de historia, stack legacy, equipo pequeño y exigencias enterprise — es lo que define cómo aplico AI: skills y agents propios para el dominio, no recetas genéricas.

## Qué hago

- **AI en el equipo de desarrollo** — adopción de Claude Code y Cursor como entorno principal, skills y subagents custom por dominio, MCPs integrados a las herramientas internas.
- **Plataforma Encuentra** — evolución de una plataforma Java (Jersey, Jetty, Redis, RabbitMQ) multi-tenant con clientes enterprise activos en 5 países.
- **Automatización operativa** — herramientas internas sobre Jira para soporte, sprints y reporting.

## Cómo trabajo con AI

- **Claude Code** como entorno principal: skills custom por dominio (Java legacy, JSP/Struts, Jetty, Redis, multi-tenancy), subagents especializados con responsabilidad acotada, memoria persistente entre sesiones.
- **MCPs** integrados a Atlassian, Slack y herramientas internas para mantener el contexto sin salir del flujo.
- **AI sobre legacy enterprise** — el desafío real no es generar código nuevo, es operar con AI dentro de un codebase con años de historia, convenciones idiosincráticas y clientes que no toleran regresiones.

📂 **[claude-code-routing](https://github.com/norefice/claude-code-routing)** — el framework que uso para decidir cuándo una tarea va como prompt directo, subagent, o agent team. Catálogo de los 11 subagents que dispatcheo y guía para adaptarlo a otro stack.

## Proyectos públicos

| Repo | Qué es |
|---|---|
| [claude-code-routing](https://github.com/norefice/claude-code-routing) | Framework de decisión para routear tareas en Claude Code (prompt / subagent / agent team) en codebases enterprise. |
| [Obsidian-Taskify](https://github.com/norefice/Obsidian-Taskify) | Plugin de Obsidian para gestionar tareas dentro de notas (estados, prioridad, tags, due date). TypeScript. |
| [JiraSoporte](https://github.com/norefice/JiraSoporte) | Dashboard Flask para métricas de Service Desk en Jira. |
| [JiraSprints](https://github.com/norefice/JiraSprints) | Análisis y visualización de sprints sobre la API de Jira. |
| [JiraHoras](https://github.com/norefice/JiraHoras) | Control de tiempo y productividad sobre tickets de Jira. |

La mayor parte de mi código vive en repositorios privados de Encuentra.

## Stack principal

Java · Python · TypeScript · MySQL · Redis · RabbitMQ · Jetty · Jersey · Claude Code · Cursor · MCPs

## Contacto

[LinkedIn](https://www.linkedin.com/in/norefice/) · norefice@gmail.com · Montevideo, Uruguay
