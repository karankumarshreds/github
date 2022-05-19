# github cheat sheet

## list all the commits on the branch 

```sh
git log --no-merges master..
```

## list all the files added to the branch (not pushed)

```sh
git diff --cached --name-only
```
