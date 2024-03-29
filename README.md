# goto_dotnet
C#,dotnet,asp.net core


<div align="center">  

<img src="https://img1.mukewang.com/59e96e2900010d7d02400240.jpg" width=""/> 
<br/>

[![Build Status](https://travis-ci.org/crossoverJie/JCSprout.svg?branch=master)](https://travis-ci.org/crossoverJie/JCSprout)
[![QQ群](https://img.shields.io/badge/QQ%E7%BE%A4-787381170-yellowgreen.svg)](https://jq.qq.com/?_wv=1027&k=5HPYvQk)

[qq0groupsvg]: https://img.shields.io/badge/QQ%E7%BE%A4-787381170-yellowgreen.svg
[qq0group]: https://jq.qq.com/?_wv=1027&k=5HPYvQk

</div><br>


> `dotnet Core Sprout`：处于萌芽阶段的 Csharp 核心知识库。

[![Slack](https://img.shields.io/badge/slack-996ICU-%23de335e.svg)](https://join.slack.com/t/996icu/shared_invite/enQtNTc5MTU4MDkxOTA1LTJlYWVmMGQxOWNjZDA2NzdkMzQ3MjkzYmFlYTAxMTczZGQ0NmQ5ZWY5MTVjODQ4MWFkZGRhMmRmY2UwZGUyOTQ)
[![LICENSE](https://img.shields.io/badge/license-NPL%20(The%20996%20Prohibited%20License)-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![Badge](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu/#/zh_CN)
[![HitCount](http://hits.dwyl.com/996icu/996ICU.svg)](http://hits.dwyl.com/996icu/996ICU)


<br/>


| 📊 |⚔️ | 🖥 | 🚏 | 🏖  | 🌁| 📮 | 🔍 | 🚀 | 🌈 |💡
| :--------: | :---------: | :---------: | :---------: | :---------: | :---------:| :---------: | :-------: | :-------:| :------:|:------:|
| [集合](#常用集合) | [多线程](#csharp-多线程)|[CLR](#CLR) | [分布式](#分布式相关) |[框架](#常用框架第三方组件)|[架构设计](#架构设计)| [数据库](#db-相关) |[算法](#数据结构与算法)|[Netty](#netty-相关)| [附加技能](#附加技能)|[联系作者](#联系作者) |

### C# 中的新增功能
- [C# 7.3](https://docs.microsoft.com/zh-cn/dotnet/csharp/whats-new/csharp-7-3)
- [C# 7.2](https://docs.microsoft.com/zh-cn/dotnet/csharp/whats-new/csharp-7-2)
- [C# 7.1](https://docs.microsoft.com/zh-cn/dotnet/csharp/whats-new/csharp-7-1)
- [C# 7.0](https://docs.microsoft.com/zh-cn/dotnet/csharp/whats-new/csharp-7)

### dotnet
- [DiagnosticSource](https://github.com/kaanid/goto_dotnet/blob/master/md/DiagnosticSource.md)

### 微服务

- [steeltoe](http://steeltoe.io/)
- [Grpc](https://github.com/grpc/grpc)
- [Thrift](http://thrift.apache.org/)
- [Surging](https://github.com/dotnetcore/surging)

### WebApi 相关

- [ActionFilterAttribute json](https://github.com/kaanid/goto_dotnet/blob/master/md/WebApi-ActionFilterAttribute.md)

### 常用集合
- [ArrayList/Vector](https://github.com/crossoverJie/JCSprout/blob/master/MD/ArrayList.md)
- [LinkedList](https://github.com/crossoverJie/JCSprout/blob/master/MD/LinkedList.md)
- [HashMap](https://github.com/crossoverJie/JCSprout/blob/master/MD/HashMap.md)
- [HashSet](https://github.com/crossoverJie/JCSprout/blob/master/MD/collection/HashSet.md)
- [LinkedHashMap](https://github.com/crossoverJie/JCSprout/blob/master/MD/collection/LinkedHashMap.md)

### Java 多线程
- [多线程中的常见问题](https://github.com/crossoverJie/JCSprout/blob/master/MD/Thread-common-problem.md)
- [synchronized 关键字原理](https://github.com/crossoverJie/JCSprout/blob/master/MD/Synchronize.md)
- [多线程的三大核心](https://github.com/crossoverJie/JCSprout/blob/master/MD/Threadcore.md)
- [对锁的一些认知](https://github.com/crossoverJie/JCSprout/blob/master/MD/Java-lock.md)
- [ReentrantLock 实现原理 ](https://github.com/crossoverJie/JCSprout/blob/master/MD/ReentrantLock.md)
- [ConcurrentHashMap 的实现原理](https://github.com/crossoverJie/JCSprout/blob/master/MD/ConcurrentHashMap.md)
- [如何优雅的使用和理解线程池](https://github.com/crossoverJie/JCSprout/blob/master/MD/ThreadPoolExecutor.md)
- [深入理解线程通信](https://github.com/crossoverJie/JCSprout/blob/master/MD/concurrent/thread-communication.md)
- [交替打印奇偶数](https://github.com/crossoverJie/JCSprout/blob/master/src/main/java/com/crossoverjie/actual/TwoThread.java)

### CLR
- [Java 运行时内存划分](https://github.com/crossoverJie/JCSprout/blob/master/MD/MemoryAllocation.md)
-  [类加载机制](https://github.com/crossoverJie/JCSprout/blob/master/MD/ClassLoad.md)
-  [OOM 分析](https://github.com/crossoverJie/JCSprout/blob/master/MD/OOM-analysis.md)
- [垃圾回收](https://github.com/crossoverJie/JCSprout/blob/master/MD/GarbageCollection.md)
- [对象的创建与内存分配](https://github.com/crossoverJie/JCSprout/blob/master/MD/newObject.md)
- [你应该知道的 volatile 关键字](https://github.com/crossoverJie/JCSprout/blob/master/MD/concurrent/volatile.md)

### 分布式相关

- [分布式限流Java](http://crossoverjie.top/2018/04/28/sbc/sbc7-Distributed-Limit/)
- [分布式限流](https://github.com/kaanid/goto_dotnet/blob/master/md/DistributedLimit.md)
- [基于 Redis 的分布式锁](http://crossoverjie.top/2018/03/29/distributed-lock/distributed-lock-redis/)
- [分布式缓存设计](https://github.com/crossoverJie/JCSprout/blob/master/MD/Cache-design.md)
- [分布式 ID 生成器](https://github.com/crossoverJie/JCSprout/blob/master/MD/ID-generator.md)

### 常用框架\第三方组件

- [Spring Bean 生命周期](https://github.com/crossoverJie/JCSprout/blob/master/MD/spring/spring-bean-lifecycle.md)
- [Spring AOP 的实现原理](https://github.com/crossoverJie/JCSprout/blob/master/MD/SpringAOP.md) 
- [Guava 源码分析（Cache 原理）](https://crossoverjie.top/2018/06/13/guava/guava-cache/)
- SpringBoot 启动过程
- [Dotnet](https://github.com/microsoft/dotnet)
- [ASP.NET Core 2.1](https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-2.1)
- [Framework 45 源码](https://referencesource.microsoft.com/)
- AutoFac
- Mapper
- Quartz.net
- [Hangfire](http://docs.geteventflow.net/index.html)
- Topshelf
- [Exceptionless](https://github.com/exceptionless/Exceptionless)



### 架构设计
- [秒杀系统设计](https://github.com/crossoverJie/JCSprout/blob/master/MD/Spike.md)
- [秒杀架构实践](http://crossoverjie.top/2018/05/07/ssm/SSM18-seconds-kill/)

### DB 相关

- [MySQL 索引原理](https://github.com/crossoverJie/JCSprout/blob/master/MD/MySQL-Index.md)
- [SQL 优化](https://github.com/crossoverJie/JCSprout/blob/master/MD/SQL-optimization.md)
- [数据库水平垂直拆分](https://github.com/crossoverJie/JCSprout/blob/master/MD/DB-split.md)

### 数据结构与算法
- [红包算法](https://github.com/crossoverJie/JCSprout/blob/master/src/main/java/com/crossoverjie/red/RedPacket.java)
- [二叉树层序遍历](https://github.com/crossoverJie/JCSprout/blob/master/src/main/java/com/crossoverjie/algorithm/BinaryNode.java#L76-L101)
- [是否为快乐数字](https://github.com/crossoverJie/JCSprout/blob/master/src/main/java/com/crossoverjie/algorithm/HappyNum.java#L38-L55)
- [链表是否有环](https://github.com/crossoverJie/JCSprout/blob/master/src/main/java/com/crossoverjie/algorithm/LinkLoop.java#L32-L59)
- [从一个数组中返回两个值相加等于目标值的下标](https://github.com/crossoverJie/JCSprout/blob/master/src/main/java/com/crossoverjie/algorithm/TwoSum.java#L38-L59)
- [一致性 Hash 算法](https://github.com/crossoverJie/JCSprout/blob/master/MD/Consistent-Hash.md)
- [限流算法Java](https://github.com/crossoverJie/JCSprout/blob/master/MD/Limiting.md)
- [限流算法](https://github.com/kaanid/goto_dotnet/blob/master/md/DistributedLimit.md)
- [三种方式反向打印单向链表](https://github.com/crossoverJie/JCSprout/blob/master/src/main/java/com/crossoverjie/algorithm/ReverseNode.java)
- [合并两个排好序的链表](https://github.com/crossoverJie/JCSprout/blob/master/src/main/java/com/crossoverjie/algorithm/MergeTwoSortedLists.java)
- [两个栈实现队列](https://github.com/crossoverJie/JCSprout/blob/master/src/main/java/com/crossoverjie/algorithm/TwoStackQueue.java)
- [动手实现一个 LRU cache](http://crossoverjie.top/2018/04/07/algorithm/LRU-cache/)
- [链表排序](./src/main/java/com/crossoverjie/algorithm/LinkedListMergeSort.java)
- [数组右移 k 次](./src/main/java/com/crossoverjie/algorithm/ArrayKShift.java)

### Netty 相关
- [SpringBoot 整合长连接心跳机制](https://crossoverjie.top/2018/05/24/netty/Netty(1)TCP-Heartbeat/)
- [从线程模型的角度看 Netty 为什么是高性能的？](https://crossoverjie.top/2018/07/04/netty/Netty(2)Thread-model/)

### Thrift 相关
- [example](https://github.com/kaanid/ThriftDome)

### C# 7.0 新增功能
- [Deconstruct](https://github.com/kaanid/goto_dotnet/blob/master/md/Deconstruct.md)

### .net core 3 新增功能

- [分层编译](https://www.cnblogs.com/xiaoliangge/p/9441988.html)

### 设计模式

- [Specification Pattern 规约模式](https://github.com/kaanid/SpecificationPattern)

### 附加技能

- [TCP/IP 协议](https://github.com/crossoverJie/JCSprout/blob/master/MD/TCP-IP.md)
- [一个学渣的阿里之路](https://crossoverjie.top/2018/06/21/personal/Interview-experience/)

### 工具

- [windbg内存分析工具](http://www.windbg.org/)
- [debugview](https://docs.microsoft.com/en-us/sysinternals/downloads/debugview)
- [DnsAgent](https://github.com/stackia/DNSAgent)

### 常用方法
- [DataTabe转List<T>扩展](https://github.com/kaanid/goto_dotnet/blob/master/md/DataTableToList.md)
