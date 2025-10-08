


# Making Your First Contribution

Welcome! This guide will help you make your **first contribution** to an open-source repository on GitHub.  
Even if you have never used GitHub before, follow these steps carefully and you’ll succeed.

---

## 1. Why We Are Doing This

The goal of this exercise is to teach you:

- How to **fork a repository**.
- How to **create a branch**.
- How to **make a change and submit a Pull Request (PR)**.
- How to see your contributions merged into the main repository.

---

## 2. Fork the Repository

1. Go to this repository: [first-contribution-guide](https://github.com/rishabh3562/first-contribution-guide)  
2. Click the **Fork** button in the top-right corner.  
3. Your GitHub account now has a copy of the repo.

---

## 3. Clone Your Fork Locally

Open your terminal or Git Bash and run:

```bash
git clone <YOUR-FORK-URL>
cd first-contribution-guide
````

Replace `<YOUR-FORK-URL>` with the URL of your forked repository.

---

## 4. Create a New Branch

Always create a branch for your change:

```bash
git checkout -b yourname-first-PR
```

*Example:* `git checkout -b rishabh-first-PR`

---

## 5. Make Your Contribution

1. Go to the `contributions/` folder in the repo.
2. Create a new text file named:

```
yourname_date.txt
```

*Example:* `rishabh_2025-10-08.txt`

3. Inside the file, write something simple:

```
Name: Rishabh
Date: 2025-10-08
Message: My first PR
```

---

## 6. Commit Your Changes

In the terminal, run:

```bash
git add contributions/yourname_date.txt
git commit -m "Add first contribution by YourName"
```

---

## 7. Push Your Branch to GitHub

```bash
git push origin yourname-first-PR
```

---

## 8. Open a Pull Request (PR)

1. Go to your fork on GitHub.
2. You will see a button **Compare & Pull Request**. Click it.
3. Add a simple description: “Adding my first contribution.”
4. Submit the Pull Request.

---

## 9. Wait for Review/Merge

* Your instructor or student maintainers will review and merge your PR.
* Once merged, congratulations—you’ve made your **first contribution**!

---

## 10. Tips for Success

* Only **one file per PR**.
* Use **meaningful branch names**: `yourname-first-PR`.
* Follow the steps exactly — the goal is to understand the workflow.
* If your PR is not merged immediately, don’t worry. Learn from feedback and try again.

---

**Congratulations!** You are now on your way to contributing to open-source.


