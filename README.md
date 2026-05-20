# 🚀 Claude Shortcut Hacks & Prompting Toolkit

A comprehensive guide to accelerating your engineering and prompting workflows using Claude's internal commands, advanced session management, and development toolkit. Perfect for AI engineers, researchers, and technical founders.

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
*Contributions, issues, and optimization PRs are welcome. Star this repository to keep these shortcuts at hand.*# Awesome-Claude-Shortcuts
