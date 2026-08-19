# Instalação detalhada

DETRAN MS Guia Flex: Licenciamentos é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_detran_ms_licenciamentos_flex`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_detran_ms_licenciamentos_flex` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_detran_ms_licenciamentos_flex` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_detran_ms_licenciamentos_flex` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.detran_ms_licenciamentos_flex` (ou `servers.detran_ms_licenciamentos_flex` no VS Code) do config do cliente e reinicie.
