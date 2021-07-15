## Git Cheat Sheet

* `git init` - Initialize a local git repo in working directory.
* `git status` - Show state of local repo
* `git log` - List commit history
* `git log --oneline` - Compact commit history

### Branching
* `git branch` - list local branches
* `git branch newBranch` - create local branch
* `git checkout newBranch` - loads into new branch
<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
* `git checkout -b *name of new branch*` - created and checks out new branch
=======
* `git checkout -b *name of new branch*` - created and checks out new branch 
>>>>>>> dd274873bc2b868c617b1dd0661b694ef717bc08
=======
* `git checkout -b *name of new branch*` - created and checks out new branch
>>>>>>> 2f9a8a1a9f424ecb45a736c5f1002fc26fd3a09a
=======

* `git checkout -b *name of new branch*` - created and checks out new branch.
* `git diff sha` -Show diffs between current commit and commit id `sha`
* `git diff oneBranch otherBranch` - Show diffs between `oneBranch` and `otherBranch`

### Remote Repos
* `git remote add alias url` - add `alias` as name for remote repo `url` in project configuration
* `git push alias aBranch` - push local commits to remote repo `alias`'s branch `aBranch`
* `git pull alias aBranch` - pull remote `aBranch` from `alias` into current local branches
>>>>>>> cc28d5d774ac5c9177e64c6a5f655b7c0d628259
