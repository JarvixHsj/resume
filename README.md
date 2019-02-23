

# 联系方式

- 手机：15868759135 
- Email：zhujingdi1998@gmail.com
- QQ/微信号：986494553

---

# 个人信息

 - 朱静迪/男/1998
 - 本科/温州大学城市学院计算机系 
 - 技术博客：http://www.zhanshengpipidi.cn
 - Github：https://github.com/xiantang
 - 期望职位：java后端实习生
 - 期望薪资：3k~5k
 - 期望城市：杭州

---


# 开源项目和作品
## Java项目

### 共享单车微信小程序
* 简介：
    * 基于Spring Boot和腾讯地图的共享单车小程序。
* 技术细节:
    * 调用聚合数据的短信api发送短信，使用Redis对用户手机验证码进行为期`60s`的缓存。
    * 利用MongoDB的地理位置索引`2dsphere`,对球面上附近地点的单车进行查询，实现在加载地图和移动地图的时候，加载附近的单车。
* Github:[共享单车微信小程序](https://github.com/xiantang/bike)

### Android仿知乎日报
* 简介:
    * 一个轻量版的知乎日报，加载更快，体积更小。
* 负责模块:
    * 产品数据库设计
    * 首页模块设计
    * 重构项目
* 技术细节:
    * 使用`fiddler`确定知乎日报接口。
    * 使用`jsoup`对知乎接口返回的`HTML`进行裁剪。
    * 使用开源的`RecyclerView`代替原生的`ListView`，利用`volley`异步请求库，进行数据获取。
* Github:[Android仿知乎日报](https://github.com/wzbcCoder/ZhiHuDaily)
## Python项目
### 个人技术博客
* 简介：
    * 使用django+bootstarp搭建的个人博客。
* 技术细节：
    * 前端使用`edit.js`库，提升用户的写博文时的体验，后端使用`markdown`库，将`Markdown`文档渲染为`HTML`进行展示。
* Github:[个人技术博客](https://github.com/xiantang/myblog)



### 京东全站商品爬虫
* 简介：
    * 基于scrapy-redis的京东全站增量爬虫。
* 技术细节:
    * 重构爬虫的`pipeline`,使用**有限状态机**省去了繁杂的`if-else`代码。
    * 通过阅读和修改`scrapy-redis`源码，将原来基于`redis` `set`的去重对列，改为基于布隆过滤器的实现，提高了去重的效率。
    * 使用`scrapyd`的api编写脚本控制爬虫的状态，达到增量爬取的效果。
    * 使用`docker` 进行爬虫的批量部署。
* 总结:
    * 爬虫部署在三台`ubuntu`云服器上，并稳定爬取。
    * 只需三天就可以完成对京东的`1100w`商品数据的价格监控，每日能够记录`3W+`条价格更新。

# 在校外包经历

### 知乎问题爬虫项目
* 简介：
    * 使用scrapy框架编写爬虫爬取知乎2016-2017年 50w 条问题的标题描述和关注数。
* 技术细节：
    * 爬虫架构设计：使用DFS遍历，从某知乎大V开始，分别将大V的关注和粉丝加入队列，通过fiddler获取知乎对应用户的问题api，并过滤问题。
    * IP代理池设计：使用芝麻代理，使用redis维护了一个代理池，定期检查IP池内部IP的可用性。
    * 部署: 使用ubuntu云服器进行部署。
* 成果:
    * 通过代理池，使爬虫更加`Robustness`。
    * 原定在30天的采集计划于7天内完成。

#  工作以及开发经历
## 2018.07-2018.09 我和我们文化传播  
* 简介:
    * 负责豆瓣全站电影数据增量采集
    




## 技术文章

- [爬虫遭遇状态码521陷阱 破解js加密cookie](https://zhuanlan.zhihu.com/p/40321850)  收获73个赞同，330个收藏。

## 获得奖项
* **2018第一届全国大数据竞赛二等奖**
* **2018年学业三等奖学金**

# 技能清单

以下均为我熟练使用的技能

- Web开发：Java/Python
- 数据采集：scrapy/selenium/requests/urllib
- 后端框架：Spring Boot/Django/ssm
- 前端框架：Bootstrap
- 数据库相关：Mysql/redis(了解)/sqlserver
- ORM框架：mybatis
- 项目构建：maven
- 版本管理、文档和自动化部署工具：git
- 运维: linux(terminal),docker

# 我的优势
## 代码之内
* 热爱开源，Github 2018年贡献`990+` Commits。
* 喜欢总结, [个人博客](zhanshengpipidi.cn)拥有博文40余篇，方向包括但不限于`machine-learning`，`算法`，`Linux`。
* 有刷题的喜欢,在`leetcode`上`Accepted`的题目 150+ 。
* 具有自我驱动能力，由于有较扎实的CS基础，学习语言和新技术较快，遇到问题会先思考再通过`Stack Overflow`/`Google`来解决问题。
## 代码之外
* 喜欢健身，在钻研技术的同时保持良好的体魄。


---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
