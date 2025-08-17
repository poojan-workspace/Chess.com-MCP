# Chess.com MCP Package Hosted on GitHub


Install the Chess.com MCP by simpling adding the following JSON code to you MCP JSON Config File:

```json
{
  "mcpServers": {
    "weather": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/poojan-workspace/Chess.com-MCP.git",
        "chess"
      ]
    },
  }  
}
```