Commit all changes and push to remote repository in one command.

Rules:

- Stage all changes (git add -A)
- Commit with concise 1-line message
- Format: `app-name: message` (detect app name from current working directory)
- Keep message under 72 characters
- No Co-Authored-By or Claude mentions
- Push to current branch after successful commit
- Show both commit and push results
