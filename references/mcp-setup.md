# Obsidian MCP 配置指南

本技能通过 Obsidian MCP 与你的知识库交互。社区有两种主流方案，可根据需求选择。

## 方案一：直接文件系统访问（推荐）

- 通过 `npx obsidian-mcp` 直接读写 Vault 文件夹
- **零依赖**：不需要在 Obsidian 里装任何插件
- **不需要打开 Obsidian**：AI 直接读写硬盘上的 `.md` 文件

## 方案二：REST API 插件访问

- 需要先在 Obsidian 里安装 **Local REST API** 插件
- 需要配置 API Key
- MCP 服务器通过 HTTP 请求与 Obsidian 通信