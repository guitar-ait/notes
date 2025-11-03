# git

## git常用命令

~~~bash
# 设置用户签名（必做）
git config --global user.name JAY
git config --global user.email JAY.edu.cn
# 在一个文件夹里初始化本地库
git init # 生成的git文件夹隐藏
# 查看本地库状态
git status
# 添加到暂存区
git add <file name>
# 提交到本地库
git commit -m "日志信息" <file name>
# 查看历史记录
git reflog
git log
# 版本穿梭
git reset --hard <版本号>

~~~

## git分支

~~~bash
# 创建分支
git branch <branch name>
# 查看分支
git branch -v
# 切换分支
git checkout <branch name>
# 合并分支（合并到当前分支）
git merge <branch name>
~~~

## git团队协作

~~~ bash
# add another name
git remote add <another name> <reposity links>
# checkout
git remote -v
# push branch to repository
git push <another name> <branch name>
# pull branch to local
git pull <another name> <branch name>
# clone (init + clone + creat another name(origin))
git clone <repository links>
~~~

