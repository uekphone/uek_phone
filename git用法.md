## git的用法
     ##从指定url 获取资源仓库
    git clone url

    git init  
    ##链接到远端仓库
    git remote add origin https://github.com/lzxb/react-cnode.git

    一个项目可以同时拥有好几个远端仓库为了能够区分，通常会起不用的名字。通常住远端仓库被称为origin、
   ##检查转态
    git status
   ##git add 提交到暂存盘
    *暂存一个文件
       git add a.html
    *暂存所有文件
       git add .
   ##提交信息，做了哪些工作（注释）
      git commit -m "提示内容"
   ##提交日志
      git log
  ##同步到服务器上
-----------------------------------------
    ##上传到服务器
        git push origin master (默认提交到主分支上)-->git push origin master
        git push origin gh-pages(提交到其他分枝上)
        输入 github 账号 密码
    ##更新
        git pull