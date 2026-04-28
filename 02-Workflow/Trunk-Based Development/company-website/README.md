
# 🚀 Trunk-Based Development Workflow (Real Company Scenario)

![Git](https://img.shields.io/badge/GIT-Version%20Control-orange?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Collaboration-black?style=for-the-badge&logo=github)
![Workflow](https://img.shields.io/badge/Workflow-Trunk%20Based-blue?style=for-the-badge)

---

# 📌 Overview

This project demonstrates **Trunk-Based Development (TBD)** using a real company scenario.

In this workflow:

```text
main branch = trunk
All developers frequently merge small changes into main
````

---

# 🏢 Project Scenario

```text
Project: company-website

Developer 1 → Navbar
Developer 2 → Footer
```

Goal:

```text
Build features using small commits and frequent merges into main.
```

---

# 📂 Project Structure

```text
company-website/
├── index.html
├── style.css
└── README.md
```

---

# 🚀 STEP 1: Initial Base Code (Main)

## index.html

```html
<!DOCTYPE html>
<html>
<head>
  <title>Company Website</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

<h1>Welcome to Company Website</h1>
<p>This is the base project.</p>

</body>
</html>
```

---

## style.css

```css
body {
  font-family: Arial;
  text-align: center;
  margin-top: 50px;
}

h1 {
  color: blue;
}
```

---

# 📌 Core Idea of Trunk-Based Development

```text
Small change → Commit → Push → Merge → Repeat
```

---

# 👨‍💻 Developer 1 – Navbar (Step-by-Step)

---

## 🔹 STEP 1: Sync with Main

```bash
git checkout main
git pull origin main
```

---

## 🔹 STEP 2: Create Short Branch

```bash
git checkout -b navbar-step1
```

---

## 🔹 STEP 3: Add Small Change

```html
<nav>
  <a href="#">Home</a>
</nav>
```

---

## 🔹 STEP 4: Commit & Push

```bash
git add .
git commit -m "Navbar basic structure"
git push -u origin navbar-step1
```

---

## 🔹 STEP 5: Pull Request

```text
navbar-step1 → main
```

```text
Create PR → Merge → Delete Branch
```

---

## 🔹 STEP 6: Next Small Change

```bash
git checkout main
git pull origin main
git checkout -b navbar-step2
```

Add:

```html
<a href="#">About</a>
<a href="#">Contact</a>
```

---

## 🔹 STEP 7: Commit & Merge Again

```bash
git add .
git commit -m "Navbar links added"
git push -u origin navbar-step2
```

Merge again.

---

## 🔹 STEP 8: Styling Step

```bash
git checkout main
git pull origin main
git checkout -b navbar-style
```

```css
nav {
  background: #333;
  padding: 10px;
}

nav a {
  color: white;
}
```

Commit → Push → Merge

---

# 📌 Navbar Built in Small Steps

```text
Commit 1 → Structure
Commit 2 → Links
Commit 3 → Styling
```

---

# 👨‍💻 Developer 2 – Footer (Step-by-Step)

---

## 🔹 STEP 1: Sync with Main

```bash
git checkout main
git pull origin main
```

---

## 🔹 STEP 2: Create Short Branch

```bash
git checkout -b footer-step1
```

---

## 🔹 STEP 3: Add Footer

```html
<footer>
  <p>© 2026 Company Website</p>
</footer>
```

---

## 🔹 STEP 4: Commit & Push

```bash
git add .
git commit -m "Footer basic structure"
git push -u origin footer-step1
```

---

## 🔹 STEP 5: Merge Quickly

```text
footer-step1 → main
```

---

## 🔹 STEP 6: Styling Step

```bash
git checkout main
git pull origin main
git checkout -b footer-style
```

```css
footer {
  background: #222;
  color: white;
  text-align: center;
}
```

---

## 🔹 STEP 7: Commit & Merge

```bash
git add .
git commit -m "Footer styling added"
git push -u origin footer-style
```

Merge again.

---

# 🌳 Final Trunk Timeline

```text
main (trunk)
├── navbar-step1   → merged
├── navbar-step2   → merged
├── navbar-style   → merged
├── footer-step1   → merged
└── footer-style   → merged
```

---

# 📌 Key Principles of TBD

## ✅ Small Changes

```text
Work in small steps
```

## ✅ Frequent Merges

```text
Merge many times a day
```

## ✅ Short-Lived Branches

```text
Branches live for hours
```

## ✅ Always Stable Main

```text
main should never break
```

---

# ⚠️ What NOT to Do

```text
❌ Long feature branches
❌ Big commits
❌ Delayed merging
```

---

# 📌 Important Commands

| Command                   | Purpose             |
| ------------------------- | ------------------- |
| git checkout main         | Switch to trunk     |
| git pull origin main      | Get latest updates  |
| git checkout -b branch    | Create small branch |
| git add .                 | Stage changes       |
| git commit -m             | Save changes        |
| git push -u origin branch | Upload branch       |

---

# 💼 Real Company Workflow

```text
Morning → Small change → Merge
Noon → Small change → Merge
Evening → Fix → Merge
```

---

# 🎯 Interview Answer

> Trunk-Based Development is a workflow where developers make small changes using short-lived branches and frequently merge into the main branch to ensure continuous integration and minimal conflicts.

---

# 📈 Skills Demonstrated

* Git branching
* Continuous integration
* Small incremental development
* Team collaboration
* Clean commit practices

---

# 👨‍💻 Author

**Vigneshwar Naik**
MCA Graduate | Java Backend Developer | Open to Work

---

# ⭐ Support

If this helped you:

```text
Give it a Star ⭐
```


