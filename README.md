# Hey, I'm Martin 👋

Netherlands-based .NET developer pushing DevExpress XAF to its limits with AI. Each repo here is a focused proof-of-concept: one subject, fully documented, built to explore what's possible. These aren't libraries — they're reference implementations you can learn from, fork, or feed to your AI assistant. YMMV, but have fun.

![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=flat&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![DevExpress XAF](https://img.shields.io/badge/DevExpress-XAF-FF7200?style=flat)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

## Headless XAF

- **[XafHeadless](https://github.com/MBrekhof/XafHeadless)** — Host XAF's model-driven core (TypesInfo, Application Model, Security, Validation) in a plain ASP.NET Core Web API, projected as JSON and rendered by a thin multi-render-mode Blazor client with zero XAF engine references (DevExpress 26.1 / .NET 10)

## AI-Powered

- **[XafDynamicAssemblies](https://github.com/MBrekhof/XafDynamicAssemblies)** — AI-powered runtime entity system: create new business object types, properties, and relationships at runtime using Roslyn compilation (EF Core)
- **[XafXPODynAssem](https://github.com/MBrekhof/XafXPODynAssem)** — Same concept as above, but built on XPO instead of EF Core
- **[XafAIReportDesigner](https://github.com/MBrekhof/XafAIReportDesigner)** — Standalone prompt-to-report designer with schema-aware AI context
- **[XafEasyTestAI](https://github.com/MBrekhof/XafEasyTestAI)** — AI-authored XAF EasyTest functional tests for WinForms + Blazor: "making EasyTests the easy way"
- **[XafTornado](https://github.com/MBrekhof/XafTornado)** — Multi-provider AI assistant integrated into XAF via LLMTornado
- **[xafrag](https://github.com/MBrekhof/xafrag)** — RAG pipeline for XAF Blazor using PostgreSQL/PGVector and DxAIChat
- **[XafGitHubCopilot](https://github.com/MBrekhof/XafGitHubCopilot)** — GitHub Copilot integration for XAF
- **[xafskills](https://github.com/MBrekhof/xafskills)** — Claude Code skills distilling hard-learned XAF + EF Core patterns

## MCP Servers

- **[mcpRoslyn](https://github.com/MBrekhof/mcpRoslyn)** — C# code intelligence MCP server: 13 symbol-level navigation tools (find_references, goto_definition, semantic_search, …) over Roslyn MSBuildWorkspace
- **[mcpOffice](https://github.com/MBrekhof/mcpOffice)** — MCP server for Microsoft Office documents, built on DevExpress.Docs
- **[mcpsql](https://github.com/MBrekhof/mcpsql)** — Read-only MCP server for Microsoft SQL Server: schema introspection plus SELECT-only queries behind a strict validator

## Security & Roles

- **[XafRoleChooser](https://github.com/MBrekhof/XafRoleChooser)** — Runtime role selection
- **[xafroles](https://github.com/MBrekhof/xafroles)** — Role export/import for DEV/TEST/PROD synchronization
- **[XafSecureDash](https://github.com/MBrekhof/XafSecureDash)** — Secured dashboard patterns
- **[XafSecureSearch](https://github.com/MBrekhof/XafSecureSearch)** — Secure search implementation
- **[XafNavigationHub](https://github.com/MBrekhof/XafNavigationHub)** — Navigation hub patterns
- **[XafPartition](https://github.com/MBrekhof/XafPartition)** — Data partitioning

## Infrastructure & Integration

- **[XafGrafana](https://github.com/MBrekhof/XafGrafana)** — Prometheus/Grafana observability stack for XAF Blazor Server
- **[XAFProfiler](https://github.com/MBrekhof/XAFProfiler)** — StackExchange MiniProfiler in XAF Blazor Server, including profiling over the SignalR circuit where there is no HttpContext
- **[xafhangfire](https://github.com/MBrekhof/xafhangfire)** — Hangfire job dispatcher integration
- **[XAFn8nCRM](https://github.com/MBrekhof/XAFn8nCRM)** — XAF Blazor CRM with n8n workflow automation via OData/REST
- **[xafmaui](https://github.com/MBrekhof/xafmaui)** — XAF Blazor Server + .NET MAUI mobile companion
- **[XafFilter](https://github.com/MBrekhof/XafFilter)** — Custom column-filter UI for XAF Blazor Server: five drop-in filter menus with a tested demo app
- **[XafTVF](https://github.com/MBrekhof/XafTVF)** — Mapping SQL table-valued functions to non-persistent DTOs (EF Core 10, DevExpress 25.2, .NET 10)
- **[XafReportParametersObjects](https://github.com/MBrekhof/XafReportParametersObjects)** — Generate ReportsV2 `ReportParametersObjectBase` classes from report metadata at the push of a button
- **[XafDataDrivenConditionalApp](https://github.com/MBrekhof/XafDataDrivenConditionalApp)** — Database-stored, runtime-editable appearance rules
- **[XafSearch](https://github.com/MBrekhof/XafSearch)** — Search functionality patterns

## Other & Experimental

- **[limbo](https://github.com/MBrekhof/limbo)** — Limbo-inspired 2D puzzle-platformer built with Godot 4.6 + C# (not XAF!)
- **[ClaudeBoard](https://github.com/MBrekhof/ClaudeBoard)** — WinForms dashboard for managing Claude Code configuration across projects
- **[ClaudeViewer](https://github.com/MBrekhof/ClaudeViewer)** — WinForms artifact viewer for Claude Code: watches a folder for HTML/Markdown and renders them in tabbed WebView2 panes
- **[tcpdebug](https://github.com/MBrekhof/tcpdebug)** — WinForms HTTP debug message receiver
- **[yvanGPT](https://github.com/MBrekhof/yvanGPT)** — GPT experiment
- **[Reactive.XAF](https://github.com/MBrekhof/Reactive.XAF)** — Fork of the ExpandFramework XAF extensions

---

All repos are POCs — they aim to cover the feature fully but aren't production-polished libraries. I use them as reference for my own XAF apps, and they're documented well enough that both humans and AI can pick them up. Star what you find useful, fork what you need.
