1.gitBash Here  </br>
2.git config --user user.name "username"  
3.git config --user user.email "email"  
4.第一次创建仓库，仓库内会有提示git的上传命令  
5. git init  
    git add 文件名（目录或者具体的文件)  
    git commint -m '每次提交的备注信息'  
    git remote add origin 具体的位置  
    git push -u origin master  
6.对提交的文件修改后，可以用git status查看状态----  
7.git diff 文件名       --->可以查看修改的不同的地方  
8.每次修改完之后，需要git add 和git commit命令进行重新提交，本地commit之后再用git push上传  
9.用git log查看最近上传的情况,用git reflog查看更新的版本情况  
10.git reset --hard HEAD^（^有几个代表往上回退几个版本）  
11.git reset --hard 版本号（直接通过reflog的版本号回退）  
12.同时删除本地仓库和远程仓库文件  
     git rm 文件名（如果带目录记得/）  
     git commit -m '删除。。。'  
     此时可能会跳出vim输入框，只需要填写删除备注信息即可  
     git push  
      完成操作  

