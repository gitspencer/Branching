# Git Cheat Sheet

## Basic Commands
* 'git init' - initialize local repo
* 'git add .' - add (stage) current working folder contents to local repo index
* 'git commit -m "Message" - commit staged work to local repo, with commit message

## Info Commands
* 'git status' - show commit status of local working folder
* 'git log' - list commit history of local repo
* 'git log --oneline' - list commit history (compact format)

## Branch Commands
* 'git branch' - list local branches
* 'git branch -m newName' - rename current local branch

## Remote Commands
* 'git remote add remName remoteUrl' - connect local repo to remote repository 'remoteUrl' with shortcut 'remName' for the remote URL
* 'git push remName branchName' - push local commits to remote branch