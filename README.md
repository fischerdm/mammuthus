# mammuthus

Agentic AI for non-life (P&C) insurance pricing.

This project is at an early stage. `mammuthus` is a meta-package that installs
the following components, which share the `mammuthus` namespace:

| PyPI package        | Import as           | Purpose                                                     |
| ------------------- | ------------------- | ----------------------------------------------------------- |
| `mammuthus-tools`   | `mammuthus.tools`   | Building-block utilities used by agents.                    |
| `mammuthus-agents`  | `mammuthus.agents`  | Agentic components built on top of tools.                   |
| `mammuthus-mcp`     | `mammuthus.mcp`     | MCP server exposing mammuthus tools and agents.             |
| `mammuthus-servers` | `mammuthus.servers` | Servers that expose mammuthus tools and agents as services. |

## Installation

```bash
pip install mammuthus
```
