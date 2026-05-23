# mcp-code-sandbox

A Model Context Protocol (MCP) server that executes code in isolated Docker
containers. Built to give LLM agents safe, sandboxed code execution across
multiple languages.

**Status:** active development — not yet production-ready.

## Supported Languages (planned for v0.1)

- Python 3.12
- Node.js 20
- Bash
- .NET 8 (stretch)

## Quick Start

_TODO: fill in after Day 6._

## Security Model

See [SECURITY.md](./SECURITY.md). Short version: read-only root filesystem,
no network, dropped Linux capabilities, configurable memory and CPU limits,
hard timeouts with guaranteed cleanup.

## Design Decisions

See [DESIGN.md](./DESIGN.md).

## License

MIT