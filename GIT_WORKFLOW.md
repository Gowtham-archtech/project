# Git Workflow Guide

## Understanding Git Commands

### 1. **ADD** - Staging Changes
- **What it does:** Stages modified files for commit
- **Command:** `git add <filename>` or `git add .` for all changes
- **Purpose:** Prepares files to be included in the next commit
- **Example:** `git add README.md`

### 2. **COMMIT** - Recording Changes
- **What it does:** Creates a snapshot of staged changes with a message
- **Command:** `git commit -m "commit message"`
- **Purpose:** Saves changes to local repository with descriptive message
- **Example:** `git commit -m "Add new feature"`

### 3. **PUSH** - Uploading to Remote
- **What it does:** Uploads commits from local to remote repository
- **Command:** `git push origin <branch-name>`
- **Purpose:** Makes your changes available to team members
- **Example:** `git push origin main`

## Key Differences

| Operation | Scope | Purpose | Location |
|-----------|-------|---------|----------|
| **ADD** | Working Directory → Staging Area | Select which changes to commit | Local |
| **COMMIT** | Staging Area → Local Repository | Create snapshot with message | Local |
| **PUSH** | Local Repository → Remote Repository | Share changes with others | Remote |

## Workflow Sequence
1. **Modify** files in your working directory
2. **ADD** files you want to commit: `git add <file>`
3. **COMMIT** with message: `git commit -m "message"`
4. **PUSH** to remote: `git push origin main`
5. **CLONE** to get a copy: `git clone <repository-url>`
