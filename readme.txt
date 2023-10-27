0.安装软件
1. 获取本地仓库
	1）在电脑任意位置创建一个目录，作为本地GIT仓库
	2）进入目录，右键打开Git bash窗口
	3）执行命令：git init
	4）目录有.git目录说明创建成功

2.基础命令
   -touch file01.txt （创建一个文件，在工作区（worksapce）Untracked files状态
   -git rm --cached		(把暂存区（index）的文件回退到工作区（workspace）状态：unstaged(未暂存)-->staged(已暂存)
   -git status			(查看仓库（repository）状态)
   -git file.txt		(把工作区的新增或是修改的文件提交到暂存区（index）) 
   -git add .			(把工作区的所有新增修改的文件提交到暂存区（index）) 
   -git commit -m "add file"    (把暂存区（index）文件提交到本地仓库（repository）)			