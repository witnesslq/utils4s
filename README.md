<h1 id="id1">utils4s</h1>

[![Build Status](https://travis-ci.org/jacksu/utils4s.svg?branch=master)](https://travis-ci.org/jacksu/utils4s)[![Join the chat at https://gitter.im/jacksu/utils4s](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/jacksu/utils4s?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

*   [utils4s](#id1)
    *   [scala语法学习](#id2)
    *   [common库](#id21)
    *   [BigData库](#id22)
        *   [Spark](#id221)
            *   [Spark core](#id2211)
            *   [Spark Streaming](#id2212)
            *   [Spark DataFrame](#id2213)
            *   [Spark 机器学习](#id2213)
            *   [Spark 其它](#id2214)
        *   [ES](#id222)
    *   [贡献代码步骤](#id23)
    *   [贡献者](#id24)

utils4s包含各种scala通用、好玩的工具库demo和使用文档，通过简单的代码演示和操作文档，各种库信手拈来。

**同时欢迎大家贡献各种好玩的、经常使用的工具库。**

[开源中国地址](http://git.oschina.net/jack.su/utils4s)

QQ交流群 `432290475`

微博：[**jacksu_**](http://weibo.com/jack4s)

<h2 id="id2">scala语法学习</h2>

说明：scala语法学习过程中，用例代码都放在scala-demo模块下。

[快学scala电子书](http://vdisk.weibo.com/s/BP8uNBebkvpOe)(推荐入门级书)

[scala理解的比较深](http://hongjiang.info/scala/)

[scala99问题](http://aperiodic.net/phil/scala/s-99/)

[scala初学者指南](https://windor.gitbooks.io/beginners-guide-to-scala/content/introduction.html)(这可不是初学者可以理解的欧，还是写过一些程序后再看)

[scala初学者指南英文版](http://danielwestheide.com/scala/neophytes.html)

[scala学习用例](scala-demo)

<h2 id="id21">common库</h2>

[日志操作](log-demo)（[log4s](https://github.com/Log4s/log4s)）

[单元测试](unittest-demo)（[scalatest](http://www.scalatest.org)）

[日期操作](lamma-demo)（[lama](http://www.lamma.io/doc/quick_start)）（注:只支持日期操作，不支持时间操作）

[日期时间操作](nscala-time-demo)（[nscala-time](https://github.com/nscala-time/nscala-time)）（注：没有每月多少天，每月最后一天，以及每年多少天）

[json解析](json4s-demo)（[json4s](https://github.com/json4s/json4s)）

[resources下文件加载用例](resources-demo)

[文件操作](file-demo)（[better-files](https://github.com/pathikrit/better-files)）

[单位换算](analysis-demo)（[squants](https://github.com/garyKeorkunian/squants)）

[线性代数和向量计算](breeze-demo)([breeze](https://github.com/scalanlp/breeze))

[分布式并行实现库akka](akka-demo)([akka](http://akka.io))

[Twitter工具库](twitter-util-demo)（[twitter util](https://github.com/twitter/util)）

<h2 id="id22">BigData库</h2>

<h3 id="id221">Spark</h3>

<h4 id="id2211">Spark core</h4>
[一个不错的spark学习互动课程](http://www.hubwiz.com/class/5449c691e564e50960f1b7a9)

[spark 设计与实现](http://spark-internals.books.yourtion.com/index.html)

<h4 id="id2212">Spark Streaming</h4>

[spark streaming测试用例](sparkstreaming-demo)

[spark streaming源码解析](https://github.com/proflin/CoolplaySpark)

[基于spark streaming的聚合分析(Sparkta)](https://github.com/Stratio/Sparkta)

<h4 id="id2213">Spark DataFrame</h4>

[spark DataFrame测试用例](spark-dataframe-demo)

[Hive Json加载](hive-json-demo)

<h4 id="id2213">Spark 机器学习</h4>

[spark TS](spark-timeseries-demo)

<h4 id="id2214">Spark 其它</h4>

[spark学习知识总结](spark-knowledge)

[图处理(cassovary)](https://github.com/twitter/cassovary)

[基于spark进行地理位置分析(gagellan)](https://github.com/harsha2010/magellan)

<h3 id="id222">ES</h3>

[ES 非阻塞scala客户端](https://github.com/sksamuel/elastic4s)
<h2 id="id23">贡献代码步骤</h2>
1. 首先 fork 我的项目
2. 把 fork 过去的项目也就是你的项目 clone 到你的本地
3. 运行 git remote add jacksu git@github.com:jacksu/utils4s.git 把我的库添加为远端库
4. 运行 git pull jacksu master 拉取并合并到本地
5. coding
6. commit后push到自己的库( git push origin master )
7. 登陆Github在你首页可以看到一个 pull request 按钮,点击它,填写一些说明信息,然后提交即可。
1~3是初始化操作,执行一次即可。在coding前必须执行第4步同步我的库(这样避免冲突),然后执行5~7既可。

<h2 id="id24">贡献者</h2>
[jjcipher](https://github.com/jjcipher)