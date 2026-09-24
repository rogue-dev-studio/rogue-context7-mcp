# rogue-context7-mcp

**Rogue Development** MCP package for agents.

Rogue Context7 MCP - remote library docs lookup for agents

- Asset Store: https://rogue-dev-studio.github.io/rogue-asset-store/

## Requirements

- MCP host with remote HTTP MCP support
- Network access to Context7

## Install (Cursor)

Copy `cursor.mcp.fragment.json` into your Cursor MCP config, or merge:

```json
{
  "mcpServers": {
    "context7": {
      "url": "https://mcp.context7.com/mcp"
    }
  }
}
```

Then restart Cursor.

## License

MIT - Rogue Development. See `LICENSE` and `NOTICE`.
