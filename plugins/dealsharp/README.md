# DealSharp for Claude

Connect your DealSharp production account to Claude. This package contains a hosted MCP connection and workflow instructions.

In Claude Desktop, open Customize → Plugins and install this plugin. Follow the DealSharp sign-in prompt to connect your production account. You can also add `https://app.dealsharp.ai/mcp` through Customize → Connectors → Add custom connector.

Ask Claude to list your projects, inspect document information or a negotiation matrix, start a strategy chat, prepare an Open Item Tracker, or prepare an avatar practice conversation. Your usual DealSharp access and organization document-sharing policy apply. Development and production accounts are separate.

The server runs on DealSharp infrastructure. This package launches no local server and contains no credentials. It does not grant access until you sign in. Removing the connector disconnects Claude; revoke access through DealSharp when needed.

Privacy: https://www.dealsharp.ai/privacy
Support: ekjosbakken@dealsharp.ai

The connector can read and change data in response to your requests. Claude's tool approvals and DealSharp's access controls still apply. See the server's current tool descriptions for available operations.
