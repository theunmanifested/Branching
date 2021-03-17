## Git Branching Cheat Sheet

### Basic git Commands
* `git init` - initialize working directory with git repository
* `git status` - show status of working directory/repository
* `git add .` - stage changes for commit
* `git commit -m "message"` - commit staged changes to local repository
* `git log` - lists commit
* `git log --oneline` - lists commits in compact format
`git config --list` -  list current git configuration
### Remote Commands
* `git pull origin main` - Pull remote branch `main` into current local branch
* `git push origin main` - Push local commits to remote repository

### Branching Commands
* `git branch -M newName` - Rename current branch to `newName`
* `git branch newBranch` - checkout a branch
* `git branch` - list local branches, indicating current branch
* `git checkout newBranch` - Make `newBranch` the current branch
* `git checkout -b otherBranch` - Create and checkout `otherBranch`
