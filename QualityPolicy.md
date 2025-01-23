# Quality Policy

## Git Workflow
- **Branching Strategy**: 
  - The `main` branch is used for production-ready code.
  - Feature branches (e.g., `feature-*`) are created for individual tasks or features.
  - All feature branches are merged back into `main` after review.

- **Commit Workflow**:
  - Every commit must include a clear and descriptive commit message.
  - Commits should follow this format: `[type]: short description`, where `type` could be `fix`, `feat`, or `docs`.

- **Pull Requests**:
  - Pull requests are mandatory for merging changes into the `main` branch.
  - At least one team member must review and approve a pull request before it can be merged.
  - Include a link to the related issue or task in the pull request description.
