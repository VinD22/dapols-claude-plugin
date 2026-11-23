# Dapols plugin for Claude

[Dapols](https://www.dapols.com) helps small businesses use AI: an AI plan for your kind of business, a website, and a Design Library of 60+ web designs, each made from one AI prompt.

This plugin connects Claude Code to Dapols' two MCP servers:

| Server | URL | Sign-in | What it does |
|---|---|---|---|
| `dapols` | `https://www.dapols.com/api/mcp` | None | Browse the Design Library, look up AI tools with dated prices, compare models, list plans and prompts. Read-only. |
| `dapols-business` | `https://www.dapols.com/api/mcp/me` | Your Dapols account (OAuth) | Read your plan, tasks, documents and updates; get Design Library prompts (included with every plan); save notes and drafts. Nothing is sent, posted or published. |

It also adds three skills: `/dapols:design-library`, `/dapols:run-my-business` and `/dapols:choose-ai-tools`.

## Install

```
/plugin marketplace add VinD22/dapols-claude-plugin
/plugin install dapols@dapols
```

The first time a `dapols-business` tool runs, Claude opens a browser so you can sign in to Dapols and approve access. You can revoke it any time from your Dapols dashboard under Connect.

Using Claude on the web or desktop instead? The public connector is in the [Claude directory](https://claude.ai/directory/connectors/dapols): add it from there in one click. Or add `https://www.dapols.com/api/mcp` (and `https://www.dapols.com/api/mcp/me` for your account) as custom connectors. See [Connect your AI](https://www.dapols.com/connect-your-ai).

## Privacy and support

- Privacy policy: https://www.dapols.com/privacy-policy
- Terms: https://www.dapols.com/terms-of-service
- Support: https://www.dapols.com/contact

## License

MIT
