.. Redis 实战 documentation master file, created by
   sphinx-quickstart on Tue Jun 24 13:59:13 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Redis 实战
======================================

.. image:: ria-cover.png
   :align: left
   :scale: 23

《Redis in Action》是由 Josiah Carlson 博士编写，
Manning 出版社出版的一本关于 Redis 应用方面的书籍，
该书深入浅出地介绍了 Redis 的五种数据类型，
并通过多个实用例子展示了 Redis 的用法，
除此之外，
该书还讲述了 Redis 的优化方法以及扩展方法，
是一本对于学习和使用 Redis 来说不可多得的参考书籍。

《Redis 实战》是《Redis in Action》一书的简体中文翻译版，
译者为黄健宏（huangz），
**翻译工作目前正在进行中，**
翻译完成之后将由人民邮电出版社出版。

要了解本书的最新消息，
以及目前的翻译进度，
请定期访问本网站，
或者关注译者的\ `微博 <http://weibo.com/huangz1990>`_\ 、\ `豆瓣 <http://www.douban.com/people/i_m_huangz/>`_\ 、\ `twitter <https://twitter.com/huangz1990>`_\ 。


目录以及翻译进度
------------------

以下表格展示了《Redis in Action》一书的各个章节，
以及这些章节目前的翻译进度。


+---------------------------------------------------+-----------+
| 章节                                              | 翻译进度  |
+===================================================+===========+
| 序                                                | 已完成    |
+---------------------------------------------------+-----------+
| 前言                                              | 已完成    |
+---------------------------------------------------+-----------+
| 致谢                                              | 已完成    |
+---------------------------------------------------+-----------+
| 关于此书                                          | 已完成    |
+---------------------------------------------------+-----------+
| 关于本书封面插图                                  | 已完成    |
+---------------------------------------------------+-----------+
| 第 1 章： 初识 Redis                              | 已完成    |
+---------------------------------------------------+-----------+
| 第 2 章： 使用 Redis 构建 web 应用                | 已完成    |
+---------------------------------------------------+-----------+
| 第 3 章： Redis 命令                              | 已完成    |
+---------------------------------------------------+-----------+
| 第 4 章： 数据安全与性能保障                      | 已完成    |
+---------------------------------------------------+-----------+
| 第 5 章： 使用 Redis 构建支持程序                 | 已完成    |
+---------------------------------------------------+-----------+
| 第 6 章： 使用 Redis 构建应用组件                 | 已完成    |
+---------------------------------------------------+-----------+
| 第 7 章： 基于搜索的应用程序                      | 进行中    |
+---------------------------------------------------+-----------+
| 第 8 章： 构建简单的社交网站                      | 已完成    |
+---------------------------------------------------+-----------+
| 第 9 章： 减少内存占用                            | 进行中    |
+---------------------------------------------------+-----------+
| 第 10 章： 扩展 Redis                             | 未开始    |
+---------------------------------------------------+-----------+
| 第 11 章： 使用 Lua 语言在 Redis 中进行脚本编程   | 未开始    |
+---------------------------------------------------+-----------+
| 附录 A ： 快速安装步骤                            | 已完成    |
+---------------------------------------------------+-----------+
| 附录 B ： 其他资源以及引用参考                    | 已完成    |
+---------------------------------------------------+-----------+


作者简介
------------

在大学毕业之后，
Josiah Carlson 博士继续在加州大学欧文分校学习理论计算机科学。
在学习之余，
Josiah 还断断续续地做过一些助教工作，
并偶尔承接一些编程方面的工作。
在 Josiah 即将要研究生毕业的时候，
他发现教职方面的工作机会并不多， 
于是他加入了 Networks in Motion 公司，
开始了自己的职业生涯。
在 Networks in Motion 公司期间，
Josiah 负责开发实时 GPS 导航软件，
以及交通事故通知系统。

在离开 Networks in Motion 公司之后，
Josiah 加入了 Google 公司，
之后他又到了 Adly 公司工作，
并开始学习和使用 Redis 来构建内容定向广告系统（content-targeting advertising）和 Twitter 分析平台。
几个月之后，
Josiah 加入了 Redis 邮件列表，
并在那里回答了数百个关于使用和配置 Redis 的问题。
在离开 Adly 公司并成为 ChowNow 公司的首席架构师兼联合创始人之后不久，
Josiah 开始创作这本《Redis 实战》。

要了解关于《Redis 实战》作者 Josiah Carlson 博士的更多信息，
请访问他的 `twitter <https://twitter.com/dr_josiah>`_ 、 `博客 <http://www.dr-josiah.com/>`_ 或者 `github <https://github.com/josiahcarlson>`_ 。


译者简介
------------

黄健宏（huangz）在 2011 年开始接触 Redis 以来就一直在学习和研究 Redis ，
他从 Redis 2.4 开始阅读并追踪 Redis 的源码，
对 `Redis 2.6 <https://github.com/huangz1990/annotated_redis_source>`_ 以及 `Redis 3.0 <https://github.com/huangz1990/redis-3.0-annotated>`_ 的源码进行了详细的注释，
并通过分析源码创作了\ `《Redis 设计与实现》 <http://redisbook.com>`_\ 一书。

除此之外，
黄健宏还是 Redis 中文文档\ `《Redis 命令参考》 <http://RedisDoc.com>`_\ 的译者，
以及\ `《Redis 从入门到精通》课程 <http://www.chinahadoop.cn/course/53>`_\ 的讲师。

要了解关于《Redis 实战》译者黄健宏（huangz）的更多信息，
请访问他的个人主页 `huangz.me <http://huangz.me>`_ 。


相关资源
-----------

《Redis in Action》在 Manning 出版社的介绍页面：
http://www.manning.com/carlson/

《Redis in Action》书中的源码示例：
https://github.com/josiahcarlson/redis-in-action

《Redis in Action》在 
`亚马逊 <http://www.amazon.cn/Redis-in-Action-Carlson-Josiah-L/dp/1617290858>`_ 、 
`amazon.com <http://www.amazon.com/Redis-Action-Josiah-L-Carlson/dp/1617290858>`_ 
以及
`豆瓣 <http://book.douban.com/subject/10597898/>`_ 
的页面。
