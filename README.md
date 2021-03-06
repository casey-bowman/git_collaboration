# git_collaboration
Git collaboration notes (O'Reilly live online training)

- `git clone <url>` : downloads the repository from the web to your local computer

## Display information

- `git log --oneline --all --graph --decorate` : displays commits

- `git status` : displays status of staging and changes

- `git diff` : display differences

## Branches

- `git branch <branch_name>` : creates a new branch where HEAD is

- `git switch <branch_name>` : move to branch

- `git checkout -b <branch_name>` : create a new branch and move to it

- `git branch -a` : lists branches local and remote

- `git push <remote-location> <branch>` : pushes branch to remote repository

- `git push -u <remote-location> <branch>` : establishes default for `git push`

- `git fetch --prune` : removes references to remote branches that have been deleted from remote repository

- `git branch -d <branch>` : deletes local branch

- `git stash` :

- `git stash list` :

- `git stash apply` :
