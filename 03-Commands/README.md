# 🚀 Git & GitHub Commands Cheat Sheet

<p align="center">
  <img src="https://img.shields.io/badge/Git-Commands-orange?style=for-the-badge&logo=git"/>
  <img src="https://img.shields.io/badge/GitHub-Workflow-black?style=for-the-badge&logo=github"/>
  <img src="https://img.shields.io/badge/Level-Beginner_to_Pro-blue?style=for-the-badge"/>
</p>

<p align="center">
  ⚡ Simple • Practical • Real Output
</p>

---

## ⚡ Daily Workflow

```bash id="aa1"
git status
git add .
git commit -m "message"
git push
git pull
```

---

# ⚙️ Setup

### 🟢 `git config`

```bash id="aa2"
git config --global user.name "Vignesh"
git config --global user.email "vignesh@gmail.com"
```

<details>
<summary>📌 Output</summary>

```text id="aa3"
(no output)
```

</details>

---

# 📁 Repository

### 🟢 `git init`

```bash id="aa4"
git init
```

<details>
<summary>📌 Output</summary>

```text id="aa5"
Initialized empty Git repository in /project/.git/
```

</details>

---

### 🟢 `git clone`

```bash id="aa6"
git clone https://github.com/user/repo.git
```

<details>
<summary>📌 Output</summary>

```text id="aa7"
Cloning into 'repo'...
Receiving objects: 100%
```

</details>

---

# 🔍 Checking

### 🟢 `git status`

```bash id="aa8"
git status
```

<details>
<summary>📌 Output</summary>

```text id="aa9"
On branch main
Untracked files:
  index.html
```

</details>

---

### 🟢 `git log`

```bash id="aa10"
git log --oneline
```

<details>
<summary>📌 Output</summary>

```text id="aa11"
a1b2c3 Added file
```

</details>

---

### 🟢 `git diff`

```bash id="aa12"
git diff
```

<details>
<summary>📌 Output</summary>

```diff id="aa13"
- old line
+ new line
```

</details>

---

# ➕ Staging & Commit

### 🟢 `git add`

```bash id="aa14"
git add .
```

<details>
<summary>📌 Output</summary>

```text id="aa15"
(no output)
```

</details>

---

### 🟢 `git commit`

```bash id="aa16"
git commit -m "Added file"
```

<details>
<summary>📌 Output</summary>

```text id="aa17"
[main a1b2c3] Added file
 1 file changed
```

</details>

---

# 🌿 Branching

### 🟢 `git branch`

```bash id="aa18"
git branch
```

<details>
<summary>📌 Output</summary>

```text id="aa19"
* main
```

</details>

```bash id="aa20"
git branch feature-login
```

---

### 🟢 `git checkout`

```bash id="aa21"
git checkout feature-login
```

<details>
<summary>📌 Output</summary>

```text id="aa22"
Switched to branch 'feature-login'
```

</details>

```bash id="aa23"
git checkout -b feature-ui
```

<details>
<summary>📌 Output</summary>

```text id="aa24"
Switched to a new branch 'feature-ui'
```

</details>

---

# 🔀 Merge

### 🟢 `git merge`

```bash id="aa25"
git merge feature-login
```

<details>
<summary>📌 Output</summary>

```text id="aa26"
Fast-forward
```

</details>

---

# 🔗 Remote

### 🟢 `git remote`

```bash id="aa27"
git remote add origin https://github.com/user/repo.git
```

```bash id="aa28"
git remote -v
```

<details>
<summary>📌 Output</summary>

```text id="aa29"
origin https://github.com/user/repo.git (fetch)
origin https://github.com/user/repo.git (push)
```

</details>

---

# 🚀 Push & Pull

### 🟢 `git push`

```bash id="aa30"
git push -u origin main
```

<details>
<summary>📌 Output</summary>

```text id="aa31"
Branch 'main' set up to track 'origin/main'
```

</details>

---

```bash id="aa32"
git push
```

<details>
<summary>📌 Output</summary>

```text id="aa33"
Everything up-to-date
```

</details>

---

### 🟢 `git pull`

```bash id="aa34"
git pull
```

<details>
<summary>📌 Output</summary>

```text id="aa35"
Already up to date.
```

</details>

---

### 🟢 `git fetch`

```bash id="aa36"
git fetch
```

<details>
<summary>📌 Output</summary>

```text id="aa37"
Fetching origin
```

</details>

---

# ❌ Undo

### 🟢 `git restore`

```bash id="aa38"
git restore file.txt
```

<details>
<summary>📌 Output</summary>

```text id="aa39"
(no output)
```

</details>

---

### 🟢 `git reset`

```bash id="aa40"
git reset file.txt
```

<details>
<summary>📌 Output</summary>

```text id="aa41"
Unstaged changes after reset
```

</details>

```bash id="aa42"
git reset --hard
```

<details>
<summary>📌 Output</summary>

```text id="aa43"
HEAD is now at a1b2c3 commit message
```

</details>

---

### 🟢 `git revert`

```bash id="aa44"
git revert a1b2c3
```

<details>
<summary>📌 Output</summary>

```text id="aa45"
Revert commit created
```

</details>

---

# 📦 Stash

### 🟢 `git stash`

```bash id="aa46"
git stash
```

<details>
<summary>📌 Output</summary>

```text id="aa47"
Saved working directory
```

</details>

```bash id="aa48"
git stash pop
```

<details>
<summary>📌 Output</summary>

```text id="aa49"
Dropped refs/stash@{0}
```

</details>

---

# 🧹 File Commands

### 🟢 `git rm`

```bash id="aa50"
git rm file.txt
```

<details>
<summary>📌 Output</summary>

```text id="aa51"
rm 'file.txt'
```

</details>

---

### 🟢 `git mv`

```bash id="aa52"
git mv old.txt new.txt
```

<details>
<summary>📌 Output</summary>

```text id="aa53"
(no output)
```

</details>

---

### 🟢 `git clean`

```bash id="aa54"
git clean -f
```

<details>
<summary>📌 Output</summary>

```text id="aa55"
Removing temp.txt
```

</details>

---

# 🔥 Advanced

### 🟢 `git rebase`

```bash id="aa56"
git rebase main
```

<details>
<summary>📌 Output</summary>

```text id="aa57"
Successfully rebased
```

</details>

---

### 🟢 `git cherry-pick`

```bash id="aa58"
git cherry-pick a1b2c3
```

<details>
<summary>📌 Output</summary>

```text id="aa59"
Applied commit
```

</details>

---

### 🟢 `git blame`

```bash id="aa60"
git blame index.html
```

<details>
<summary>📌 Output</summary>

```text id="aa61"
a1b2c3 (Vignesh) line content
```

</details>

---

## 🧠 Flow

```bash id="aa62"
git status → git add → git commit → git push → git pull
```

---

## ⭐ Support

If this helps:

⭐ Star this repo
🔁 Share it

---

## 👨‍💻 Author

**Vigneshwar Naik**

---
