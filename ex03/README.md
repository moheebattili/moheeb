# Dev Workspace Setup & Git Foundations

This repository contains the setup scripts, environment layouts, and workflow documentation for the initial development workspace.

## Why Git Makes Development Easier

Version control systems like Git serve as a fundamental backbone for modern software development. Here is how Git improves the workflow:

1. **Safeguarding Code:** Git acts as an safety net. Every commit creates a snapshot of your project state. If a bad update, bug, or experimental feature breaks the system, you can easily restore your codebase to a previously known working state without losing history.
2. **Comprehensive History Tracking:** Git keeps a complete, granular log of every modification made—including who made the change, when it occurred, and why (via commit messages). This makes debugging straightforward through tools like `git diff` and `git log`.
3. **Seamless Team Collaboration:** Through branching and merging, multiple developers can work simultaneously on separate features, bug fixes, or experiments without overwriting each other's work. Remote hosts like GitHub act as a single source of truth for repository state and code reviews.

---

## Project Structure

- `dev_workspace/`: Primary working environment directory.
- `manage_files.sh`: Automated script for file creation, copying, renaming, and cleanup.
- `run_log.txt`: Execution output log of `manage_files.sh`.
- `ex00/tree_structure.txt`: Recursive listing (`ls -laR`) of the workspace layout.
