# 分支管理

- 远程分支删除
  - git branch -r -d origin/branch_name
  - git push origin :branch_name
- 删除本地分支
  - git branch -D branch_name
- 切换分支
  - git checkout branch_name
- 查看远程分支
  - git branch -a
- 创建分支
  - git branch branch_name
- 查看本地分支
  - git branch
- 如果远程新建了一个分支，本地没有该分支
  - git checkout --track origin/branch_name
- 如果本地新建了一个分支 branch_name，但是在远程没有
  - git push --set-upstream origin branch_name
- 合并分支到 master 上
  - git checkout master
  - git pull origin master
  - git merge dev
