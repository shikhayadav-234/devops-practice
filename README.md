# 📁 DevOps Git Practice Project

### 🧰 Description

This is a **hands-on Git and DevOps practice project** created as part of my learning journey.
It demonstrates a **real-world Git workflow** using feature branches, merging, and syncing with GitHub.

The project simulates a typical development process where features are developed in isolation and integrated into development (`dev`) and production (`main`) branches using best practices.

---

### 📌 What This Project Covers

✅ Initialize a Git repository
✅ Create and push branches (`main`, `dev`, `feature-login`, `feature-signup`)
✅ Add and commit feature-specific changes
✅ Merge feature branches into `dev`
✅ Merge `dev` into `main` (for production)
✅ Push branches to GitHub
✅ View and manage branches on GitHub

---

### 🌿 Branching Structure

```
main                 ← Production-ready code
│
└── dev              ← Active development branch
     ├── feature-login    ← Login feature (merged)
     └── feature-signup   ← Signup feature (merged)
```

---

### 📂 Files in This Repo

* `login.txt` – Placeholder file for login feature
* `signup.txt` – Placeholder file for signup feature
* `README.md` – This project description and learning documentation

---

### 🔀 Git Commands Practiced

Here are some of the important Git commands used:

```bash
git init
git checkout -b dev main
git checkout -b feature-login dev
git add <file>
git commit -m "Message"
git merge <branch>
git push -u origin <branch>
```

---

### 💡 What I Learned

* How to manage Git branches for different features
* The importance of isolating features using `feature-*` branches
* How merging works between branches (`feature → dev → main`)
* Using GitHub to push, view, and manage branches
* Solving common Git errors (e.g., push rejection, host resolution)

---

### 📤 Branches Pushed to GitHub

| Branch Name      | Description                    |
| ---------------- | ------------------------------ |
| `main`           | Production/stable branch       |
| `dev`            | Development integration branch |
| `feature-login`  | Login feature (merged)         |
| `feature-signup` | Signup feature (merged)        |

✅ All branches were created locally and manually pushed to GitHub.

---

### 🚀 Next Steps

In the future, I may:

* Add real code instead of placeholder `.txt` files
* Use Pull Requests (PRs) for code reviews
* Integrate CI/CD pipelines (GitHub Actions or Jenkins)
* Learn about Gitflow or trunk-based development models

---

### 🙋‍♀️ About Me

I'm a beginner in DevOps and Cloud technologies, exploring version control, automation, and modern software development practices.

This project is a reflection of my learning journey — feel free to fork, follow, or contribute as I continue to grow and build more projects.
---

## 🔗 Repo Link

👉 [https://github.com/shikhayadav-234/devops-practice](https://github.com/shikhayadav-234/devops-practice)
