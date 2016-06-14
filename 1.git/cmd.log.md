#1.先注册一个github用户
https://github.com/join

#2.安装git,在命令号中分别配置用户名和邮箱
git config --global user.name "用户名"
git config --global user.email "邮箱"

#3.初始化仓库 在E盘目录邮件打开gitBash
mkdir 201602git 创建空目录
cd 201602git 进入该目录
git init 初始化仓库

#4.工作流程
```
touch 1.txt 新建一个名字叫1.txt的文件
git -add 将文件添加到暂存区
git commit -m"add 1.txt" 将文件提交到历史区，并且添加注释
git log 查看历史记录
```