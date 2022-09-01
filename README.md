# git使用指南
## git常用指令
```
git init - 初始化仓库
git add - 添加文件到暂存区
git commit - 将暂存区内容添加到仓库
git status - 查看仓库当前的状态，显示有变更的文件
git clone [URL] - 拷贝git仓库到本地进行查看及修改

git branch - 查看分支
git branch (name) - 创建分支
git checkout (name) - 切换分支
git branch -d (name) - 删除分支
git merge (name) - 将name分支合并到当前分支

git log - 查看历史提交记录

git remote add [shortname] [url] - 添加远程仓库，并取个别名
git push [alias] [branch] - 推送分支与数据到远程仓库
git fetch - 从远程仓库下载新分支与数据
git merge - 从远端仓库提取数据并尝试合并到当前分支
git pull - 等于fetch + merge
git remote rm (name) - 删除远程仓库
```
