# Git 命令学习


```git
git init 初始化本地仓库
git add file_name 添加到暂存区
git commit -m "" 提交到本地仓库

git status 当前分支的状态

git relog 查看精简版本信息
git log 查看详细版本信息

git reset --hard 版本号 # 版本回溯


分支
git branch name 创建分支
git branch -V  查看分支
git checkout branch_name 切换分支
git branch -m new_name 修改分支名字
git merge branch_name 合并分支

给远程库起一个别名
git remote add origin https://github.com/zzzppcc/git.git 起别名
git remote -v 查看别名

远程协作开发
git clone 地址 # （1）拉取代码 （2）初始化本地库 （3） 创建别名 可以用 git remote -v 查看
git pull origin master
git push -u origin master # 第一次带上-u参数
git remote add origin
git init 初始化本地仓库
git add file_name 添加到暂存区
git commit -m "" 提交到本地仓库

git status 当前分支的状态

git relog 查看精简版本信息
git log 查看详细版本信息

git reset --hard 版本号 # 版本回溯


分支
git branch name 创建分支
git branch -V  查看分支
git checkout branch_name 切换分支
git branch -m new_name 修改分支名字
git merge branch_name 合并分支

给远程库起一个别名
git remote add origin https://github.com/zzzppcc/git.git 起别名
git remote -v 查看别名

远程协作开发
git clone 地址 # （1）拉取代码 （2）初始化本地库 （3） 创建别名 可以用 git remote -v 查看
git pull origin master
git push -u origin master # 第一次带上-u参数
git remote add origin


ssh 免密登录
ssh -keygen -t rsa -C 1192472939@qq.com



```

