# mine-kids-why-review

This Codex skill asks a fresh subagent simple "why?" questions about the assistant's changes and claims. The assistant answers with evidence and repeats the review for three rounds, then reports problems and explains whether the review converged.

## Install in another Codex

Ask Codex: "Install the skill from [this folder](https://github.com/Pqlet/kids-why-review/tree/main/skills/mine-kids-why-review)." Then start a new turn and invoke `$mine-kids-why-review` with the work you want checked.

If you install skills manually, copy the entire `skills/mine-kids-why-review` directory into your Codex skills directory (usually `~/.codex/skills/`). Keep the folder name.

## Paste into a chat

This option needs a chat that can start a separate subagent without conversation history. If that capability is unavailable, the assistant should say so; a self-review is not an independent review. Open [SKILL.md](skills/mine-kids-why-review/SKILL.md), copy its full text into the chat, and name the changes or claims to review.

The skill is read-only when invoked solely for review. It does not publish, merge, deploy, or run jobs.
