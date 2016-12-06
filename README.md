# test1205

#创建仓库
  git init test
#进入目录
cd test
#新建一个包含123内容返腶.txt文件
echo "123">a.txt
#git add
  git add a.txt
   //计算a.txt档膆ash值，将文件放入暂存区ndex，生成blob类型文件
#提交
git commit -m "新建a.txt"
   　//计算目录的hash值，生成tree类型和commit类型的git对象
#显示log
git log --oneline

git log --oneline --all

git log --oneline --alll --decorate

git log --oneline --all --decorate --graph
图形化显示历史
#糜胠ogg命令代替那一长串命令，后续操作的时候只用logg即可
 git config alias.logg "log --oneline --all --decorate --graph"
#中文输入，检查是否还会存在异常
啊啊啊啊啊哦哦哦哦哦哦哦哦哦
嗯嗯嗯嗯嗯嗯每天的工作
#git log内容太多时，英文状态下输入Q，即可退出
操作
#新建一个包含123的a.txt文件

