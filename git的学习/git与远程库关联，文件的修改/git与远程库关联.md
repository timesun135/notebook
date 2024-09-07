- [git与远程库关联](#git与远程库关联)
  - [1.删除仓库里面的某个文件](#1删除仓库里面的某个文件)
  - [2.将文件添加到github仓库里面](#2将文件添加到github仓库里面)

# git与远程库关联

## 1.删除仓库里面的某个文件

```bash
git pull origin master  将远程仓库里面的项目拉下来

删除文件

git commit -m ""

git push -u origin master
```

## 2.将文件添加到github仓库里面

```bash

git add .

git commit -m "first commit"

git push -u origin master

```