git commit

git branch newImage
git checkout <name>
git checkout -b <branch-name>

git merge <branch> 合并指定分支到当前分支
git rebase <branch> 衍合指定分支到当前分支

git rebase -i HEAD~4 (交互式rebase，--interactive)

HEAD
^
~<num> 向上返回几代

^后加数字，多个父节点时使用

git reset 变更还在，处于未加入暂存区状态，local
git revert 用于remote

git cherry-pick <提交号>

commit --amend

git tag （永久标签）
>如：git tag v1 C1

git describe <ref> 描述最近的标签
>`<tag>_<numCommits>_g<hash>`

git clone

git fetch

git push

git pull
