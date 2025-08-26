# Install this MCP server by adding the following JSON code to your MCP config file
```json
{
    "mcpServers": {
	    "chess-query": {
			"command": "uvx",
			"args": [
				"--from",
				"git+https://github.com/jisaacs85/chess-mcp-server.git",
				"chess"
			]
		}
	}
}
```