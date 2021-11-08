# git 学习测试

创建并初始化 git
git init

提交文件到暂存区
git add .

提交文件到本地 git 仓库
git commit -m "提交日志"

创建分支
git branch 'branchname

切换分支
git checkout 'branchname

创建并切换分支
git checkout -b 'branchname

删除本地分支
git branch -d 'branchname
删除远程分支
git push origin --delete 'originbranchname

代码回滚到最近一次提交
git stash

代码回滚释放
git stash pop

(代码写到一半，远程代码更新了，先回滚代码，然后拉取远程代码，然后回滚释放，解决冲突后提交)

对一段线性提交的进行编辑、删除、复制、粘贴
git rebase -i HEAD~2
