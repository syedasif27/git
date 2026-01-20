# Git Basic Commands Cheat Sheet 🚀
_A beginner-friendly guide to Git_

---

## 1. What is Git?
Git is a **distributed version control system** used to track changes in files and collaborate with others.

---

## 2. One-Time Git Setup

### Set username
```bash
git config --global user.name "Your Name"
```

### Set email
```bash
git config --global user.email "your@email.com"
```

### Check configuration
```bash
git config --list
```

---

## 3. Creating & Cloning Repositories

### Initialize a new repository
```bash
git init
```

### Clone an existing repository
```bash
git clone <repo-url>
```

Example:
```bash
git clone git@github.com:user/repo.git
```

---

## 4. Checking Repository Status

```bash
git status
```

---

## 5. Staging Files

```bash
git add file.txt
git add .
```

---

## 6. Committing Changes

```bash
git commit -m "Commit message"
git commit --amend
```

---

## 7. Viewing History

```bash
git log
git log --oneline
git log --oneline --graph --decorate
```

---

## 8. Branching

```bash
git branch
git branch new-branch
git checkout new-branch
git checkout -b new-branch
git branch -d new-branch
```

---

## 9. Remote Repositories

```bash
git remote -v
git remote add origin <repo-url>
git remote set-url origin <new-url>
```

---

## 10. Push & Pull

```bash
git push
git push -u origin main
git pull
git fetch
```

---

## 11. Undoing Changes

```bash
git restore --staged file.txt
git restore file.txt
git reset --hard
```

---

## 12. Stash

```bash
git stash
git stash list
git stash apply
git stash drop
```

---

## 13. Tags

```bash
git tag v1.0
git push origin v1.0
```

---

## 14. Diff

```bash
git diff
git diff --staged
```

---

## 15. Remove & Rename Files

```bash
git rm file.txt
git rm --cached file.txt
git mv old.txt new.txt
```

---

## 16. .gitignore Example

```
node_modules/
.env
*.log
```

---

## 17. SSH Authentication

```bash
ssh -T git@github.com
```

---

## 18. Common Workflow

```text
Edit → git add → git commit → git push
```

---

## END 🎯
