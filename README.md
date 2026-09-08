# Agent Revenue Auditor MCP

Official distribution metadata for the hosted Agent Revenue Auditor MCP server.

- MCP endpoint: `https://agent-revenue-auditor.vandurmedries.workers.dev/mcp`
- Partner page: `https://agent-revenue-auditor.vandurmedries.workers.dev/partners`
- Support: `capi2@agentmail.to`
- Privacy: `https://agent-revenue-auditor.vandurmedries.workers.dev/privacy`
- Terms: `https://agent-revenue-auditor.vandurmedries.workers.dev/terms`

## Install

### One click

- [Install in VS Code](vscode:mcp/install?%7B%22name%22%3A%22agent-revenue-auditor%22%2C%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fagent-revenue-auditor.vandurmedries.workers.dev%2Fmcp%22%7D)
- [Install in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=agent-revenue-auditor&config=eyJhZ2VudC1yZXZlbnVlLWF1ZGl0b3IiOnsidXJsIjoiaHR0cHM6Ly9hZ2VudC1yZXZlbnVlLWF1ZGl0b3IudmFuZHVybWVkcmllcy53b3JrZXJzLmRldi9tY3AifX0=)

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
