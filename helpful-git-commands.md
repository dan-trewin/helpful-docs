# Helpful Git Commands

Create a new local branch and eventually push it to a new remote branch (with tracking):
```
git checkout -b <branch-A>
git push -u origin <branch-A>
```

Delete multiple local branches:
```
git branch -D <branch-A> <branch-B> <brach-C>
```

Reset branch locally and remotely to a particular commit
(assuming that your branch has the same name locally and remotely):
```
git reset --hard <commit-sha>
git push -f origin <branch-A>
```

Untrack files already added to git repository based on .gitignore
(before proceeding, make sure all your changes are committed, including your .gitignore file):
```
git rm -r --cached .
git add -A
```

Clone a repo with submodules making sure to fetch them all:
```
git clone <repo>
git submodule update --init --recursive
```

Cherry pick (adds a single commit from another branch to current branch):
```
git cherry-pick <commit-sha>
```
