-[@kyledominick](https://github.com/kyledominick/)


cd planetAnimation/
code .
git checkout -b pA-240223
git status
git diff
git add . 
git commit -m "Notes"
git push origin pA-240223

git pull origin master
git checkout master
git merge pA-240223
git push -u origin master