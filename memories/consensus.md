# Auto Company Consensus

## Last Updated
2026-05-23T00:00:00+09:00

## Current Phase
Migration

## What We Did This Cycle
- Initialized shared state for moving the workflow to `SooLee99/Auto-Company` and `SooLee99/Dorothy`.
- Recorded that existing projects and Harness-generated agents and skills must be continued.

## Key Decisions Made
- Auto-Company will provide the file-based continuation loop.
- Dorothy will provide dashboard, Kanban, Vault, scheduled tasks, and multi-agent management.
- Existing Harness files should be preserved and inspected before any edits.

## Active Projects
- Existing SI project: status pending local inspection — continue the current work rather than starting over.
- Harness continuation: status pending inspection — preserve `.claude/agents/` and `.claude/skills/`.
- Dorothy migration: status pending setup — configure after local dashboard state is reviewed.

## Harness State
- Agents: pending inspection.
- Skills: `team` skill exists; other skills pending inspection.
- Next harness action: document current agents, skills, project path, and next task.

## Dorothy State
- Dashboard: target repository is `SooLee99/Dorothy`; local install state unknown.
- Scheduled Tasks: pending.
- Kanban/Vault: pending.

## Next Action
Inspect the current project path, Harness files, active tasks, test commands, and documentation state. Then update `memories/handoff.md` and `docs/dorothy-auto-company-harness-migration.md`.

## Company State
- Product: existing SI project, details pending inspection.
- Tech Stack: Auto-Company, Dorothy, Claude Code, Harness, plus project-specific stack pending inspection.
- Repository: `SooLee99/Auto-Company`, `SooLee99/Dorothy`, and the existing project repository or local path.
- Revenue: TBD
- Users: TBD

## Open Questions
- Local path or repository name of the existing SI project.
- Local path and state location of the currently installed dashboard.

## Handoff Notes
- Preserve existing project work and Harness files.
- Prefer documentation, tests, and branch-based changes before larger project changes.
- First migration deliverable is state preservation and setup documentation.
