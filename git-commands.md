# m122 - Git Commands

### Create new repository on command line
echo "# <name>" >> README.md
git init
git add README.md
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/<name>/<reponame>.git
git push -u origin main

### Push existing repository on command line
git remote add origin https://github.com/<name>/<reponame>.git
git branch -M main
git push -u origin main
  
