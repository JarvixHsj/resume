

# 联系方式

- 手机：15868759135 
- Email：986494553@qq.com 
- QQ/微信号：986494553

---

# 个人信息

 - 朱静迪/男/1998
 - 本科/温州大学城市学院计算机系 
 - 技术博客：http://www.zhanshengpipidi.cn/blog/ 
 - Github：https://github.com/xiantang?tab=repositories

 - 期望职位：Python爬虫实习生，java后端实习生
 - 期望薪资：3k~5k
 - 期望城市：上海

---

# 生活照片
![Mou icon](http://www.zhanshengpipidi.cn/media/img_post/P70111-2307411.jpg)


# 在校外包经历

### 知乎问题爬虫项目
使用scrapy框架编写爬虫爬取知乎2016-2017年 50w 条问题的标题描述和关注数，在这个项目中我遇到的最大问题是如何设计爬虫架构，期间尝试了scrapy 框架中的crawlSpider，但是效果不佳，最后突然想到能够通过修改之前写的用户爬虫的爬取的接口，从用户信息接口转为爬取用户问题接口，再筛选问题的时间，最终解决了问题，历时一周。在这个项目中我最满意的是通过定时爬取免费的ip使用redis数据库维护了一个代理池，代理池分别有100+条http/https代理，解决了被网站封禁的问题，在加上这个模块后，爬虫一次性爬取了剩下的45w条数据，原定在30天内完成的项目只用了7天就采集完了。




# 开源项目和作品

### 个人技术博客
使用django+bootstarp搭建的个人博客，在这个项目中我遇到的最大的问题是对django的view 和 model没有理解，导致项目停滞了一段时间，在对数据库和orm有了一定了解后一步一步看着django的文档完成了项目，在这个项目中我最满意的是博文支持Markdown语法，能够写出图文结合的博客，使读者在阅读博客的时候能够产生较好的阅读体验。这个博客对我意义很大，每当我对某些技术有新的见解的时候，我都会打开我的网站写上一篇文章，现在我的技术博客已经有20篇技术文章了，并且不断在更新。

### 狗年抢红包游戏
使用java swing 编写狗年抢红包游戏，在这个项目中我遇到的最大的问题是无法实现多键监听，经过翻阅了很多的相关博客，最后选择在每个方向上都设置一个布尔值，在鼠标按下的时候转换为True，松开后变换为False，分别将跳跃和左右移动写入到两个不同线程中，最后解决了问题。在这个项目中我最满意的是我编写的重力类，修改了队友在跳跃线程内设置下落距离来落地的方式，并且解决了无法从高出下落的BUG，保证狗子能在跳跃后顺利下落，优化了跳跃的思路，对之后的编写产生了至关重要的作用。

### 京东商品爬虫
基于scrapy-redis 使用代理服务器池提供代理进行爬取，在这个项目中最让我疑惑的是scrapy-redis是如何实现多台机子共同爬取，和朋友一起研究源码并探讨后得出，scrapy-redis重写了scrapy的调度和队列，将爬取队列存在了redis中的request中，各台机器都通过连接redis取出request并下载，我们还发现scrapy-redis去重手段十分有趣，采用哈希散列的方法将参数位置不同的url生成相同的哈希地址。这个项目最让我满意的是在并发开启为10的情况下每天能够有10w+条商品60w+评论入库。 



## 技术文章

- [爬虫遭遇状态码521陷阱 破解js加密cookie](https://blog.csdn.net/qq_27302597/article/details/79411808)



# 技能清单

以下均为我熟练使用的技能

- 数据采集: scrapy/selenium/requests/urllib
- Web开发：Python/Java
- Web框架：Django/Jsp
- 前端框架：Bootstrap/HTML5
- 数据库相关：Sqlserver/Mysql/redis(了解)
- 版本管理、文档和自动化部署工具：git


---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
