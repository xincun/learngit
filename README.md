#about readm.md
use makrdown lable to description your project

###����git�����ֲ�
ѡ��һ������Ŀ¼��Ȼ���ʼ���汾��
cd ~  
mkdir learngit  
cd learngit  
git init  

###����Զ�ֿ̲�
git remote add origin git:github/xincun/learngit.git

###����Զ�ֿ̲⵽���ذ汾��
git pull

###�ύ��Զ�ֿ̲�
git push origin master

###How do I commit all deleted files in Git?
git add -u  
This tells git to automatically stage tracked files -- including deleting the previously tracked files.  

###�����ݴ���ɾ���������ļ��ڵ�ǰĿ¼�����ٸ���
git rm �Ccached readme.txt

###�������ļ�
git mv reademe.txt readme

###�޸����һ���ύע�͵ģ����èCamend����
git commit --amend


###�������Ѿ�ʹ��git add .�����޸Ĺ����ļ�a��b�ӵ��ݴ���������ֻ���ύa�ļ��������ύb�ļ���Ӧ������
git reset HEAD b  

ȡ�����ļ����޸�  
git checkout �C- readme.txt

