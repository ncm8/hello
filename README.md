echo "# hello" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ncm8/hello.git
git push -u origin main

git config --global user.name "Noel Moore"
git config --global user.email ncm84@case.edu
