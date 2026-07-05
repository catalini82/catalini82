# Catalin Iliescu

**Systems Engineer and hands-on AI systems builder** — almost 20 years in enterprise
infrastructure and customer-facing solution design, now focused on self-directed
**agentic AI engineering**: multi-agent orchestration, LLMOps, local LLM inference,
model evaluation, and memory/retrieval architecture.

I design and build agentic AI systems end-to-end and contribute upstream to popular
open-source AI projects. My work spans a local/cloud LLM lab on an RTX 4090, a
from-scratch agentic workflow control plane, and durable multi-agent memory systems.

## What I build

- **CMC OS** — a local-first agentic workflow control plane that turns vague goals into
  structured design, Pipeline/Kanban work items, agent + tool execution, and test/audit
  gates, with human escalation only at risk or decision points. Companion Android app in design.
- **Hermes Agent** — a 7-role multi-agent system (generalist, coder, auditor, orchestrator,
  ops, pr-scout, researcher) with a Mixture-of-Agents "LLM council" + judge for high-stakes
  decisions, over durable memory (append-only JSONL + SQLite FTS5 + RRF hybrid retrieval).
- **Odysseus Vault Mode** — a downstream privacy/isolation feature for sensitive AI sessions
  (local-model-only execution, isolated from normal memory/RAG/agentic context), structured
  as an upstream feature proposal.
  
Some systems are private/local-first; public repositories here document architecture, reproducible labs, upstream contributions, and selected safe artifacts.

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
- **Enterprise foundation:** ~20 years infrastructure + customer-facing solution design

## Featured repositories

- [`local-llm-lab`](https://github.com/catalini82/local-llm-lab) — practical local LLM inference, agents, model evaluation, memory/retrieval, and GPU/hardware constraints.
- [`enterprise-ai-architecture-checklists`](https://github.com/catalini82/enterprise-ai-architecture-checklists) — GenAI production-readiness, LLMOps, governance, and adoption checklists.
- [`odysseus`](https://github.com/catalini82/odysseus) — fork used for upstream contribution work and agent-workflow exploration.

## Links

- LinkedIn: https://www.linkedin.com/in/catalin-iliescu-64989755/
- GitHub: https://github.com/catalini82
