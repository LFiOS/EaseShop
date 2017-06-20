# EaseShop
EaseShop
# HTKG
航天科工服装定制项目(Personal Tailoring)   定制平台


1.clone

2.pod install --verbose --no-repo-update

3.git stauts   查看当前分支的修改状态

4.git branch lxf  建立一个分支“lxf”

5.git branch -a  查看本地和远程的分支list    ，常用的命令 git branch 等等

6.git checkout lxf   切换分支到“lxf”  

7.提交代码分两步：

第一步：git commit -m"modify by gpp"  or  git commit -a -m"mmodify by lxf"  
第二步：git push origin lxf
    
8.合并代码   

第一步切换到主干分支上来：git checkout master

第二步合并分支到主干：git merge lxf

第三步：git push






# 提交代码步骤
1.git status                    查看当前分支状态

2.git add .                     添加修改的文件

3.git commit -m "by lixuefei"   提交修改的文件

4.git push origin lixuefei      提交本地lixuefei分支到远程lixuefei分支


5.git checkout master            切换到master主分支

6.git merge lixuefei             master分支合并lixuefei分支

7.git pull origin master         更新远程master主分支

8.git push                       提交本地分支到远程分支
