1.gitBash Here
2.git config --user user.name "username"
3.git config --user user.email "email"
4.第一次创建仓库，仓库内会有提示git的上传命令
5. git init
    git add 文件名（目录或者具体的文件）
    git commint -m '每次提交的备注信息'
    git remote add origin 具体的位置
    git push -u origin master
6.对提交的文件修改后，可以用git status查看状态----
7.git diff 文件名       --->可以查看修改的不同的地方
8.每次修改完之后，需要git add 和git commit命令进行重新提交，本地commit之后再用git push上传
9.用git log查看最近上传的情况,用git reflog查看更新的版本情况
10.git reset --hard HEAD^（^有几个代表往上回退几个版本）
11.git reset --hard 版本号（直接通过reflog的版本号回退）

