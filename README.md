# test1205

#创建仓库
  git init test
#进入目录
cd test
#新建一个鞍�123内容兜腶.txt文件
echo "123">a.txt
#git add
  git add a.txt
   //计算a.txt滴募膆ash值，浇募湃朐荽媲index，生成blob类型文件
#提交
git commit -m "新建a.txt"
   　�//计算目录的hash值，生成tree类型和commit类型的git对象
#显示log
git log --oneline
git log --oneline --all
git log --oneline --alll --decorate
git log --oneline --all --decorate --graph
图形化显示历史
#媒蠲蚧�
 git config alias.logg "log --oneline --all --decorate --graph"

