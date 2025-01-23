# Git Commands Cheat Sheet

This document provides a list of commonly used Git commands with descriptions and examples for easy reference.

---

| **Sr. No.** | **Command**                          | **Description**                                                                 | **Example**                                     |
|-------------|--------------------------------------|---------------------------------------------------------------------------------|------------------------------------------------|
| 1           | `git init`                           | Initializes a new Git repository in the current directory.                      | `git init`                                     |
| 2           | `git clone <repository_url>`         | Creates a local copy of a remote repository.                                    | `git clone https://github.com/user/repo.git`   |
| 3           | `git status`                         | Displays the state of the working directory and staging area.                   | `git status`                                   |
| 4           | `git add <file_or_directory>`        | Adds changes in a file or directory to the staging area.                        | `git add file.txt` or `git add .`             |
| 5           | `git commit -m "Commit message"`    | Records changes to the repository with a descriptive commit message.            | `git commit -m "Initial commit"`             |
| 6           | `git push origin <branch_name>`      | Uploads local branch commits to the remote repository.                          | `git push origin main`                         |
| 7           | `git pull origin <branch_name>`      | Fetches and integrates changes from the remote repository into the current branch.| `git pull origin main`                        |
| 8           | `git log`                            | Displays the commit history for the current branch.                             | `git log` or `git log --oneline`              |
| 9           | `git branch <branch_name>`           | Creates a new branch.                                                           | `git branch feature/new-feature`              |
| 10          | `git checkout <branch_name>`         | Switches to the specified branch.                                               | `git checkout main`                            |
| 11          | `git merge <branch_name>`            | Combines the specified branch into the current branch.                          | `git merge feature/new-feature`               |
| 12          | `git branch -d <branch_name>`        | Deletes the specified branch (only if fully merged).                            | `git branch -d feature/new-feature`           |
| 13          | `git branch -D <branch_name>`        | Force deletes the specified branch.                                             | `git branch -D feature/new-feature`           |
| 14          | `git checkout -- <file>`             | Reverts changes in the working directory to the last committed state.           | `git checkout -- file.txt`                    |
| 15          | `git tag -a <tag_name> -m "Message"`| Creates a tag for marking a specific point in history.                          | `git tag -a v1.0 -m "Version 1.0"`           |
| 16          | `git remote -v`                      | Lists all configured remote repositories.                                       | `git remote -v`                                |
| 17          | `git stash`                          | Temporarily saves changes without committing them.                              | `git stash`                                   |
| 18          | `git stash pop`                      | Reapplies stashed changes.                                                     | `git stash pop`                                |
| 19          | `git diff`                           | Shows changes between the working directory and the index.                      | `git diff`                                    |
| 20          | `git config --global user.name`      | Sets your user name for Git globally.                                           | `git config --global user.name "Your Name"`  |
| 21          | `git config --global user.email`     | Sets your email for Git globally.                                               | `git config --global user.email "email@example.com"` |
| 22          | `git reset --soft HEAD~1`            | Undoes the last commit, keeping changes staged.                                 | `git reset --soft HEAD~1`                      |
| 23          | `git reset --hard <commit_hash>`     | Resets the repository to the specified commit and discards all changes.         | `git reset --hard abc123`                      |

---


## 1. **Initialize a Git Repository**

**Command:**
```bash
git init
```
**Description:**
Initializes a new Git repository in the current directory.

**Example:**
```bash
mkdir my-project
cd my-project
git init
```

---

## 2. **Clone a Repository**

**Command:**
```bash
git clone <repository_url>
```
**Description:**
Creates a local copy of a remote repository.

**Example:**
```bash
git clone https://github.com/user/repo.git
```

---

## 3. **Check Repository Status**

**Command:**
```bash
git status
```
**Description:**
Displays the state of the working directory and staging area, showing changed, staged, or untracked files.

---

## 4. **Stage Changes**

**Command:**
```bash
git add <file_or_directory>
```
**Description:**
Adds changes in a file or directory to the staging area.

**Example:**
```bash
git add file.txt
```
To stage all changes:
```bash
git add .
```

---

## 5. **Commit Changes**

**Command:**
```bash
git commit -m "Commit message"
```
**Description:**
Records changes to the repository with a descriptive commit message.

**Example:**
```bash
git commit -m "Initial commit"
```

---

## 6. **Push Changes to Remote Repository**

**Command:**
```bash
git push origin <branch_name>
```
**Description:**
Uploads local branch commits to the remote repository.

**Example:**
```bash
git push origin main
```

---

## 7. **Pull Changes from Remote Repository**

**Command:**
```bash
git pull origin <branch_name>
```
**Description:**
Fetches and integrates changes from the remote repository into the current branch.

**Example:**
```bash
git pull origin main
```

---

## 8. **View Commit History**

**Command:**
```bash
git log
```
**Description:**
Displays the commit history for the current branch.

To view one-line summaries:
```bash
git log --oneline
```

---

## 9. **Create a New Branch**

**Command:**
```bash
git branch <branch_name>
```
**Description:**
Creates a new branch.

**Example:**
```bash
git branch feature/new-feature
```

---

## 10. **Switch Branches**

**Command:**
```bash
git checkout <branch_name>
```
**Description:**
Switches to the specified branch.

**Example:**
```bash
git checkout main
```

---

## 11. **Merge Branches**

**Command:**
```bash
git merge <branch_name>
```
**Description:**
Combines the specified branch into the current branch.

**Example:**
```bash
git merge feature/new-feature
```

---

## 12. **Delete a Branch**

**Command:**
```bash
git branch -d <branch_name>
```
**Description:**
Deletes the specified branch (only if fully merged).

**Example:**
```bash
git branch -d feature/new-feature
```
To force delete:
```bash
git branch -D feature/new-feature
```

---

## 13. **Revert Changes**

**Command:**
```bash
git checkout -- <file>
```
**Description:**
Reverts changes in the working directory to the last committed state.

**Example:**
```bash
git checkout -- file.txt
```

---

## 14. **Create a Tag**

**Command:**
```bash
git tag -a <tag_name> -m "Tag message"
```
**Description:**
Creates a tag for marking a specific point in history.

**Example:**
```bash
git tag -a v1.0 -m "Version 1.0"
```

---

## 15. **Show Remote Repositories**

**Command:**
```bash
git remote -v
```
**Description:**
Lists all configured remote repositories.

---

## 16. **Stash Changes**

**Command:**
```bash
git stash
```
**Description:**
Temporarily saves changes without committing them.

To reapply stashed changes:
```bash
git stash pop
```

---

## 17. **View Differences**

**Command:**
```bash
git diff
```
**Description:**
Shows changes between the working directory and the index.

---

## 18. **Configure Git User Information**

**Command:**
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
**Description:**
Sets your user name and email for Git globally.

---

## 19. **Undo Last Commit**

**Command:**
```bash
git reset --soft HEAD~1
```
**Description:**
Undoes the last commit, keeping changes staged.

---

## 20. **Hard Reset**

**Command:**
```bash
git reset --hard <commit_hash>
```
**Description:**
Resets the repository to the specified commit and discards all changes.

**Example:**
```bash
git reset --hard abc123
