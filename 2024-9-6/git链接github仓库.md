- [git链接GitHub仓库](#git链接github仓库)
  - [1.创建电脑密钥](#1创建电脑密钥)
    - [1.1 生成密钥](#11-生成密钥)
    - [1.2 查看密钥，添加密钥到GitHub](#12-查看密钥添加密钥到github)
    - [1.3 远程库](#13-远程库)
    - [1.4 克隆远程库](#14-克隆远程库)
    - [1.5 流程](#15-流程)

# git链接GitHub仓库

## 1.创建电脑密钥

### 1.1 生成密钥

```bash 
在git bash中输入以下命令

ssh-keygen -t rsa -C "your_email@example.com"
```

### 1.2 查看密钥，添加密钥到GitHub

<img src="https://github.com/timesun135/notebook/blob/master/2024-9-6/%E5%9B%BE%E7%89%87/1.jpg"  style="zoom:50%;" alt="" title=""  />

```bash
在电脑c盘中找到.ssh文件夹，打开id_rsa.pub文件，复制里面的内容

/c/Users/zhouxiaojun/.ssh/id_rsa.pub

cat ~/.ssh/id_rsa.pub

```

### 1.3 远程库
```
git remote add origin git@github.com:michaelliao/learngit.git
把上面的michaelliao替换成你自己的GitHub账户名
```
```
把本地库的所有内容推送到远程库上：git push -u origin master

git push origin master
```

### 1.4 克隆远程库

```
git clone git@github.com:michaelliao/gitskills.git

```
### 1.5 流程

```

git add .

git commit -m "wrote a readme file"

git push  origin master
```





