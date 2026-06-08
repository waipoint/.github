<p align="center">
  <img src="../res/logo/waipoint-logo_green.svg" width="96" alt="Waipoint">
</p>
<h1 align="center" style="border-bottom: none;">Waipoint</h1>
<h3 align="center">One gateway in front of every model.</h3>

<p align="center">
  Rust-native, OpenAI-compatible <b>LLM edge gateway</b> you self-host in a single binary.
</p>

<p align="center">
  <a href="https://waipoint.io">Website</a> ·
  <a href="https://docs.waipoint.io">Docs</a> ·
  <a href="https://github.com/waipoint/waipoint">Gateway</a>
</p>

---

Waipoint sits between your apps and every model provider, so client code targets
**one stable, OpenAI-compatible API** while routing, credentials, spend, and
rate limits are enforced at the edge — declared once, not rebuilt per service.

```bash
cargo install waipoint        # or: docker run waipoint/waipoint
```

- **Config-first routing** — routes, models, and fallbacks in a version-controlled `waipoint.toml`.
- **Virtual keys** — scoped, revocable credentials; provider keys never leave your perimeter.
- **Budgets** — hard USD ceilings per route and per key. Spend stops at the limit.
- **Rate limits** — RPM and TPM enforced at the edge.
- **Streaming & fallbacks** — first-class SSE with ordered provider failover, no redeploy.
- **Low operational surface** — one ~12 MB static binary. No control plane, mesh, or database.

## The ecosystem

| | |
| --- | --- |
| **Gateway & core** | [`waipoint`](https://github.com/waipoint/waipoint) (the gateway) · [`waipoint-scout`](https://github.com/waipoint/waipoint-scout) · [`waipoint-cli`](https://github.com/waipoint/waipoint-cli) |
| **SDKs** | [`-py`](https://github.com/waipoint/waipoint-sdk-py) · [`-ts`](https://github.com/waipoint/waipoint-sdk-ts) · [`-go`](https://github.com/waipoint/waipoint-sdk-go) · [`-rust`](https://github.com/waipoint/waipoint-sdk-rust) · [`-java`](https://github.com/waipoint/waipoint-sdk-java) |
| **Integrate** | [`waipoint-mcp`](https://github.com/waipoint/waipoint-mcp) (MCP server) · [`waipoint-chatbox`](https://github.com/waipoint/waipoint-chatbox) · [`waipoint-action`](https://github.com/waipoint/waipoint-action) |
| **Deploy** | [`waipoint-compose`](https://github.com/waipoint/waipoint-compose) · [`waipoint-helm`](https://github.com/waipoint/waipoint-helm) · [`waipoint-terraform`](https://github.com/waipoint/waipoint-terraform) · [`waipoint-homebrew`](https://github.com/waipoint/waipoint-homebrew) |
| **Govern** | [`waipoint-guardrails`](https://github.com/waipoint/waipoint-guardrails) · [`waipoint-compliance`](https://github.com/waipoint/waipoint-compliance) · [`waipoint-observatory`](https://github.com/waipoint/waipoint-observatory) |
| **Docs & design** | [`waipoint-docs`](https://github.com/waipoint/waipoint-docs) · [`stylescape-waipoint`](https://github.com/waipoint/stylescape-waipoint) · [`site-waipoint_io`](https://github.com/waipoint/site-waipoint_io) |

## Get involved

- ⭐ **Star** [`waipoint/waipoint`](https://github.com/waipoint/waipoint) and try the quickstart.
- 💬 **Ask & share** in [Discussions](https://github.com/waipoint/waipoint/discussions).
- 🐛 **Report issues** on the relevant repo. Security reports: `security@waipoint.io`.

<p align="center"><sub>Apache-2.0 · self-host anywhere · built in Rust 🦀 · <a href="https://waipoint.io">waipoint.io</a></sub></p>
