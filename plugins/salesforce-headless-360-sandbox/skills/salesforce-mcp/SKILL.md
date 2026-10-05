---
name: salesforce-mcp
description: Use when the user asks to work with Salesforce through the connected Salesforce Hosted MCP Server.
---

# Salesforce Hosted MCP

Use the connected Salesforce Hosted MCP server through the configured local mcp-remote bridge.

Authentication is handled by mcp-remote against the Salesforce Hosted MCP endpoint. Supply the OAuth client ID and secret through runtime environment variables named SALESFORCE_CLIENT_ID and SALESFORCE_CLIENT_SECRET.

Never request or expose the client secret in chat. Preserve Salesforce permissions and do not guess credentials, scopes, or endpoints.