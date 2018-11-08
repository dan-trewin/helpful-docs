# Helpful Git Commands

Create new local branch and eventually push it to a new remote (with tracking):
```
git checkout -b branch-A
git push -u origin branch-A
```

Delete multiple local branches:
```
git branch -D branch-A branch-B
```

Reset branch to a particular commit
(Assuming that your branch is called **branch-A** both here and remotely):
```
git reset --hard <commit-sha>
git push -f origin branch-A
```
