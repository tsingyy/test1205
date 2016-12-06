git ²Ù×÷
echo "# test" >> A.md
#´´½¨²Ö¿â
git init
#Ìí¼ÓA.mdÎÄ¼ş
git add A.md
#Ìá½»²¢Ìí¼ÓÃèÊö
git commit -m "first commit"
#Á¬½ÓÔ¶³Ì²Ö¿âÔ
git remote add origin https://github.com/tsingyy/test1205.git
#push
git push -u origin master

»ñÈ¡×´Ì¬£º
git status

#VI±à¼­
Press Insert button to edit the md file;
Press ESC button to exit the edit;
:wq means save and quit
:q! quit but not save

#²é¿´ÊÇ·ñÁ¬½ÓÉÏÔ¶³Ì²Ö¿â
git remote -v
#ÒÆ³ıÖ®Ç°µÄÔ¶³Ì²Ö¿â
git remote rm origin

