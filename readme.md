#
git init
cd .git/
git add readme.txt
git commit -m "wrpte a readme file"
git status
git diff readme.txt
git reset --hard HEAD^将文件返回上一次保存的时候
git reset --pretty=oneline 文件号弄成一行方便查看
git checkout--readme.txt 撤销文件
git reset HEAD readme.txt 把添加到暂存区的文件取消进入暂存区然后再用上面的撤销文件