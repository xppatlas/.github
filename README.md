# XppAtlas

**Status:** internal / private pilot — sales paused, engineering hardening in progress.

**Your AI coding agent, finally fluent in your X++.**

XppAtlas is an on-prem knowledge platform and MCP server that indexes the
Microsoft Dynamics 365 Finance & Operations X++ models you select in
`xppatlas.toml` — standard, ISV, and custom — and serves them to AI agents
(Claude Code, GitHub Copilot, any MCP client). Run it on a D365 devbox or
against local model copies. **Your code never leaves your network.**

General code tools see XML blobs. XppAtlas understands D365 — tables, forms, data
entities, security, Chain-of-Command extensions, and how they reference each
other — so your agent verifies symbols and grounds its answers instead of guessing.

### Platform
**[`xppatlas`](https://github.com/xppatlas/xppatlas)** — the core: indexer, hybrid retrieval, MCP server, intelligence layers. Private during the pilot; any open-core / public release is **deferred**.

### Get started (internal pilot)
**[`xppatlas-template`](https://github.com/xppatlas/xppatlas-template)** — starter repo with quickstarts, `xppatlas.toml` examples, and stdio MCP config. Install on a devbox or against local model copies, index the models you select, query over MCP.

### Learn more
🌐 [xppatlas.com](https://xppatlas.com) · ✉️ hello@xppatlas.com
