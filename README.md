##  66小数据分享： study-note


## 线上故障如何快速排查？来看这套技巧大全,有了这一篇文章排查线上故障问题就容易多了
https://mp.weixin.qq.com/s/tG1kOGtAJzHc37XGlsfAPQ

https://developer.aliyun.com/article/778128


## 我的社交资料
- B站UP账号：[后端研发Marion](https://space.bilibili.com/269097482)
- 今日头条账号：[后端研发Marion](https://www.toutiao.com/c/user/token/MS4wLjABAAAAChrLQhHvIVE31-TLHrkth8_9uQLhosRHQmKC5jkat70/)
- CSDN账号：[后台研发Marion](https://blog.csdn.net/luomao2012)
- 微信公众号：【后端研发Marion】加微信进JAVA技术交流群

|                       微信公众号                      |                      微信群（备注：加群）                       |
| :----------------------------------------------: | :-----------------------------------------------: |
| <img src="./resources/images/qrcode.jpg" width="200" /> | <img src="./resources/images/wx.jpg" width="200" /> |

## JAVA架构师笔记
- [01-JAVA基础](/01-JAVA基础)
- [02-JVM](/02-JVM)
- [03-MySQL](/03-MySQL)
- [04-Spring](/04-Spring])
- [05-Kafka](/05-Redis)
- [06-设计模式](/06-设计模式)
- [07-Kafka](/07-Kafka)
- [08-Zookeeper](/08-Zookeeper)
- [09-Netty](/09-Netty)
- [10-大数据](/10-大数据)
- [11-操作系统](/11-操作系统)
- [12-数据结构与算法](/12-数据结构与算法)
- [13-计算机网络](/13-计算机网络)
- [14-JAVA高级面试题](/14-JAVA高级面试题)
- [15-深度学习](/15-深度学习)
- [16-精选文章](/16-精选文章)
- [17-技术年货](/17-技术年货)
- [18-Go语言](/18-Go语言)
- [19-JAVA工程师成神之路](/19-JAVA工程师成神之路)
  
  
# [【JAVA工程师成神之路】](https://hollischuang.gitee.io/tobetopjavaer/#/)

<p align=center>
    <img src="./resources/images/roadmap.jpeg" width="500"/>
</p>

## 基础篇

### 面向对象

- 什么是面向对象

    - 面向对象与面向过程
    - 面向对象的三大基本特征
    - 面向对象的五大基本原则

- 封装、继承、多态

    - 什么是多态
    - 方法重写与重载
    - Java的继承与实现
    - Java为什么不支持多继承
    - Java的继承与组合
    - 构造函数与默认构造函数
    - 类变量、成员变量和局部变量
    - 成员变量和方法作用域

- 平台无关性

    - Java如何实现的平台无关性的
    - JVM还支持哪些语言

- 值传递

    - 值传递、引用传递
    - 为什么说Java中只有值传递

### Java基础知识

- 基本数据类型

    - 8种基本数据类型

        - 整型中byte、short、int、long的取值范围
        - 什么是浮点型？
        - 什么是单精度和双精度？
        - 为什么不能用浮点型表示金额？

- 自动拆装箱

    - 自动拆装箱
    - Integer的缓存机制
    - 如何正确定义接口的返回值(boolean/Boolean)类型及命名(success/isSuccess)

- String

    - 字符串的不可变性
    - JDK 6和JDK 7中substring的原理及区别
    - replaceFirst、replaceAll、replace区别
    - String对“+”的重载
    - 字符串拼接的几种方式和区别
    - String.valueOf和Integer.toString的区别
    - switch对String的支持
    - 字符串池
    - Class常量池
    - 运行时常量池
    - intern
    - String有没有长度限制？

- Java中各种关键字

    - transient
    - instanceof
    - volatile
    - synchronized
    - final
    - static
    - const

- 集合类

    - Collection和Collections区别
    - 常用集合类的使用
    - Set和List区别？
    - ArrayList和LinkedList和Vector的区别
    - ArrayList使用了transient关键字进行存储优化，而Vector没有，为什么？
    - SynchronizedList和Vector的区别
    - Set如何保证元素不重复?
    - HashMap、HashTable、ConcurrentHashMap区别
    - Java 8中Map相关的红黑树的引用背景、原理等
    - HashMap的容量、扩容
    - HashMap中hash方法的原理
    - 为什么HashMap的默认容量设置成16
    - 为什么HashMap的默认负载因子设置成0.75
    - 为什么建议设置HashMap的初始容量，设置多少合适
    - Java 8中stream相关用法
    - Apache集合处理工具类的使用
    - 不同版本的JDK中HashMap的实现的区别以及原因
    - Arrays.asList获得的List使用时需要注意什么
    - Collection如何迭代
    - Enumeration和Iterator区别
    - fail-fast 和 fail-safe
    - 如何在遍历的同时删除ArrayList中的元素
    - CopyOnWriteArrayList
    - ConcurrentSkipListMap

- 枚举

    - 枚举的用法
    - 枚举的实现
    - 枚举与单例
    - Enum类
    - Java枚举如何比较
    - switch对枚举的支持
    - 枚举的序列化如何实现
    - 枚举的线程安全性问题
    - 为什么不建议在对外接口中使用枚举

- IO

    - 字符流、字节流
    - 输入流、输出流
    - 字节流和字符流之间的相互转换
    - 同步、异步
    - 阻塞、非阻塞
    - Linux 5种IO模型
    - BIO、NIO和AIO的区别、三种IO的用法与原理
    - netty

- 反射

    - 反射
    - 反射有什么作用
    - Class类
    - 反射与工厂模式实现Spring IOC
    - java.lang.reflect.*

- 动态代理

    - 静态代理
    - 动态代理
    - 动态代理和反射的关系
    - 动态代理的几种实现方式
    - AOP

- 序列化

    - 什么是序列化与反序列化
    - Java如何实现序列化与反序列化
    - Serializable 和 Externalizable 有何不同
    - 为什么序列化
    - serialVersionUID
    - 为什么serialVersionUID不能随便改
    - transient
    - 序列化底层原理
    - 序列化如何破坏单例模式
    - protobuf
    - Apache-Commons-Collections的反序列化漏洞
    - fastjson的反序列化漏洞

- 注解

    - 元注解
    - 自定义注解
    - Java中常用注解使用
    - 注解与反射的结合
    - 如何自定义一个注解？
    - Spring常用注解

- 泛型

    - 什么是泛型
    - 类型擦除
    - 泛型带来的问题
    - 泛型中K T V E ？ object等的含义
    - 泛型各种用法
    - 限定通配符和非限定通配符
    - 上下界限定符extends 和 super
    - List<Object>和原始类型List之间的区别?
    - List<?>和List<Object>之间的区别是什么?

- 单元测试

    - junit
    - junit 和Spring 的结合
    - mock
    - JMockit
    - 内存数据库（h2）

- 正则表达式

    - java.lang.util.regex.*

- 常用的Java工具库

    - commons.lang
    - commons.*...
    - guava-libraries
    - netty

- API&SPI

    - API
    - API和SPI的关系和区别
    - 如何定义SPI
    - SPI的实现原理

- 异常

    - Error和Exception
    - 异常类型
    - 异常相关关键字
    - 正确处理异常
    - 自定义异常
    - 异常链
    - try-with-resources
    - finally和return的执行顺序

- 时间处理

    - 时区
    - 冬令时和夏令时
    - 时间戳
    - Java中时间API
    - 格林威治时间
    - CET,UTC,GMT,CST几种常见时间的含义和关系
    - SimpleDateFormat的线程安全性问题
    - Java 8中的时间处理
    - 如何在东八区的计算机上获取美国时间
    - yyyy和YYYY有什么区别？
    - 为什么日期格式化时必须有使用y表示年，而不能用Y？

- 编码方式

    - 什么是ASCII？
    - Unicode
    - 有了Unicode为啥还需要UTF-8
    - UTF8、UTF16、UTF32区别
    - 有了UTF8为什么还需要GBK？
    - GBK、GB2312、GB18030之间的区别
    - URL编解码
    - Big Endian和Little Endian
    - 如何解决乱码问题

- 语法糖

    - Java中语法糖原理、解语法糖
    - 语法糖介绍

- JMS

    - 什么是Java消息服务
    - JMS消息传送模型

- JMX

    - java.lang.management.*
    - javax.management.*

- BigDecimal

    - 为什么0.1+0.2不等于0.3
    - 为什么不能使用BigDecimal的equals比较大小

- Java 8

    - lambda表达式
    - Stream API
    - 时间API

- 阅读源代码

    - String
    - Integer
    - Long
    - Enum
    - BigDecimal
    - ThreadLocal
    - ClassLoader & URLClassLoader
    - ArrayList & LinkedList
    - HashMap & LinkedHashMap & TreeMap & CouncurrentHashMap
    - HashSet & LinkedHashSet & TreeSet

### Java并发编程

- 并发与并行

    - 什么是并发
    - 什么是并行
    - 并发与并行的区别

- 线程

    - 线程与进程的区别
    - 线程的特点
    - 线程的实现
    - 线程的状态
    - 线程优先级
    - 线程调度
    - 多线程如何Debug
    - 守护线程

- 创建线程的多种方式

    - 继承Thread类创建线程
    - 实现Runnable接口创建线程
    - 通过Callable和FutureTask创建线程
    - 通过线程池创建线程

- 线程池

    - 自己设计线程池
    - submit() 和 execute()
    - 线程池原理
    - 为什么不允许使用Executors创建线程池

- 线程安全

    - 什么是线程安全
    - 多级缓存和一致性问题
    - CPU时间片和原子性问题
    - 指令重排和有序性问题
    - 线程安全和内存模型的关系
    - happens-before
    - as-if-serial

- 锁

    - 可重入锁
    - 阻塞锁
    - 乐观锁与悲观锁
    - 数据库相关锁机制
    - 分布式锁

- 无锁

    - CAS
    - CAS的ABA问题

- 锁优化

    - 偏向锁
    - 轻量级锁
    - 重量级锁
    - 锁消除
    - 锁粗化
    - 自旋锁

- 死锁

    - 什么是死锁
    - 死锁的原因
    - 如何避免死锁
    - 写一个死锁的程序
    - 死锁问题如何排查

- synchronized

    - synchronized是如何实现的？
    - synchronized和lock之间关系
    - 不使用synchronized如何实现一个线程安全的单例
    - synchronized和原子性
    - synchronized和可见性
    - synchronized和有序性

- volatile

    - 编译器指令重排和CPU指令重排
    - volatile的实现原理
    - 内存屏障
    - volatile和原子性
    - volatile和可见性
    - volatile和有序性
    - 有了synchronized为什么还需要volatile

- 线程相关方法

    - start & run
    - sleep 和 wait
    - notify & notifyAll

- ThreadLocal

    - ThreadLocal 原理
    - ThreadLocal 底层的数据结构

- 写代码来解决生产者消费者问题
- 并发包

    - 同步容器与并发容器
    - Thread
    - Runnable
    - Callable
    - ReentrantLock
    - ReentrantReadWriteLock
    - Atomic*
    - Semaphore
    - CountDownLatch
    - ConcurrentHashMap
    - Executors

## 底层篇

### JVM

- JVM内存结构

    - 运行时数据区
    - 运行时数据区哪些是线程独享
    - 堆和栈区别
    - 方法区在不同版本JDK中的位置
    - 运行时常量池
    - 堆外内存
    - TLAB
    - Java中的对象一定在堆上分配吗？

- 垃圾回收

    - GC算法：标记清除、引用计数、复制、标记压缩、分代回收、增量式回收
    - GC参数
    - 对象存活的判定
    - 垃圾收集器（CMS、G1、ZGC、Epsilon）

- JVM参数及调优

    - -Xmx
    - -Xmn
    - -Xms
    - -Xss
    - -XX:SurvivorRatio
    - -XX:PermSize
    - -XX:MaxPermSize
    - -XX:MaxTenuringThreshold

- Java对象模型

    - oop-klass
    - 对象头

- HotSpot

    - 即时编译器
    - 编译优化

- Java内存模型

    - 计算机内存模型
    - 缓存一致性
    - MESI协议
    - 可见性
    - 原子性
    - 顺序性
    - happens-before
    - as-if-serial
    - 内存屏障
    - synchronized
    - volatile
    - final
    - 锁

### 虚拟机性能监控与故障处理工具

- jps
- jstack
- jmap
- jstat
- jconsole
- jinfo
- jhat
- javap
- btrace
- TProfiler
- jlink
- Arthas

### 类加载机制

- classLoader
- 类加载过程是线程安全的吗？
- 类加载过程
- 如何判断JVM中类和其他类是不是同一个类
- 双亲委派原则
- 为什么需要双亲委派？
- “父子加载器”之间的关系是继承吗？
- 双亲委派是如何实现的？
- 如何打破双亲委派
- 如何自定义类加载器
- 双亲委派被破坏的例子
- 为什么JNDI，JDBC等需要破坏双亲委派？
- 为什么Tomcat要破坏双亲委派
- 模块化（jboss modules、osgi、jigsaw）

### 打包工具

- jar
- jlink
- jpackage

### 编译与反编译

- 什么是编译
- 什么是反编译
- Class常量池
- 编译工具：javac
- 反编译工具：javap 、jad 、CRF

### JIT

- JIT优化（逃逸分析、栈上分配、标量替换、锁优化）

## 进阶篇

### Java底层知识

- 字节码
- class文件格式
- CAFEBABE

### 位运算

- 用位运算实现加、减、乘、除、取余

### 设计模式

- 设计模式的六大原则

    - 开闭原则（Open Close Principle）
    - 里氏代换原则（Liskov Substitution Principle）
    - 依赖倒转原则（Dependence Inversion Principle）
    - 接口隔离原则（Interface Segregation Principle）
    - 迪米特法则（最少知道原则）（Demeter Principle）
    - 合成复用原则（Composite Reuse Principle）

- 创建型设计模式

    - 单例模式
    - 抽象工厂模式
    - 建造者模式
    - 工厂模式
    - 原型模式

- 结构型设计模式

    - 适配器模式
    - 桥接模式
    - 装饰模式
    - 组合模式
    - 外观模式
    - 享元模式
    - 代理模式

- 行为型设计模式

    - 模版方法模式
    - 命令模式
    - 迭代器模式
    - 观察者模式
    - 中介者模式
    - 备忘录模式
    - 解释器模式
    - 状态模式
    - 策略模式
    - 责任链模式
    - 访问者模式

- 单例的七种写法

    - 懒汉——线程不安全
    - 懒汉——线程安全
    - 饿汉
    - 饿汉——变种
    - 静态内部类
    - 枚举
    - 双重校验锁

- 为什么推荐使用枚举实现单例？
- 三种工厂模式的区别及联系

    - 简单工厂、工厂方法、模板工厂

- 会使用常用设计模式

    - 工厂模式
    - 适配器模式
    - 策略模式
    - 模板方法模式
    - 观察者模式
    - 外观模式
    - 代理模式

- 不用synchronized和lock，实现线程安全的单例模式
- nio和reactor设计模式
- Spring中用到了哪些设计模式

### 网络编程知识

- 常用协议

    - tcp、udp、http、https
    - 用Java实现FTP、SMTP协议

- OSI七层模型

    - 每一层的主要协议

- TCP/UDP

    - 三次握手与四次关闭
    - 流量控制和拥塞控制
    - tcp粘包与拆包

- TCP/IP

    - IPV4
    - IPV6

- HTTP

    - http/1.0 http/1.1 http/2之间的区别
    - http和https的区别
    - http中 get和post区别
    - 常见的web请求返回的状态码
    - 404、302、301、500分别代表什么
    - 用Java写一个简单的静态文件的HTTP服务器

- HTTP/2

    - HTTP/2 存在哪些问题？

- HTTP/3
- Java RMI，Socket，HttpClient
- cookie 与 session

    - cookie被禁用，如何实现session

- 了解nginx和apache服务器的特性并搭建一个对应的服务器
- 进程间通讯的方式
- 什么是CDN？如果实现？
- DNS？

    - 什么是DNS
    - 记录类型:A记录、CNAME记录、AAAA记录等
    - 域名解析
    - 根域名服务器
    - DNS污染
    - DNS劫持
    - 公共DNS：114 DNS、Google DNS、OpenDNS

- 反向代理

    - 正向代理
    - 反向代理
    - 反向代理服务器

### 框架知识

- Servlet

    - 生命周期
    - 线程安全问题
    - filter和listener
    - web.xml中常用配置及作用

- Hibernate

    - 什么是OR Mapping
    - Hibernate的缓存机制
    - Hibernate的懒加载
    - Hibernate/Ibatis/MyBatis之间的区别

- MyBatis

    - Mybatis缓存机制
    - #{}和${}的区别
    - mapper中传递多个参数
    - Mybatis动态sql
    - Mybatis的延迟加载

- Spring

    - Bean的初始化
    - AOP原理
    - Spring AOP不支持方法自调用的问题
    - 实现Spring的IOC
    - spring四种依赖注入方式
    - 为什么我不建议使用@Transactional声明事务

- Spring MVC

    - 什么是MVC
    - Spring mvc与Struts mvc的区别

- Spring Boot

    - Spring Boot 2.0
    - 起步依赖
    - 自动配置
    - Spring Boot的starter原理
    - 自己实现一个starter
    - 为什么Spring Boot可以通过main启动web项目

- Spring Security
- Spring Cloud

    - 服务发现与注册：Eureka、Zookeeper、Consul
    - 负载均衡：Feign、Spring Cloud Loadbalance
    - 服务配置：Spring Cloud Config
    - 服务限流与熔断：Hystrix
    - 服务链路追踪：Dapper
    - 服务网关、安全、消息

### 应用服务器知识

- JBoss
- tomcat
- jetty
- Weblogic

### 工具

- git & svn
- maven & gradle
- git技巧

    - 分支合并
    - 冲突解决
    - 提交回滚

- maven技巧

    - 依赖树
    - 依赖仲裁

- Intellij IDEA

    - 常用插件：Maven Helper、FindBugs-IDEA、阿里巴巴代码规约检测、GsonFormat、Lombok plugin、.ignore、Mybatis plugin

## 高级篇

### 新技术

- Java 9

    - Jigsaw
    - Jshell
    - Reactive Streams

- Java 10

    - 局部变量类型推断
    - G1的并行Full GC
    - ThreadLocal握手机制

- Java 11

    - ZGC
    - Epsilon
    - 增强var

- Java 12

    - Switch 表达式

- Java 13

    - Text Blocks
    - Dynamic CDS Archives

- Java 14

    - Java打包工具
    - 更有价值的NullPointerException
    - record类型

- Spring 5

    - 响应式编程

- Spring Boot 2.0
- http/2
- http/3

### 性能优化

- 使用单例
- 使用Future模式
- 使用线程池
- 选择就绪
- 减少上下文切换
- 减少锁粒度
- 数据压缩
- 结果缓存
- Stream并行流
- GC调优
- JVM内存分配调优
- SQL调优

### 线上问题分析

- dump

    - 线程Dump
    - 内存Dump
    - gc情况

- dump获取及分析工具

    - jstack
    - jstat
    - jmap
    - jhat
    - Arthas

- dump分析死锁
- dump分析内存泄露
- 自己编写各种outofmemory，stackoverflow程序

    - HeapOutOfMemory
    - Young OutOfMemory
    - MethodArea OutOfMemory
    - ConstantPool OutOfMemory
    - DirectMemory OutOfMemory
    - Stack OutOfMemory Stack OverFlow

- Arthas

    - jvm相关
    - class/classloader相关
    - monitor/watch/trace相关
    - options
    - 管道
    - 后台异步任务

- 常见问题解决思路

    - 内存溢出
    - 线程死锁
    - 类加载冲突
    - load飙高
    - CPU利用率飙高
    - 慢SQL

- 使用工具尝试解决以下问题，并写下总结

    - 当一个Java程序响应很慢时如何查找问题
    - 当一个Java程序频繁FullGC时如何解决问题
    - 如何查看垃圾回收日志
    - 当一个Java应用发生OutOfMemory时该如何解决
    - 如何判断是否出现死锁
    - 如何判断是否存在内存泄露
    - 使用Arthas快速排查Spring Boot应用404/401问题
    - 使用Arthas排查线上应用日志打满问题
    - 利用Arthas排查Spring Boot应用NoSuchMethodError

### 编译原理知识

- 编译与反编译
- Java代码的编译与反编译
- Java的反编译工具

    - javap
    - jad
    - CRF

- 即时编译器

    - 编译器优化

### 操作系统知识

- Linux的常用命令

    - find、grep、ps、cp、move、tar、head、tail、netstat、lsof、tree、wget、curl、ping、ssh、echo、free、top
    - 为什么kill -9 不能随便执行
    - rm一个被打开的文件会发生什么

- 进程间通信
- 服务器性能指标

    - load
    - CPU利用率
    - 内存使用情况
    - qps
    - rt

- 进程同步

    - 生产者消费者问题
    - 哲学家就餐问题
    - 读者写者问题

- 缓冲区溢出
- 分段和分页
- 虚拟内存与主存
- 虚拟内存管理
- 换页算法

### 数据库知识

- MySql 执行引擎
- MySQL 执行计划

    - 如何查看执行计划
    - 如何根据执行计划进行SQL优化

- 索引

    - Hash索引&B树索引
    - 普通索引&唯一索引
    - 聚集索引&非聚集索引
    - 覆盖索引
    - 最左前缀原则
    - 索引下推
    - 索引失效

- 回表
- SQL优化
- 数据库事务和隔离级别

    - 事务的ACID
    - 事务的隔离级别与读现象
    - 事务能不能实现锁的功能

- 编码方式

    - utf8
    - utf8mb4
    - 为什么不要在数据库中使用utf8编码

- 行数统计

    - count(1)、count(*)、count(字段)的区别
    - 为什么建议使用count(*)

- 数据库锁

    - 共享锁、排它锁
    - 行锁、表锁
    - 乐观锁、悲观锁
    - 使用数据库锁实现乐观锁
    - Gap Lock、Next-Key Lock

- 连接

    - 内连接
    - 左连接
    - 右连接

- 数据库主备搭建
- log

    - binlog
    - redolog

- 内存数据库

    - h2

- 分库分表
- 读写分离
- 常用的nosql数据库

    - redis
    - memcached

- Redis

    - Redis多线程

- 分别使用数据库锁、NoSql实现分布式锁
- 性能调优
- 数据库连接池

### 数据结构与算法知识

- 简单的数据结构

    - 栈
    - 队列
    - 链表
    - 数组
    - 哈希表
    - 栈和队列的相同和不同之处
    - 栈通常采用的两种存储结构
    - 两个栈实现队列，和两个队列实现栈

- 树

    - 二叉树
    - 字典树
    - 平衡树
    - 排序树
    - B树
    - B+树
    - R树
    - 多路树
    - 红黑树

- 堆

    - 大根堆
    - 小根堆

- 图

    - 有向图
    - 无向图
    - 拓扑

- 稳定的排序算法

    - 冒泡排序
    - 插入排序
    - 鸡尾酒排序
    - 桶排序
    - 计数排序
    - 归并排序
    - 原地归并排序
    - 二叉排序树排序
    - 鸽巢排序
    - 基数排序
    - 侏儒排序
    - 图书馆排序
    - 块排序

- 不稳定的排序算法

    - 选择排序
    - 希尔排序
    - Clover排序算法
    - 梳排序
    - 堆排序
    - 平滑排序
    - 快速排序
    - 内省排序
    - 耐心排序

- 各种排序算法和时间复杂度
- 深度优先和广度优先搜索
- 全排列
- 贪心算法
- KMP算法
- hash算法

### 海量数据处理

- 分治
- hash映射
- 堆排序
- 双层桶划分
- Bloom Filter
- bitmap
- 数据库索引
- mapreduce等。

### 大数据知识

- 搜索

    - Solr
    - Lucene
    - ElasticSearch

- 流式计算

    - Storm
    - Spark
    - Flink

- Hadoop，离线计算

    - HDFS
    - MapReduce

- 分布式日志收集

    - flume
    - kafka
    - logstash

- 数据挖掘

    - mahout

### 网络安全知识

- XSS

    - XSS的防御

- CSRF
- 注入攻击

    - SQL注入
    - XML注入
    - CRLF注入

- 文件上传漏洞
- 加密与解密

    - 对称加密
    - 非对称加密
    - 哈希算法
    - 加盐哈希算法

- 加密算法

    - MD5，SHA1、DES、AES、RSA、DSA

- 彩虹表
- DDOS攻击

    - DOS攻击
    - DDOS攻击
    - memcached为什么可以导致DDos攻击
    - 什么是反射型DDoS
    - 如何通过Hash碰撞进行DOS攻击

- SSL、TLS，HTTPS
- 脱库、洗库、撞库

## 架构篇

### 架构设计原则

- 单一职责原则
- 开放封闭原则
- 里氏替代原则
- 依赖倒置原则
- 接口分离原则

### 分布式

- 分布式理论

    - 2PC
    - 3PC
    - CAP
    - BASE

- 分布式协调 Zookeeper

    - 基本概念
    - 常见用法
    - ZAB算法
    - 脑裂

- 分布式事务

    - 本地事务&分布式事务
    - 可靠消息最终一致性
    - 最大努力通知
    - TCC

- Dubbo

    - 服务注册
    - 服务发现
    - 服务治理

- 分布式数据库

    - 怎样打造一个分布式数据库
    - 什么时候需要分布式数据库
    - mycat
    - otter
    - HBase

- 分布式文件系统

    - mfs
    - fastdfs

- 分布式缓存

    - 缓存一致性
    - 缓存命中率
    - 缓存冗余

- 限流降级

    - 熔断器模式
    - Hystrix
    - Sentinal
    - resilience4j

- 分布式算法

    - 拜占庭问题与算法
    - 2PC
    - 3PC
    - 共识算法
    - Paxos 算法与 Raft 算法
    - ZAB算法

### 领域驱动设计

- 实体、值对象
- 聚合、聚合根
- 限界上下文
- DDD如何分层
- 充血模型和贫血模型
- DDD和微服务有什么关系

### 微服务

- SOA
- 康威定律
- ServiceMesh

    - sidecar

- Docker & Kubernets
- Spring Boot
- Spring Cloud

### 高并发

- 分库分表

    - 横向拆分与水平拆分
    - 分库分表后的分布式事务问题

- CDN技术
- 消息队列

    - RabbitMQ、RocketMQ、ActiveMQ、Kafka
    - 各个消息队列的对比

### 高可用

- 双机架构

    - 主备复制
    - 主从复制
    - 主主复制

- 异地多活
- 预案
- 预热
- 限流

### 高性能

- 高性能数据库

    - 读写分离
    - 分库分表

- 高性能缓存

    - 缓存穿透
    - 缓存雪崩
    - 缓存热点

- 负载均衡
- PPC、TPC

### 监控

- 监控什么

    - CPU
    - 内存
    - 磁盘I/O
    - 网络I/O

- 监控手段

    - 进程监控
    - 语义监控
    - 机器资源监控
    - 数据波动

- 监控数据采集

    - 日志
    - 埋点

- Dapper

### 负载均衡

- 负载均衡分类

    - 二层负载均衡
    - 三层负载均衡
    - 四层负载均衡
    - 七层负载均衡

- 负载均衡工具

    - LVS
    - Nginx
    - HAProxy

- 负载均衡算法

    - 静态负载均衡算法：轮询，比率，优先权
    - 动态负载均衡算法: 最少连接数,最快响应速度，观察方法，预测法，动态性能分配，动态服务器补充，服务质量，服务类型，规则模式。

### DNS

- DNS原理
- DNS的设计

### CDN

- 数据一致性

## 扩展篇

### 云计算

- IaaS
- SaaS
- PaaS
- 虚拟化技术
- openstack
- Serverlsess

### 搜索引擎

- Solr
- Lucene
- Nutch
- Elasticsearch

### 权限管理

- Shiro

### 区块链

- 哈希算法
- Merkle树
- 公钥密码算法
- 共识算法
- Raft协议
- Paxos 算法与 Raft 算法
- 拜占庭问题与算法
- 消息认证码与数字签名
- 比特币

    - 挖矿
    - 共识机制
    - 闪电网络
    - 侧链
    - 热点问题
    - 分叉

- 以太坊

    - 超级账本

### 人工智能

- 数学基础
- 机器学习
- 人工神经网络
- 深度学习
- 应用场景
- 常用框架

    - TensorFlow
    - DeepLearning4J

### IoT

### 量子计算

### AR & VR

### 其他语言

- Groovy
- Kotlin
- Python
- Go
- NodeJs
- Swift
- Rust
- PHP

*XMind - Trial Version*
