# HackGreenville.com agent instructions

Use these repo-specific Git conventions when you create or suggest branches and commits.

## Branch names

- Branch from `develop`
- Use the format `{type}/{description}`
- Keep the description short, meaningful, unique, and kebab-case
- Avoid issue numbers in branch names

Examples:

- `feat/add-sponsors`
- `fix/calendar-popup-css`
- `docs/typos-in-readme`

## Commit messages

Use conventional commits:

- `type: short description`
- `type(scope): short description`

Common types:

- `feat`
- `fix`
- `docs`
- `test`
- `refactor`
- `chore`

Guidelines:

- Keep the subject line short and clear
- Put extra detail in the commit body when needed

Examples:

- `fix: update API routes`
- `feat: add event RSVP`
- `fix(docs): update database schema image`
