---
name: agentstatus-heartbeat-mcp
description: "Use the public Heartbeat API MCP hosted by AgentStatus. No sign-in."
license: MIT
compatibility: Needs the agentstatus MCP server from this package (Streamable HTTP, no sign-in).
metadata:
  homepage: https://heartbeat-mcp.mcp.agentstatus.dev/
---

# Heartbeat API

The server at https://heartbeat-mcp.mcp.agentstatus.dev/ is a public MCP. It does not ask for a key.

1. Read the tool list from that server.
2. Call a tool that the list names, with that tool's arguments.
3. Do not invent a tool name.
