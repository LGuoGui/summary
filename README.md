# Git 学习
## 什么是Git
Git是目前世界上最先进的分布式版本控制系统（没有之一）
## Git 的下载
[Git官方下载网址](https://git-scm.com/download)
## 如何使用Git
1.按照完成Git后，右键点击桌面->找到"Git Base Here".如果显示小黑框就证明安装成功

2.配置你的信息

$ git config --global user.name "Your Name"  
$ git config --global user.email "email@example.com"  
$ git config --global（所有的Git仓库都会使用这个配置）

3.Git简单指令

$mkdir 文件名 （创建文件名）  
$cd 文件名（进入该文件）  
$pwd（显示当前目录）  
$git init （将该目录变成Git可以管理的仓库）  
$git clone 项目地址（可以将GitHub的仓库克隆到该文件中）  
$git add 项目名 （将修改过的项目放到暂存区）  
$git commit -m'解释内容' （将暂存区的文件上传到本地仓库）  
$git push （将本地仓库的文件上传到GitHub）  
$git reset （清除缓存区的所有文件）  
$ git rm -r --cached target   （删除指定文件夹）  
$git ls-files （查看暂存区的所有文件）  

4.Git工作区和暂存区的区别

电脑里面能看到的目录是一个工作区，而里面有个隐藏项目.git，不算工作区，而是Git的版本库。
版本库中有一个重要的东西叫做暂存区。  
当我们$git add文件名 时，该文件并不会直接放到仓库中，而是先放到暂存区。我们可以用$git ls-files
指令来查看暂存区的文件。  
要想将文件上传到仓库中，要继续使用$git commit -m'解释内容'。才能上传到本地仓库中去。

# GitHub学习

## 什么是GitHUb

github是一个基于git的代码托管平台，付费用户可以建私人仓库，我们一般的免费用户只能使用公共仓库，也就是代码要公开。
可以创建Repository，存储我们的代码。。

# Git和GitHub配合使用

1.$git clone 项目地址（可以将GitHub的仓库克隆到该文件中）  
2.$git add 项目名 （将修改过的项目放到暂存区）  
3.$git commit -m'解释内容' （将暂存区的文件上传到本地仓库）  
4.$git push （将本地仓库的文件上传到GitHub）


