# Hey, I'm Wesley 👋

Self-taught, with a BA in CS and data analytics in there somewhere. I mess around with computers and markets, and the stuff that survives ends up here.

## 🔌 Agent infrastructure & security

- **[claude-custom-connector-server](https://github.com/wnkinc/claude-custom-connector-server)** — secure MCP server framework for the Claude apps: Cloudflare Tunnel ingress, Google OAuth per tool, egress allowlists, an LLM-output guardrail sidecar, and out-of-band approvals. Runs on your own Linux box, or provisions its own EC2 VM with Pulumi.
- **[beta-tools](https://github.com/wnkinc/beta-tools)** — the incubator overlay for that stack: X API surface, crypto market-data lake (OpenBB), self-hosted Lean backtesting.

## 🧬 Applied ML & data

- **[Hull Tactical Market Prediction](https://www.kaggle.com/competitions/hull-tactical-market-prediction)** — **19th of 3,677 teams (top 0.5%)** in a nine-month featured Kaggle competition run by a quantitative asset manager: forecasting excess S&P 500 returns under volatility constraints, scored on a modified Sharpe ratio. tsfresh-generated features selected against purpose-built time-series folds; blended LightGBM + AutoGluon ensembles tuned to the constrained objective rather than raw return. → [my Kaggle](https://www.kaggle.com/wesleyklaassen)
- **[Bio-RAG](https://github.com/wnkinc/Bio-RAG)** — biomedical question-answering RAG on AWS: Chainlit + LangChain app, GPU semantic reranker, OpenSearch hybrid retrieval, Pulumi infra. Implements Stuhlmann et al. (2025).
- **[delta-bridge](https://github.com/wnkinc/delta-bridge)** — data-sharing service built on Delta Sharing: upload a CSV, serve it as a live Delta table, consume it from any notebook.

## 🎓 Roots

- **[the-odin-project](https://github.com/wnkinc/the-odin-project)** — the full-stack JavaScript path, end to end: 46 projects in one repo, from a first HTML page to a deployed full-stack blog.
