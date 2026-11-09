---
name: agentstatus-oregon-libraries
description: Use the public Oregon Public Libraries MCP hosted by AgentStatus. No sign-in.
license: MIT
compatibility: Needs the agentstatus MCP server from this package (Streamable HTTP, no sign-in).
metadata:
  homepage: https://oregon-libraries.mcp.agentstatus.dev/
---

# Oregon Public Libraries

The server at https://oregon-libraries.mcp.agentstatus.dev/ is a public MCP. It does not ask for a key.

1. Read the tool list from that server.
2. Call a tool that the list names, with that tool's arguments.
3. Do not invent a tool name.
