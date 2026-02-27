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
claude plugin update claude-harness@claude-harness
```

> **Note**: The full `claude-harness@claude-harness` identifier is required.

## Troubleshooting

### Plugin update not detected

Force-refresh the marketplace cache, then update:

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
