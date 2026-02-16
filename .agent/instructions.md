# Antigravity Instructions - Enveloppe10

This repository uses a structured project management system located in the `project-management/` directory. When working on this project, adhere to the following guidelines and leverage the existing documentation.

## Project Structure

- **`project-management/`**: Core directory for all management artifacts.
  - **`backlog/`**: Contains the product backlog and individual items.
    - `product-backlog.md`: The central tracking table for all features and bugs.
    - `features/`: Detailed markdown files for each feature request (FR-XXX).
    - `bugs/`: Detailed markdown files for each bug fix (BF-XXX).
  - **`sprints/`**: Documents for sprint planning and tracking (sprint-XX-name.md).
  - **`docs/`**: Process documentation and templates.
    - `processes/backlog-management-process.md`: DEFINITIVE GUIDE for backlog and sprint management.
    - `templates/`: Templates for feature requests, bug fixes, and sprint planning.

## Working with the Backlog

1.  **Reference Before Acting**: Always check the `product-backlog.md` and the relevant `sprints/` document before starting a task.
2.  **Update Status Regularly**: When starting or finishing a task, update:
    - The relevant FR or BF file in `backlog/features/` or `backlog/bugs/`.
    - The `product-backlog.md` table.
    - The active sprint document in `sprints/`.
3.  **Use Templates**: Always use the templates in `project-management/docs/templates/` when creating new backlog items or sprints.

## Git Commit Standards (MANDATORY)

Always generate commit messages in this format:
- **Header**: `<type>(<scope>): <subject>`
- **Business Body**: Why this change matters for the project.
- **Technical Body**: Bullet points of files and logic changed.
- **Footer**: `Related to FR-XXX` or `Fixes BF-XXX`.

See `project-management/docs/git-standards.md` for full examples.

## Repository Knowledge

- This project uses a "backlog-toolkit" for managing development flow through markdown files.
- Consistency between the backlog table and individual detail files is CRITICAL.
