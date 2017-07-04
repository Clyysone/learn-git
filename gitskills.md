#Git-skill
>我的gitlab [my-gitlab](http://211.67.27.251/Pappiu)  
>我的github [my-github](https://github.com/Clyysone)  

- - -
##1.history
- CVS Concurrent Version System 代码版本控制系统（编码问题）
- SVN Subversion简称 开发源代码的版本控制系统

##2.Git
###概念 
- 版本库repo(repository)  
- 暂存区stage(index)  
- 记录（diff-文件变更的记录形式)  
- 指针（head-当前checkout的commit指针，fetch,pull默认对象，本地更改对比的对象)  
- 提交 (commit-diff快照)  
- 分支 （branch-指向特定commit的指针）  


![](http://www.runoob.com/wp-content/uploads/2015/02/1352126739_7909.jpg)
###常用查询操作 
- pwd 显示当前工作目录  
- git status 掌握当前仓库状态
- git diff <fn> 查看修改
- git log 查看提交状态  
- git reflog 查看历史命令  
- git branch 查看当前分支  
- git stash list 查看存储表
- git remot 查看远程库  
- git tag 查看所有标签(<tag_name>）
###常见命令
- git init 将当前变为可管理仓库reop 
- git checkout <branch> 更换HEAD所指分支  
- git branch <branch> 新建一个分支
- git branch -d <branch> 删除一个分支（-D 强制）
- git merge <branch> 将指定分支合并到当前HEAD
- git reset --hard HEAD^ 回到生一个本地
- git revert 撤销更改
- git stash 存储工作现场
- git rm <fn> 删除  
- git remote add origin <http://211.67.27.251/Pappiu/pap_pro.git> (http)
- git push -u origin master （之后git push origin master)
- git clone <git@211.67.27.251:Pappiu/pap_pro.git> (SSH)
- git branch --set-upstream <l_branch> origin/<r_branch> 本地和远程连接创建  
- git pull (=git fetch + git merge)

###复杂点的
- git diff HEAD -- readme.txt 查看工作区和版本库中最新版本区别
- git status -s 简化版  
- git log --pretty=oneline只查看id和备注
- git checkout --readme.txt 丢弃工作区的修改（回到最近一次commit 或 add 时的状态）
- git reset HEAD readme.txt (加到暂存区后)+git checkout --readme,txt 丢弃工作区修改
- git checkout -b <branch> 新建一个分支并转换到该分支
- git merge --no-ff -m "message" (--no-f:no fast-forward)  
- git stash pop & git stash apply stash@{0} 前面一个查看并删除，后者只查看





