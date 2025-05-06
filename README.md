# 🧾 Git + GitHub Cheatsheet

A concise and practical guide to essential Git and GitHub commands — perfect for your Laravel or any dev workflow.

---

## 🚀 Git + GitHub Quick Summary

This guide covers:

- Local Git project flow
- Branching and version control
- Working with GitHub remotes
- Undoing and restoring changes
- Staging, deleting, renaming files

---

## 📁 Local Git Commands (Project Lifecycle)

| Command                            | Description                                      |
|-----------------------------------|--------------------------------------------------|
| `git init`                        | Start a Git repo in your local project.          |
| `git status`                      | Show the current state of changes in the repo.   |
| `git add .`                       | Stage all modified files for commit.             |
| `git commit -m "message"`         | Save staged changes with a message.              |
| `git log --oneline`               | View concise commit history.                     |
| `git diff`                        | View unstaged changes in files.                  |
| `git restore <file>`             | Undo changes in working directory (unstaged).    |
| `git restore --staged <file>`    | Unstage changes (move from staged to unstaged).  |
| `git reset <commit>`              | Move HEAD and optionally reset the working tree. |
| `git revert <commit>`             | Make a new commit that undoes a previous commit. |

---

## 🌳 Branching

| Command                               | Description                                       |
|--------------------------------------|---------------------------------------------------|
| `git branch`                         | List all branches.                                |
| `git branch <name>`                 | Create a new branch.                              |
| `git checkout <name>`              | Switch to an existing branch.                     |
| `git checkout -b <name>`           | Create and switch to a branch in one step.        |
| `git merge <branch>`               | Merge given branch into current one.              |
| `git branch -d <name>`             | Delete a branch (safe – only if merged).          |
| `git branch -D <name>`             | Force delete a branch.                            |

---

## 🧹 Staging, Removing, Renaming Files

| Command                     | Description                                 |
|----------------------------|---------------------------------------------|
| `git rm <file>`           | Remove a file and stage the removal.         |
| `git mv <old> <new>`      | Rename a file and stage the change.          |

---

## 💻 GitHub (Remote) Commands

| Command                                           | Description                                               |
|--------------------------------------------------|-----------------------------------------------------------|
| `git remote add origin <URL>`                   | Link local repo to GitHub remote.                         |
| `git push -u origin master`                     | Upload local commits to GitHub & track remote branch.     |
| `git push`                                       | Send committed changes to GitHub.                         |
| `git pull`                                       | Fetch and merge changes from GitHub to local.             |
| `git fetch`                                      | Only fetch updates from GitHub (no merge).                |
| `git clone <URL>`                               | Download a full repo from GitHub.                         |
| `git log origin/main`                           | View commit history of the remote branch.                 |
| `git diff origin/main`                          | Compare local branch with remote one.                     |

---

## ✅ Bonus Tip: When to Use What?

- **Init**: Start a project
- **Clone**: Download a project from GitHub
- **Add + Commit**: Save changes locally
- **Push**: Upload changes to GitHub
- **Pull**: Download + merge changes from GitHub
- **Fetch**: Just check for updates without merging
- **Branches**: Work on features or fixes without touching the main project

---

Made with 💻 by **Umair Abideen** — Laravel Developer exploring the power of Git 💥
