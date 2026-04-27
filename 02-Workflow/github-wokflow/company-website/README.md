
# 🚀 Complete Git & GitHub Workflow Guide (With What Each Command Does)

![Git](https://img.shields.io/badge/GIT-Version%20Control-orange?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Collaboration-black?style=for-the-badge&logo=github)
![Workflow](https://img.shields.io/badge/Workflow-Industry%20Ready-blue?style=for-the-badge)

---

# 📌 Real Company Scenario

```text
Project Name: company-website
Developer 1 → Navbar Task
Developer 2 → Footer Task
````

---

# 🚀 STEP 1: Clone Repository

## Command

```bash
git clone https://github.com/username/repository.git
```

## What This Command Does

```text
Downloads full project from GitHub to your computer.
Creates project folder.
Connects local repo with remote GitHub repo.
```

---

# 🚀 STEP 2: Enter Project Folder

## Command

```bash
cd git-github-workflow-guide
```

## What This Command Does

```text
Moves terminal inside project folder.
Now all Git commands work for this repo.
```

---

# 🚀 STEP 3: Open in VS Code

## Command

```bash
code .
```

## What This Command Does

```text
Opens current folder in Visual Studio Code.
"." means current directory.
```

---

# 🚀 STEP 4: Go to Main Branch

## Command

```bash
git checkout main
```

## What This Command Does

```text
Switches working branch to main.
Used before starting new task.
```

---

# 🚀 STEP 5: Get Latest Code

## Command

```bash
git pull origin main
```

## What This Command Does

```text
Downloads latest changes from GitHub main branch.
Updates your local main branch.
Used before creating new feature branch.
```

---

# 🚀 STEP 6: Create Navbar Feature Branch

## Command

```bash
git checkout -b navbar-feature
```

## What This Command Does

```text
Creates new branch called navbar-feature.
Automatically switches into that branch.
Used for separate feature development.
```

---

# 🚀 STEP 7: Check File Changes

## Command

```bash
git status
```

## What This Command Does

```text
Shows changed files.
Shows staged files.
Shows current branch.
Shows whether working tree is clean or modified.
```

---

# 🚀 STEP 8: Add Files for Commit

## Command

```bash
git add .
```

## What This Command Does

```text
Stages all changed files.
Prepares files for commit.
"." means all files in current folder.
```

---

# 🚀 STEP 9: Save Snapshot

## Command

```bash
git commit -m "Added navbar with styling"
```

## What This Command Does

```text
Creates local save point (snapshot).
Stores code changes in Git history.
-m adds commit message.
```

---

# 🚀 STEP 10: Upload Branch to GitHub

## Command

```bash
git push -u origin navbar-feature
```

## What This Command Does

```text
Uploads navbar-feature branch to GitHub.
Creates remote branch if not exists.
-u links local branch with remote branch.
Future push can use only git push.
```

---

# 🔀 STEP 11: Pull Request

## What Happens

```text
GitHub compares:
main ← navbar-feature
```

## Task

```text
Request to merge your code into main branch.
```

---

# 🚀 STEP 12: Merge Pull Request

## What This Does

```text
Moves navbar-feature code into main branch.
Now project officially updated.
```

---

# 🚀 STEP 13: Delete Branch

## What This Does

```text
Deletes old feature branch after merge.
Keeps repository clean.
```

---

# 🚀 STEP 14: Developer 2 Starts Footer

## Commands

```bash
git checkout main
git pull origin main
git checkout -b footer-feature
```

## What These Do

```text
Go to updated main branch.
Download navbar changes.
Create new branch for footer task.
```

---

# 🚀 STEP 15: Footer Save Process

## Commands

```bash
git add .
git commit -m "Added footer feature"
git push -u origin footer-feature
```

## What These Do

```text
Stage footer files.
Create commit snapshot.
Upload footer branch to GitHub.
```

---

# 🌳 Full Workflow

```text
Clone Repo
↓
Open VS Code
↓
Pull Latest Main
↓
Create Feature Branch
↓
Edit Code
↓
git status
↓
git add .
↓
git commit
↓
git push
↓
Pull Request
↓
Merge
↓
Delete Branch
```

---

# 📌 Important Command Summary

| Command                   | Task                 |
| ------------------------- | -------------------- |
| git clone URL             | Download project     |
| cd folder                 | Enter folder         |
| code .                    | Open VS Code         |
| git checkout main         | Switch to main       |
| git pull origin main      | Get latest code      |
| git checkout -b branch    | Create branch        |
| git status                | Check changes        |
| git add .                 | Stage files          |
| git commit -m             | Save snapshot        |
| git push -u origin branch | Upload branch        |
| Pull Request              | Ask merge permission |
| Merge PR                  | Add code to main     |

---

# 💼 Real Company Meaning

```text
Each developer gets task.
Each task uses separate branch.
Main branch stays safe.
Code reviewed before merge.
```

---

# 👨‍💻 Author

Vigneshwar Naik

---

# ⭐ Support

If useful:

```text
Give Star ⭐
```

```
```
