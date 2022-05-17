# Git 速查表

> 记录常用的一些 git 命令。

[Pro Git 手册](https://www.progit.cn/) &ensp;  [Git 官网](https://git-scm.com/)


## 配置工具
配置工具
设置关联的用户名
```bash
git config --global user.name "[name]"
```

设置关联的邮箱地址
```bash
git config --global user.email "[address]"
```

检查配置
```bash
git config --global --list
git config --global user.name
git config --global user.email
```

修改commit Author 信息
```bash
git commit --amend --author="Meyerzh <meyerz@ciandt.com>" --no-edit
```