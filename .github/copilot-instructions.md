# GitHub Copilot Instructions - Enveloppe10

When working in this repository, please follow these project management and structural guidelines.

## Repository Structure Context

- **Project Management**: Everything related to planning, backlog, and status is in `project-management/`.
- **Backlog**: The main source of truth for work items is `project-management/backlog/product-backlog.md`.
- **Sprints**: Active work is detailed in the latest document within `project-management/sprints/`.

## Operational Rules

1.  **Context Loading**: When a user mentions a task ID (e.g., FR-001), index the corresponding file in `project-management/backlog/features/` or `project-management/backlog/bugs/`.
2.  **Process Adherence**: Follow the lifecycle defined in `project-management/docs/processes/backlog-management-process.md`.
3.  **Documentation Standards**: Use templates from `project-management/docs/templates/` for new planning documents.
4.  **Status Sync**: Always remind the user or help them update the backlog status consistently when a task is started, progressed, or completed.

## Mandatory Git Commit Format

Follow these rules for ALL commits:
1.  **Subject**: `<type>(<scope>): <subject>`
2.  **Body 1**: Concise paragraph on Business Value (The 'Why').
3.  **Body 2**: Technical implementation details (The 'How').
4.  **Footer**: Reference the specific Task ID (FR-XXX/BF-XXX).

Details in `project-management/docs/git-standards.md`.
