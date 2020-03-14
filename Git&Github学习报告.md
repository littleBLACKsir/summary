#  第1周学习报告

`@邓家祺`

`@2020223`
### 此为二次修改版本，之前写的太~~low~~

[学习内容1](#1) | [学习内容2](#2) | [学习内容3](#3) .....

# <a id='1'>学习内容1</a>

学习廖雪峰的git和GitHub教程

[廖老师的教程](https://www.liaoxuefeng.com/wiki/896043488029600)



学习了一些git常用的指令-->



## 配置账户信息

git config user.name 

git config user.email 

git config --global user.name "name" 

git config --global user.email "email" 

git config --list 

## 生成ssh key

ssh-keygen  -t  rsa  -C  "mail" 

cat ~/.ssh/id_rsa.pub 

## 复制repo

 git clone <link> 

## 创建分支

git checkout -b branch // Create a new branch
git branch  // Check local branch
git branch -v // Check all local branch and the head information
git branch -vv // Check all local branch and upstream branch
git branch -a  // Check all branch
git branch -av  // Check all branch  and the head information

## 删除分支

git branch –m oldbranch newbranch  // Modify branch 

git branch –D branch  // Delete local branch 

## commit操作

git status  // Check git tree, what changed currently
git log  // Check the commit history
git diff  // Check changed files
git patch > patch.diff  // Create a patch
patch -p1 <patch.diff  // Patch on branch

## 以上来自[CSDN]( https://blog.csdn.net/yunxiang_cheng/article/details/90755396 )



# <a id='2'>学习内容2</a>



观看B站的视频教程

[视频作者：庄七](https://www.bilibili.com/video/av10475153?from=search&seid=8658744626137178261)



# <a id='3'>学习内容3</a>

实际下载git，在GitHub上建库，并将本地写好的报告上传

这个使用的是git GUI上传，实际操作个人觉得两个（Bash）都可

[学习过程截图1](http://note.youdao.com/noteshare?id=f9fc77eee179c65f061912debd15080f)



[学习过程截图2](http://note.youdao.com/noteshare?id=0abcced9d3b557e0c1cc3dde77421ce8)



[学习过程截图3](http://note.youdao.com/noteshare?id=3967e45fd5c643d9a586385cc7c01056)



[学习过程截图4](http://note.youdao.com/noteshare?id=05321ad898e060f2139fd44db2ebd0a4)


### 学习心得

|            总体体会             |       廖雪峰       |    某站视频    |               菜鸟教程               |
| :-----------------------------: | :----------------: | :------------: | :----------------------------------: |
| git很强大，GitHub很实用也很有用 | 通俗易懂，思路清晰 | 作配套了解使用 | ding呱呱的一个讲解类学习网站，不多说 |
|               ...               |        ...         |      ...       |                 ...                  |

