# toutiao_requests
目标：爬取今日头条用户收藏，将所有收藏的分类、标题、链接、发布时间保存到本地execl表格或json文件；

技术要点：requests、json、xlwt

访问URL： https://www.toutiao.com/c/user/favourite/?page_type=2； 获取User_Agent, cookie，代替代码中init函数中的对应值后，运行。
