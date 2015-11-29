#about readm.md
use makrdown lable to description your project

###常用git命令手册
选择一个工作目录，然后初始化版本库
cd ~  
mkdir learngit  
cd learngit  
git init  

###关联远程仓库
git remote add origin git:github/xincun/learngit.git

###下载远程仓库到本地版本库
git pull

###提交到远程仓库
git push origin master

###How do I commit all deleted files in Git?
git add -u  
This tells git to automatically stage tracked files -- including deleting the previously tracked files.  

###仅在暂存区删除，保留文件在当前目录，不再跟踪
git rm –cached readme.txt

###重命名文件
git mv reademe.txt readme

###修改最后一次提交注释的，利用–amend参数
git commit --amend


###假设你已经使用git add .，将修改过的文件a、b加到暂存区现在你只想提交a文件，不想提交b文件，应该这样
git reset HEAD b  

取消对文件的修改  
git checkout –- readme.txt

