# 🚀 Git Commands Revision Sheet 

Git is a distributed version control system used to track changes in source code during software development. It enables multiple developers to collaborate efficiently while maintaining the complete history of a project.

---------------------------------------------------------------------------
| Command                                | Description                         |
| -------------------------------------- | ----------------------------------- |
| `git --version`                        | Check installed Git version         |
| `git config --global user.name "Name"` | Set Git username                    |
| `git config --global user.email "Email"` | Set Git email                    |
| `git config --list`                    | View Git configuration              |
| `git init`                             | Initialize new Git repository       |
| `git clone <url>`                      | Clone remote repository             |
| `git status`                           | Show repository status              |
| `git add file.txt`                     | Stage specific file                 |
| `git add .`                            | Stage all changes                   |
| `git commit -m "message"`              | Commit staged changes               |
| `git log`                              | Show commit history                 |
| `git log --oneline`                    | Compact commit history              |
| `git show`                             | Show latest commit details          |
| `git diff`                             | Show unstaged changes               |
| `git diff --staged`                    | Show staged changes                 |
| `git branch`                           | List all branches                   |
| `git branch feature`                   | Create new branch                   |
| `git checkout feature`                 | Switch branch                       |
| `git checkout -b feature`              | Create & switch branch              |
| `git switch feature`                   | Switch branch (new syntax)          |
| `git merge feature`                    | Merge branch into current branch    |
| `git branch -d feature`                | Delete branch                       |
| `git remote -v`                        | View remote repository              |
| `git remote add origin <url>`          | Connect GitHub repository           |
| `git remote remove origin`             | Remove remote repository            |
| `git push origin main`                 | Push code to GitHub                 |
| `git push -u origin main`              | First push with upstream            |
| `git pull origin main`                 | Pull latest changes                 |
| `git fetch`                            | Download remote changes             |
| `git fetch --all`                      | Fetch all remote branches           |
| `git stash`                            | Save uncommitted changes            |
| `git stash list`                       | View saved stashes                  |
| `git stash apply`                      | Apply latest stash                  |
| `git stash pop`                        | Apply & remove latest stash         |
| `git stash drop`                       | Delete latest stash                 |
| `git reset HEAD file.txt`              | Unstage file                        |
| `git reset --soft HEAD~1`              | Undo commit (keep staged changes)   |
| `git reset --mixed HEAD~1`             | Undo commit (keep unstaged changes) |
| `git reset --hard HEAD~1`              | Remove last commit permanently      |
| `git reset --hard <commit-id>`         | Rollback to specific commit         |
| `git revert <commit-id>`               | Reverse a commit safely             |
| `git restore file.txt`                 | Discard changes in file             |
| `git restore .`                        | Discard all unstaged changes        |
| `git rm file.txt`                      | Delete tracked file                 |
| `git mv old.txt new.txt`               | Rename file                         |
| `git clean -fd`                        | Remove untracked files/folders      |
| `git reflog`                           | View reference history              |
| `git blame file.txt`                   | Show who modified each line         |
| `git tag`                              | List all tags                       |
| `git tag v1.0`                         | Create new tag                      |
| `git push origin v1.0`                 | Push tag to GitHub                  |
---------------------------------------------------------------------------


















git init
git add
git rm --cached 
git commit -m "   "
git status
git remote add origin https://TOKEN@github.com/Bhaveshkahar268/GITHUB-FOR-DEVOPS.git
git remote set-url origin https://TOKEN@github.com/Bhaveshkahar268/GITHUB-FOR-DEVOPS.git
git config --list
git push origin master
git push -u origin main
git clone

commit from github

git reset --hard
git pull orgin master (pulling the last commit or push code on the local from git hub)
git stash 
git stash pop

git branch
git branch branch_name
git switch branch_name

git checkout
git checkout branch_name
git log
git log --oneline

git fetch (fetching all the remote branch from git hub to local system)
