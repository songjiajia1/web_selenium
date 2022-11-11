# test_selenium
2022-11-11创建


一、将本地已有项目添加到git管理的几种方法：
1、在 github 上面新建一个空的项目。
复制刚创建的项目git地址

2、在本地目录下 ，右键打开”GitBash Here”黑窗口

3、使用命令，本地推送到远程地址
git init   # 把项目初始化,相当于在项目的跟目录生成一个 .git 目录
git add .    # 把项目的所有文件加入暂存区
git commit -am '项目初始化'     # 把项目提交到本地仓库，引号里面的是这次提交的注释，方便以后查看。
git remote rm origin  # 先删除远程 Git 仓库
git remote add origin https://github.com/BobinYang/   #为本地的仓库创建一个远程仓库. 例如：git remote add origin https://github.com/BobinYang/HtmlAgilityPackSample.git
git pull --rebase origin master  # 把远端仓库中的代码 拉到本地进得合并一下。
git push origin master  # 将本地缓存仓库的文件推送到远程。master这个是分支名



二、使用克隆到本地的方法
1、在github上创建一个新仓库，克隆到本地文件夹
git clone git@github.com:songjiajia1/web_selenium.git

2、将本地的文件夹里面的所有内容拷贝到新克隆下来的文件夹中

3、提交修改后的的文件
git add . 
git commit -am “项目初始化” 
git push -u origin master