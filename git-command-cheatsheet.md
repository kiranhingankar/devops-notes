# Git Command Cheat Sheet 🚀

## 📦 Git Setup

| Command | Description |
|----------|-------------|
| `git --version` | Check installed Git version |
| `git config --global user.name "Your Name"` | Set Git username |
| `git config --global user.email "you@example.com"` | Set Git email |
| `git config --list` | View Git configuration |

---

## 📁 Repository Commands

| Command | Description |
|----------|-------------|
| `git init` | Initialize a new Git repository |
| `git clone <repo-url>` | Clone a remote repository |
| `git status` | Check repository status |
| `git remote -v` | Show remote repositories |

---

## 📄 Staging & Commit

| Command | Description |
|----------|-------------|
| `git add <file>` | Add specific file to staging |
| `git add .` | Add all files to staging |
| `git commit -m "message"` | Commit changes |
| `git commit -am "message"` | Add and commit tracked files |
| `git diff` | Show file changes |

---

## 🌿 Branching

| Command | Description |
|----------|-------------|
| `git branch` | List branches |
| `git branch <branch-name>` | Create new branch |
| `git checkout <branch-name>` | Switch branch |
| `git checkout -b <branch-name>` | Create and switch branch |
| `git merge <branch-name>` | Merge branch into current branch |
| `git branch -d <branch-name>` | Delete branch |

---

## ☁️ Remote Repository

| Command | Description |
|----------|-------------|
| `git push origin <branch>` | Push code to remote repository |
| `git pull origin <branch>` | Pull latest changes |
| `git fetch` | Fetch latest remote changes |
| `git remote add origin <repo-url>` | Connect local repo to GitHub |

---

## 🔄 Undo Changes

| Command | Description |
|----------|-------------|
| `git restore <file>` | Restore file changes |
| `git reset --soft HEAD~1` | Undo last commit but keep changes |
| `git reset --hard HEAD~1` | Remove last commit completely |
| `git revert <commit-id>` | Revert a specific commit |

---

## 📜 Logs & History

| Command | Description |
|----------|-------------|
| `git log` | View commit history |
| `git log --oneline` | Compact commit history |
| `git show <commit-id>` | Show commit details |

---

## 🧹 Stashing

| Command | Description |
|----------|-------------|
| `git stash` | Save temporary changes |
| `git stash list` | View stash list |
| `git stash apply` | Apply stashed changes |
| `git stash drop` | Delete stash |

---

## 🏷️ Tags

| Command | Description |
|----------|-------------|
| `git tag` | List tags |
| `git tag <tag-name>` | Create new tag |
| `git push origin <tag-name>` | Push tag to remote |

---

## ⚡ Useful Shortcuts

| Command | Description |
|----------|-------------|
| `git rm <file>` | Remove file from Git |
| `git mv <old> <new>` | Rename/move file |
| `git clean -f` | Remove untracked files |
| `git reflog` | Show all Git references |

---

# 📌 Common Git Workflow

```bash
git init
git add .
git commit -m "Initial Commit"
git branch -M main
git remote add origin <repo-url>
git push -u origin main

---


📚 Helpful Resources
- Official Git Docs: https://git-scm.com/doc
- GitHub Docs: https://docs.github.com
- Learn Git Branching: https://learngitbranching.js.org
