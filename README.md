# Yapi MCP Server - Binary Releases

这个仓库用于发布 Yapi MCP Server 的二进制文件。

## 安装

使用 Homebrew 安装：

```bash
brew tap Arthas-cn/homebrew-yapi-mcp-server
brew install yapi-mcp-server
```

## 使用

```bash
yapi-mcp-server --help
```

## Cursor
```json
"YapiMCPServer": {
      "type": "stdio",
      "command": "yapi-mcp-server",
      "args": [
        "stdio",
        "--base-url",
        "https://you.host.cn",
        "--email",
        "youeamil@gmail.com",
        "--password",
        "xxxx"
      ]
    }
```

## Releases

所有二进制文件都在 [Releases](https://github.com/Arthas-cn/yapi-mcp-server-releases/releases) 页面。

## 源代码

源代码在私有仓库中维护。

## License

MIT

