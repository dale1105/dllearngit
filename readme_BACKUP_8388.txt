git is a distributed version control system.
git is free software distributed under the GPL.
git has a mutable index called stage.
Creating a new branch is quick AND & simple.

#git 步骤：
#1.git init创建空的仓库
#2.git add把文件添加到仓库
#3.git commit提交 -m 本次提交的说明

#4.git status命令让我们掌握仓库当前状态，有修改，但是没有准备好提交
#5.git diff ：查看difference

#更新提交
#1.git add readme.txt
#2.git commit

#回滚 :
#1.git log:查看日志--pretty=oneline，精简成1行
#2.git reset：回滚
#3.HEAD表示当前版本，HEAD^表示上个版本，HEAD^^表示上上个版本，HEAD~100表示上100个版本
#4.git reflog：记录你的每一次提交

#版本库：.git目录，最重要的就是stage（index）的暂存区，还有第一个分支master，指向master的一个指针HEAD
#当Git无法自动合并分支时，就必须首先解决冲突。解决冲突后，再提交，合并完成。
#解决冲突就是把Git合并失败的文件手动编辑为我们希望的内容，再提交。
#用git log --graph命令可以看到分支合并图

test --no-ff
<<<<<<< HEAD
pppppppppppppppp
=======
123455667
>>>>>>> dev
