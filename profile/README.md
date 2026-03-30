## AI image generation, right in your terminal.

Add to your Claude Code MCP config:

```json
{
  "mcpServers": {
    "xbrush": {
      "command": "npx",
      "args": ["-y", "@lweight/xbrush-api-mcp"],
      "env": { "XBRUSH_API_KEY": "your-key" }
    }
  }
}
```

Get your API key at [xbrush.run](https://xbrush.run), then just ask: *"Generate a pixel art character wearing a red hat"*

### Our MCP Servers

**[xbrush-api-mcp](https://github.com/lweight/xbrush-api-mcp)** — AI image generation, editing, upscaling, background removal — 10+ models through one API
[![npm](https://img.shields.io/npm/v/@lweight/xbrush-api-mcp)](https://www.npmjs.com/package/@lweight/xbrush-api-mcp)

```bash
claude mcp add xbrush -- npx -y @lweight/xbrush-api-mcp
```

**[inblog-mcp](https://github.com/lweight/inblog-mcp)** — Blog post CRUD, tag management, and publishing for inblog.ai
[![npm](https://img.shields.io/npm/v/@lweight/inblog-mcp)](https://www.npmjs.com/package/@lweight/inblog-mcp)

```bash
claude mcp add inblog -- npx -y @lweight/inblog-mcp
```

MIT · TypeScript · zero-install via `npx`

Built by [Lightweight](https://lightweight.kr) · API keys at [xbrush.run](https://xbrush.run)
