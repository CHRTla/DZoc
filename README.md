# Git instruction

## Basic Commands

* git init - initialize git repository on local machine
* git status - show status of files in git working directory (ready to add, existence of some changes in files, etc.)
* git add - add some (by passing filename as an argument) or all (using wildcard as an argument) files for git to be ready for commit
* git commit -m "some text here" - persist changes to git log
* git diff - show changes between git working directory and last commited changes
* git checkout -b branch_name - create new branch (-b argument) and checkout on this branch immediately, or just checkout (without -b argument)

## Commands to work with remote repository

* git clone - clone remote repository
* git remote add origin link_to_remote_repository - use it when you already have local repository and want to link it with remote
* git push -u origin branch_name - set upstream branch in remote repository to link your local branch with remote (use it just for the first time to link your new one branch, then you can use just git push)
* git push - push local commits to remote repository
* git pull - fetch and merge remote changes to local repository
