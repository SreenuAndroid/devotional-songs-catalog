Amend all staged and unstaged changes to the previous commit.

Steps:

1. Stage all changes
2. Amend to previous commit (keep existing message unless user specifies new one)

Safety checks before amending:

- Verify the last commit is yours (check author)
- Verify the commit hasn't been pushed (branch is ahead of remote)
- If either check fails, warn user and ask for confirmation

Rules:

- Only amend if safe (unpushed, own commit)
- Keep existing commit message by default
- If updating message, follow same format as /cmt
- Never use --trailer (no "Made-with: Cursor" or similar)