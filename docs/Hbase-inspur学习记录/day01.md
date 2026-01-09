# day01--docker 创建 hbase 容器

## git准备工作
- 创建学习文件夹，并同步至github
    - 创建本地git仓库
    - 初始化本地仓库
    - 将本地仓库与远程github仓库关联......
    ```
    # 1. 进入你的项目根目录
    cd ~/projects/hbase-learning

    # 2. 初始化本地Git仓库
    git init

    # 3. 将本地仓库与你的GitHub远程仓库关联
    # 将下面的URL替换成你刚刚创建的仓库的HTTPS或SSH地址
    git remote add origin https://github.com/你的用户名/hbase-distributed-learning.git
    https://github.com/TZZO-tracer/hbase-distributed-learning.git (fetch)
    origin  https://github.com/TZZO-tracer/hbase-distributed-learning.git (push)

    # 4. 将当前所有文件添加到暂存区
    git status--查看git状态（文件内容是否有改变？）
    git add .
    git add “你的新增变化的文件名/文件夹”

    # 5. 提交你的第一次更改，并写上描述信息
    git commit -m "描述信息"
    例如：git commit “本次提交新增了登录接口/某某功能/某某文档等等”

    # 6. 推送到GitHub的主分支（默认是main或master）
    # 如果是第一次推送，需要用 -u 参数建立追踪
    git branch -M master（master是分支  git branch -a 查看分支有哪些（本地、git远程））
    git push -u origin master（正式推送到git上）
    ```


## 服务器:inspur
    - 10.110.141.111
    - 36.140.169.14/root  rW5.lB9#bK6mC1$Y
    - 10.110.141.12  administrator  ife34Te$d*(?Fq&  mstsc
    - 


