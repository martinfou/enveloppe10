# Claude Code Instructions - Enveloppe10

This project follows a structured markdown-based backlog management process. Please adhere to the following when assisting with development.

## Key Directories

- `project-management/backlog/`: Contains `product-backlog.md` and detailed items in `features/` or `bugs/`.
- `project-management/sprints/`: Contains active sprint plans.
- `project-management/docs/processes/`: Contains `backlog-management-process.md` which defines the status lifecycle and workflows.

## Guidelines

- **Backlog First**: Always check the backlog and active sprint BEFORE suggesting or implementing changes.
- **Maintain Consistency**: Ensure task status is updated in the backlog table, the specific FR/BF file, and the sprint document.
- **Template Usage**: Use the templates in `project-management/docs/templates/` for all new management documents.
- **Reference IDs**: Use task IDs (FR-XXX, BF-XXX) in commit messages and documentation.

## Git Commit Message Generation

Ensure all commits follow this mandatory format:
1.  `<type>(<scope>): <subject>` (Max 50 chars)
2.  Paragraph explaining business value and context.
3.  Bulleted list of technical implementation details.
4.  Task ID reference (e.g., Related to FR-XXX).

Full standards: `project-management/docs/git-standards.md`.
