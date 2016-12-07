# test1205

#创建仓库
  git init test
#进入目录
cd test
#新建一个包含123内容的a.txt文件
echo "123">a.txt
#git add
  git add a.txt
   //计算a.txt文件hash值，将文件放入暂存区index，生成blob类型文件
#提交
git commit -m "新建a.txt"
   　//计算目录的hash值，生成tree类型和commit类型的git对象
#显示log
git log --oneline

git log --oneline --all

git log --oneline --alll --decorate

git log --oneline --all --decorate --graph
图形化显示历史
#糜改名：利用logg代替那一长串命令，后续操作的时候只用logg即可
 git config alias.logg "log --oneline --all --decorate --graph"
#git log内容太多时，英文状态下输入Q，即可退出

#分支操作
git branch br
git checkout br
等同于git checkout -b br
#新建分支并切换至此分支

#显示所有分支
git branch

#基于master创建一个新的分支，遣⑶谢恢链朔种�
git checkout -b b master //一个基于master的b分支

#显示暂存区的内容
git ls-file -s

#显示commit对象的内容
git ls-tree [hash值]或[分支名]





