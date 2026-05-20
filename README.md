# 🚀 Claude Shortcut Hacks & Prompting Toolkit

<div align="center">
  <p><strong>A comprehensive guide to accelerating your engineering and prompting workflows using Claude Code, internal commands, and advanced session management.</strong></p>

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  [![GitHub stars](https://img.shields.io/github/stars/ishan/Awesome-Claude-Shortcuts.svg?style=social&label=Star)](https://github.com/ishan/Awesome-Claude-Shortcuts)
</div>

---

## 📖 Table of Contents
- [Overview](#-overview)
- [⚡ 26 Claude Shortcut Hacks](#-26-claude-shortcut-hacks-for-faster-prompts)
- [📚 Exclusive Engineering Prompt Library](#-exclusive-engineering-prompt-library)
- [🛠️ How to Access the Library](#️-how-to-access-the-library)
- [🤝 Contributing](#-contributing)
- [⚖️ License](#️-license)

---

## 🌟 Overview

Welcome to the ultimate resource for **Claude Code** and **Prompt Engineering**. This repository is designed for AI engineers, researchers, and technical founders who want to master the Claude CLI and maximize their productivity with **Claude 3.5 Sonnet** and other Anthropic models.

Whether you're looking for internal commands, **Model Context Protocol (MCP)** configurations, or advanced state management, this toolkit has you covered.

---

## ⚡ 26 Claude Shortcut Hacks for Faster Prompts
*Maximize efficiency by dropping one of these commands at the very start of your prompt to control session context, state management, and the execution environment.*

| Command | Arguments | Primary Use Case & Functionality |
| :--- | :--- | :--- |
| `/CLEAR` | — | Clears conversation history and resets state context completely. |
| `/COST` | — | Displays token consumption metrics and execution billing for the active session. |
| `/COMPACT` | `[instructions]` | Compresses the current conversation history while retaining specified focal context. |
| `/RESUME` | `[session]` | Reopens a historical conversation thread via Session ID or alphanumeric name. |
| `/BRANCH` | `[name]` | Forks the current conversation thread into a standalone, parallel branch. |
| `/REWIND` | — | Rolls back conversation states, code generations, or tool executions to a prior checkpoint. |
| `/RENAME` | `[name]` | Renames the active session. Auto-generates a descriptive title if left blank. |
| `/EXPORT` | `[filename]` | Serializes and exports the entire conversation thread as plain text. |
| `/MODEL` | `[model]` | Hot-swaps the underlying LLM engine (e.g., *Sonnet*, *Opus*, *Haiku*) mid-session. |
| `/USAGE` | — | Retrieves operational plan consumption limits and active API rate-limit statuses. |
| `/EXTRA-USAGE`| — | Programmatically opts into supplementary compute/usage tiers when standard caps are met. |
| `/INIT` | — | Bootstraps the workspace/repository context with a dedicated `CLAUDE.md` engineering guide. |
| `/MEMORY` | — | Modifies workspace-specific `CLAUDE.md` memory targets and toggles auto-context learning. |
| `/ADD-DIR` | `<path>` | Mounts and indexes an external working directory for direct session file system access. |
| `/DIFF` | — | Launches an interactive diff viewer tracking local uncommitted file system changes and per-turn outputs. |
| `/SECURITY-REVIEW`| — | Scans pending code modifications and generated outputs for potential security vulnerabilities. |
| `/PLAN` | `[description]`| Enters agentic **Plan Mode**, setting explicit behavioral objectives before code generation. |
| `/PERMISSIONS`| — | Grants, revokes, or configures the interactivity rules (`allow`/`ask`/`deny`) for runtime tool execution. |
| `/AGENTS` | — | Orchestrates sub-agent configurations, behavioral policies, and parallel task distribution. |
| `/SKILLS` | — | Enumerates all core architectural capabilities, covering both native primitives and custom hooks. |
| `/PLUGIN` | — | Serves as the package manager for Claude Code native extensions and execution plugins. |
| `/RELOAD-PLUGINS`| — | Refreshes and re-registers active plugins hot-swappably without restarting the daemon. |
| `/MCP` | — | Configures Model Context Protocol (MCP) servers, endpoint configurations, and OAuth sequences. |
| `/CONFIG` | — | Accesses the configuration matrix to customize system themes, model variations, and default formatting styles. |
| `/THEME` | — | Toggles visual style sheets including `light`, `dark`, and high-contrast accessible layouts. |
| `/COLOR` | `[color]` | Changes the accent color of the session's prompt interface for clear environmental boundaries. |

---

## 📚 Exclusive Engineering Prompt Library

After months of rigorous production testing and evaluation, a centralized Prompt Library has been developed containing optimized engineering prompts, architectural blueprints, and agentic wrappers.

### 🛠️ How to Access the Library
Follow these four sequential steps to unlock the repository assets and video deep-dives:

1. **Subscribe (Free):** Head over to [how-to-ai.guide](https://how-to-ai.guide) and sign up.
2. **Verify Inbox:** Open the incoming confirmation and welcome email.
3. **Trigger Access:** Click the internal **Automatic Reply** handler embedded within the email message body.
4. **Deploy Assets:** Instantly receive your fully decoupled prompt engineering library along with a bonus operational walkthrough video.

---

## 🤝 Contributing
Contributions, issues, and optimization PRs are welcome! Feel free to:
1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## ⚖️ License
Distributed under the MIT License. See `LICENSE` for more information.

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ishandutta2007/Awesome-Claude-Shortcuts&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Claude-Shortcuts&type=date&legend=top-left)

---

<div align="center">
  <em>Star this repository to keep these shortcuts at hand!</em>
</div>
