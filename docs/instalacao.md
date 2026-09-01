# Instalação detalhada

Jurisprudência TJMS é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tjms`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tjms` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_tjms` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_tjms` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tjms` (ou `servers.tjms` no VS Code) do config do cliente e reinicie.
