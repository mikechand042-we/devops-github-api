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

## SSH

SSH is used for secure communication between Git and GitHub.

Generate SSH key:

```bash
ssh-keygen -t ed25519 -C "your-email"
```

SSH Key Pair:

```text
Private Key → Local computer
Public Key  → GitHub
```

## GitHub Remote

Check remote connection:

```bash
git remote -v
```

Add GitHub remote:

```bash
git remote add origin <repository-url>
```

Change remote URL:

```bash
git remote set-url origin <repository-url>
```

Example SSH remote:

```bash
git remote set-url origin git@github.com:username/repository.git
```

## Push to GitHub

First push and set upstream:

```bash
git push -u origin main
```

After upstream is set:

```bash
git push
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
* `git remote -v` → configured remote connection check karta hai.
* `git remote add origin` → GitHub repository ko remote ke taur par add karta hai.
* `git remote set-url origin` → existing remote ka URL change karta hai.
* `git push -u origin main` → first push ke saath upstream set karta hai.
* `git push` → upstream set hone ke baad changes GitHub par push karta hai.
