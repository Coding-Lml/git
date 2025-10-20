Git使用教学

## 创建本地仓库

1. 找个本地位置 使用git init 即可创建.git文件代表本地仓库创建完成
2. git clone来克隆远程仓库的地址

## 工作区和文件状态

- 工作区  实际操作的目录     git. add
- 暂存区 中间区域临时存放的中间目录.  git commit
- 本地仓库  

## 常用命令

- git init 初始化仓库
- git status. 查看当前仓库状态
- git add 添加到暂存区
- git commit 将暂存区的内容提交到仓库
- git log 查看提交日志

## git reset的三种模式

![image-20251020164202305](/Users/aloong/Library/Application Support/typora-user-images/image-20251020164202305.png)

使用时 git reset --soft [提交版本号]

## git diff用法

1. 查看工作区、暂存区、本地仓库之间的差异
2. 查看不同版本之间的差异
3. 查看不同分支之间的差异

## 版本库删除文件

1. rm删除文件 再add 再提交

2. git rm 再提交

![image-20251020170301196](/Users/aloong/Library/Application Support/typora-user-images/image-20251020170301196.png)

## .gitignore文件

用于忽略文件 添加到版本库

## 远程仓库

1. 添加远程仓库   git remote add <远程仓库别名> <远程仓库地址>     远程仓库别名一般是origin ，然后 git push -u <远程仓库名><分支名>
2. 查看远程仓库  git remote -v
3. 拉取远程仓库内容.   git pull <远程仓库名> <远程分支名>：<本地分支名>![image-20251020180054984](/Users/aloong/Library/Application Support/typora-user-images/image-20251020180054984.png)

上述是无仓库和有仓库与远程仓库绑定的两种方式