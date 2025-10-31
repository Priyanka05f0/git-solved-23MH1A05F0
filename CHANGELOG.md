# Changelog

All notable changes to this project are documented here.

## [v3.0.0] - 2025-10-27

### Fixed
- **Final Cleanup:** Removed all stray Git conflict markers from documentation files, including the final one found in `GIT_JOURNEY.md`.

### Chore
- Performed final commit history cleanup to ensure required commit count was met before submission.

## [v2.0.0] - 2025-10-27

### Merged
- **Major Conflict Resolution (Merge 2):** Completed the second major merge, integrating the `conflict-simulator` branch into `main`.
  - Resolved **6 conflicts** across configuration and documentation files.

### Added
- Implemented a new feature set (as documented in the `feat: Add new feature` commit).
- Updated the README with comprehensive architecture and feature sections.

## [v1.1.0] - 2025-10-27

### Added
- Added an FAQ section to the project documentation.
- Completed initial documentation review and updates.

## [v1.0.0] - 2025-10-27

## [v3.0.1] - 2025-10-27

### Synced

* Used *git fetch (1 time)* to retrieve the latest updates from the instructor’s repository before final merge verification.
* Used *git pull (1 time)* to integrate remote changes into the local branch before performing Merge 2.

### Verified

* Ensured all changes were successfully fetched and merged without overwriting local commits.
* Confirmed synchronization by running git status and git log --oneline --graph.

### Chore

* Final verification of branches, tags, and commit count before project submission.
* Ensured no pending files or unstaged changes remained.

---

### Merged
- **Major Conflict Resolution (Merge 1):** Completed the first critical merge, integrating the `dev` branch into `main`.
  - Resolved **6 conflicts** in configuration and script files (e.g., `config/app-config.yaml`, `scripts/deploy.sh`).

  - **Resolution Strategy:** Restructured config files to support environment-based settings (production and development) to maintain stability.


### Initial Commit
- Project repository cloned and initialized with initial file structure.
