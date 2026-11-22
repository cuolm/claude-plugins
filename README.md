# Claude Plugins
A [plugin marketplace](https://code.claude.com/docs/en/plugins/create-marketplace) for Claude Desktop and
Claude Code: a list of plugins that Claude installs and keeps up to date.

## Quick Start
In Claude Desktop, go to Customize > Plugins > Add > Add marketplace, enter `cuolm/claude-plugins` and add the
plugin you want.

In Claude Code, add the marketplace once, then install a plugin by its name:
```bash
claude plugin marketplace add cuolm/claude-plugins
claude plugin install swiss-weather-mcp@cuolm
```

## Available Plugins
| Plugin | What it adds |
|--------|--------------|
| [`swiss-weather-mcp`](https://github.com/cuolm/swiss-weather-mcp) | Weather forecasts, measurements, snow, the avalanche bulletin and sun and moon times for Switzerland |

Each plugin lives in its own repository, which says what it needs, such as
[uv](https://docs.astral.sh/uv/getting-started/installation/) for `swiss-weather-mcp`.
