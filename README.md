# MyFistRepository
MyFistRepository
2019/04/04
本地仓库删除文件后推送至网络 无法更新？？？

解决：1. 命令行确认(向本地仓库确认删除MovieBootstrap文件夹)  git rm MovieBootstrap -r -f
      2. git commit -m "提交删除MovieBootstrap文件夹"
      3. 推送 至网络  git push -u origin master
