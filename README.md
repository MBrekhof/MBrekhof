# Hey, I'm Martin 👋

Netherlands-based .NET developer pushing DevExpress XAF to its limits with AI. Each repo here is a focused proof-of-concept: one subject, fully documented, built to explore what's possible. These aren't libraries — they're reference implementations you can learn from, fork, or feed to your AI assistant. YMMV, but have fun.

![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=flat&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![DevExpress XAF](https://img.shields.io/badge/DevExpress-XAF-FF7200?style=flat)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

*Updated = last push. Repos marked **(fork)** are other people's projects I work in, not my own.*

---

## Headless XAF

| Repo | Updated | Description |
|---|---|---|
| **[XafHeadless](https://github.com/MBrekhof/XafHeadless)** | 2026-09-10 | Host XAF's model-driven core (TypesInfo, Application Model, Security, Validation) in a plain ASP.NET Core Web API, projected as JSON and rendered by a thin multi-render-mode Blazor client with zero XAF engine references (DevExpress 26.1 / .NET 10) |

## AI-Powered

| Repo | Updated | Description |
|---|---|---|
| **[SharpMind](https://github.com/MBrekhof/SharpMind)** *(fork)* | 2026-09-15 | Pure C# / .NET LLM engine — inference, training and agent tooling in one solution |
| **[XafTornado](https://github.com/MBrekhof/XafTornado)** | 2026-09-12 | Multi-provider AI assistant integrated into XAF via LLMTornado |
| **[XafDynamicAssemblies](https://github.com/MBrekhof/XafDynamicAssemblies)** | 2026-09-10 | AI-powered runtime entity system: create business object types, properties and relationships at runtime via Roslyn compilation (EF Core) |
| **[XafAIReportDesigner](https://github.com/MBrekhof/XafAIReportDesigner)** | 2026-09-09 | Standalone prompt-to-report designer with schema-aware AI context |
| **[XafXPODynAssem](https://github.com/MBrekhof/XafXPODynAssem)** | 2026-09-09 | Same runtime-entity concept as XafDynamicAssemblies, but built on XPO instead of EF Core |
| **[XafEasyTestAI](https://github.com/MBrekhof/XafEasyTestAI)** | 2026-08-26 | AI-authored XAF EasyTest functional tests for WinForms + Blazor: "making EasyTests the easy way" |
| **[XAFLogicExplainer](https://github.com/MBrekhof/XAFLogicExplainer)** *(fork)* | 2026-08-26 | Teach your AI coding agent what your XAF app actually does — Roslyn extraction of entities, controllers, business rules and Model Editor customizations |
| **[xafrag](https://github.com/MBrekhof/xafrag)** | 2026-07-19 | RAG pipeline for XAF Blazor using PostgreSQL/PGVector and DxAIChat |
| **[xafskills](https://github.com/MBrekhof/xafskills)** | 2026-06-14 | Claude Code skills distilling hard-learned XAF + EF Core patterns |
| **[LLMTornado](https://github.com/MBrekhof/LLMTornado)** *(fork)* | 2026-05-26 | The .NET library for building AI agents, with 30+ built-in connectors |
| **[XafGitHubCopilot](https://github.com/MBrekhof/XafGitHubCopilot)** *(fork)* | 2026-03-01 | GitHub Copilot integration for XAF |

## MCP Servers

| Repo | Updated | Description |
|---|---|---|
| **[mcpRoslyn](https://github.com/MBrekhof/mcpRoslyn)** | 2026-09-13 | C# code intelligence MCP server: 20 tools plus echo for navigation, diagnostics, DI analysis, dead-code detection and rename over Roslyn MSBuildWorkspace |
| **[mcpOffice](https://github.com/MBrekhof/mcpOffice)** | 2026-09-02 | MCP server for Microsoft Office documents, built on DevExpress.Docs |
| **[mcpsql](https://github.com/MBrekhof/mcpsql)** | 2026-08-26 | Read-only MCP server for Microsoft SQL Server: schema introspection plus SELECT-only queries behind a strict validator |
| **[XafMcp](https://github.com/MBrekhof/XafMcp)** | 2026-08-10 | An XAF LOB app exposing *itself* as an MCP server — metadata, secured data, log forensics, schema drift |

## Security & Roles

| Repo | Updated | Description |
|---|---|---|
| **[XafRoleChooser](https://github.com/MBrekhof/XafRoleChooser)** | 2026-08-26 | Runtime role selection |
| **[XafNavigationHub](https://github.com/MBrekhof/XafNavigationHub)** | 2026-08-26 | Navigation hub patterns |
| **[XafSecureSearch](https://github.com/MBrekhof/XafSecureSearch)** | 2026-03-18 | Secure search implementation |
| **[XafSecureDash](https://github.com/MBrekhof/XafSecureDash)** | 2026-03-11 | Secured dashboard patterns |
| **[xafroles](https://github.com/MBrekhof/xafroles)** | 2026-03-08 | Role export/import for DEV/TEST/PROD synchronization |
| **[XafPartition](https://github.com/MBrekhof/XafPartition)** | 2026-03-06 | Data partitioning |

## Infrastructure & Integration

| Repo | Updated | Description |
|---|---|---|
| **[XAFn8nCRM](https://github.com/MBrekhof/XAFn8nCRM)** | 2026-09-16 | XAF Blazor CRM with n8n workflow automation via OData/REST |
| **[XafLayoutBuilder](https://github.com/MBrekhof/XafLayoutBuilder)** | 2026-09-15 | Typed C# builders for XAF view layouts and appearance rules, with export from the running Blazor app back to code |
| **[XafMergerTool](https://github.com/MBrekhof/XafMergerTool)** | 2026-09-15 | Developer tool for saving XAF Blazor runtime view customizations back into module XAFML |
| **[xafgrid](https://github.com/MBrekhof/xafgrid)** | 2026-09-03 | XAF Blazor grid demos: nested detail rows, rich cells, custom grouping, summaries, row reordering and saved layouts |
| **[XafReportScheduler](https://github.com/MBrekhof/XafReportScheduler)** | 2026-08-26 | XAF Blazor report scheduling with editable seeded reports, saved filter criteria and Hangfire cron jobs |
| **[XafReportParametersObjects](https://github.com/MBrekhof/XafReportParametersObjects)** | 2026-08-22 | Generate ReportsV2 `ReportParametersObjectBase` classes from report metadata at the push of a button |
| **[xafmaui](https://github.com/MBrekhof/xafmaui)** | 2026-08-10 | XAF Blazor Server + .NET MAUI mobile companion (Project Administration MVP) |
| **[XafImport](https://github.com/MBrekhof/XafImport)** | 2026-08-02 | ETL-style import/export module for XAF with Hangfire background jobs |
| **[XAFProfiler](https://github.com/MBrekhof/XAFProfiler)** | 2026-05-31 | StackExchange MiniProfiler in XAF Blazor Server, including profiling over the SignalR circuit where there is no HttpContext |
| **[XafTVF](https://github.com/MBrekhof/XafTVF)** | 2026-05-23 | Mapping SQL table-valued functions to non-persistent DTOs (EF Core 10, DevExpress 25.2, .NET 10) |
| **[XafFilter](https://github.com/MBrekhof/XafFilter)** | 2026-05-17 | Custom column-filter UI for XAF Blazor Server: five drop-in filter menus with a tested demo app |
| **[XafGrafana](https://github.com/MBrekhof/XafGrafana)** | 2026-04-06 | Prometheus/Grafana observability stack for XAF Blazor Server |
| **[XafSearch](https://github.com/MBrekhof/XafSearch)** | 2026-03-08 | Search functionality patterns |
| **[XafDataDrivenConditionalApp](https://github.com/MBrekhof/XafDataDrivenConditionalApp)** | 2026-03-06 | Database-stored, runtime-editable appearance rules |
| **[xafhangfire](https://github.com/MBrekhof/xafhangfire)** | 2026-03-04 | Hangfire job dispatcher integration |

## Tooling & Experimental

| Repo | Updated | Description |
|---|---|---|
| **[limbo](https://github.com/MBrekhof/limbo)** | 2026-08-10 | Limbo-inspired 2D puzzle-platformer built with Godot 4.6 + C# (not XAF!) |
| **[MarkdownToDocxGenerator](https://github.com/MBrekhof/MarkdownToDocxGenerator)** *(fork)* | 2026-06-08 | Markdown → docx library for turning one or more files into a Word document |
| **[tcpdebug](https://github.com/MBrekhof/tcpdebug)** | 2026-02-10 | WinForms HTTP debug receiver for capturing debug traffic from browser/web-service environments |
