# EaseShop
EaseShop
# HTKG
航天科工服装定制项目(Personal Tailoring)   定制平台


1.clone

2.pod install --verbose --no-repo-update

3.git stauts          查看当前分支的修改状态

4.git branch lxf      建立一个分支“lxf”

5.git branch -a       查看本地和远程的分支list    ，常用的命令 git branch 等等

6.git checkout lxf    切换分支到“lxf”  

7.提交代码分两步：

第一步：git add .                       将当前目录下修改的所有代码从工作区添加到暂存区 . 代表当前目录
第二步：git commit -m"modify by gpp"    将缓存区内容添加到本地仓库
     ：git commit -a -m"mmodify by lxf"
第三步：git push origin lxf             将本地版本库推送到远程服务器
    
8.合并代码   

第一步切换到主干分支上来：git checkout master

第二步合并分支到主干：git merge lxf

第三步：git push 






# 提交代码步骤

## <提交代码到远程>

1.git status                    查看当前分支状态

2.git add .                     将当前目录下修改的所有代码从工作区添加到暂存区 . 代表当前目录

3.git commit -m "by lixuefei"   将缓存区内容添加到本地仓库

4.git push origin lixuefei      将本地lixuefei分支到远程lixuefei分支



## <合并代码>

5.git checkout master            切换到master主分支

6.git merge lixuefei             master分支合并lixuefei分支

7.git pull origin master         更新远程master主分支

8.git push origin master         提交本地分支到远程分支


## <git 其他命令>
git branch -D branch-name               删除本地分支

git branch -r -d origin/branch-name(git push origin :branch-name)     删除远程分支


##
# Cornerstone 忽略文件、文件夹
#### 拷贝以下代码  
#### 参考地址  https://blog.csdn.net/wenzfcsdn/article/details/80729781
*.o,*.lo,*.la,*.al,.libs,*.so,*.so.[0-9]*,*.pyc,*.pyo,*.rej,*~,#*#,.#*,.*.swp,.DS_Store,xcuserdata,*.xcuserdatad,.xcuserdatad,.xcuserstate,Pods,*.lock

# git中 忽略文件、文件夹
#### 拷贝以下代码  
#### 参考地址  https://blog.csdn.net/wenzfcsdn/article/details/82218140
*.xcuserstate
project.xcworkspace
xcuserdata
UserInterfaceState.xcuserstate
project.xcworkspace/
xcuserdata/
UserInterface.xcuserstate 


