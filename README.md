# cursor-rules

Cursor remote rules stored in `.cursor/rules/` as `.mdc` files.

## Always Apply
- `common-coding-style.mdc` — Coding style, immutability, error handling, input validation

## Apply Intelligently
- `common-testing.mdc` — TDD workflow and coverage requirements
- `common-security.mdc` — Security checklist and secret management
- `common-git-workflow.mdc` — Commit message format and PR conventions
- `common-development-workflow.mdc` — Feature implementation workflow
- `common-patterns.mdc` — Repository pattern, API response format

## Apply to Specific Files (`**/*.go, **/go.mod, **/go.sum`)
- `golang-coding-style.mdc` — Go formatting, interfaces, error wrapping
- `golang-patterns.mdc` — Functional options, DI, small interfaces
- `golang-security.mdc` — Secret management, gosec, context timeouts
- `golang-testing.mdc` — Table-driven tests, race detection, coverage
