git ����
echo "# test" >> A.md
#�����ֿ�
git init
#���A.md�ļ�
git add A.md
#�ύ���������
git commit -m "first commit"
#����Զ�ֿ̲��
git remote add origin https://github.com/tsingyy/test1205.git
#push
git push -u origin master

��ȡ״̬��
git status

#VI�༭
Press Insert button to edit the md file;
Press ESC button to exit the edit;
:wq means save and quit
:q! quit but not save

#�鿴�Ƿ�������Զ�ֿ̲�
git remote -v
#�Ƴ�֮ǰ��Զ�ֿ̲�
git remote rm origin

