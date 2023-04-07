# create a new repository on the command line

```bash
#初始化：本地建库（即文件夹），git init
git init
#添加到仓库：代码文件放入本地库，git add .
git add README.md
#提交： git commit -m “注释内容”，提交到仓库
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:adooper/odoo-custom-addons.git
git remote -v
#由于新建的远程仓库是空的，所以要加上-u这个参数
git push -u origin master
#之后仓库不是空的，就不用加上-u
git push origin master

# 追加知识点
git remote remove origin 删除即可
```

# push an existing repository from the command line

```bash
git remote add origin git@github.com:adooper/odoo-custom-addons.git
git branch -M main
git push -u origin main
```

# git
```bash
git config --list
 
# 编辑 git 配置文件:
git config -e    # 针对当前仓库
git config -e --global   # 针对系统上所有仓库

git config --global user.name "runoob"
git config --global user.email test@runoob.com
```
