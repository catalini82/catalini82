# Catalin Iliescu

**Senior Systems Solution Engineer and hands-on applied AI systems builder** — almost 20 years
in enterprise infrastructure and customer-facing solution engineering, now focused on
self-directed **agentic AI engineering**: multi-agent orchestration, LLMOps, local LLM
inference, model evaluation, and memory/retrieval architecture.

I build agentic AI systems from scratch and run them in production for my own work —
actively adding features, fixes, and optimizations — and I contribute upstream to popular
open-source AI projects.

## What I build

- **[CMC OS](https://github.com/catalini82/cmc-os-architecture)** — a local-first agentic
  workflow control plane that turns vague goals into structured design, Pipeline/Kanban work
  items, agent + tool execution, and test/audit gates, with human escalation only at risk or
  decision points. Running in production for my own workflows, under active development;
  companion Android app in design. (Public architecture notes + Mermaid diagrams.)
- **[Hermes Agent](https://github.com/catalini82/hermes-agent-architecture)** — a 7-role
  multi-agent system (generalist, coder, auditor, orchestrator, ops, pr-scout, researcher)
  with a Mixture-of-Agents "LLM council" + judge for high-stakes decisions, over durable
  memory (append-only JSONL + SQLite FTS5 + RRF hybrid retrieval). In active use and
  continuously improved. (Public architecture notes + Mermaid diagrams.)
- **Odysseus Vault Mode** — a downstream privacy/isolation feature for sensitive AI sessions
  (local-model-only execution, isolated from normal memory/RAG/agentic context), structured
  as an upstream feature proposal.

## Pinned repositories

- **[`cmc-os-architecture`](https://github.com/catalini82/cmc-os-architecture)** — public
  architecture notes for CMC OS: multi-agent orchestration, MCP/tool execution, audit gates,
  and human-in-the-loop AI workflows.
- **[`hermes-agent-architecture`](https://github.com/catalini82/hermes-agent-architecture)** —
  public architecture notes for my Hermes-based multi-agent system: role-specialized agents,
  LLM council/judge orchestration, durable memory, hybrid retrieval, and local AI operations.
- **[`local-llm-lab`](https://github.com/catalini82/local-llm-lab)** — practical local LLM lab:
  inference runtimes, AI agents, LLM evaluation, memory/retrieval, and GPU infrastructure.
- **[`odysseus`](https://github.com/catalini82/odysseus)** — fork of a popular self-hosted AI
  workspace (80k+ stars), used for upstream contribution work and agent-workflow exploration.
- **[`enterprise-ai-architecture-checklists`](https://github.com/catalini82/enterprise-ai-architecture-checklists)** —
  practical enterprise GenAI architecture, readiness, governance, security, and LLMOps checklists.

## Public open-source contributions

**22 public PRs (21 merged)** hardening two popular open-source AI platforms — tests,
integrity checks, safe deployment, and upstream-friendly documentation.

- **Oprel** (local-AI platform) — 15 merged PRs: binary provenance, SHA256/size integrity
  checks, safe download cleanup, verified manifest entries, deployment guides, CI smoke/link checks.
- **Odysseus** (self-hosted AI workspace, 80k+ stars) — 7 PRs (6 merged, 1 open): memory
  owner-isolation tests, webhook test isolation, hardware-fit CPU fallback, CORS/proxy docs,
  server metadata preservation, provider detection.

## Focus areas

- **Agentic AI:** multi-agent orchestration, LLM councils / Mixture-of-Agents, tool calling, MCP
- **LLMOps & inference:** local/cloud LLMs, llama.cpp/GGUF, quantization, KV-cache, long-context, cost/latency/reliability trade-offs
- **Memory & retrieval:** SQLite FTS5, semantic + hybrid retrieval, RRF ranking, memory architecture
- **AI infrastructure:** GPU/CPU workload placement, model-role separation, model evaluation for real engineering tasks
- **Enterprise foundation:** ~20 years infrastructure + customer-facing solution engineering

## Links

- LinkedIn: https://www.linkedin.com/in/catalin-iliescu-64989755/
- GitHub: https://github.com/catalini82
