# Installing the IndiaRestros MCP server

The IndiaRestros MCP server is hosted. Do not clone or build anything.

1. Add this remote server to the MCP settings (Streamable HTTP):

```json
{
  "mcpServers": {
    "indiarestros": {
      "type": "streamableHttp",
      "url": "https://indiarestros.com/mcp"
    }
  }
}
```

2. None for reads: connect and use it. Optional foodie tools (save places, log visits) live at `https://indiarestros.com/mcp/agent` and use OAuth.

3. Test it by asking: "Find a pure-veg South Indian restaurant open now in Indiranagar, Bengaluru, and give me its phone number."
