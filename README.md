AwnWay's Blog
========

keep learning...

## Blog使用相关

### 1 添加新文章    

- 格式markdown，目录_post，命名：yyyy-mm-dd-文章名

- 文章需要添加Header格式：    
  ```
  ---
  layout:     post
  title:      "<文章名>"
  subtitle:   "<optional>"
  date:       2020-03-29 16:00:32
  author:     "awn"
  header-img: "<optional>"  #eg: /img/xx.jpg
  catalog:    true  #是否显示目录
  tags:
      - C/C++ 
  ---
  ```

- markdown图片，只能使用绝对路径，放在root目录的img中，文章中使用 `![](/img/xxx.jpg)`
- 发布新文章后，要用本github先访问一次，不然此文章的gitalk显示异常（未找到相关的 [Issues](https://github.com/Awnway/BlogComment/issues) 进行评论 请联系 xxxx 初始化创建）

###  2 local server调试
需要安装ruby jekyll...（网上搜教程）   
使用，进入blog目录，cmd: jekyll server

## Blog主题配置相关
基于hux Theme的一些改动     
- [x] 修改导航栏的显示名称
- [x] 添加gitalk评论系统
- [x] 修改Archive页面（short = false）,使得页面和其他页面统一
- [x] 删除各页面header img，加快网页加载速度（后面可能换一些小图片）
- [ ] 添加文章访问量 网页访问量的界面显示
- [ ] 修改导航栏添加方式，改为写死的方式，而不是通过获取root目录的page



## 致谢
本blog主题来自于[hux](https://github.com/huxpro/huxpro.github.io/) ，感谢hux制作出如此优秀的主题。

