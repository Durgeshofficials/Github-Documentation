# 🚀 Git & GitHub Complete Guide (Beginner to Advanced)

This repository is created to understand **Git and GitHub** from **scratch to advanced level**, with clear commands, concepts, and real-world workflows.

---

## 📌 Table of Contents
1. What is Git?
2. What is GitHub?
3. Git Installation
4. Git Basic Workflow
5. Creating a Local Repository
6. Connecting Local Repo to GitHub
7. Pushing Code to GitHub
8. Daily Git Workflow
9. Branching in Git
10. Merging Branches
11. Handling Merge Conflicts
12. Git Pull vs Fetch vs Clone
13. Undoing Changes
14. Git Stash
15. Best Practices
16. Common Errors & Fixes
17. Interview Quick Notes

---

## 1️⃣ What is Git?
Git is a **distributed version control system** used to track code changes and collaborate with teams.

✔ Tracks history  
✔ Allows rollback  
✔ Supports collaboration  

---

## 2️⃣ What is GitHub?
GitHub is a **remote code hosting platform** that stores Git repositories online.

✔ Backup  
✔ Collaboration  
✔ CI/CD integration  

---

## 3️⃣ Git Installation
Check installation:
```bash
git --version

4️⃣ Git Basic Workflow (MOST IMPORTANT)
Working Directory → Staging Area → Local Repo → Remote Repo

5️⃣ Creating a Local Repository
git init
git status
git add .
git commit -m "Initial commit"

6️⃣ Creating Repository on GitHub
Login to GitHub

Click New Repository

Enter repository name

❌ Do NOT add README / .gitignore

Copy HTTPS URL

Example:

https://github.com/username/repo-name.git

7️⃣ Connecting Local Repo to GitHub
git remote add origin https://github.com/username/repo-name.git
git remote -v

8️⃣ Pushing Code to GitHub

Check branch:

git branch

If branch is main
git push -u origin main

If branch is master
git push -u origin master

🔐 Authentication:

Username → GitHub username
Password → Personal Access Token (PAT)
