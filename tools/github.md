# Deploy Command 
git pull
git status
git add .
git commit -m "Your Messages"
git push origin main

# AKA gh-pages branch
git branch --set-upstream-to=origin/gh-pages gh-pages
git push --all