<p align="center">
    <img src="../res/logo/waipoint-logo-aqua.svg" width="20%" alt="Waipoint Logo">
</p>
<h1 align='center' style='border-bottom: none;'>Waipoint</h1>
<h3 align="center">AI Governance Gateway</h3>

---

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


## Get involved

- **Star** [`waipoint/waipoint`](https://github.com/waipoint/waipoint) and try the quickstart.
- **Ask & share** in [Discussions](https://github.com/waipoint/waipoint/discussions).
- **Report issues** on the relevant repo. Security reports: `security@waipoint.io`.

---

<!-- FOOTER START -->
<p align="center">
    <img src="../res/logo/waipoint-logo-aqua.svg" width="5%" alt="Waipoint Logo">
</p>
<p align="center">
    <sub>Copyright © 2025-2026 <a href="https://www.waipoint.io" target="_blank">Waipoint</a>. All Rights Reserved.</sub>
</p>
<!-- FOOTER END -->
