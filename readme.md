# My Git Cheatsheet

## Creating a Git Reppo

In the folder you want to create a repo, do the following command in terminal

```
git init
```

**Always check that you are not already in a repo by using**

---

## Adding Files to Staging

Staging is files that are being tracked to be committed.

Use git to see which files are untracked (red) or in staging (green)
```
git status
```

Three ways to add files to staging

- add one file at a time `git add <filename>`
- add all files in repo `git add -A`
- add all files in my current folder `git add .`

---

## Committing Files to Our Repo

```
git commit -m "some descriptive text"
```
**If you forget the -m, you will end up in vim, to exit type `:wq`**
