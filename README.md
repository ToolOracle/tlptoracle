# 🎯 tlptOracle

**DORA Execution MCP Server** — 10 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-10-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)
![Bus](https://img.shields.io/badge/Oracle_Bus-Connected-00C853?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/tlpt/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "tlptoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/tlpt/mcp/"]
    }
  }
}
```

## Tools (10)

| Tool | Description |
|------|-------------|
| `register_exercise` | Register a TLPT/pentest exercise. |
| `phase_tracker` | Track TIBER-EU 8-phase lifecycle. |
| `threat_profile` | Define threat landscape for TLPT scoping. |
| `team_assignment` | Manage Red/Blue/White/Purple team assignments. |
| `finding_register` | Log a pentest/TLPT finding. |
| `remediation_plan` | Track remediation of TLPT findings. Set add=true to create. |
| `evidence_bundle` | Compile TLPT evidence for authority attestation. |
| `test_calendar` | Annual testing schedule and compliance check. |
| `tlpt_readiness` | Assess organizational readiness for a TLPT exercise. |
| `health_check` | Server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

tlptOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/tlpt/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
