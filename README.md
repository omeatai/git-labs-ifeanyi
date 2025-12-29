#INTRODUCTION

echo "# ifeanyi-test-2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/omeatai/ifeanyi-test-2.git
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

