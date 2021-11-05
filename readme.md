Git is a distributed version control system.
Git is free software.


Git 命令
git init  --初始化一个Git仓库;
添加一个文件分两步

1.  git add <file>   可以反复多次使用，添加多个文件;
2.  git commit -m <message>


git status --随时掌握工作区的状态
如果有文件被修改过
git diff 查看被修改的文件内容

git log  可以查看提交历史
HEAD指向的版本就是当前版本
git reset --hardHEAD^ 来回退版本
git允许我们在版本之间来回的穿梭，以确定要进入哪个版本
要返回未来时，用 git reflog来查看命令历史，以确定要回到未来的哪个版本
回退后也可以回到当前版本
