### git study

新建分支 git branch <name>

切换分支 git checkout <name>

合并某分支到当前分支（快进模式） git merge <name>

删除分支 git branch -d <name>

合并某分支到当前分支（非快进模式） git merge --no-ff -m "something" <name>
会记录分支，查看历史可以知道这个分支曾经存在过



分支其实是指针，指向提交。HEAD指向当前分支的指针。