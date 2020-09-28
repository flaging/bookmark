# linux使用

## 新建用户

root模式或者sudo权限下
```bash
adduser username or useradd -m username
passwd ****
```

useradd:只添加用户名，不会添加用户目录和基本设置，所有设置均需要手动完成。

建立用户时的其他操作：

```bash
#删除用户
userdel username
#添加组群
groupadd groupname
#删除组群
groupdel groupname
#为用户添加sudo权限
visudo
username all=(all) all
```

## conda

conda环境中升级python

```bash
#conda升级python
conda update python
#conda下使用pip安装keras
pip install keras
```

## vim

[vim实用技巧-读书笔记](./vim.md)
