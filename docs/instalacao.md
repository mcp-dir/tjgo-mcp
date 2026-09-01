# Instalação detalhada

Jurisprudência TJGO é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tjgo`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tjgo` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_tjgo` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_tjgo` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tjgo` (ou `servers.tjgo` no VS Code) do config do cliente e reinicie.
