# DevOps Learning — Git

Notes and practice from the CoderCo Git module; simple and practical.

---

## What is Git
Git is a distributed version control system; it tracks changes; supports branching and merging; keeps a reliable history.

---

## Everyday workflow
```bash
git status
git add <file>
git commit -m "imperative, specific message"
git log --oneline --graph --decorate --all

---

# push or pull if you use a remote; optional here
Commit habits
Commit small, related changes; test before committing.

Write clear messages that explain why; not what.

Do not commit generated files or secrets.

Branching with checkout
bash
Copy
Edit
---

# create and switch to a new branch
git checkout -b nameofbranch
---

# do work; commit as you go

# update main and merge your feature when ready
git checkout main
git merge name of branch

---

#Interactive visualiser; helped solidify the commit graph and merges:
https://learngitbranching.js.org/

Completed 11 levels.
