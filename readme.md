#
git init
cd .git/
git add readme.txt
git commit -m "wrpte a readme file"
git status
git diff readme.txt
git reset --hard HEAD^将文件返回上一次保存的时候
git reset --pretty=oneline 文件号弄成一行方便查看