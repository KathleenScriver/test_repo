# Git and Github


## Learning Goals

* Explain the difference between remote and local repositories
* Create a Git repository locally
* Create a repository on GitHub
* Link a local repository to a remote repository
* Use a branching workflow with Git and GitHub









# Warmup

Take a minute and jot down:
  - what you already know about Git/Github.
  - why do we use Git/Github?







## Overview

* Git is a version control system that we use in programming.

* GitHub is a website that allows us to share Git repositories.

* In order to keep our code safe we use a branching workflow that allows us to make changes to multiple files before fully committing to those changes.



## Commits
- Unstaged
- Staged
- Committed




### Important Git Commands

* git init - initialize a local git repository

* git symbolic-ref HEAD refs/heads/main (to switch the default of master to main)
**Do this at the beginning of your project**

* git commit -m "message describing functionality"

* git remote -v

* git checkout -b <name_of_branch>





## Git Workflow  

* Update our local repository
  - `git pull origin main`
* Create new branch to work on
  - `git checkout -b <name_of_branch>`
* Do work
  - git add
  - git commit
  - repeat
* Push local branch to remote repository
  - `git push origin <branch_name>`
* Go to github (remote repository) and make a Pull Request (PRs)
* Go back to machine and go back to main
  - `git checkout main`
* Updates local main with the changes from remote repo
  - 'git pull origin main'
