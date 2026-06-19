# posthog-analytics-pro

Manage resources using posthog natively from your AI agent.

## Requirements

- **License key** — purchase from [MCP Marketplace](https://mcpmarketplace.com) to get your `MCP_LICENSE_KEY`
- Node.js 18+

## Installation

```json
{
  "mcpServers": {
    "posthog-analytics-pro": {
      "command": "npx",
      "args": [
        "-y",
        "posthog-analytics-pro"
      ],
      "env": {
        "MCP_LICENSE_KEY": "your-license-key-here"
      }
    }
  }
}
```

## Tools

| Tool | Description |
|------|-------------|
| `manage` | Run arbitrary commands using the posthog CLI. |

## Development

```bash
npm install
npm run build
npm test
```
