# test1205

#´´½¨²Ö¿â
  git init test
#½øÈëÄ¿Â¼
cd test
#ĞÂ½¨Ò»¸ö°°üº¬123ÄÚÈİ¶µÄa.txtÎÄ¼ş
echo "123">a.txt
#git add
  git add a.txt
   //¼ÆËãa.txtµÎÄ¼şµÄhashÖµ£¬½½«ÎÄ¼ş·ÅÈëÔİ´æÇø£index£¬Éú³ÉblobÀàĞÍÎÄ¼ş
#Ìá½»
git commit -m "ĞÂ½¨a.txt"
   ¡¡¡//¼ÆËãÄ¿Â¼µÄhashÖµ£¬Éú³ÉtreeÀàĞÍºÍcommitÀàĞÍµÄgit¶ÔÏó
#ÏÔÊ¾log
git log --oneline
git log --oneline --all
git log --oneline --alll --decorate
git log --oneline --all --decorate --graph
Í¼ĞÎ»¯ÏÔÊ¾ÀúÊ·
#Ã½«ÃüÁîÃüÃû¼ò»¯
 git config alias.logg "log --oneline --all --decorate --graph"

