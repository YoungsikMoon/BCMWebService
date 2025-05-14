…or create a new repository on the command line
echo "# BCMWebService" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/YoungsikMoon/BCMWebService.git
git push -u origin main


…or push an existing repository from the command line
git remote add origin https://github.com/YoungsikMoon/BCMWebService.git
git branch -M main
git push -u origin main


git config --global i18n.commit.encoding utf-8