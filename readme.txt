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

git clone git@github.com:thomashhs/daily.git
��Զ�̿�clone������

git pull origin master
��Զ�̿����ص�����

20190926
�ο���ַ��https://www.zmrenwu.com/courses/django-blog-tutorial/materials/1/
Django���ͽ̳̻ع�

django-admin startproject blogproject
����django��Ŀ

blogproject/blogproject/settings.py
LANGUAGE_CODE = 'zh-hans'
TIME_ZONE = 'Asia/Shanghai'
�޸�django���ֺ�ʱ��

python manage.py startapp blog
����djangoӦ��

blogproject/blogproject/settings.py
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'blog', # ע�� blog Ӧ��
]
����Ӧ�ú�����Ҫʹ����Ҫ��INSTALLED_APPS�����

�������ݿ�ģ�Ͳ��裺
1��������ݿ��ṹ
2����models.py������Class�̳�models.Model
3����Class�ж������ݿ��ֶ�
4��Ǩ�����ݿ�
(1)python manage.py makemigrations
(2)python manage.py migrate

20190928
1��ȫ�����Django���ͻ����̳����ݣ�
2���ڲ����м���ע�ᡢ��¼���̣�
3����һ����Ҫ�����ѵ�¼�û���δ��¼�û���

20190929
1������ԭʼע���¼���̣�����all-authģ����ٴ��
�ο���ַ��https://www.cnblogs.com/crime/p/11025823.html



