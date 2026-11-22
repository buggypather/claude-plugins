# buggypather's Claude Code plugins

One place to install all of buggypather's [Claude Code](https://claude.com/claude-code) plugins.
Windows (first), Mac and Linux. MIT licence. Suggestions, issues and pull requests are welcome on
each plugin's own repo.

| Plugin | What it does |
| --- | --- |
| [save-me-claude](https://github.com/buggypather/save-me-claude) | Saves every conversation, your requests and every command or file change Claude makes, to dated folders on your computer. |
| [notify-me-claude](https://github.com/buggypather/notify-me-claude) | Desktop notifications when Claude starts working, needs your permission, replies while still working, or finishes. |
| [crash-me-claude](https://github.com/buggypather/crash-me-claude) | Collects Claude Code and IDE-extension crash and error reports on your computer, redacted, ready to save or send. |

## Install

Add this marketplace once, then install whichever plugins you want. In a terminal:

```sh
claude plugin marketplace add buggypather/claude-plugins
claude plugin install save-me-claude@buggypather
claude plugin install notify-me-claude@buggypather
claude plugin install crash-me-claude@buggypather
```

Or inside Claude Code, type `/plugin marketplace add buggypather/claude-plugins`, then `/plugin`
to browse and install. (In the VS Code extension, use the terminal commands above.)

Restart Claude Code after installing. To get updates: `claude plugin marketplace update buggypather`.
To remove one: `claude plugin uninstall save-me-claude@buggypather`.

## Also by buggypather

- [view-me-claude](https://github.com/buggypather/view-me-claude): a VS Code panel beside Claude Code
  showing your phones, running agents and builds, plan usage and the servers your agents started.
- Everything else open-source: [open-buggy](https://github.com/buggypather/open-buggy).

## Adding a plugin here

Add an entry to `.claude-plugin/marketplace.json` pointing at the plugin's repo, then check it:

```sh
claude plugin validate .
```
