# Claude Harness Marketplace

Marketplace catalog for the [Claude Harness](https://github.com/panayiotism/claude-harness) plugin.

## Installation

```bash
# 1. Register this marketplace
claude plugin marketplace add panayiotism/claude-harness-marketplace

# 2. Install the plugin
claude plugin install claude-harness@claude-harness

# 3. Initialize in your project
/claude-harness:setup
```

## Updating

```bash
claude plugin update claude-harness
```

## Troubleshooting

If updates are not being picked up:

```bash
claude plugin uninstall claude-harness
claude plugin install claude-harness@claude-harness
```
