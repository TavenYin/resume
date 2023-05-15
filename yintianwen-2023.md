# 基本信息

- 殷天文/男/1995
- 专科/大连软件职业学院/软件工程
- 工作年限：5.5年
- 电子邮箱：yintianwen7@qq.com
- 电话：18741555096
- 博客：http://yintianwen.top
- 简书：https://www.jianshu.com/u/cd682de00804
- 知乎：https://www.zhihu.com/people/yintianwen
- Github: https://github.com/TavenYin
- 公众号：殷天文
- 期望岗位：高级Java工程师 / 架构师



# 专业技能

- 精通Java, 扎实的Java基础, 熟练掌握多线程、IO等技术, 了解JVM 
- 对优秀开源项目源码学习有浓厚的兴趣, 有开源项目贡献经验
- 熟练掌握微服务框架技术, 丰富的微服务架构实战经验
- 熟练掌握微服务中网关、服务调用、熔断限流、链路追踪、服务治理等技术
- 精通Spring Cloud、Spring Cloud Alibaba、Spring Boot等常用微服务框架, 并深入分析过其实现原理
- 熟练掌握MySQL/Redis/Oracle等数据库, 熟悉Elasticsearch/MongoDB/Postgres等数据库
- 熟练掌握RabbitMQ、RocketMQ、Kafka。对消息队列持久化方案有深入研究
- 熟练掌握不停机数据库迁移解决方案（Debezium + Kafka）
- 掌握Seata等分布式事务解决方案
- 熟悉PHP/JavaScript/Lua等语言的开发
- 熟悉Linux/Shell
- 熟悉Docker/Kubernetes



# 原创博客 / 开源项目
- [jasypt 贡献的 PR](https://github.com/ulisesbocchio/jasypt-spring-boot/pull/344)
- [jasypt 3.0.4 Bug 分析与解决](https://www.jianshu.com/p/612fbce0484f)
- [聊聊 Redis 分布式锁](https://www.jianshu.com/p/37a4eedc9041)
- [Spring Kafka：Retry Topic、DLT 的使用与原理](https://www.jianshu.com/p/8498ee18d993)
- [深入理解 Sentinel 中的限流算法](https://www.jianshu.com/p/5d26fe1dec3b)
- [Opentracing 链路追踪实战](https://www.jianshu.com/p/b6114ab00978)
- [聊聊 IO 多路复用](https://www.jianshu.com/p/9ebd4fd8c892)
- [数据库CDC (Change Data Capture) 核心技术](https://github.com/TavenYin/database-cdc)
- [深入理解 Dijkstra 算法实现原理](https://www.jianshu.com/p/ff6db00ad866)
- [分布式事务 Seata AT模式原理与实战](https://www.jianshu.com/p/e5dc4d07e24e)
- [Spring 源码解析 @RequestBody @ResponseBody 的来龙去脉](https://www.jianshu.com/p/f8e48ac2dce7)



# 工作经历

**OpenJaw（大连） 2021.5 ~ 至今 高级Java工程师**
- 微服务基础架构与组件   
技术：SpringCloud全家桶, SpringBoot, Nacos, Alibaba Sentinel, Redis, Drools, Kafka, RocketMQ, Kubernetes    
参与并主导了微服务基础框架与组件的设计、开发、code review等工作。还负责提供技术解决方案, 多次在团队内进行技术分享
    - 基于 Spring Cloud Gateway 的二次开发
    - 微服务应用 sidecar 的设计与开发
    - 基础组件的设计与开发
    - 提供技术解决方案。例如：如何保证Rocket与Kafka消息幂等与消息持久性
    - 掌握了项目中所有的微服务解决方案。例如：全链路追踪、分布式日志收集等
    - 日志监控相关功能的设计与开发

**思佰益必智信息技术（大连）有限公司 2021.1 ~ 2021.5 高级DBA开发工程师**
- 数据迁移系统  
技术：Kafka, Kafka Connect, Debezium, Oracle, Postgres  
参与并主导了数据迁移系统的二次开发, 技术方案调研, 测试, 部署
    - 掌握了Oracle全量加增量数据迁移方案（闪回查询 + LogMiner/XStream）
    - 掌握了Debezium Oracle-Connector源码
    - 期间自学了Kafka/Kafka Connect

**大连云匠科技 2019.8 ~ 2021.1 高级后端工程师**

- IronERP  
技术：Java8, SpringBoot, Mybatis, MySQL, Redis, RocketMQ  
参与并主导了订单推送消费的开发  
    - 期间自学并掌握了RocketMQ

- 罗马优鲜  
技术：PHP, YII2, MySQL, Redis  
参与并主导了库存的重构, 解决超卖问题, 并总结了完整的库存实现方案
    - 重构原系统中不合理的库存表设计, 利用Redis命令原子性的特点, 使用Redis+Lua作为库存扣减的新方案
    - 后来还发现了订单的并发操作情况（例如用户取消和系统自动取消, 系统自动取消和支付回调）同样会造成超卖的现象, 分别针对这些场景做了优化
    - 期间自学了PHP相关技术


- 小太熊（潮流品交易平台）/ 电商Saas  
技术：Java8, SpringBoot, JdbcTemplate, SpringCloud Config, Spring Security, ElasticSearch, Redis, MySQL, RabbitMQ  
参与并主导了核心业务的设计与开发, 如交易功能, 保证金相关  
    - 掌握MQ实现分布式事务的方案  
    - 掌握如何在并发场景增减库存  
    - 学习到了如何设计可插拔的业务插件  
    - 开发了基于Logback的分布式日志收集

**大连致知云数据技术有限公司 2018.5 ~ 2019.8**

- 国家义务教育优质均衡发展评估系统  
技术：Java8, SpringBoot, Mybatis, MySQL, Druid, Shiro, JWT, Redis  
参与并主导了产品基础架构与核心业务的设计。
    - 开发了基于Shiro + Jwt实现了用户鉴权以及踢出用户功能  
    - 开发了基于Spring AOP 和 Redis分布式锁的防止并发提交功能  

**大连万思动科技 2016.9 ~ 2018.5**

- 通信运行方式管理系统（国家电网）  
技术：Java8, Springboot, Mybatis, MySQL, Ehcache, ElasticSearch, Thymeleaf, Openlayer3  
参与并主导了整个后端业务的设计与开发  
    - 自学并掌握了Dijkstra算法, 用于故障迂回算法的开发  
    - 自学并掌握了ElasticSearch的使用, 实现了分词搜索, 同义词匹配搜索等功能  



# 致谢
感谢您花时间阅读我的简历, 期待能有机会和您共事
