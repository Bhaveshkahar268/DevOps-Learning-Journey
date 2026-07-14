# 🌿 Git Branching

A branch is an independent line of development.

Instead of changing the main project directly, developers create branches to develop new features safely.

---

## Why Branches?

- Prevent breaking the main code
- Work independently
- Collaborate with team members
- Test new features safely

---

## Git Branch Workflow

```text
           main
             │
      -----------------
      │               │
 feature-login    feature-payment
      │               │
      └──────Merge────┘
             │
            main
```

---

## Branch Commands

| Command | Description |
|----------|-------------|
| `git branch` | List branches |
| `git branch feature-login` | Create new branch |
| `git checkout feature-login` | Switch branch |
| `git checkout -b feature-login` | Create & switch branch |
| `git switch feature-login` | Switch branch |
| `git merge feature-login` | Merge into current branch |
| `git branch -d feature-login` | Delete branch |

---

## Complete Branch Example

### Create branch

```bash
git checkout -b feature-login
```

---

### Write code

Modify your project files.

---

### Commit

```bash
git add .

git commit -m "Added Login Page"
```

---

### Push branch

```bash
git push origin feature-login
```

---

### Merge

```bash
git checkout main

git merge feature-login
```

---

### Delete branch

```bash
git branch -d feature-login
```

---

## Best Practices

✔ Create a branch for every feature.

✔ Never work directly on `main`.

✔ Merge only after testing.

✔ Delete merged branches to keep repository clean.
