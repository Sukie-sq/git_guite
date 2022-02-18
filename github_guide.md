# github_guide.md

### 说明

- 参考视频教程 https://www.bilibili.com/video/BV1db4y1d79C?spm_id_from=333.999.0.0
- 记录常用操作

# 常用命令

克隆仓库：git clone <git地址>

初始化仓库：git init 

添加文件到暂存区：git add -A

把暂存区的文件提交到仓库：git commit -m "提交信息"

查看提交的历史记录：git log --stat

工作区回滚：git checkout <filename>

撤销最后一次提交：git reset HEAD^1

以当前分支为基础新建分支：git checkout -b <branchname>

列举所有的分支：git branch

单纯地切换到某个分支：git checkout <branchname>

删掉特定的分支：git branch -D <branchname>

合并分支：git merge <branchname>

推送当前分支最新的提交到远程：git push

拉取远程分支最新的提交到本地：git pull

# 导入项目到远程
1.初始化仓库  
> git init 

2.添加文件到暂存区  
> git add -A

3.提交文件到仓库：
> git commit -m "提交信息"

4.github新建仓库： 
> 网页操作

5.根据新建仓库提示命令上传到远程

> push an existing repository from the command line
> 
> 5.1 git remote add origin git@github.com:Sukie-sq/test4.git
> 
> 5.2 git branch -M main
> 
> 5.3 git push -u origin main

# 编辑本地项目
1.初始化仓库  
> git init 

2.添加文件到暂存区  
> git add -A

3.提交文件到仓库：
> git commit -m "提交信息"

4.以当前分支为基础新建分支：
> git checkout -b <branchname>

5.单纯地切换到某个分支：
> git checkout <branchname>

6.合并分支<branchname>到当前分支：
> git merge <branchname>

7.删掉特定的分支：
> git branch -D <branchname>

# 学习其他项目
克隆仓库：
> git clone <git地址>