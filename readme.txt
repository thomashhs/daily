20190925
参考网址：https://www.liaoxuefeng.com/wiki/896043488029600/898732792973664
（一）Git操作
git init
初始化操作

git add readme.txt
添加文件至仓库

git commit -m "wrote a readme file"
提交文件至仓库并备注

git status
查看当前仓库状态

git diff readme.txt
比较文件差异

git log
查看历史记录

git reset --hard “HEAD^”（Head~1）（commit id 开头）
回退至历史版本

git reflog
查看命令历史，回退到未来版本

git checkout -- readme.txt
丢弃工作区的修改
让该文件回到最近一次git commit或git add时的状态

git reset HEAD <file>
文件add未commit
暂存区的修改撤销掉（unstage），重新放回工作区

（二）远程仓库操作命令
git remote add origin git@github.com:thomashhs/daily.git
git push -u origin master
第一次关联推送

git push origin master
本地做修改后推送至github

git clone git@github.com:thomashhs/daily.git
从远程库clone至本地

git pull origin master
从远程库拉回到本地

20190926
参考网址：https://www.zmrenwu.com/courses/django-blog-tutorial/materials/1/
Django博客教程回顾

django-admin startproject blogproject
创建django项目

blogproject/blogproject/settings.py
LANGUAGE_CODE = 'zh-hans'
TIME_ZONE = 'Asia/Shanghai'
修改django文字和时区

python manage.py startapp blog
创建django应用

blogproject/blogproject/settings.py
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'blog', # 注册 blog 应用
]
创建应用后如需要使用需要在INSTALLED_APPS中添加

创建数据库模型步骤：
1、设计数据库表结构
2、在models.py中增加Class继承models.Model
3、在Class中定义数据库字段
4、迁移数据库
(1)python manage.py makemigrations
(2)python manage.py migrate

20190928
1、全部完成Django博客基本教程内容；
2、在博客中加入注册、登录流程；
3、下一步需要区分已登录用户和未登录用户；

20190929
1、舍弃原始注册登录流程，改用all-auth模块快速搭建；
参考网址：https://www.cnblogs.com/crime/p/11025823.html



