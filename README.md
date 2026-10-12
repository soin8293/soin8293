# Sorbarikor Inene

I build and test automated systems across infrastructure and AI, with a focus
on clear system behavior, operational safeguards, and reliable state.

[Portfolio](https://sorbarikorinene.com) ·
[LinkedIn](https://www.linkedin.com/in/sorbarikor-inene/)

## Flagship work

### Infrastructure security and AI reliability

[AI SOC Assistant](https://github.com/soin8293/ai_soc_assistant) turns authorized
private-network scan results into plain-language explanations of observed open
ports. This educational prototype pairs scan boundaries and a local fallback
with tests for authorization and explanation quality.

[Explainable Network Exposure Benchmark](https://github.com/soin8293/explainable-network-exposure-benchmark)
explores the same reliability problem using synthetic cases: does an explanation
stay faithful to the evidence, communicate uncertainty, and resist an injected
instruction? It has separate scoring from the application's evaluator.

[Application architecture](https://github.com/soin8293/ai_soc_assistant#architecture) ·
[Evaluation method and limits](https://github.com/soin8293/explainable-network-exposure-benchmark/blob/main/docs/methodology.md)

### Operations and automation

[PowerShell QOps](https://github.com/soin8293/powershell-qops) helps operators
inspect system capacity and preview file cleanup before making changes. It
produces structured reports and supports dry-run and confirmation controls,
with Windows/Linux CI and regression tests for cleanup behavior.

[Architecture and safeguards](https://github.com/soin8293/powershell-qops/blob/main/docs/architecture.md) ·
[Synthetic audit output](https://github.com/soin8293/powershell-qops/blob/main/examples/full-audit.sample.json)

### Agent state and retrieval

[Memory_DB](https://github.com/soin8293/memory_Db) helps agents retain project
facts and decisions between sessions. This experimental local-first tool uses
an append-only ledger, project-scoped recall, and optional semantic retrieval;
tests cover store isolation and correction handling.

[Store and recall a project fact](https://github.com/soin8293/memory_Db#quickstart) ·
[Synthetic lexical retrieval benchmark](https://github.com/soin8293/memory_Db/blob/main/docs/retrieval-benchmark.md)

## Supporting work

- [Live Music Request Orchestrator](https://github.com/soin8293/live-music-request-orchestrator):
  turns incoming music-request events into a deduplicated queue and an OBS-ready
  overlay, with REST/SSE updates.
- [Selenium Web Testing](https://github.com/soin8293/Selenium-Web-Testing):
  educational browser-flow and accessibility smoke checks against a public sandbox.

## How I develop these systems

I extend existing systems around concrete problems, make their boundaries
explicit, and turn discovered failures into regression tests.

I develop independent projects through AmirahCo. Each repository documents its
own maintenance, license, and upstream credits.

## AI assistance

I use AI assistance for implementation, tests, documentation, and maintenance.
As maintainer (soin8293), I remain responsible for project decisions, review,
and validation. Project READMEs describe the assistance scope, checks, limitations,
and applicable credits.
