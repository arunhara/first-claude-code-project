# first-claude-code-project

A starter project for exploring [Claude Code](https://claude.ai/code) — Anthropic's AI-powered CLI for software engineering tasks.

## What is Claude Code?

Claude Code is an agentic coding tool that lives in your terminal. It understands your codebase, edits files, runs tests, manages git, and handles multi-step engineering tasks through natural language.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) 18+
- A Claude account at [claude.ai](https://claude.ai)

### Installation

```bash
npm install -g @anthropic-ai/claude-code
```

### Running Claude Code

```bash
# Launch in the current directory
claude

# Ask Claude to do something right away
claude "explain this codebase"
```

## Project Structure

```
first-claude_code-project/
├── README.md       # This file
└── .git/           # Git repository metadata
```

## Useful Claude Code Commands

| Command | Description |
|---|---|
| `/help` | Show available commands |
| `/clear` | Clear conversation context |
| `/review` | Review current branch changes |
| `/init` | Generate a CLAUDE.md for your project |
| `!<cmd>` | Run a shell command inline (e.g. `! git status`) |

## Tips

- Claude Code reads your entire project before responding — no need to paste code manually.
- Use `CLAUDE.md` in the root to give Claude persistent instructions about your project conventions.
- Prefix any shell command with `!` to run it and pipe the output directly into the conversation.

## Resources

- [Claude Code Docs](https://docs.anthropic.com/en/docs/claude-code)
- [Anthropic API](https://docs.anthropic.com)
- [GitHub Issues](https://github.com/anthropics/claude-code/issues)

## License

MIT
