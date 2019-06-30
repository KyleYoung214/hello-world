+ git commit
+ commit --amend

---

+ git branch <name> 查看分支 -a 查看所有
+ git branch -d <name> 删除分支
+ git checkout <name> 切换分支
+ git checkout -b <branch-name> 创建并切换分支

---

+ git merge <branch> 合并指定分支到当前分支
+ git rebase <branch> 衍合指定分支到当前分支

+ git rebase -i HEAD~4 (交互式rebase，--interactive)

> HEAD
> ^
> ~<num> 向上返回几代
>
> ^后加数字，多个父节点时使用

---

+ git reset 变更还在，处于未加入暂存区状态，local
+ git reset --hard <commit-id>
+ git revert 用于remote
+ git cherry-pick <提交号>

---

+ git tag （永久标签）

>如：git tag v1 C1

+ git tag <tag_name> commit_id>
+ git show <tag_name>
+ git tag -d <tag_ name>

> 大版本号.小更新.修复bug

---

git describe <ref> 描述最近的标签
>`<tag>_<numCommits>_g<hash>`

---

git clone <url>

git fetch

git push <orgin> <master>

git pull

git merge <branch> 合并branch到当前分支

git reflog <-n num>

---

git config --global alias.<name> <command_name> 简化别名

git config -l

---

.ignore 失效 

>git rm -r --cached . 清除缓存后再提交

---

    $ git remote -v
    origin  git@github.com:KyleYoung214/hello-world.git (fetch)
    origin  git@github.com:KyleYoung214/hello-world.git (push)