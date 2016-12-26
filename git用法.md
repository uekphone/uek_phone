## git的用法
     ##从指定url 获取资源仓库
     git clone url
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
-----------------------------------------
    ##上传到服务器
        git push origin master (默认提交到主分支上)
        输入 github 账号 密码
    ##更新
        git pull