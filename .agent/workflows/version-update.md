---
description: Update project versioning (index.html, CHANGELOG, README)
---

1.  **Analyze Changes**: Determine if the changes constitute a Major (breaking), Minor (new feature), or Patch (bug fix) update.
2.  **Update index.html**:
    -   Find the version string in the comment header (e.g., `Version: v1.7.6`).
    -   Find the version string in the footer (e.g., `App Version: v1.7.6`).
    -   Increment them according to the analysis.
3.  **Update CHANGELOG.md**:
    -   Add a new section at the top for the new version.
    -   Format: `## [vX.Y.Z] - YYYY-MM-DD`
    -   List changes under `### Added`, `### Changed`, or `### Fixed`.
4.  **Update README.md**:
    -   Update the version number in the title/header (e.g., `# Blessed Draw App (v1.7.6)`).
    -   Update the version badge URL (e.g., `https://img.shields.io/badge/version-v1.7.6-blue`).
    -   Update any relevant instructions if the changes affect usage.
5.  **Check/Update Copyright Year**:
    -   Check the current year.
    -   If `current_year > 2025` (project creation year):
        -   Update copyright notices in `LICENSE`, `README.md`, and `index.html`.
        -   Format should be `2025-[Current Year]` (e.g., `2025-2026`).
    -   If `current_year == 2025`, ensure it says `2025`.
6.  **Commit and Push**:
    -   Stage all changes: `git add .`
    -   Commit with a conventional message (e.g., `feat: ...`, `fix: ...`, `style: ...`).
    -   **Push to GitHub**: `git push`
