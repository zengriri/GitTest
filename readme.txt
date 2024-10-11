*git有4个工作区域
    1：工作目录（Working Directory）
    2：暂存区(Stage/Index)
    3:本地仓库(Repository或Git Directory)
    4：远程的git仓库(Remote Directory)


*add:添加到暂存区区
        git add .   //添加所有文件到暂存区

*commit:添加到本地仓库       
    git commit -m  //提交暂存区中的文件的本地仓库   -m 提交信息    


push：添加到远程仓库        
fetch:从远程仓库拉取到本地仓库


*分支
    git checkout -b [branch]    //新建一个分支，并切换到该分支
    git merge [branch]          //合并指定分支到当前分支
    git branch -d [branch]      //删除分支

    git push origin --delete [branch-name]      //删除远程仓库
    git branch -dr [remote/branch]              //删除远程仓库
