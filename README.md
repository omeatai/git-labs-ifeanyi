# INTRODUCTION

## Write Text to README.md File
- [ ] echo "# ifeanyi-test-2" >> README.md

## Commit README.md File
- [ ] git init
- [ ] git add README.md
- [ ] git commit -m "first commit"

## Set remote Path
git branch -M main
git remote add origin https://github.com/omeatai/ifeanyi-test-2.git

## Push Local to Remote
git push -u origin main

git branch
git branch -r
git checkout -b "first-branch"
git rm --cached ./app/rough.txt
git add .
git commit -m "Removed rough.txt"
git push origin first-branch
git push origin -d "first-branch"
git checkout main
git branch -D "first-branch"

