# Helpful Git Commands

Delete multiple local branches:
```
git branch -D branch-A branch-B
```

Reset branch to a particular commit:
(Assuming that your branch is called **branch-A** both here and remotely)
```
git reset --hard <commit-sha>
git push -f origin branch-A
```
