# 初始化
git init
# 将工作区代码放到暂存区
git add xx.txt
# 将暂存区代码放到本地库
git commit -m "description" xx.txt
# 通过ssh连接远程库， origin_ssh是ssh_link的别名
git remote origin_ssh [ssh_link from github ssh]
# 将本地库代码push到远程库
git push origin_ssh master


# 新建分支
git branch [分支名称]
# 切换到另一个分支
git checkout [分支名称]

# 查看有哪些分支
git branch -v
