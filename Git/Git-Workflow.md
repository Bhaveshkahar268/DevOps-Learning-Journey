# 🔄 Git Workflow

Git Workflow is the sequence of steps developers follow while working on a project.

## Standard Git Workflow

```text
Create Project
      │
      ▼
git init / git clone
      │
      ▼
Write Code
      │
      ▼
git status
      │
      ▼
git add .
      │
      ▼
git commit -m "message"
      │
      ▼
git push origin main
      │
      ▼
GitHub Repository
```

---

## Step-by-Step Workflow

| Step | Command | Purpose |
|------|----------|----------|
| 1 | `git clone` | Clone existing repository |
| 2 | Write code | Make changes |
| 3 | `git status` | Check modified files |
| 4 | `git add .` | Stage files |
| 5 | `git commit -m "message"` | Save changes locally |
| 6 | `git push` | Upload changes to GitHub |

---

## Pull Existing Changes

```bash
git pull origin main
```

Downloads latest changes from GitHub.

---

## Check Commit History

```bash
git log --oneline
```

Shows compact commit history.

---

## Best Practices

✔ Commit frequently.

✔ Write meaningful commit messages.

✔ Pull latest changes before pushing.

✔ Never commit sensitive files like passwords.

✔ Use branches for new features.
