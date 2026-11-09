---
name: agentstatus-rhode-island
description: Use the public Rhode Island DMV MCP hosted by AgentStatus. No sign-in.
license: MIT
compatibility: Needs the agentstatus MCP server from this package (Streamable HTTP, no sign-in).
metadata:
  homepage: https://rhode-island.mcp.agentstatus.dev/
---

# Rhode Island DMV

The server at https://rhode-island.mcp.agentstatus.dev/ is a public MCP. It does not ask for a key.

1. Read the tool list from that server.
2. Call a tool that the list names, with that tool's arguments.
3. Do not invent a tool name.
