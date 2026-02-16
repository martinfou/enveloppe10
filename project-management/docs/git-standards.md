# Git Commit Standards

All contributors (human and AI) must adhere to these standards to ensure project history is clean, meaningful, and professional.

## Commit Message Format

Commit messages must follow this structure:

```text
<type>(<scope>): <subject> (Max 50 characters)

[Business Context Paragraph]
A short paragraph (2-3 sentences) explaining the business value, the 'why' behind the change, and the expected benefit to the project or users.

[Technical Implementation Details]
- Bullet point list of technical changes.
- Mention specific files, classes, or patterns used.
- Highlight any trade-offs or performance considerations.

[Footer]
- Issue/PR references (e.g., Fixes #123, Related to FR-002).
```

### Allowed Types

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code (white-space, formatting, etc)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools and libraries

### Example

```text
feat(project-management): establish git commit standards

This change introduces mandatory commit message standards for all AI assistants. By providing structured business and technical context in every commit, we ensure the project history is readable for both management and engineering teams, facilitating better knowledge transfer and auditing.

- Created `project-management/docs/git-standards.md` detailing the format.
- Included business-paragraph and technical-bullets requirements.
- Defined a set of allowed commit types (feat, fix, refactor, etc.).

Related to FR-002.
```

## Branching & Initialization

1.  **Branch Name**: Use descriptive names like `feature/FR-XXX-description` or `bugfix/BF-XXX-description`.
2.  **Initialization**: For new repositories, always run `git init` as part of the first sprint.
3.  **Task Alignment**: Every significant change should correspond to a task in the backlog.
