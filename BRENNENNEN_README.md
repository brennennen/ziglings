# Brennennen Zigling solutions
Forked from https://codeberg.org/ziglings/exercises

## Repo Admin Notes
Forked ziglings with a 2 branch setup. 
* `main` is intended to be kept as a clean fork of `ziglings`.
* `brennennen_solutions` is main + this file + solutions to the exercises.

### Update Notes
```
git checkout main
git pull
git checkout brennennen_solutions
git rebase main
```

### Common Diagnostic Commands
```
git remote show             # list all remote connected git repos (should just be "upstream" and "origin"). origin: my github forked repo, upstream: original ziglings repo.
git remote show upstream    # show original zigling upstream repo
git remote show origin      # show my github forked repo
```

### Original Setup Notes
```
git remote add upstream https://codeberg.org/ziglings/exercises.git
git pull upstream main
git push origin main
```
