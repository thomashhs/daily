20190925
�ο���ַ��https://www.liaoxuefeng.com/wiki/896043488029600/898732792973664
��һ��Git����
git init
��ʼ������

git add readme.txt
����ļ����ֿ�

git commit -m "wrote a readme file"
�ύ�ļ����ֿⲢ��ע

git status
�鿴��ǰ�ֿ�״̬

git diff readme.txt
�Ƚ��ļ�����

git log
�鿴��ʷ��¼

git reset --hard ��HEAD^����Head~1����commit id ��ͷ��
��������ʷ�汾

git reflog
�鿴������ʷ�����˵�δ���汾

git checkout -- readme.txt
�������������޸�
�ø��ļ��ص����һ��git commit��git addʱ��״̬

git reset HEAD <file>
�ļ�addδcommit
�ݴ������޸ĳ�������unstage�������·Żع�����

������Զ�ֿ̲��������
git remote add origin git@github.com:thomashhs/daily.git
git push -u origin master
��һ�ι�������

git push origin master
�������޸ĺ�������github