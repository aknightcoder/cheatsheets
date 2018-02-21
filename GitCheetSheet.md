# Git Cheatsheet

## Show local branches

-> git branch

## Show remote branches

-> git branch -r


## Show local and remote branches

-> git branch -a


## Update remote branch list

-> git fetch


## Create a new branch

git checkout -b <branch name>


## Switch to a branch:

-> git checkout <branch name>


## Create remote tracking branch

-> git push -u origin <branch name>


## Delete remote branch:

As of Git v1.7.0, you can delete a remote branch using
git push origin --delete <branch name>


## Show remote tracking info:

-> git branch -vv


## Show current status of branch

-> git status


## Revert all modified files (nuclear option):

-> git reset --hard


## Revert changes to a specific file:

-> git checkout <filepath>/<filename>


## Remove file from repo:

Use git rm:
git rm <filename>.txt
git commit -m "Remove <filename>.txt"

But if you want to remove the file only from the Git repository and not remove it from the filesystem, use: 
git rm --cached file1.txt

## Clone repository:

git clone "<url>.git"
















