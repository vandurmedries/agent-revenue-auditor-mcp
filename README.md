# Agent Revenue Auditor MCP

Official distribution metadata for the hosted Agent Revenue Auditor MCP server.

- MCP endpoint: `https://agent-revenue-auditor.vandurmedries.workers.dev/mcp`
- Partner page: `https://agent-revenue-auditor.vandurmedries.workers.dev/partners`
- Support: `capi2@agentmail.to`
- Privacy: `https://agent-revenue-auditor.vandurmedries.workers.dev/privacy`
- Terms: `https://agent-revenue-auditor.vandurmedries.workers.dev/terms`

## Productized agency pack

The [Agency Prospect Audit Pack](AGENCY-PROSPECT-PACK.md) ranks up to 20 public company websites for visible conversion and technical opportunities, with evidence and a recommended next sales action.

- 5-site pilot: up to $0.40
- 10-site batch: up to $0.80
- 20-site pack: up to $1.60
- Checkout and delivery run through [Apify](https://apify.com/wintry_nutmeg/agent-revenue-auditor)

## Install

### One click

[Open the HTTPS install page](https://agent-revenue-auditor.vandurmedries.workers.dev/partners), then choose **Add to VS Code** or **Add to Cursor**.

VS Code and Cursor will show the server configuration before enabling it. No API key is required for the free discovery tools.

### Universal MCP configuration

Use this Streamable HTTP configuration in a compatible MCP client:

```json
{
  "mcpServers": {
    "agent-revenue-auditor": {
      "url": "https://agent-revenue-auditor.vandurmedries.workers.dev/mcp"
    }
  }
}
```

### Platform-specific files

- VS Code / GitHub Copilot: copy [`examples/vscode-mcp.json`](examples/vscode-mcp.json) to `.vscode/mcp.json` in a workspace.
- Cursor: copy [`examples/cursor-mcp.json`](examples/cursor-mcp.json) to `.cursor/mcp.json` in a workspace.
- Amazon Q Developer: merge [`examples/amazon-q-default.json`](examples/amazon-q-default.json) into `.amazonq/default.json` in a workspace.

For Amazon Q CLI, the same `mcpServers` entry can be imported into an agent configuration. The remote server uses HTTP and does not require OAuth for its free tools.

## Registry

The server is published in the official MCP Registry as [`io.github.vandurmedries/agent-revenue-auditor`](https://registry.modelcontextprotocol.io/v0.1/servers?search=io.github.vandurmedries%2Fagent-revenue-auditor).

## Safety and billing

The public MCP tools provide free website preflight, product discovery and exact purchase instructions. They do not silently execute a paid audit or payment.

The hosted implementation remains in the private product repository. This public repository contains only installation and registry metadata.
