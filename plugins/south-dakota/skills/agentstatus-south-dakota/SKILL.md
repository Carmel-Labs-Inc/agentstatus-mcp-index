---
name: agentstatus-south-dakota
description: Use the public South Dakota DMV MCP hosted by AgentStatus. No sign-in.
license: MIT
compatibility: Needs the agentstatus MCP server from this package (Streamable HTTP, no sign-in).
metadata:
  homepage: https://south-dakota.mcp.agentstatus.dev/
---

# South Dakota DMV

The server at https://south-dakota.mcp.agentstatus.dev/ is a public MCP. It does not ask for a key.

1. Read the tool list from that server.
2. Call a tool that the list names, with that tool's arguments.
3. Do not invent a tool name.
