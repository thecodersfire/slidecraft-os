# Built-in features for slidecraft-os

Purpose: presentations

1. **organize project files** — run slidecraft-os-workspace. It creates ~/Documents/slidecraft-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run slidecraft-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/slidecraft-os-session-plans/.
3. **check task readiness** — run slidecraft-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/slidecraft-os-workspace features/slidecraft-os-plan features/slidecraft-os-check "$HOME/.local/bin/"
