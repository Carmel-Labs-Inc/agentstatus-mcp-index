---
name: agentstatus-us-ev-chargers
description: Use the public US Public EV Chargers MCP hosted by AgentStatus. No sign-in.
license: MIT
compatibility: Needs the agentstatus MCP server from this package (Streamable HTTP, no sign-in).
metadata:
  homepage: https://us-ev-chargers.mcp.agentstatus.dev/
---

# US Public EV Chargers

The server at https://us-ev-chargers.mcp.agentstatus.dev/ is a public MCP. It does not ask for a key.

1. Read the tool list from that server.
2. Call a tool that the list names, with that tool's arguments.
3. Do not invent a tool name.
