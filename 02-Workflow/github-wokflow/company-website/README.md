
# 🚀 Real GitHub Workflow Practice – Complete README.md

![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Workflow](https://img.shields.io/badge/WORKFLOW-Industry%20Ready-success?style=for-the-badge)

---

# 📌 Introduction

This repository explains a **real company Git & GitHub workflow** using VS Code, Terminal, and GitHub Pull Requests.

It shows how developers work in real companies like:

- Google  
- Microsoft  
- Infosys  
- Accenture  
- TCS  
- Startups  

---

# 🎯 What You Will Learn

✅ Clone Repository  
✅ Open Project in VS Code  
✅ Check Branch  
✅ Pull Latest Code  
✅ Create Feature Branch  
✅ Edit Files  
✅ Git Status  
✅ Commit Changes  
✅ Push Branch  
✅ Pull Request  
✅ Merge Workflow  

---

# 📂 Project Name

```bash
git-github-workflow-guide
````

---

# 🖼️ Step 1 – Clone Repository

![Clone Repository](your-screenshot-1.png)

```bash
git clone https://github.com/VigneshwarNaik/git-github-workflow-guide.git
```

### Explanation:

Copies GitHub repository into your computer.

### Output Meaning:

* Cloning into → Creating folder
* Enumerating objects → Counting files
* Receiving objects → Downloading files
* Resolving deltas → Final setup complete

✅ Project downloaded successfully.

---

# 🖼️ Step 2 – Open Project in VS Code

![Open VS Code](your-screenshot-2.png)

```bash
code .
```

### Explanation:

* `code` = Open VS Code
* `.` = Current folder

✅ Opens current project folder in VS Code.

---

# 🖼️ Step 3 – Check Current Branch

![Check Branch](your-screenshot-3.png)

```bash
git branch
```

### Output:

```bash
* main
```

### Meaning:

* `main` = Current branch
* `*` = Active branch

✅ You are on main branch.

---

# 🖼️ Step 4 – Pull Latest Code

![Pull Latest Code](your-screenshot-4.png)

```bash
git pull origin main
```

### Explanation:

Downloads latest code from GitHub main branch.

### Output:

```bash
Already up to date.
```

✅ Your project already latest.

---

# 🖼️ Step 5 – Create Feature Branch

![Create Branch](your-screenshot-5.png)

```bash
git checkout -b navbar-feature
```

### Explanation:

* `checkout` = Switch branch
* `-b` = Create new branch
* `navbar-feature` = Branch name

### Output:

```bash
Switched to a new branch 'navbar-feature'
```

✅ New branch created.

---

# 🖼️ Step 6 – Edit Files

![Modified Files](your-screenshot-6.png)

Edited files:

```text
index.html
style.css
```

Saved using:

```text
Ctrl + S
```

VS Code showed:

```text
M
```

### Meaning:

`M = Modified`

Git detected changes.

---

# 🖼️ Step 7 – Check Status

![Git Status](your-screenshot-7.png)

```bash
git status
```

### Output:

```bash
modified: index.html
modified: style.css
```

### Meaning:

2 files changed.

---

# 🖼️ Step 8 – Add Changes

```bash
git add .
```

### Explanation:

Adds all changed files to staging area.

---

# 🖼️ Step 9 – Commit Changes

![Git Commit](your-screenshot-8.png)

```bash
git commit -m "Added navbar with styling"
```

### Explanation:

Creates project snapshot with message.

✅ Code saved in Git history.

---

# 🖼️ Step 10 – Push Branch

![Git Push](your-screenshot-9.png)

```bash
git push -u origin navbar-feature
```

### Explanation:

Uploads branch to GitHub.

* `-u` links local branch with remote branch.

Next time use:

```bash
git push
```

✅ Branch uploaded successfully.

---

# 🖼️ Step 11 – GitHub Popup

![Compare Pull Request](your-screenshot-10.png)

GitHub showed:

```text
Compare & pull request
```

### Meaning:

GitHub detected new branch and asks to merge into main.

✅ Click it.

---

# 🖼️ Step 12 – Create Pull Request

![Create PR](your-screenshot-11.png)

GitHub page showed:

```text
base: main
compare: navbar-feature
```

### Pull Request Title:

```text
Added navbar with styling
```

### Pull Request Description:

```md
## Changes Made

- Added navbar in index.html
- Added CSS styling in style.css
- Improved website header

## Files Changed

- index.html
- style.css

## Tested

- Browser checked
- Working properly
```

Then click:

```text
Create Pull Request
```

---

# 🖼️ Step 13 – Merge Pull Request

```text
Merge Pull Request
Confirm Merge
```

✅ Code merged into main branch.

---

# 🏢 Real Company Workflow

```text
Clone Repo
↓
Pull Latest Code
↓
Create Feature Branch
↓
Do Task
↓
git status
↓
git add .
↓
git commit -m "message"
↓
git push
↓
Pull Request
↓
Code Review
↓
Merge to Main
```

---

# 🔥 Commands Summary

```bash
git clone <repo-url>
code .
git branch
git pull origin main
git checkout -b navbar-feature
git status
git add .
git commit -m "Added navbar with styling"
git push -u origin navbar-feature
```

---

# 💡 Why Use Branches?

✅ Safe development
✅ Main branch protected
✅ Easy review
✅ Team collaboration
✅ Easy rollback
✅ Professional workflow

---

# 🚫 Avoid

```bash
Work directly on main branch
```

Use:

```bash
git checkout -b feature-name
```

---

# 📚 Example Branch Names

```text
navbar-feature
login-page
footer-ui
bugfix-header
dashboard-design
payment-api
```

---

# 🎯 What I Learned

✅ Git clone
✅ Git branch
✅ Git pull
✅ Git checkout -b
✅ Git status
✅ Git add
✅ Git commit
✅ Git push
✅ Pull Request
✅ Merge Request

---

# 🚀 Next Level Git Topics

* Merge Conflict
* Rebase
* Cherry Pick
* Git Stash
* Reset vs Revert
* Team Workflow
* 3 Developer Collaboration

---

# ⭐ Support

If you found this useful:

⭐ Star this repository
🍴 Fork it
📘 Practice daily

---

# 👨‍💻 Author

**Vigneshwar Naik**
Learning Git, GitHub, React & Full Stack Development 🚀

```
```
