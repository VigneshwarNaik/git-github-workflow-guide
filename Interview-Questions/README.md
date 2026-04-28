# 🎯 Git & GitHub Interview Questions

<p align="center">
  <img src="https://img.shields.io/badge/Git-Interview-orange?style=for-the-badge&logo=git"/>
  <img src="https://img.shields.io/badge/GitHub-Preparation-black?style=for-the-badge&logo=github"/>
  <img src="https://img.shields.io/badge/Level-Interview_Ready-blue?style=for-the-badge"/>
</p>

> 💡 Includes **20 Normal Questions + 15 Scenario-Based Questions**
> ✔️ Simple • Clear • Interview-Ready

---

# 🔹 Part 1: Normal Questions (Core Concepts)

---

### 1. What is Git?

Git is a **version control system** used to track changes in code.
It helps developers manage history and collaborate on projects.

---

### 2. What is GitHub?

GitHub is a **cloud platform** used to store and collaborate on Git repositories.
It allows multiple developers to work on the same project.

---

### 3. Difference between Git and GitHub

| Git            | GitHub             |
| -------------- | ------------------ |
| Local tool     | Online platform    |
| Tracks changes | Hosts repositories |
| Works offline  | Requires internet  |

---

### 4. What is a repository?

A repository is a **project folder tracked by Git**, containing code and history.

---

### 5. What is a commit?

A commit is a **snapshot of changes** saved in Git history.

---

### 6. What is staging area?

It is a **temporary area** where files are prepared before committing.

---

### 7. What does `git add` do?

It moves files from working directory to the **staging area**.

---

### 8. What does `git commit` do?

It saves staged changes into the repository permanently.

---

### 9. What is `git status`?

It shows the **current state of files** (modified, staged, untracked).

---

### 10. What is `git clone`?

It copies a repository from GitHub to your local system.

---

### 11. What is `git push`?

It uploads local commits to GitHub.

---

### 12. What is `git pull`?

It downloads and merges the latest changes from the remote repository.

---

### 13. Difference between `git fetch` and `git pull`

* `git fetch` → downloads changes only
* `git pull` → downloads + merges changes

---

### 14. What is a branch?

A branch is a **separate line of development** used to work on features independently.

---

### 15. What is merge conflict?

It occurs when Git cannot automatically merge changes from different branches.

---

### 16. What is HEAD?

HEAD is a **pointer to the current commit or branch** you are working on.

---

### 17. What is origin?

Origin is the **default name of the remote repository**.

---

### 18. Difference between `git reset` and `git revert`

| Reset             | Revert                  |
| ----------------- | ----------------------- |
| Removes commit    | Creates new undo commit |
| Not safe for team | Safe for team           |

---

### 19. What is `.git` folder?

It is a hidden folder that stores **all Git data (history, branches, commits)**.

---

### 20. What is Pull Request (PR)?

A Pull Request is a request to merge your changes into another branch for review.

---

### ⭐ Extra Important

### 21. What is Fork?

A fork is a copy of someone else's repository into your own GitHub account.

---

### 22. Difference between Merge and Rebase

| Merge                | Rebase          |
| -------------------- | --------------- |
| Keeps history        | Linear history  |
| Creates extra commit | No extra commit |

---

# 🔹 Part 2: Scenario-Based Questions (Real-World)

---

### 23. You forgot to add a file before commit

👉 I will add the missing file and commit again.

```bash id="s1"
git add file.txt
git commit -m "Added missing file"
```

---

### 24. You wrote wrong commit message

👉 I will amend the last commit message.

```bash id="s2"
git commit --amend -m "Correct message"
```

---

### 25. You pushed wrong code to GitHub

👉 I will safely undo using revert to avoid affecting team members.

```bash id="s3"
git revert <commit-id>
git push
```

---

### 26. Two developers changed same file

👉 This creates a merge conflict. I will manually fix the file and commit.

```bash id="s4"
git add .
git commit
```

---

### 27. You need to develop a new feature

👉 I will create a new branch to avoid affecting main code.

```bash id="s5"
git checkout -b feature-login
git add .
git commit -m "Feature added"
git push origin feature-login
```

---

### 28. Your code is outdated

👉 I will pull the latest changes from the remote repository to sync my code.

```bash id="s6"
git pull
```

---

### 29. You want to save unfinished work temporarily

👉 I will use stash to save changes without committing.

```bash id="s7"
git stash
```

---

### 30. You want to undo last commit

👉 I will reset the last commit but keep changes.

```bash id="s8"
git reset --soft HEAD~1
```

---

### 31. You want to see changes before committing

👉 I will check differences using diff.

```bash id="s9"
git diff
```

---

### 32. You joined a new project

👉 First step is to clone the repository.

```bash id="s10"
git clone <repo-url>
```

---

### 33. You want to switch branch

👉 I will checkout the required branch.

```bash id="s11"
git checkout branch-name
```

---

### 34. You want to merge branch

👉 I will merge the branch into the current branch.

```bash id="s12"
git merge branch-name
```

---

### 35. You want to see commit history

👉 I will check log in short format.

```bash id="s13"
git log --oneline
```

---

### 36. You added file by mistake to staging

👉 I will unstage the file.

```bash id="s14"
git reset file.txt
```

---

### 37. You want to discard file changes

👉 I will restore the file to last committed state.

```bash id="s15"
git restore file.txt
