# Work Log


## October 10, 2026

### Time Spent

Not recorded

### Objectives

- Review project documentation and GitHub repository after a development pause.
- Resolve outstanding Markdown formatting issues.
- Complete Milestone 1: Planning and Documentation.

### Work Completed

- Reviewed Git commit history and existing project documentation.
- Corrected Markdown formatting in `technical-decisions.md` and verified its rendering in GitHub.
- Committed and pushed the formatting corrections to the `development` branch.
- Created and merged Pull Request #1, incorporating 20 development commits and 10 changed files into `main`.
- Synchronized local and remote `main` and `development` branches.

### Issues Encountered

- Markdown formatting displayed incorrectly on GitHub.
- Local `main` was behind the remote branch following the pull request merge.
- Needed to distinguish tracked changes from untracked local design files.

### Resolution

- Reviewed changes using `git diff` before staging and committing.
- Corrected Markdown formatting and verified the GitHub preview.
- Used `git fetch`, `git pull --ff-only`, `git merge`, and `git push` to synchronize branches.
- Preserved untracked design files without including them in the documentation merge.

### Lessons Learned

- Review file changes before committing to maintain accurate version history.
- Pull request merges may require local branch synchronization.
- Git and GitHub workflows support traceability and controlled project development.
- Project progress can resume after interruptions by reviewing existing work and identifying manageable next steps.

### Outcomes

- Completed Milestone 1: Planning and Documentation.
- Successfully merged the first GitHub pull request.
- Established a synchronized Git baseline for Milestone 2.

### Next Steps

- Update project backlog to reflect completed Milestone 1 tasks.
- Review existing Figma wireframes against documented requirements and site architecture.
- Begin Milestone 2: UI/UX Design and Frontend Implementation.

---

## June 5, 2026

### Time Spent

~1 hour

### Objectives

- Present project artifacts at Code Club RDU
- Gather stakeholder feedback on MVP scope and architecture

### Work Completed

- Presented Vision, Mission, and Goals
- Presented Requirements and User Stories
- Presented Site Architecture
- Presented Technical Decisions
- Presented initial Home Page wireframe

### Feedback Received

- Avoid overengineering the MVP
- Consider frontend-first implementation
- Use LinkedIn and email for contact functionality
- Defer database requirements until a clear business need exists
- Explore modern frontend frameworks and static-site approaches

### Lessons Learned

- Stakeholder feedback can significantly influence technical direction
- MVP scope should focus on solving current business needs
- Simpler architectures are often preferable for early project versions

### Outcomes

- Received actionable feedback from developers
- Identified opportunities to simplify implementation
- Reconsidered Java + Spring Boot as an MVP technology choice

### Next Steps

- Update Technical Decisions documentation
- Update Backlog based on stakeholder feedback
- Refine wireframes
- Research frontend framework options
- Continue MVP planning and implementation preparation

---

## June 3, 2026

### Time Spent

~1.5 hours

### Objectives

- Continue project planning and design activities
- Begin translating requirements into visual artifacts

### Work Completed

- Reviewed and updated Technical Decisions documentation
- Documented decision to use Figma for wireframing
- Evaluated future database requirements and deferred the decision
- Created initial desktop Home Page wireframe in Figma
- Continued translating project requirements into design artifacts

### Lessons Learned

- Technical decisions should be documented as they evolve
- Not every future requirement needs to be solved during MVP planning

### Outcomes

- First visual representation of the portfolio website created
- Home Page wireframe prepared for stakeholder review
- Technical decisions documented for future reference

### Next Steps

- Present project at Code Club RDU
- Gather stakeholder feedback
- Create additional page wireframes
- Refine site structure and content organization

---

## June 2, 2026

### Time Spent

~1 hour

### Objectives

- Continue repository setup
- Migrate documentation from Notion to GitHub

### Work Completed

- Added Vision, Mission, and Goals documentation
- Added Requirements documentation
- Added User Stories documentation
- Added Site Architecture documentation
- Created local project directory
- Cloned GitHub repository locally
- Verified development branch workflow

### Issues Encountered

- The `site-architecture.md` file was not rendering correctly on GitHub
- The `user-stories.md` file was missing the `.md` extension
- Commit message referenced the wrong file after renaming

### Resolution

- Renamed documentation files with `.md` extensions
- Learned how GitHub renders Markdown files
- Performed an interactive rebase to correct the commit message
- Successfully updated remote history using `git push --force-with-lease`

### Lessons Learned

- Verify file extensions when creating documentation
- Review commits messages before committing
- Interactive rebase can safely correct commit history on a private development branch

### Next Steps

- Review README
- Organize project documentation
- Begin low-fidelity Figma wireframes







