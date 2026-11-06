# Sorbarikor Inene

I build tools that help software agents retain decisions, follow workflows,
and recover from failures. My projects also cover infrastructure automation
and evaluation of AI-generated security explanations.

[Portfolio](https://sorbarikorinene.com) ·
[LinkedIn](https://www.linkedin.com/in/sorbarikor-inene/)

## Flagship work

### Agent context and workflows

[Context Keeper](https://github.com/soin8293/context-keeper) helps coding agents
save and retrieve project decisions between sessions. It preserves decision
history, links records to their sources, and produces task briefs that report
missing or outdated context. Its Python helpers run locally without model calls.

[Usage guide](https://github.com/soin8293/context-keeper/blob/main/docs/usage.md) ·
[Example brief](https://github.com/soin8293/context-keeper/blob/main/examples/expected-handoff.md) ·
[Tests and limits](https://github.com/soin8293/context-keeper/blob/main/docs/testing.md)

[Workflow Creator](https://github.com/soin8293/workflow-creator) helps an agent
turn project documents into runnable workflows with checks and saved progress.
It reuses an existing project engine where one fits, or the included Workflow
Foundry runtime. This early release includes an offline installer and an example
that rejects a wrong result, saves a wait, and resumes after repair.

[Runnable example](https://github.com/soin8293/workflow-creator/blob/main/examples/README.md) ·
[Testing and trial limits](https://github.com/soin8293/workflow-creator/blob/main/TESTING.md)

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

## Supporting work

- [Memory_DB](https://github.com/soin8293/memory_Db): experimental local-first
  agent memory with an append-only ledger, project-scoped recall, optional semantic
  retrieval, and a [synthetic lexical benchmark](https://github.com/soin8293/memory_Db/blob/main/docs/retrieval-benchmark.md).
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
