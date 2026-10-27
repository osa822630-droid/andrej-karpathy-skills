# Karpathy Guidelines

A single skill that applies four rules from Andrej Karpathy's observations about LLM coding mistakes: Think Before Coding, Simplicity First, Surgical Changes, and Goal-Driven Execution. It works in chat on claude.ai, in Cowork, and in Claude Code.

## Use it

Add the plugin from a marketplace (see the repository README), then ask Claude to write, review, or refactor code. Claude loads the `karpathy-guidelines` skill when it fits the task, and you can also pick it from the `+` menu or type `/` in a chat. For a one-off conversation, paste `CLAUDE.md` from the repository root into your project instructions instead.

In Claude Code, one command installs it from the marketplace:

```
/plugin install andrej-karpathy-skills --marketplace osa822630-droid/andrej-karpathy-skills
```

On claude.ai, use **Customize → Plugins → Add → Add marketplace → Add from a repository** with `osa822630-droid/andrej-karpathy-skills`, then add **Karpathy Guidelines** from **Discover**.

## Data

The plugin is Markdown instructions only. It contains no connectors, scripts, hooks, or executables, makes no network requests, and sends no data anywhere.
