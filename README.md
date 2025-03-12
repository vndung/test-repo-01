npx semantic-release --no-ci
git add .\ngit commit -m "fix: update log message"\ngit push origin main
npx semantic-release --no-ci
git commit -m "featbig change"
git add .
git push origin main
git log --oneline
npx semantic-release --no-ci
git log --oneline
git tag -l
git add .
git commit -m "feat: change 2\n\nBREAKING CHANGE: change 222"
git push
npx semantic-release --no-ci
