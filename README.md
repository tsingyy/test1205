# test1205

#�����ֿ�
  git init test
#����Ŀ¼
cd test
#�½�һ������123���ݷ��a.txt�ļ�
echo "123">a.txt
#git add
  git add a.txt
   //����a.txt���hashֵ�����ļ������ݴ����index������blob�����ļ�
#�ύ
git commit -m "�½�a.txt"
   ��//����Ŀ¼��hashֵ������tree���ͺ�commit���͵�git����
#��ʾlog
git log --oneline

git log --oneline --all

git log --oneline --alll --decorate

git log --oneline --all --decorate --graph
ͼ�λ���ʾ��ʷ
#���logg���������һ�����������������ʱ��ֻ��logg����
 git config alias.logg "log --oneline --all --decorate --graph"
#�������룬����Ƿ񻹻�����쳣
����������ŶŶŶŶŶŶŶŶŶ
������������ÿ��Ĺ���
#git log����̫��ʱ��Ӣ��״̬������Q�������˳�
����
#�½�һ������123��a.txt�ļ�

