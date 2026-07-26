# Hey, I'm Wesley 👋

I build infrastructure for AI agents — self-hosted MCP servers with a real security posture: OAuth on every tool, default-deny egress, output screening, and human-in-the-loop approval gates.

## 🔌 Agent infrastructure

- **[claude-custom-connector-server](https://github.com/wnkinc/claude-custom-connector-server)** — secure MCP server framework for the Claude apps: Cloudflare Tunnel ingress, Google OAuth per tool, egress allowlists, an LLM-output guardrail sidecar, and out-of-band approvals. Runs on your own Linux box, or provisions its own EC2 VM with Pulumi.
- **[beta-tools](https://github.com/wnkinc/beta-tools)** — the incubator overlay for that stack: X API surface, crypto market-data lake (OpenBB), self-hosted Lean backtesting.

## 🧬 Applied ML & data

- **[Bio-RAG](https://github.com/wnkinc/Bio-RAG)** — biomedical question-answering RAG on AWS: Chainlit + LangChain app, GPU semantic reranker, OpenSearch hybrid retrieval, Pulumi infra. Implements Stuhlmann et al. (2025).
- **[delta-bridge](https://github.com/wnkinc/delta-bridge)** — data-sharing service built on Delta Sharing: upload a CSV, serve it as a live Delta table, consume it from any notebook.

## 🎓 Roots

- **[the-odin-project](https://github.com/wnkinc/the-odin-project)** — the full-stack JavaScript path, end to end: 46 projects in one repo, from a first HTML page to a deployed full-stack blog.
