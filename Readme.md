# Practicing Git-GitHub 


## Used Git commands

| Command | Description |
|----------|----------|
| git init | Initialize git in the current folder |
| git status | See changed files |
| git add . | Stage all current changes |
| git commit -m "*comment*" | Commit all staged changes to git -> stage is empty afterwards |
| git commit -am "*comment*" | Commit all files that are already being tracked by git (no new ones) |
| git branch -M main | Renames current branch into **main** |
| git remote add origin `https://github.com/username/repo-name` | Connects git with a repo on GitHub |
| git push -u origin main | Push all commits to main-branch |
| git push | Push after git push -u origin main was done once |
| git log | Show full comment history: author, date, message, hash (press **Q** to quit back to terminal) |
| git log --oneline | Comment history: one line per commit - easier to read |
| git diff *file* | See differences between local file and staged file-version |
| git restore -- staged *filename* | Removed file from staged without changing local version |
| git stash push -- *file* | Stashes changes in *file* |
| git stash list | Show stash list |
| git stash show stash@{*stash number*} | See what is inside a stash |
| git stash show -p stash@{*stash number*} | See line-by-line changes in the stash |
| git stash pop | Restore stash |
| git rm *file* | Delete file |
| git checkout --ours -- *file* | Keep own version of a file e.g. when merge conflict |
| git clone `https://github.com/username/repo-name.git` | Clone a repo |
| git remote -v | Check the current remote of a git project |
| git remote set-url origin `https://github.com/newusername/new-repo.git` | Change the remote to a new repo |
| git switch -c *branch-name* | Create and switch to a new branch |
| git switch main/*branch-name* | Switch to main branch or other branch |
| git merge *branch-name* | Merge branch into the current branch |
| git branch -d *branch-name* | (Optional) Delete branch |
| git push origin --delete *branch-name* | Delete branch from Github |

---

## Used console commands

| Command | Description |
|----------|----------|
| mkdir *foldername* | Creating a new folder |
| cd *foldername* | switching to folder |
| echo *text* > *file* | write a text into a file |
| echo *text* >> *file* | add a test to the end of a file |
