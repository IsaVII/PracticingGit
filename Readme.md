# Practicing Git-GitHub 


## Used Git commands

| Command | Description |
|----------|----------|
| git init | Initialize git in the current folder |
| git status | See changed files |
| git add . | Stage all current changes |
| git commit -m "*comment*" | Commit all staged changes to git -> stage is empty afterwards |
| git commit -am "*comment*" | Stage and commit all files that are already being tracked in one go |
| git branch -M main | Renames current branch into **main** |
| git remote add origin `https://github.com/username/repo-name` | Connects git with a repo on GitHub |
| git push -u origin main | Pushed to main-branch |
| git push | Push after git push -u origin main was done once |
| git log | Show full comment history: author, date, message, hash (press **Q** to quit back to terminal) |
| git log --oneline | Comment history: one line per commit - easier to read |
| git stash push -- *file* | Stashes changes in *file* |
| git diff *file* | See differences between local file and staged file-version |
| git restore -- staged *filename* | Removed file from staged without changing local version |


---

## Used console commands

| Command | Description |
|----------|----------|
| mkdir *foldername* | Creating a new folder |
| cd *foldername* | switching to folder |
| echo *text* > *file* | write a text into a file |
| echo *text* >> *file* | add a test to the end of a file |
