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
   

00.Git�����ļ�����
   .gitignore                   (�Ѳ���Git������ļ�д������ļ���) 











   