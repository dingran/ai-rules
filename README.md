# ai-rules

Project rules for AI coding agents/tools.

## Files

- [`CLAUDE.md`](https://github.com/dingran/ai-rules/blob/main/CLAUDE.md) - Instructions and conventions for Claude

## Usage

This is how I typically use this repo, for example CLAUDE.md:

```
> can you create docs based on ~/projects/ai-rules/CLAUDE.md

  keep it simple

⏺ Read(../ai-rules/CLAUDE.md)…
  ⎿  Read 451 lines (ctrl+r to expand)

⏺ I'll create a simple documentation structure based on the AI rules provided. Let me first check if a docs directory exists:

⏺ Bash(ls -la docs/)…
  ⎿  Error: ls: docs/: No such file or directory

⏺ Now I'll create the docs directory and the required documentation files:

⏺ Call(Create docs directory and initial files)…
  ⎿  Bash(mkdir docs)…
  ⎿  Done (1 tool use · 3.4s)

⏺ Update Todos
  ⎿ ☐ Create CLAUDE.md in project root
     ☐ Create docs/TODO.md
     ☐ Create docs/[date]_product_requirements.md
     ☐ Update CLAUDE.md documentation index
     ☐ Update README.md with AI rules reference
```

## Best Practices

- [Claude Code Best Practices](https://www.anthropic.com/engineering/claude-code-best-practices)
- [Using LLMs for Code](https://simonwillison.net/2025/Mar/11/using-llms-for-code/)
