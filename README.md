# gs-marketplace

Claude Code plugin marketplace for the GrantSmiths platform.

## Installation

```bash
claude plugin marketplace add https://github.com/nperilla1/gs-marketplace
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **gs-orchestrator** | 13 agents, 38 skills, 7 hooks, 7 commands, 5 MCP servers |

Install any plugin with:
```bash
claude plugin install <plugin-name>
```

## For Team Members

One-time setup:
```bash
claude plugin marketplace add https://github.com/nperilla1/gs-marketplace
claude plugin install gs-orchestrator
```

Then start a new Claude Code session and run `/gs:setup`.
