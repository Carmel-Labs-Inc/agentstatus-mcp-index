# AgentStatus MCP Index

Public remote MCP for the [AgentStatus MCP Index](https://agentstatus.dev/mcp-index).

Endpoint, no key:

```
https://index.mcp.agentstatus.dev/mcp
```

A coding agent attaches that URL. It can search the live public Index, recommend a server for a job, and call that server's tools.

## Cursor

```json
{
  "mcpServers": {
    "agentstatus-index": {
      "url": "https://index.mcp.agentstatus.dev/mcp"
    }
  }
}
```

## Claude Code

```
claude mcp add --transport http agentstatus-index https://index.mcp.agentstatus.dev/mcp
```

## Codex

```toml
[mcp_servers.agentstatus-index]
url = "https://index.mcp.agentstatus.dev/mcp"
```

## License

MIT
