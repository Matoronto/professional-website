# Lessons Learned

## Lesson 1: Git Commit History Management

### Situation

While organizing project documentation, I renamed the User Stories file to include the `.md` extension so GitHub would render it correctly as Markdown.

### Issue

I accidentally created a commit message that referenced the Site Architecture file instead of the User Stories file. Although the file change was correct, the commit message did not accurately describe the work performed.

### Resolution

To correct the issue, I:

- Cloned the repository locally
- Learned basic Git Bash navigation and commands
- Performed an interactive rebase
- Reworded the incorrect commit message
- Pushed the updated commit history using `git push --force-with-lease`

### Lesson Learned

Commit messages should accurately describe the changes being made. Reviewing both the affected files and the commit message before committing helps maintain a clean and understandable project history.

### Future Action

Before committing changes:

- Review staged files
- Verify commit message accuracy
- Confirm branch selection
- Verify file naming conventions
- Perform a final review before pushing changes

---

## Lesson 2: Align Technical Decisions with Business Requirements

### Situation

At the start of the project, I planned to build the website using Java + Spring Boot and implement a database-backed contact form to store user inquiries.

### Issue

While presenting the project at Code Club RDU, stakeholders questioned whether these technologies were necessary for the MVP. The proposed architecture introduced additional complexity without solving an immediate business need.

### Resolution

After reviewing stakeholder feedback, I decided to defer Java + Spring Boot and database-backed contact functionality for the MVP. Instead, I will focus on a frontend-first implementation and provide contact options through LinkedIn and email.

### Lesson Learned

Technical decisions should be driven by business requirements rather than technology preferences. Simpler solutions are often more appropriate when they satisfy the project's current goals.

### Future Action

Before introducing new technologies:

- Validate the business need
- Evaluate simpler alternatives
- Consider MVP scope and project goals
- Gather stakeholder feedback before increasing complexity
- Document technical decisions and tradeoffs
