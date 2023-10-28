0.安装软件
1. 获取本地仓库
	1）在电脑任意位置创建一个目录，作为本地GIT仓库
	2）进入目录，右键打开Git bash窗口
	3）执行命令：git init
	4）目录有.git目录说明创建成功

2.基础命令（*号标注为经常使用命令）
   touch file01.txt		不属于 Git command 创建一个文件，在工作区（worksapce）Untracked files状态
   git rm --cached		(把暂存区（index）的文件回退到工作区（workspace）状态：unstaged(未暂存)-->staged(已暂存)
   git status			(*查看文件状态--暂存区、工作区)
   git file.txt			(把工作区的新增或是修改的文件提交到暂存区（index）) 
   git add .			(*把工作区的所有新增修改的文件提交到暂存区（index）) 
   git commit -m "add file"	(*把暂存区（index）文件提交到本地仓库（repository），-m "" 是添加这提交仓库的改动说明) 			
   git log			(*check commit command detail) 
   git reflog			(check all commit command detail 不常用) 

3.版本回退命令
   git reset --hard commitID    (commitID可以执行 git log 或是 git-log 查看)

4.分支命令
   git branch                   (check branch)
   git branch dev01             (create branch)
   git checkout dev01           (Switch branch)
   git branch -b dev02          (create and switch branch)

   git merge dev01              (merge branch)
   git checkout -d dev02        (delete branch)
   git checkout -D dev02        (force delete branch)
   
5.remote命令
   git remote add origin https://github.com/${user_name}/Origin.git (get remote repository service URL )
   git remote                   (check remote repository)
   git push -u origin master    (GitHub:push branch master to the remote repository) 
   git push origin master       (push branch master to the remote repository) 
   git push --set-upstream origin master:master   (Buil local repo and remote repo relationship) 
   git remote -vv               (check remote repo relationship) 
   git branch -vv               (check local repo and remote repo relationship) 

6.clone命令
   git clone https://github.com/Gluttony007/Origin.git (clone remote repo to local repo)
  
7.拉取和抓取命令
   git fetch                    (fetch remote repo data to local, but not merge) 
   git merge                    (merge fetch remote repo data to local)
   git pull                     (fetch + merge)  

00.删除文件
   git rm --cached file.txt     (local repository to delete)
   git rm -r  在删除文件夹的时候，使用参数 -r 表示循环删除文件夹中的内容（不做详细介绍）

00.查看用户信息
   git config user.name
   git config user.email

00.Git忽略文件管理
   .gitignore                   (把不用Git管理的文件写到这个文件中) 








   