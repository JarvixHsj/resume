# 个人信息

 - 朱静迪/男/1998
 - 专业：**计算科学与技术专业**
 - 期望职位：后端工程师(不限语言)/测试开发工程师
 - 期望城市：**不限**
 - 本科：温州商学院 2016/9 - 2020/6
---

# 联系方式


<p style="position:absolute;left:70%">
    <img src="https://github.com/xiantang/resume/blob/master/image/a32c252efda587d2062785de59b78a6.jpg?raw=true" alt="Sample"  width="100" height="100">
</p>


- 手机：15868759135 
- 微信号：b986494553
- Email：zhujingdi1998@gmail.com
- Github: [xiantang](https://github.com/xiantang)
- Twitter: [xiantang98](https://twitter.com/xiantang98)
- Blog：[咸糖的博客](http://xiantang.info)

---


#  工作经历

## 2019.10-2020.03 Growing IO (Scala 服务端实习生)
* 简介:
    * Growing IO 是一款支持无埋点的数据分析产品，通过集成 SDK 快速实现数据驱动，以及精细化运营。
* 工作内容:
    * 负责推送业务健壮性的维护，使用 `akka` 完成对推送的重试特性开发，将推送的送达率提升 `5%`。阅读 `RateLimiter` 源码，开发分布式的限流组件`RedisLimiter` 进行 `削峰` 将 `100w+` 的大用户量查询平缓化。
    * 协助导师完成 `100w+` 用户的推送性能提升，采用 `grpc` 与 `kafka` 异步文件下载的方式，降低了数据端的压力并且提升了 `50%` 的推送速度，完成 `5 min 推送 100w 用户`的目标。
    * 负责服务端接口封装 `API Java SDK`开发，使用 `TDD` 测试驱动开发，将测试覆盖率提升至 `80%`。
    * 独立完成`中型模块`的需求的后端开发，编写技术文档主持评审会议，与前端测试产品充分交流，编写单元测试通过 code review 并上线。
    * 积极参与项目中的 `code review` 环节，与组内同事互相评审代码，消灭代码中的`坏味道`。



## 2019.05-2019.08 北京爱奇艺科技有限公司(基础架构部 Java 服务端实习生)
* 简介:
    * 使用 Git 工作流参与QLB(QIYI Load Balance)的后端日常开发与 `BUG` 修复。
* 工作内容:
    * 负责`分布式定时任务调度功能`的开发，支持动态任务调度(反射解耦)。
    * 将项目中部分串行的操作，使用线程池并发完成，提高了接口至少 `50%` 的查询速度。


# 个人项目经历
<p align="left">
    <img src="https://i.loli.ma/pic/e43d059f917e888605efd06119001557.png" alt="Sample"  width="400" height="100">
</p>

### [NIO Servlet Container](https://github.com/xiantang/JerryMouse)
* 简介:
    * 基于Java NIO 多线程、XML 解析、log4j 日志的 HTTP 服务器和 Servlet 容器，并实现 `热加载/热部署` 功能。
* 技术细节:
    * 整个项目使用 `TDD` 测试驱动开发，代码的单元测试覆盖率在 `70%`。
    * 阅读 paper [《Scalable IO in Java》](http://gee.cs.oswego.edu/dl/cpjslides/nio.pdf) 并构建实现`可伸缩`的高性能IO模型`Reactor`。
    * 为了实现多 Web `服务之间的隔离`与`运行时应用的装载卸载`，编写`自定义类加载器`对用户代码进行加载。
    * 配置 `travis-ci` 对于合并与提交的 commits 执行自动化测试。
* 总结:
    * 使用JMeter进行压力测试：connection:close 以下测试总请求次数都为 20000 次2个线程，每个线程循环访问10000次，吞吐量为 `630` 个请求/sec。

## 技术栈
* **语言**: 熟悉 Java(NIO，并发，JVM)，Scala(函数式编程)，Python(装饰器，爬虫，脚本)
* **框架**: 熟悉 Spring 全家桶，Scrapy 了解 PlayFrameWork Slick Akka
* **数据库**: 熟悉 Mysql Redis
* **工具**: 熟练运用 Linux 命令行操作
* **其他**: TDD 教徒 有代码洁癖


## 获得奖项
* **2018第一届全国大数据竞赛二等奖**
* **2018年学业三等奖学金**
