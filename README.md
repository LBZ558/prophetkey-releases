# ProphetKey — API Key Vault for AI Agents

Offline-first, encrypted API key vault with local MCP bridge for AI agents.

## What is ProphetKey?

ProphetKey is a desktop app that securely stores API keys (OpenAI, Anthropic, GitHub, etc.) and exposes a **local MCP server** (`127.0.0.1:1421/mcp`). AI agents can call 5 tools over stdio or HTTP to read keys, check health, and make API calls — **real keys never reach the agent**.

## Quick start (stdio via npm)

Install and configure in one step — works with Claude Code, Cursor, Windsurf, and any MCP-compatible agent.

```bash
# One-liner to run
npx -y prophetkey-mcp
