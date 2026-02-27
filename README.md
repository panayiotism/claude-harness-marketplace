# Claude Harness Marketplace

Marketplace catalog for the [Claude Harness](https://github.com/panayiotism/claude-harness) plugin.

## Installation

```bash
# 1. Register this marketplace
claude plugin marketplace add panayiotism/claude-harness-marketplace

# 2. Install the plugin
claude plugin install claude-harness@claude-harness

# 3. Initialize in your project
cd your-project && claude
/claude-harness:setup
```

## Updating

```bash
# Refresh the marketplace cache, then update the plugin
claude plugin marketplace update claude-harness
claude plugin update claude-harness@claude-harness
```

Both steps are required — `plugin update` checks a local cache that doesn't auto-refresh.

> **Important**: The full `claude-harness@claude-harness` identifier is required.
> `claude plugin update claude-harness` (without `@claude-harness`) will fail with "not found".

## Troubleshooting

### Plugin update says "already at latest" but a newer version exists

Claude Code caches marketplace data locally. Force-refresh it first:

```bash
claude plugin marketplace update claude-harness
claude plugin update claude-harness@claude-harness
```

### Clean reinstall

```bash
claude plugin uninstall claude-harness@claude-harness
claude plugin marketplace update claude-harness
claude plugin install claude-harness@claude-harness
```
