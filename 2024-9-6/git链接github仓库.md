[TOC]

# git链接GitHub仓库

## 1.创建电脑密钥

### 1.1 生成密钥

```bash 
在git bash中输入以下命令

ssh-keygen -t rsa -C "your_email@example.com"
```

### 1.2 查看密钥，添加密钥到GitHub

```bash
在电脑c盘中找到.ssh文件夹，打开id_rsa.pub文件，复制里面的内容

/c/Users/zhouxiaojun/.ssh/id_rsa.pub

cat ~/.ssh/id_rsa.pub

```

### 1.3 
