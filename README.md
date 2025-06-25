这是用来学习git的事例仓库
包含 git remote origin URL源仓库地址
//将远程仓库地址添加为本地仓库的远程源，命名为"origin"
git branch -M main 
//将当前分支重命名为"main"（Git默认分支名从master改为main后的常见操作）
git push -u origin main
//将本地的main分支推送到远程origin仓库
-u参数设置上游跟踪，以后可以直接用git push而不用指定远程和分支
这组命令完整执行后，你的本地代码库就成功推送到了GitHub上的first_repo仓库，并且建立了跟踪关系。
