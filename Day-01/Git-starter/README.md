# Day 1: Git & GitHub Starter Kit

Welcome to **Day 1** of our *Introduction to Coding* course! Today, you'll begin from zero—learning how to initialize, track, and collaborate on a Git repository from scratch.

---

## 🎯 Learning Objectives

- Install and configure Git locally  
- Initialize a new Git repository  
- Create, commit, and review changes  
- Create feature branches and open pull requests  
- Practice reviewing and merging a peer’s pull request

---

## 🚀 How to Use This Repo

Create a repository unders your Github account then name it `day-01-git-starter` and this repository is your sandbox—empty and clean, ready for you to initiate:

1. Clone this template (which is currently empty):
   ```bash
   git clone https://github.com/your-username/day-01-git-starter.git
   cd day-01-git-starter
   ```

2. Initialize the repository:

   ```bash
   git init
   git branch -M main
   git remote add origin https://github.com/your-username/day-01-git-starter.git
   ```
3. Create the `exercises/` folder:

   ```bash
   mkdir exercises
   echo "Exercise files go here" > README.md
   git add exercises README.md
   git commit -m "Initialize project structure"
   git push -u origin main
   ```
4. For **Exercise 1**, create a branch:

   ```bash
   git checkout -b exercise-1
   ```
5. Add a sentence in `exercises/exercise1.txt` about why you’re learning Git:

   ```bash
   echo "I'm learning Git to confidently manage code and collaborate with others." > exercises/exercise1.txt
   ```
6. Commit and push your branch:

   ```bash
   git add exercises/exercise1.txt
   git commit -m "Add motivation sentence in exercise1"
   git push -u origin exercise-1
   ```
7. On GitHub, open a **Pull Request (PR)** from `exercise-1` into `main`.
8. Review a classmate’s PR, leave feedback, and once approved, merge it. ✅



## 🧩 Exercises

### `exercise1` — Edit Motivation

* In `exercises/exercise1.txt`, include a line such as:
  *"I'm learning Git to confidently manage code and collaborate with others."*

### `exercise2` — Introduce Yourself

* Create a branch `exercise-2`, then:

  * Create `exercises/exercise2.md`
  * Add a brief “About Me” paragraph (1–2 lines)
  * Commit, push, and open a PR



## ⏱ Suggested Schedule

| Time          | Activity                                             |
| ------------- | ---------------------------------------------------- |
| **0–10 min**  | Install Git and configure `user.name` & `user.email` |
| **10–15 min** | Demo: `git init`, clone, branch, commit, PR flow     |
| **15–25 min** | **Exercises 1 & 2** with instructor help             |
| **25–35 min** | Peer reviews: exchange PRs and give feedback         |
| **35–40 min** | Merge PRs, reflect on learning, and close day        |



## 🛠 Resources & Tips

* **Learn Git Branching** (visual, interactive training)
* **GitHub “Hello World”** demo in GitHub’s Docs for guidance
* **GitHub Skills: Intro to GitHub** for optional reinforcement

> **Tip**: Keep branches small and focused—great for clear reviews!



## ✅ What to Submit

By the end of class:

* Your repo (initialized from scratch) with exercises
* A PR you've created **and** one you've reviewed
* A short insight or challenge to share in the wrap‑up



**Happy initializing—and happy committing!**
