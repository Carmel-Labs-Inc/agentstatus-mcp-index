# Install AgentStatus MCP Index

Remote server. Nothing to run locally. No key.

Endpoint:

```
https://index.mcp.agentstatus.dev/mcp
```

## Cline / Claude Code / Cursor

```json
{
  "mcpServers": {
    "agentstatus-index": {
      "url": "https://index.mcp.agentstatus.dev/mcp"
    }
  }
}
```

## Claude Code command

```
claude mcp add --transport http agentstatus-index https://index.mcp.agentstatus.dev/mcp
```
