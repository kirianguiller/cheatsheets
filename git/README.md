# cheatsheets


## Revert a commit pushed online

1. get the commit hash number of the master you want to retrieve 
```
git log
```
```commit 8f937c683929b08379097828c8a04350b9b8e183
Merge: 8989ee0 7c6b236
Author: Ben James <ben@example.com>
Date:   Wed Aug 17 22:49:41 2011 +0100

Merge branch 'gh-pages'

Conflicts:
    README
```

2. revert to the merge last commit 
```
git revert 8989ee0 -m 1
```


## checkout remote branch : 
```
git checkout --track origin/branch_reactiveSentence
```


## Commit rebase
Commits rebasing can be useful for many things : 
- Keep a linear history of master by altering the branch before merging : https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase
- Aggregate many commits into one for keeping a more meaningful history : https://www.internalpointers.com/post/squash-commits-into-one-git


