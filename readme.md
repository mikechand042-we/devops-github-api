# Git & GitHub Practice

## Repository

This repository is created for practicing Git and GitHub.

## Basic Git Commands

```bash
git status
git add .
git commit -m "commit message"
git log --oneline
git push
git pull
```

## GitHub Remote

```bash
git remote -v
```

## SSH

SSH is used for secure communication between Git and GitHub.

```bash
ssh-keygen -t ed25519 -C "your-email"
```

## Basic Workflow

```text
Create / Modify Files
        ↓
git add .
        ↓
git commit -m "message"
        ↓
git push
        ↓
GitHub
```

## Branch Commands

```bash
git branch
git switch main
git switch -c feature
git merge feature
```

## Useful Notes

* `git add` → changes ko staging area mein rakhta hai.
* `git commit` → changes ko local Git history mein save karta hai.
* `git push` → commits ko GitHub par bhejta hai.
* `git pull` → GitHub se latest changes lata hai.
* `git log --oneline` → commit history short form mein dikhata hai.
* `git remote -v` → GitHub remote connection check karta hai.
