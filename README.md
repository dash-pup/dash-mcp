# Dash MCP Server

Dash is an AI teammate you can text or email, with no Slack or Teams needed. Dash's hosted Model Context Protocol server connects compatible AI clients to a Dash workspace: asking Dash to do work, skills, scheduled tasks, goals, connected apps, team members, and workspace settings.

This repository contains the public discovery metadata for the hosted server. It does not contain the server implementation.

## Connect

Use this remote server URL in an MCP client:

```text
https://api.dashpup.ai/mcp/platform
```

The server uses Streamable HTTP. Compatible clients can use the interactive sign-in flow with a normal Dash login. Dash API keys can also be supplied as bearer tokens where the client supports custom authentication.

See the [Dash MCP Server guide](https://dashpup.ai/help/use-dash-as-an-mcp-server/) for setup instructions.

## Capabilities and access

The server exposes Dash operations as MCP tools. Depending on the connected user's role, these tools can help an AI client:

- Ask Dash to do work and wait for the answer
- Create, install, and manage skills and scheduled tasks
- Save and track goals
- Connect apps and list their tools
- Manage team members, phone links, and workspace settings
- Review usage and billing details

Access remains subject to the user's Dash workspace role. MCP access is available on paid Dash workspaces.

## Registry metadata

[`server.json`](server.json) is published in the [Official MCP Registry](https://modelcontextprotocol.io/registry/about) as `io.github.dash-pup/dash-mcp` version `1.0.0`.

- [Official Registry API record, v0.1](https://registry.modelcontextprotocol.io/v0.1/servers?search=io.github.dash-pup%2Fdash-mcp)
- [Official Registry API record, v0](https://registry.modelcontextprotocol.io/v0/servers?search=io.github.dash-pup%2Fdash-mcp)

Published Registry versions are immutable. Any metadata correction must use a new unique version.

## Resources

- [MCP Server documentation](https://dashpup.ai/help/use-dash-as-an-mcp-server/)
- [Dash Help Center](https://dashpup.ai/help/)
- [Security](https://dashpup.ai/security/)
- [Privacy policy](https://dashpup.ai/legal/privacy/)
- [Terms of service](https://dashpup.ai/legal/terms/)
- [Contact Dash](https://dashpup.ai/contact/)

## Repository scope

Issues and pull requests in this repository should concern public discovery metadata or its documentation. Product support and security matters should use the official resources above.
