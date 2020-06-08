什么是聚簇索引  
全文索引有什么用
什么是cas
volatile的特性，实现原理



前言:

本文收集整理了各大厂常见面试题N道，你想要的这里都有内容涵盖：Java、MyBatis、ZooKeeper、Dubbo、Elasticsearch、Memcached、Redis、MySQL、Spring、Spring Boot、Spring Cloud、RabbitMQ、Kafka、Linux 等技术栈，希望大家都能找到适合自己的公司，开开心心的撸代码。

目录:

由于题量较多，篇幅的限制，文章中的面试题分享没有全部附上详细的解析，但是整理成了一份详细的PDF文档可分享给大家，文末获取免费领取方式

  

![](https://pic2.zhimg.com/v2-ca31f5a918344adccb80fab00d4c337d_b.jpg)

![](https://pic4.zhimg.com/v2-2857b22668444c641b8bc6120dbb3c83_b.jpg)

  

看面试题可以是为了面试，也可以是对自己学到的东西的一种查漏补缺，更加深刻的去了解一些核心知识点

微服务面试题
------

**SpringCloud面试题**

1.  什么是 Spring Cloud？
2.  使用 Spring Cloud 有什么优势？
3.  服务注册和发现是什么意思？Spring Cloud 如何实现？
4.  Spring Cloud 和dubbo区别?
5.  SpringBoot和SpringCloud的区别？
6.  负载平衡的意义什么？
7.  什么是 Hystrix？它如何实现容错？
8.  什么是 Hystrix 断路器？我们需要它吗？
9.  什么是 Netflix Feign？它的优点是什么？
10.  什么是 Spring Cloud Bus？我们需要它吗？
11.  Spring Cloud断路器的作用
12.  什么是SpringCloudConfig?
13.  Spring Cloud Gateway?

**SpringBoot面试题**

1.  什么是 Spring Boot？以及Spring Boot的优劣势？
2.  为什么要用 Spring Boot？
3.  Spring Boot 的核心配置文件有哪几个？它们的区别是什么？
4.  Spring Boot 的配置文件有哪几种格式？它们有什么区别？
5.  Spring Boot 的核心注解是哪个？它主要由哪几个注解组成的？
6.  开启 Spring Boot 特性有哪几种方式？
7.  Spring Boot 需要独立的容器运行吗？
8.  运行 Spring Boot 有哪几种方式？
9.  Spring Boot 自动配置原理是什么？
10.  Spring Boot 的目录结构是怎样的？
11.  你如何理解 Spring Boot 中的 Starters？
12.  如何在 Spring Boot 启动的时候运行一些特定的代码？
13.  Spring Boot 有哪几种读取配置的方式？
14.  Spring Boot 支持哪些日志框架？推荐和默认的日志框架是哪个？
15.  SpringBoot 实现热部署有哪几种方式？
16.  你如何理解 Spring Boot 配置加载顺序？
17.  Spring Boot 如何定义多套不同环境配置？
18.  Spring Boot 可以兼容老 Spring 项目吗，如何做？
19.  保护 Spring Boot 应用有哪些方法？
20.  Spring Boot 2.X 有什么新特性？与 1.X 有什么区别？

**Dubbo面试题**

1.  Dubbo与DubboX区别
2.  Dubbo中zookeeper做注册中心，如果注册中心集群都挂掉，发布者和订阅者之间还能通信么？
3.  Dubbo中有哪些角色？
4.  Dubbo在安全机制方面是如何解决的
5.  Dubbo执行流程？
6.  Dubbo支持的协议有哪些？
7.  Dubbo支持的注册中心有哪些？
8.  dubbo服务负载均衡策略？
9.  dubbo核心的配置有哪些？dubbo推荐用什么协议？
10.  dubbo连接注册中心和直连的区别
11.  dubbo通信协议dubbo协议为什么不能传大包
12.  dubbo通信协议dubbo协议为什么要消费者比提供者个数多
13.  dubbo通信协议dubbo协议为什么采用异步单一长连接
14.  dubbo通信协议dubbo协议适用范围和适用场景
15.  Spring Cloud与Dubbo的区别是什么？
16.  什么是Dubbo？
17.  简述Dubbo的均衡策略和集群容错模式
18.  为什么要用 Dubbo？
19.  Dubbo 的整体架构设计有哪些分层?
20.  默认使用的是什么通信框架，还有别的选择吗?
21.  服务调用是阻塞的吗？
22.  一般使用什么注册中心？还有别的选择吗？
23.  默认使用什么序列化框架，你知道的还有哪些？
24.  服务提供者能实现失效踢出是什么原理？
25.  服务上线怎么不影响旧版本？
26.  如何解决服务调用链过长的问题？
27.  说说核心的配置有哪些？
28.  Dubbo 推荐用什么协议？
29.  同一个服务多个注册的情况下可以直连某一个服务吗？
30.  画一画服务注册与发现的流程图？
31.  Dubbo 集群容错有几种方案？
32.  Dubbo 服务降级，失败重试怎么做？
33.  Dubbo 使用过程中都遇到了些什么问题？
34.  Dubbo Monitor 实现原理？
35.  Dubbo 用到哪些设计模式？

MyBatis 面试题
-----------

*   1、什么是 Mybatis？
*   2、Mybaits 的优点：
*   3、MyBatis 框架的缺点：
*   4、MyBatis 框架适用场合：
*   5、MyBatis 与 Hibernate 有哪些不同？
*   6、#{}和${}的区别是什么？
*   7、当实体类中的属性名和表中的字段名不一样 ，怎么办 ？
*   8、 模糊查询 like 语句该怎么写?

ZooKeeper 面试题
-------------

*   zookeeper 负载均衡和 nginx 负载均衡区别
*   Zookeeper Watcher 机制--数据变更通知
*   客户端注册 Watcher 实现
*   zookeeper 是如何保证事务的顺序一致性的？
*   Zookeeper 对节点的 watch监听通知是永久的吗？为什么不是永久的?
*   zk 节点宕机如何处理？

Redis面试题
--------

1、什么是Redis？

2、Redis相比memcached有哪些优势？

3、Redis支持哪几种数据类型？

4、Redis主要消耗什么物理资源？

5、Redis的全称是什么？

6、Redis有哪几种数据淘汰策略？

7、Redis官方为什么不提供Windows版本？

8、一个字符串类型的值能存储最大容量是多少？

9、为什么Redis需要把所有数据放到内存中？

10、Redis集群方案应该怎么做？都有哪些方案？

11、Redis集群方案什么情况下会导致整个集群不可用？

12、MySQL里有2000w数据，redis中只存20w的数据，如何保证redis中的数据都是热点数据？

13、Redis有哪些适合的场景？

14、Redis支持的Java客户端都有哪些？官方推荐用哪个？

15、Redis和Redisson有什么关系？

16、Jedis与Redisson对比有什么优缺点？

17、Redis如何设置密码及验证密码？

18、说说Redis哈希槽的概念？

19、Redis集群的主从复制模型是怎样的？

20、Redis集群会有写操作丢失吗？为什么？

21、Redis集群之间是如何复制的？

22、Redis集群最大节点个数是多少？

23、Redis集群如何选择数据库？

24、怎么测试Redis的连通性？

25、Redis中的管道有什么用？

26、怎么理解Redis事务？

27、Redis事务相关的命令有哪几个？

28、Redis key的过期时间和永久有效分别怎么设置？

29、Redis如何做内存优化？

30、Redis回收进程如何工作的？

31、Redis回收使用的是什么算法？

32、Redis如何做大量数据插入？

33、为什么要做Redis分区？

34、你知道有哪些Redis分区实现方案？

35、Redis分区有什么缺点？

36、Redis持久化数据和缓存怎么做扩容？

37、分布式Redis是前期做还是后期规模上来了再做好？为什么？

38、Twemproxy是什么？

39、支持一致性哈希的客户端有哪些？

40、Redis与其他key-value存储有什么不同？

41、Redis的内存占用情况怎么样？

42、都有哪些办法可以降低Redis的内存使用情况呢？

43、查看Redis使用情况及状态信息用什么命令？

44、Redis的内存用完了会发生什么？

45、Redis是单线程的，如何提高多核CPU的利用率？

46、一个Redis实例最多能存放多少的keys？List、Set、Sorted Set他们最多能存放多少元素？

47、Redis常见性能问题和解决方案？

48、Redis提供了哪几种持久化方式？

49、如何选择合适的持久化方式？

50、修改配置不重启Redis会实时生效吗？

MySQL面试题
--------

1.  MySQL 有哪些存储引擎啊？都有什么区别？
2.  Float、Decimal 存储金额的区别？
3.  Datetime、Timestamp 存储时间的区别？
4.  Char、Varchar、Varbinary 存储字符的区别？
5.  什么是索引？
6.  对比一下B+树索引和 Hash索引？
7.  MySQL索引类型有？
8.  如何管理 MySQL索引？
9.  对Explain参数及重要参数的理解？
10.  索引利弊是什么及索引分类？
11.  二叉树的转置是什么？
12.  聚簇索引和非聚簇索引的区别？
13.  B+tree 如何进行优化？索引遵循哪些原则？存储引擎会进行哪些自动优化？到底何时索引会失效？
14.  索引与锁有什么关系？
15.  还有什么其他的索引类型，各自索引有哪些优缺点？
16.  MySQL事务和锁有关问题
17.  谈谈对Innodb事务的理解？
18.  说说数据库事务特点及潜在问题？
19.  什么是MySQL隔离级别？
20.  有多少种事务失效的场景，如何解决？
21.  一致性非锁定读和一致性锁定读是什么？
22.  Innodb如何解决幻读？
23.  讲讲Innodb行锁？
24.  死锁及监控是什么？
25.  自增长与锁 ，锁的算法，锁问题，锁升级是什么？
26.  乐观锁的线程如何做失败补偿？
27.  高并发场景（领红包）如何防止死锁，保证数据一致性？
28.  谈谈MySQL的锁并发？
29.  MySQL性能优化有关问题
30.  回表和集群因子是什么？
31.  讲讲表与表之间的关系？
32.  了解查询优化器模块；
33.  查询优化的基本思路是什么？
34.  说说MySQL读写分离、分库分表？
35.  Query语句对数据库性能有什么影响？
36.  Schema设计对系统性能有什么影响？
37.  硬件环境对数据库的性能有什么影响？
38.  表结构对性能有什么影响?
39.  浅谈索引优化？
40.  JOIN的原理是什么？
41.  说说Sql优化的几点原则？
42.  MySQL表设计及规范？
43.  说说MySQL几种存储引擎应用场景？
44.  MySQL常用优化方式有哪些？
45.  MySQL常用监控？
46.  MySQL瓶颈分析？

Elasticsearch 面试题
-----------------

*   elasticsearch 了解多少，说说你们公司 es 的集群架构，索引数据大小，分片有多少，以及一些调优手段 。
*   elasticsearch 索引数据多了怎么办，如何调优，部署
*   elasticsearch 是如何实现 master 选举的
*   Elasticsearch 在部署时，对 Linux 的设置有哪些优化方法
*   详细描述一下 Elasticsearch 更新和删除文档的过程。
*   Elasticsearch 在部署时，对 Linux 的设置有哪些优化方法？

JVM面试题
------

1、内存模型以及分区，需要详细到每个区放什么？

2、堆里面的分区：Eden，survival （from+ to），老年代，各自的特点？、

3、对象创建方法，对象的内存分配，对象的访问定位？

4、GC 的两种判定方法？

5、SafePoint 是什么？

6、GC 的三种收集方法：标记清除、标记整理、复制算法的原理与特点，分别用在什么地方，如果让你优化收集方法，有什么思路？

7、GC 收集器有哪些？CMS 收集器与 G1 收集器的特点？

8、Minor GC 与 Full GC 分别在什么时候发生？

9、几种常用的内存调试工具：jmap、jstack、jconsole、jhat？

10、类加载的几个过程？

11、JVM 内存分哪几个区，每个区的作用是什么?

12、如和判断一个对象是否存活?(或者 GC 对象的判定方法)

13、简述 java 垃圾回收机制?

14、java 中垃圾收集的方法有哪些?

15、java 内存模型？

16、java 类加载过程？

17、简述 java 类加载机制?

18、类加载器双亲委派模型机制？

19、什么是类加载器，类加载器有哪些?

20、简述 java 内存分配与回收策率以及 Minor GC 和Major GC

Java 并发编程面试题
------------

*   在 java 中守护线程和本地线程区别？
*   什么是多线程中的上下文切换？
*   Java 中用到的线程调度算法是什么？
*   什么是线程组，为什么在 Java 中不推荐使用？
*   在 Java 中 Executor 和 Executors 的区别？
*   并发编程三要素？
*   什么是线程池？有哪几种创建方式？

Spring 面试题
----------

*   1\. 谈谈对 Spring IoC 的理解？
*   2\. 谈谈对 Spring DI 的理解？
*   3\. BeanFactory 接口和 ApplicationContext 接口不同点是什么？
*   4\. 请介绍你熟悉的 Spring 核心类，并说明有什么作用？
*   5\. 介绍一下 Spring 的事务的了解？
*   6\. 介绍一下 Spring 的事务实现方式？
*   7.什么是 Spring 的依赖注入？(文末附面试答案

Kafka面试题
--------

*   Kafka 与传统 MQ 消息系统之间有三个关键区别？
*   讲一讲 kafka 的 ack 的三种机制？
*   消费者故障，出现活锁问题如何解决？
*   kafka 分布式（不是单机）的情况下，如何保证消息的顺序消费？
*   kafka 如何不消费重复数据？比如扣款，我们不能重复的扣。

**由于内容过多，小编已经把对应的面试题和答案整理成了面试专题文档，有需要获取的朋友可以关注我，后台私信【面试资料】即可免费获取**

![](https://pic4.zhimg.com/v2-33bb2f85eb6d43c929c4bc2b3fd29727_b.jpg)