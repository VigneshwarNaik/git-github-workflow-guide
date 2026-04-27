# 🚀 Developer 1 & Developer 2 Git Workflow Scenario

![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)
![Workflow](https://img.shields.io/badge/Scenario-Team_Collaboration-success?style=for-the-badge)

> A complete explanation of what Developer 1 and Developer 2 did using branches in a real company workflow.

---
<img width="507" height="586" alt="image" src="https://github.com/user-attachments/assets/f1c775ff-8ca4-430e-bfc3-1ab4ca0ced0e" />


# 📌 Screenshot Explanation

Your GitHub branch switcher shows:

```text
main
footer-feature
navbar-feature
```

## Meaning of Each Branch

### ✅ main (default)

* Final stable branch
* Production-ready code
* Only reviewed code should enter here

### ✅ navbar-feature

* Branch created for Developer 1
* Used to build Navbar feature

### ✅ footer-feature

* Branch created for Developer 2
* Used to build Footer feature

---

# 🏢 Real Company Scenario

Project Name:

```text
company-website
```

Team:

* Developer 1 → Navbar task
* Developer 2 → Footer task
* main branch → Final approved code

Goal:

```text
Two developers work separately without breaking main branch.
```

---


# ⚠️ If Developer 2 Did Not Pull Latest Main

Then conflict may happen.

Example:

```text
Navbar changed index.html
Footer changed same file
```

GitHub says:

```text
This branch has conflicts that must be resolved.
```

---

# 🌳 Final Branch Situation

```text
main            -> Navbar + Footer
navbar-feature  -> old feature branch
footer-feature  -> old feature branch
```

You can delete feature branches after merge.

---

# 📌 Why This Workflow Is Used in Companies

✅ Safe main branch
✅ Multiple developers work together
✅ Easy code review
✅ Easier bug fixing
✅ Better teamwork

---

# 🔥 What Your Screenshot Proves

Your screenshot proves you practiced:

* Creating branches
  n- Working in feature branches
* Pull requests
* Merge workflow
* Multi-developer scenario

---

# 📚 Important Commands Used

```bash
git branch
git checkout -b branch-name
git status
git add .
git commit -m "message"
git push -u origin branch-name
git pull origin main
```


---

# 👨‍💻 Author

**Vigneshwar Naik**

Learning Git practically like real software teams 🚀
