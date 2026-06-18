# Portfolio Project: Cursor Setup and Environment Initialization

## Tools Installed
* *Cursor IDE*: Version 0.x (Free Tier setup with custom Anthropic API key configuration)
* *Git for Windows*: Terminal-based version control integration
* *Claude Code Extension*: Installed via Cursor Marketplace (Anthropic)
* *Codex Extension*: Installed via Cursor Marketplace

---

## Steps Completed
1. *IDE Installation*: Downloaded and configured Cursor on Windows.
2. *API Integration*: Linked personal Anthropic API key to Cursor settings to enable model access on the free tier.
3. *Extensions Setup: Navigated the extension ecosystem to locate, install, and authenticate both **Claude Code* and *Codex*.
4. *Repository Creation*: Set up a public repository on GitHub to host project documentation.
5. *Local Environment Link*: Cloned the remote repository to the local Windows machine via Cursor to begin the configuration write-up.

---

## Issues Encountered & Solutions

### 1. Extension Marketplace Navigation
* *Issue*: Standard keyboard shortcuts (Ctrl + Shift + X) were initially unresponsive due to window focus or sidebar visibility settings.
* *Solution*: Bypassed the shortcut restriction by utilizing the Cursor Command Palette (Ctrl + Shift + P) and executing the View: Show Extensions command to manually bring the marketplace panel into focus.

### 2. Missing Local Git Dependency (git.clone / git.showOutput Error)
* *Issue*: Attempting to clone the repository natively within Cursor triggered a missing command error because Git was not installed on the base Windows operating system.
* *Solution*: Downloaded and executed the official 64-bit Git for Windows installer from git-scm.com. Safely closed and restarted the Cursor IDE instance to refresh system path variables, allowing the environment to successfully recognize and execute Git commands.