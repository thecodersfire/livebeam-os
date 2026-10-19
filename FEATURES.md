# Built-in features for livebeam-os

Purpose: live streaming

1. **prepare racing and game notes** — run livebeam-os-workspace. It creates ~/Documents/livebeam-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run livebeam-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/livebeam-os-session-plans/.
3. **check game and controller readiness** — run livebeam-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/livebeam-os-workspace features/livebeam-os-plan features/livebeam-os-check "$HOME/.local/bin/"
