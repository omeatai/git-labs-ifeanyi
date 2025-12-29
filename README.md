# INTRODUCTION

## Write Text to README.md File
- [ ] echo "# git-labs-ifeanyi" >> README.md

## Commit README.md File
- [ ] git init
- [ ] git add README.md
- [ ] git commit -m "first commit"

## Set remote Path
- [ ] git branch -M main
- [ ] git remote remove origin
- [ ] git remote add origin https://github.com/omeatai/git-labs-ifeanyi.git

## Push Local to Remote
- [ ] git push -u origin main

## List git Local Braches
- [ ] git branch

## List git Remote Branches
- [ ] git branch -r

## Create git Branch and Switch to Branch
```bs
git branch first-branch
git checkout first-branch
```

- [ ] git checkout -b "first-branch"

## Delete File from Remote Repo
git rm --cached ./app/rough.txt
git add .
git commit -m "Removed rough.txt"
git push origin first-branch
git push origin -d "first-branch"
git checkout main
git branch -D "first-branch"


# GIT-LABS-IFEANYI

GIT-LABS-IFEANYI

<details>
  <summary>Check Git Version</summary>

```sh
git -v
```

</details>

<details>
  <summary>Git Configuration</summary>

### To setup git global settings:

```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### To view git settings:

```sh
git config --global --list
```

```sh
git config --list --show-origin
```

</details>

<details>
  <summary>Basic Git Commands</summary>

### Git Init

```sh
git init
git status
```

### Git Add (Untracked to Staged)

```sh
git add {Filename}
git add -A
git add .
```

### Git Restore (Staged to Untracked)

```sh
git restore {Filename}
git restore --staged {Filename}
```

### Git Commit (Staged to Tracked)

```sh
git commit -m "{commit Message}"
git commit -am "{commit Message}"
```

### Git Log History

```sh
git log
git log --oneline
```

### Git Push

```sh
git push
```

</details>

