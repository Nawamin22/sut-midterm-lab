git checkout main
git checkout -b issue-3
git add .
git commit -m “ui module equipment - close #3”
git remote update
git rebase origin/main
git checkout main
git merge issue-3 –no-ff
git push origin main
