# AGENTS.md: harness adapter, not a second authority

Codex, Copilot, and Hermes auto-load `AGENTS.md`. Claude Code auto-loads `CLAUDE.md`.
This file exists only to bridge them.

**`CLAUDE.md` in this directory is the sole source of standing project rules. Read it
completely before acting.**

Where a rule speaks of "the active agent" or names a specific model or tool, read that as
whichever harness is running this session. Named tools are capability choices, relevant
only when the current harness actually exposes them.

Do not copy standing rules, task priorities, project structure, or status into this file.
A copied rule drifts and becomes a competing standard. If this adapter ever disagrees with
`CLAUDE.md`, `CLAUDE.md` wins.
