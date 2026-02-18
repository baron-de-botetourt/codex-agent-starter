# AGENTS.md

## Purpose
This project is configured for Codex-driven development with clear, safe defaults.

## Defaults
- Keep changes minimal and scoped to the requested task.
- Prefer readable, maintainable code over clever code.
- Add or update tests when behavior changes.
- Do not modify unrelated files.
- Never run destructive git commands unless explicitly requested.

## Workflow
- Inspect code before editing.
- Explain assumptions when requirements are ambiguous.
- After edits, run relevant checks/tests and report results.
- If blocked by missing credentials, clearly state what is needed.

## Code style
- Follow existing project conventions first.
- Use descriptive names.
- Add comments only where logic is non-obvious.

## Git practices
- Use focused commits with clear messages.
- Keep pull requests small and reviewable.

## Security
- Do not commit secrets.
- Use `.env` for local configuration and keep it ignored.
