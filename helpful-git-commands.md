# Helpful Git Commands

Create a new local branch and eventually push it to a new remote branch (with tracking):
```
git checkout -b <branch-A>
git push -u origin <branch-A>
```

Delete multiple local branches:
```
git branch -D <branch-A> <branch-B>
```

Reset branch locally and remotely to a particular commit
(assuming that your branch has the same name locally and remotely):
```
git reset --hard <commit-sha>
git push -f origin <branch-A>
```
