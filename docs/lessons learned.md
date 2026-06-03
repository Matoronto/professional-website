# Lessons Learned

# Git Commit History Management

### Situation

While organizing project documentation, I renamed the User Stories file to include the `.md` extension so GitHub would render it as Markdown.

### Issue

I accidentally used a commit message that referenced the Site Architecture file instead of the User Stories file.

### Resolution

I cloned the repository locally, learned how to use Git Bash, performed an interactive rebase, reworded the commit message, and pushed the corrected history using `git push --force-with-lease`.

### Lesson Learned

Commit messages should accurately describe the change being made. Reviewing both the affected files and the commit message before committing helps maintain a clear project history.

### Future Action

Before committing:

- Review staged files
- Verify commit message accuracy
- Confirm branch selection
- Verify file naming conventions
