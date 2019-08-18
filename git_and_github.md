# git与github的联系
* 创建一个仓库，复制链接地址
```
生成ssh key，使用命令 ssh-keygen -t rsa -C "用户名"
ls -a 查看隐藏文件.ssh
复制到github
测试连接
ssh -T git@github.com
配置用户信息
git config ––global user.name “your name” //配置用户名
git config ––global user.email “your email” //配置email
查看配置信息：
git config user.name
git config user.email
 ——
 ——————————————
# 初始化仓库
 git init
# 添加远程地址
 git remote add origin git@github.com:
# 上传文件
 git add .
# 提交文件
 git commit -m ""
# 发送文件
 git push origin master
# 拉去文件
git clone 地址
# 应急措施
git fetch origin
git merge origin/master
git pull origin<bendicangku>master




```
