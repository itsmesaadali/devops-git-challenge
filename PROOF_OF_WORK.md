# Proof of Work — DevOps Git Challenge

## 1. Git Commit History

The complete Git commit history is shown below.

c1da342 (HEAD -> main, origin/main) Merge pull request #1 from itsmesaadali/development
7428660 (origin/development, development) fix: resolved merge conflict
65a53c0 (origin/staging, staging) fix: staging label
6cf2100 feat: updated script with staging env
d4042b7 feat: initial commit with deploy script


## 2. Reflection Questions

### Q1: Difference between Git and GitHub

Git is a distributed version control system that tracks changes to files on my local computer. It allows developers to create commits, branches, and merge changes. GitHub is an online platform that hosts Git repositories in the cloud. It also supports collaboration through Pull Requests, code reviews, and remote repository management.

### Q2: Explain the three architecture stages

The Working Directory contains the files I am currently creating or editing. The Staging Area contains the changes selected for the next commit using `git add`. The Local Repository stores committed snapshots of the project and its history. These three stages help me manage changes before saving them permanently in Git history.

### Q3: Difference between git stash pop and git stash apply

The `git stash pop` command restores stashed changes and normally removes the restored entry from the stash list. The `git stash apply` command restores the changes but keeps the stash entry. Both commands are useful when temporarily saving unfinished work. I can use `git stash apply` if I want to restore the same saved changes again later.

### Q4: Difference between git fetch and git pull

The `git fetch` command downloads new information from a remote repository without merging it into my current branch. The `git pull` command downloads remote changes and integrates them into the current branch, usually through a merge or rebase depending on the configuration. Fetching lets me inspect changes before integrating them. Pulling is useful when I want to update my local branch with the latest remote changes.
c1da342 Merge pull request #1 from itsmesaadali/development
7428660 fix: resolved merge conflict
65a53c0 fix: staging label
6cf2100 feat: updated script with staging env
d4042b7 feat: initial commit with deploy script
