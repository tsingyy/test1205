git 操作
echo "# test" >> A.md
#创建仓库
git init
#添加A.md文件
git add A.md
#提交并添加描述
git commit -m "first commit"
#连接远程仓库�
git remote add origin https://github.com/tsingyy/test1205.git
#push
git push -u origin master

获取状态：
git status

#VI编辑
Press Insert button to edit the md file;
Press ESC button to exit the edit;
:wq means save and quit
:q! quit but not save

#查看是否连接上远程仓库
git remote -v
#移除之前的远程仓库
git remote rm origin

#branch 分支操作
新建分支：
git branch [branch name]
切换到分支
git checkout [branch name]

对文件做修改
vim git-to.md
保存修改之后提交
git commit -a -m 'do same changes-111'
切回分支master
git checkout master

