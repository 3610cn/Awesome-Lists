[![返回目录](https://user-images.githubusercontent.com/5803001/38079637-ff0abcf0-3371-11e8-9b76-ad651620afc7.jpg)](https://github.com/wxyyxc1992/Awesome-Lists)

# Service Availability List

本文是对于服务端应用程序开发与系统架构领域中高可用系统搭建相关资料进行整理，更多的其他相关优秀资料可以参考笔者的 [AwesomeList](http://6me.us/qvPQ) 系列，其他的还包括[追求技术之上的进阶阅读学习索引](https://zhuanlan.zhihu.com/p/25642783) 、 [机器学习、深度学习与自然语言处理领域推荐的书籍列表](https://zhuanlan.zhihu.com/p/25612011)等等。随着公司业务的发展与终端用户的增加，保证系统的高可用性也日渐成为团队考虑的重要因素。

* [如何在云平台构建大规模分布式系统](http://www.infoq.com/cn/articles/build-a-large-scale-distributed-system)

* [LinkedIn 架构这十年 ](http://colobu.com/2015/07/24/brief-history-scaling-linkedin/)

* [构建能够每秒处理 3 百万请求的高性能 Web 集群系列文章](http://blog.jobbole.com/87509/)

* [根据 PV 计算带宽及根据 PV 算并发](http://www.tuicool.com/articles/aqi6Znr)

* [C1000K-Servers #Project#](https://github.com/smallnest/C1000K-Servers): High performance websocket servers implemented by Spray-can, Netty, undertow, jetty, Vert.x, Grizzly, node.js and Go. It supports 1,200,000 active websocket connections.

# 概览

* [2015-Practical Scalability Analysis With The Universal Scalability Law #Book#](https://parg.co/bNA): I wrote this book to help you understand the simple, but profoundly powerful, truths about scalability.

* [2016- 究竟啥才是互联网架构 “ 高可用 ”](http://6me.us/Fz25N7)

* [2017-The System Design Primer](https://github.com/donnemartin/system-design-primer): Learn how to design large scale systems. Prep for the system design interview.

* [2017- 大话程序猿眼里的高并发](https://blog.thankbabe.com/2016/04/01/high-concurrency/)：高并发是指在同一个时间点，有很多用户同时的访问 URL 地址，比如：淘宝的双 11，双 12，就会产生高并发 , 如贴吧的爆吧，就是恶意的高并发请求，也就是 DDOS 攻击，再屌丝点的说法就像玩撸啊撸被 ADC 暴击了一样 , 那伤害你懂得 ( 如果你看懂了，这个说法说明是正在奔向人生巅峰的屌丝。

* [2017- 微信高并发资金交易系统设计方案 —— 百亿红包背后的技术支撑](http://mp.weixin.qq.com/s/suBAJrP6uN2kFgHtGz16mw)：本文将为读者介绍百亿级别红包背后的系统高并发设计方案，包括微信红包的两大业务特点、微信红包系统的技术难点、解决高并发问题通常使用的方案，以及微信红包系统的高并发解决方案。

* [2017- 如何提升 Web 后端性能？我的 4 个实践和总结](http://mp.weixin.qq.com/s/KsXS5f-1-217CY5R88qOHQ)：随着互联网的不断发展，日常生活中越来越多的需求通过网络来实现，从衣食住行到金融教育，从口袋到身份，人们无时无刻不依赖着网络，而且越来越多的人通过网络来完成自己的需求。作为直接面对来自客户请求的 Web 服务端，无疑是要同时承受更多的请求，并为用户提供更好的体验。这个时候 Web 端的性能常常会成为业务发展的瓶颈，提升性能刻不容缓。本文作者在开发过程中总结了一些提升 Web 服务端性能的经验，与大家分享。

* [2017- 去哪儿 - 超时，重试，熔断，限流](http://mp.weixin.qq.com/s/wIQIv4TAHRIqR_X9iSz3Hw)

* [乐视秒杀：每秒十万笔交易的数据架构解读 ](http://www.uml.org.cn/sjjm/201611184.asp)

* [晓明 美团点评技术团队 常见性能优化策略的总结](http://tech.meituan.com/performance_tunning.html)

# 性能压测

* [open-source-database-testing-tools](http://www.softwaretestingmagazine.com/tools/open-source-database-testing-tools/)

- [扛住 100 亿次请求？我们来试一试](https://github.com/xiaojiaqi/10billionhongbaos/wiki/%E6%89%9B%E4%BD%8F100%E4%BA%BF%E6%AC%A1%E8%AF%B7%E6%B1%82%EF%BC%9F%E6%88%91%E4%BB%AC%E6%9D%A5%E8%AF%95%E4%B8%80%E8%AF%95)

- [蚂蚁金服技术专家对性能优化的常见模式及趋势的思考](https://yq.aliyun.com/articles/54004)

* [高并发性能调试经验分享](https://zhuanlan.zhihu.com/p/21348220)

* [基于 Locust、Tsung 的百万并发秒杀压测案例](http://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=405352450&idx=1&sn=77485a9f0d1e504c8a6068e3b60f81c7&scene=23&srcid=0417zuijO8QFRZo2rVYeqltv#rd)

* [如何生成每秒百万级别的 HTTP 请求？](http://blog.jobbole.com/87509/)

* [模拟百万级 TCP 并发](http://mp.weixin.qq.com/s?__biz=MzIxMjAzMDA1MQ==&mid=2648945745&idx=1&sn=422c7dd658ba83a42f5753669716378f&chksm=8f5b535db82cda4b281dfab3858e4afa6e6b453d0b77f5dd5d3f8ca3e33184fa470803d4d21e#rd)

* [性能测试应该怎么做？](http://coolshell.cn/articles/17381.html)

* [k6 #Project# ](https://github.com/loadimpact/k6): k6 is a modern load testing tool, building on Load Impact's years of experience. It provides a clean, approachable scripting API, distributed and cloud execution, and orchestration via a REST API.

- [sysbench 0.5 性能测试工具使用手册](http://blog.csdn.net/clh604/article/details/12108477)

- [wrk](https://github.com/wg/wrk)

- [Webbench]()

- [Vegeta](https://github.com/tsenart/vegeta)

- [Locust]()

- [Gauge](https://github.com/getgauge/gauge)

* [Twitter-Diffy](https://github.com/twitter/diffy): 比较新老系统之间服务差异

* [Using iPerf to Troubleshoot Speed/Throughput Issues](http://blog.softlayer.com/2011/using-iperf-to-troubleshoot-speedthroughput-issues)

- [性能测试中服务器关键性能指标浅析](http://www.tuicool.com/articles/B3IFBbe)

- [认清性能问题](http://mp.weixin.qq.com/s?__biz=MzAxMTEyOTQ5OQ==&mid=2650610655&idx=1&sn=4f38ef56ff57054ab9745b0725351159#rd)

# 负载均衡

* [How we fine-tuned HAProxy to achieve 2,000,000 concurrent SSL connections](https://medium.freecodecamp.com/how-we-fine-tuned-haproxy-to-achieve-2-000-000-concurrent-ssl-connections-d017e61a4d27)

* [Nginx/LVS/HAProxy 负载均衡软件的优缺点详解](http://os.51cto.com/art/201407/446441.htm)

- [Google 是如何做负载均衡的？](https://zhuanlan.zhihu.com/p/23826170)

- [分布式系统中负载均衡算法在高可用场景下的分析](http://tech.youzan.com/load-balancing-algorithm/)

- [多种负载均衡算法及其 Java 代码实现](http://www.duzhi.me/article/864.html)

- [负载均衡的那些算法们 ](http://mp.weixin.qq.com/s?__biz=MzA3MDExNzcyNA==&mid=2650392075&idx=1&sn=fca2ebeca258e15f78a43c44bbb6153d&scene=0#wechat_redirect)

- [Nginx 负载均衡系列](http://blog.csdn.net/zhangskd/article/details/50208527)

- [章文嵩(正明)博士和他背后的负载均衡 (LOAD BANLANCER) 帝国](https://yq.aliyun.com/articles/52752)

- [荔枝 FM 架构师刘耀华：异地多活 IDC 机房架构](http://geek.csdn.net/news/detail/53231)

- [异地多活设计难？其实是你陷入了这四大误区出不来！](http://mp.weixin.qq.com/s?__biz=MjM5MDE0Mjc4MA==&mid=2650993345&idx=1&sn=f460c51ad3dfd1da4d41e0a408969c54&scene=0#wechat_redirect)

## LVS

* [Linux 服务器集群系统](http://www.linuxvirtualserver.org/zh/lvs1.html)

- [LVS+Keepalived 构建高可用负载均衡](http://os.51cto.com/art/201202/317441.htm)

- [Ali-LVS](https://github.com/alibaba/LVS)

# 服务限流

* [2017-An alternative approach to rate limiting](https://medium.com/figma-design/an-alternative-approach-to-rate-limiting-f8a06cf7c94c)

- [2017- 服务流量控制及限流](http://blog.brucefeng.info/post/rate-limiter): 流量控制的维度主要有 QPS 流量控制以及一定时间区间(如 / 天、/ 小时)的调用次数。

- [2018-Sentinel 实战 #Series#](https://mp.weixin.qq.com/s/rjyU37Dm-sxNln7GUD8tOw): Sentinel 的三大功能： 限流 降级 系统保护。

# 服务容错

* [服务容错模式](http://tech.meituan.com/service-fault-tolerant-pattern.html)

* [亿级 Web 系统的容错性建设实践](https://stgod.com/2120)

# 系统降级

* [服务降级背后的技术架构设计](http://mp.weixin.qq.com/s/cfWwjhKgDXMSQ3BzJ_S2Ag)

* [2017-Scaling your API with rate limiters](https://stripe.com/blog/rate-limiters)

# 秒杀峰值

* [2016- 携程 - 一个经验证可落地的秒杀系统实践思路 ](http://6me.us/ChFx0)：为什么要做秒杀？这个不难解释，最起码对于互联网电商业务来说很常见，那怎么样才能设计出相对比较完善的秒杀策略呢？我觉得这其中有两个关键。

* [2016- 淘宝 - 大秒系统设计详解 | 许令波 | 文末有福利](http://6me.us/YJG)：最初的秒杀系统的原型是淘宝详情上的定时上架功能，由于有些卖家为了吸引眼球，把价格压得很低。但这给的详情系统带来了很大压力，为了将这种突发流量隔离，才设计了秒杀系统，文章主要介绍大秒系统以及这种典型读数据的热点问题的解决思路和实践经验。

* [秒杀系统架构分析与实战](http://developer.51cto.com/art/201601/503511.htm)

* [乐视秒杀：每秒十万笔交易的数据架构解读](http://dbaplus.cn/news-21-420-1.html)

* [阿里价值 “ 千万 ” 的秒杀场景参数优化](http://dbaplus.cn/news-21-457-1.html)

* [四种框架分别实现百万 websocket 常连接的服务器](http://blog.jobbole.com/103995/)

* [七种 WebSocket 框架的性能比较](http://blog.jobbole.com/103994/)

* [秒杀系统架构优化思路 ](https://mp.weixin.qq.com/s?__biz=MzA4NDc2MDQ1Nw==&mid=2650238120&idx=1&sn=b769692f21dd70ab64b118fc7fecf3c4&chksm=87e18e4eb09607581db3769df7a50526658d8b9ffea0d19523b875e8c682eb790ee4291904dc&scene=0&key=&ascene=7&uin=&devicetype=android-22&version=26031c38&nettype=WIFI)

* [2017- 如何设计一个小而美的秒杀系统？](https://parg.co/by3)
