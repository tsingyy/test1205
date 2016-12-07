# test1205

#´´½¨²Ö¿â
  git init test
#½øÈëÄ¿Â¼
cd test
#ĞÂ½¨Ò»¸ö°üº¬123ÄÚÈİµÄa.txtÎÄ¼ş
echo "123">a.txt
#git add
  git add a.txt
   //¼ÆËãa.txtÎÄ¼şhashÖµ£¬½«ÎÄ¼ş·ÅÈëÔİ´æÇøindex£¬Éú³ÉblobÀàĞÍÎÄ¼ş
#Ìá½»
git commit -m "ĞÂ½¨a.txt"
   ¡¡//¼ÆËãÄ¿Â¼µÄhashÖµ£¬Éú³ÉtreeÀàĞÍºÍcommitÀàĞÍµÄgit¶ÔÏó
#ÏÔÊ¾log
git log --oneline

git log --oneline --all

git log --oneline --alll --decorate

git log --oneline --all --decorate --graph
Í¼ĞÎ»¯ÏÔÊ¾ÀúÊ·
#ÃÓ¸ÄÃû£ºÀûÓÃlogg´úÌæÄÇÒ»³¤´®ÃüÁî£¬ºóĞø²Ù×÷µÄÊ±ºòÖ»ÓÃlogg¼´¿É
 git config alias.logg "log --oneline --all --decorate --graph"
#git logÄÚÈİÌ«¶àÊ±£¬Ó¢ÎÄ×´Ì¬ÏÂÊäÈëQ£¬¼´¿ÉÍË³ö

#·ÖÖ§²Ù×÷
git branch br
git checkout br
µÈÍ¬ÓÚgit checkout -b br
#ĞÂ½¨·ÖÖ§²¢ÇĞ»»ÖÁ´Ë·ÖÖ§

#ÏÔÊ¾ËùÓĞ·ÖÖ§
git branch

#»ùÓÚmaster´´½¨Ò»¸öĞÂµÄ·ÖÖ§£¬Ç²¢ÇĞ»»ÖÁ´Ë·ÖÖ§
git checkout -b b master //Ò»¸ö»ùÓÚmasterµÄb·ÖÖ§

#ÏÔÊ¾Ôİ´æÇøµÄÄÚÈİ
git ls-file -s

#ÏÔÊ¾commit¶ÔÏóµÄÄÚÈİ
git ls-tree [hashÖµ]»ò[·ÖÖ§Ãû]





