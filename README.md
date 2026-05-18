# Claude Code Tips

A collection of resources for getting started with [Claude Code](https://claude.ai/claude-code), Anthropic's CLI for AI-assisted software development.

## Contents

Two parallel getting-started guides covering the same material — pick the one that matches your machine:

- **[CLAUDE_CODE_GETTING_STARTED.md](CLAUDE_CODE_GETTING_STARTED.md)** — macOS edition. Originally created for an engineering student building prototype websites as a side business.
- **[CLAUDE_CODE_GETTING_STARTED_WINDOWS.md](CLAUDE_CODE_GETTING_STARTED_WINDOWS.md)** — Windows edition. Uses WSL2 (Ubuntu on Windows) as the primary path, with an appendix for native Windows / PowerShell.

## Getting Started Guide Overview

Both guides cover the same 14 sections, adapted for their platform:

1. **Choosing / Setting Up Your Development Machine** — Mac picks hardware; Windows turns on WSL2
2. **Package Manager Setup** — Homebrew (Mac) / WSL2 + `apt` (Windows)
3. **Setting Up Git and GitHub** — Version control basics and SSH configuration
4. **Installing a Better Terminal** — iTerm2 (Mac) / Windows Terminal (Windows)
5. **Installing a Code Editor** — VS Code with essential extensions (plus the WSL extension on Windows)
6. **Installing Claude Code Prerequisites** — Node.js via nvm
7. **Installing Claude Code** — Installation and authentication
8. **Installing Docker** — Container setup for local databases and infrastructure
9. **Creating Your First Project** — Project structure and workflow
10. **Using Claude Code Effectively** — Commands, tips, and prompt strategies
11. **Planning Mode and One-Shot Builds** — Planning workflow, managing multiple builds, and cleanup
12. **Recommended Free Tools** — Markdown editors, code editors, and design tools
13. **Example Prompts to Try** — Starter projects and templates
14. **Working with Your Tech Partner** — GitHub collaboration and handoff

The Windows edition adds a 15th section: a native-Windows (no WSL2) appendix for environments where virtualization isn't an option.

### Key Concepts

- **One-Shot Builds** — Plan thoroughly, then build in a single pass to minimize iteration and API costs
- **CLAUDE.md** — Project memory file that Claude Code reads automatically
- **Beginner Build Workflow** — Use versioned directories (v0.1, v0.2, etc.) for experimentation, then graduate to Git at v1.0

## Download

Both guides are also available as `.pdf`, `.html`, and `.docx` for easy sharing:

- macOS: [.pdf](CLAUDE_CODE_GETTING_STARTED.pdf) · [.html](CLAUDE_CODE_GETTING_STARTED.html) · [.docx](CLAUDE_CODE_GETTING_STARTED.docx)
- Windows: [.pdf](CLAUDE_CODE_GETTING_STARTED_WINDOWS.pdf) · [.html](CLAUDE_CODE_GETTING_STARTED_WINDOWS.html) · [.docx](CLAUDE_CODE_GETTING_STARTED_WINDOWS.docx)

## Contributing

Feel free to open issues or submit pull requests with improvements, corrections, or additional tips.

## License

This work is provided as-is for educational purposes. Feel free to adapt and share.
