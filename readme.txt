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