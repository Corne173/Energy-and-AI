
# Git Fundamentals Guide

A quick reference to help you understand and use Git for version control.

---

## 1. What is Git?

Git is a distributed version control system that tracks changes in files and collaborates on projects.

- **Version Control**: Records changes to files over time.
- **Distributed**: Every user has a full copy of the repository (history and files).
- **Commits**: Snapshots of your project’s state.

---

## 2. Installing Git

- **Windows**: https://git-scm.com/download/win  
- **macOS**: `brew install git` (requires Homebrew)  
- **Linux**: `sudo apt-get install git` (Debian/Ubuntu) or `sudo yum install git` (RHEL/CentOS)

After installing, verify with:
```bash
git --version
```

---

## 3. Initializing & Cloning Repositories

- **Initialize a new repo**:
  ```bash
  git init
  ```
- **Clone an existing repo**:
  ```bash
  git clone <repository-url>
  ```

---

## 4. Basic Workflow

1. **Modify files** in your working directory.
2. **Stage changes** (prepare for commit):
   ```bash
   git add <file1> <file2> ...
   ```
3. **Commit changes** (save a snapshot):
   ```bash
   git commit -m "Commit message describing changes"
   ```
4. **Repeat** as you continue development.

---

## 5. Checking Status & History

- **Status**: see which files are modified, staged, or untracked.
  ```bash
  git status
  ```
- **Log**: view commit history.
  ```bash
  git log
  ```

---

## 6. Branching & Merging

- **Create and switch to a branch**:
  ```bash
  git checkout -b feature/my-feature
  ```
- **List branches**:
  ```bash
  git branch
  ```
- **Switch branches**:
  ```bash
  git checkout main
  ```
- **Merge a branch into current**:
  ```bash
  git merge feature/my-feature
  ```

---

## 7. Working with Remotes

- **Add a remote**:
  ```bash
  git remote add origin <remote-url>
  ```
- **View remotes**:
  ```bash
  git remote -v
  ```
- **Push to remote** (upload commits):
  ```bash
  git push origin main
  ```
- **Fetch & Merge** (update local):
  ```bash
  git pull origin main
  ```

---

## 8. Undoing Changes

- **Unstage a file**:
  ```bash
  git reset HEAD <file>
  ```
- **Discard changes in working directory**:
  ```bash
  git checkout -- <file>
  ```
- **Revert a commit** (create a new commit that undoes changes):
  ```bash
  git revert <commit-hash>
  ```

---

## 9. Common Commands Cheat Sheet

| Task                      | Command                                 |
|---------------------------|-----------------------------------------|
| Configure user name/email| `git config --global user.name "Name"`  |
|                          | `git config --global user.email "email"`|
| Show staged diff          | `git diff --cached`                     |
| Remove tracked file       | `git rm <file>`                         |
| Rename file               | `git mv <old> <new>`                    |
| Stash changes             | `git stash`                             |
| Apply stash               | `git stash apply`                       |

---

## 10. Resources

- [Official Git docs](https://git-scm.com/doc  )
- [Pro Git book (free)]( https://git-scm.com/book/en/v2)  

Happy coding with Git!
