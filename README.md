# git-manager Skill

`git-manager` is an OpenClaw skill that helps operators run advanced Git workflows safely, especially when diagnosing regressions, pruning branches, managing stashes, and analyzing commit history.

## Quick start
1. Trigger the skill with a command like `git manager` or `bisect issue` inside a repository.
2. Follow the prompts for diagnostics, branch cleanup, stash review, or log analysis.
3. Execute the suggested commands and confirm before destructive operations such as `branch -D`, `reset`, or `push --force`.

## Core focus areas
- **Bisecting regressions** with explicit good/bad checkpoints and safety reminders.
- **Branch hygiene** through merged/escaped branch audits and reminder-driven deletions.
- **Stash management** that keeps descriptive stash entries and warns before drops.
- **Log and reflog analysis** to understand what operations led to the current state.
- **Safety prompts** bundled with every rewrite action to double-check the current commit or remote.

## Files
- `SKILL.md` – Trigger and workflow definition for the skill.
- `README.md` – Human-friendly overview and execution hints.
- `LICENSE` – Licensing terms (MIT).  

## License
This project is licensed under the MIT License.