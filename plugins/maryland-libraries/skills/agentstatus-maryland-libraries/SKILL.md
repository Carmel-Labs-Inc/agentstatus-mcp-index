---
name: agentstatus-maryland-libraries
description: Use the public Maryland Public Libraries MCP hosted by AgentStatus. No sign-in.
license: MIT
compatibility: Needs the agentstatus MCP server from this package (Streamable HTTP, no sign-in).
metadata:
  homepage: https://maryland-libraries.mcp.agentstatus.dev/
---

# Maryland Public Libraries

The server at https://maryland-libraries.mcp.agentstatus.dev/ is a public MCP. It does not ask for a key.

1. Read the tool list from that server.
2. Call a tool that the list names, with that tool's arguments.
3. Do not invent a tool name.
