0.��װ���
1. ��ȡ���زֿ�
	1���ڵ�������λ�ô���һ��Ŀ¼����Ϊ����GIT�ֿ�
	2������Ŀ¼���Ҽ���Git bash����
	3��ִ�����git init
	4��Ŀ¼��.gitĿ¼˵�������ɹ�

2.�������*�ű�עΪ����ʹ�����
   touch file01.txt		������ Git command ����һ���ļ����ڹ�������worksapce��Untracked files״̬
   git rm --cached		(���ݴ�����index�����ļ����˵���������workspace��״̬��unstaged(δ�ݴ�)-->staged(���ݴ�)
   git status			(*�鿴�ļ�״̬--�ݴ�����������)
   git file.txt			(�ѹ����������������޸ĵ��ļ��ύ���ݴ�����index��) 
   git add .			(*�ѹ����������������޸ĵ��ļ��ύ���ݴ�����index��) 
   git commit -m "add file"	(*���ݴ�����index���ļ��ύ�����زֿ⣨repository����-m "" ��������ύ�ֿ�ĸĶ�˵��) 			
   git log			(*check commit command detail) 
   git reflog			(check all commit command detail ������) 

3.�汾��������
   git reset --hard commitID    (commitID����ִ�� git log ���� git-log �鿴)

4.��֧����
   git branch                   (check branch)
   git branch dev01             (create branch)
   git checkout dev01           (Switch branch)
   git branch -b dev02          (create and switch branch)

   git merge dev01              (merge branch)
   git checkout -d dev02        (delete branch)
   git checkout -D dev02        (force delete branch)
   
5.remote����
   git remote add origin https://github.com/${user_name}/Origin.git (get remote repository service URL )
   git remote                   (check remote repository)
   git push -u origin master    (GitHub:push branch master to the remote repository) 
   git push origin master       (push branch master to the remote repository) 
   git push --set-upstream origin master:master   (Buil local repo and remote repo relationship) 
   git remote -vv               (check remote repo relationship) 
   git branch -vv               (check local repo and remote repo relationship) 

6.clone����
   git clone https://github.com/Gluttony007/Origin.git (clone remote repo to local repo)
  
7.��ȡ��ץȡ����
   git fetch                    (fetch remote repo data to local, but not merge) 
   git merge                    (merge fetch remote repo data to local)
   git pull                     (fetch + merge)  

00.ɾ���ļ�
   git rm --cached file.txt     (local repository to delete)
   git rm -r  ��ɾ���ļ��е�ʱ��ʹ�ò��� -r ��ʾѭ��ɾ���ļ����е����ݣ�������ϸ���ܣ�

00.�鿴�û���Ϣ
   git config user.name
   git config user.email

00.Git�����ļ�����
   .gitignore                   (�Ѳ���Git������ļ�д������ļ���) 








   