Git is a version control system.
Git is free software.

git config --global user.name "djmdai84"
git config --global user.email "261837197@qq.com"

cd /d/bigdata/gitcode
git init
ls -ah


git add readme.txt

git commit -m "wrote a readme file"

文档测试 

git diff readme.txt


haha

git log --pretty=oneline

git reset --hard HEAD^

git reset --hard d5e1379


git diff readme.txt

继续测试 

git add test.txt

git commit --m "添加文件"

rm test.txt

git checkout -- test.txt
git rm test.txt

ssh-keygen -t rsa -C "261837197@qq.com"

git remote add origin git@github.com:djmdai84/learngit.git

git push origin master

test a a a a a 