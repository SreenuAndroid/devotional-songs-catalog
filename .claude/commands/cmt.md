Commit all staged and unstaged changes with a concise 1-line commit message.

## Commit

1. Inspect changes: `git status`, `git diff`, `git log --oneline -5`.
2. Stage all changes (`git add -A`).
3. Commit with a concise 1-line message.

## Rules

- Format: `app-name: message` (detect app name from current working directory)
- Message describes structure/what was done, not code details
- Keep under 72 characters
- No Co-Authored-By or Claude mentions
- Never use --trailer (no "Made-with: Cursor" or similar)
- Keep commit messages clean without metadata
