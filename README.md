# myBlog

尝试写一个自己的博客，前后端都由自己起来完成，感觉是个很大的项目，准备一点一点来，功能方面也是先 从简单的开始，以后再慢慢迭代。

#预期将要使用的技术

后端: Python Django jinjia2 SQLite 

前端: vue sass gulp 

# V 1.0.0
后端部分实现博客相关的内容在数据库的读写和储存

参考资料：

[Leo_wlCnBlogs](http://www.cnblogs.com/Leo_wl/p/5824541.html "Title")

[Danny's Blog](http://www.dannysite.com/blog/?cat=3 "Title")


2016.11.22

#V 1.0.1
修复了博客创建日期的问题；

修复了admin页面css缺失的问题；

增加了静态文件目录，能够在template中引入css，js

制造了博客详情页面打不开的新问题...OTL

2016.11.23

#V 1.0.2
修复了详情页不能打开以及提交评论出错的问题；（根据报错猜测是数据库中email字段的问题，搜索到了pycharm能够可视化管理SQLite，打开之后发现确实少了email字段，手动添加表之后，问题解决。半猜半蒙的搞定了，我真机智啊哈哈哈哈哈(～￣▽￣)～）


2016.11.24