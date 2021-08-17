# note-video
马士兵系列视频：git

# 01-intro
公司必备，一定要会。

git 是一个开源、免费的分布式版本控制系统。

为什么要使用vcs？

- VCS的分类：
  - 集中式：CVS、SVN
  - 分布式：Git
# 02. Git 简史
Linux 做的。
# 03. 安装过程
# 04. Git 结构
工作区、暂存区、本地仓库

git add, git commit

# 05. 代码托管
本地库、远程库

公司内部协作
git push、git clone，git pull

跨公司协作
pull request

内网：gitlab
外网：github，gitee

# 06. 初始化本地仓库

user.name
user.email

git init
# 07. git add 和 commit 命令
# 08. git status 命令

# 09 git 常用命令 git log
对 git reflog 的说明有误。

视频说：“表示回退几步”，这样说至少是不准确的。reflog 是 HEAD 的变更记录，不代表回退记录。
另外，reflog 的数据不是持久数据，提交、推送、下载仓库都没有这个数据。
git reflog expire --expire=now --all --rewrite 命令还能清空 reflog。
# 10. git log 命令2

# 11. 常用命令 git-reset

