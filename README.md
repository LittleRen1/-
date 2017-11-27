# 前端学习笔记
前端学习笔记

git笔记（一）
git--跟踪并管理修改，非文件
首先创建空目录
git init 将目录变为可管理（同时建立.git目录，ls-ah可令隐藏的.git显示）
git add file 添加仓库
git commit -m"string"提交仓库 m:增加提示
git status 掌握仓库状态
git diff file 查看变动
git log 查看历史记录
git reset--hard HEAD^ || git reset--hard 362864
版本回退 (HEAD^ HEAD^^ HEAR~100)——————————————————HEAD实质上是指针
git reflog 记录每一次命令
工作区：可见目录
版本库：隐藏的.git
暂存区：存放于版本库中的stage（git add file）
master：存在与版本里中的链表（git commit -m"string"）
git checkout --file 撤销工作区修改————————————————实质上是同版本库里的版本替换工作区版本
git reset HEAD file 撤销暂存区修改
git reset--hard HEAD^ 已提交，通过版本回退修改
git rm file 删除版本库中文件
