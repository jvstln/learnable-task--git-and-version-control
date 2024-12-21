# Learnable: Task 2 - Git and Version Control

## What is version control?

Version control is the process of managing and tracking changes made to a set of files over time

## Difference between Git and Github

- Git is a version control system or a software that you install _locally_ which tracks changes made to a set of files and folders

- Github is a _web-based online platform_ that provides hosting for git-tracked files/repositories. It also makes collaborations and contributions to a project possible

## 3 Github Alternatives

1. GitLab
2. Bitbucket
3. Codeberg

## Difference between `git fetch` and `git pull`,

- `git fetch` downloads new branches and commits from a remote repository

- `git pull` downloads new branches and commits from a remote repository _and immdeiately merges the downloaded branches to your current working branch_

## Explain in simple terms `git rebase` and the command for it

`git rebase` is a command _similar to `git merge`_ that lets you rewrite the commit history of a branch. It takes the commits of one branch and place it on top of another branch, creating a linear, commit history.

## Explain in simple terms `git cherry-pick` and the command for it

`git cherry-pick` is similar to git rebase but allows you to pick _specific commits_ from a branch. It copies those picked commits unto the current working branch
