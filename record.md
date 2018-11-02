echo "# Oni_AlgoTrading_Env" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/akira2009999/Oni_AlgoTrading_Env.git
git push -u origin master

2 git下免账号密码push/pull
2.1 添加环境变量

  在windows中添加一个HOME环境变量，变量名:HOME,变量值：%USERPROFILE%
2.2 创建git用户名和密码存储文件

  进入%HOME%目录（linux/mac在~/），新建一个名为”_netrc”的文件，文件中内容格式如下：

machine github.com
login your-usernmae
password your-password
