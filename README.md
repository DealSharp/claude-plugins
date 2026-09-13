# DealSharp plugins for Claude

Separate production and development plugins connect Claude to your DealSharp account through hosted MCP endpoints.

| Plugin | Account | Custom MCP URL |
|---|---|---|
| [DealSharp](plugins/dealsharp) | Production | https://app.dealsharp.ai/mcp |
| [DealSharp Dev](plugins/dealsharp-dev) | Development | https://dev.dealsharp.ai/mcp |

Each plugin contains a connection configuration and short workflow instructions. Neither package contains the DealSharp backend, credentials, or customer information.

Development and production require separate sign-ins. Use the production plugin for client work. The development plugin is for users who have a DealSharp development account.

Directory review and publishing status will be documented here after submission. A directory listing is not required to add a custom MCP connector.
