《后端技术总结》

最佳阅读地址：https://github.com/jianghaorangithub/interviewGuide

Github项目主页：https://github.com/jianghaorangithub/interviewGuide

作者博客地址：https://jhrtech.cn

为什么要做这个开源项目？

之前在业余时间阅读技术书籍时，发现只阅读而不产出，这样收效甚微。所以就在网上找了很多常见的技术问题，根据自己的技术积累，查阅书籍，阅读文档和博客等资料，尝试着用自己的话去写了很多原创解答，最终整理开源到Github。一方面是便于自己复习巩固，一方面是将这些自己写的解答开源出来分享给大家，希望可以帮助到大家，也欢迎大家一起来完善这个项目，为开源做贡献。

欢迎大家进群一起学习进步！

![互联网技术教程群1群聊二维码](https://user-images.githubusercontent.com/44829600/112971196-9023b500-9181-11eb-93dd-42873687f2a9.png)

目录

    首页

    Java
        基础
            1.Java中的多态是什么？
            2.Java中变量，代码块，构造器之间执行顺序是怎么样的？
            3.final关键字有哪些作用？
            4.Integer类会进行缓存吗？
            5.抽象类有哪些特点？
            6.String，StringBuffer和StringBuilder之间的区别是什么？
            7.编译型编程语言，解释型编程语言，伪编译型语言的区别是什么？
            8.Java中的访问控制符有哪些？
            9.Java的构造器有哪些特点？
            10.Java中的内部类是怎么样的？
            11.Java中的注解是什么？
            12.为什么hashCode()和equal()方法要一起重写？
            13.Java中有哪些数据类型？
            14.包装类型和基本类型的区别是什么？
        容器
            ArrayList和LinkedList
                1.ArrayList与LinkedList的区别是什么？
                2.怎么使ArrayList，LinkedList变成线程安全的呢？
                3.ArrayList遍历时删除元素有哪些方法？
                4.ConcurrentModificationException是什么？
                5.java容器类的层次是怎么样的？
            HashMap和ConcurrentHashMap
                1.HashMap添加一个键值对的过程是怎么样的？
                2.ConcurrentHashMap添加一个键值对的过程是怎么样的？
                3.HashMap与HashTable，ConcurrentHashMap的区别是什么？
                4.HashMap扩容后是否需要rehash？
                5.HashMap扩容是怎样扩容的，为什么都是2的N次幂的大小？
                6.ConcurrentHashMap是怎么记录元素个数size的？
                7.为什么ConcurrentHashMap，HashTable不支持key，value为null？
                8.HashSet和HashMap的区别？
                9.HashMap遍历时删除元素的有哪些实现方法？
        多线程
            1.进程与线程的区别是什么？
            2.进程间如何通信？
            3.Java中单例有哪些写法？
            4.Java中创建线程有哪些方式?
            5.如何解决序列化时可以创建出单例对象的问题?
            6.volatile关键字有什么用？怎么理解可见性，一般什么场景去用可见性？
            7.Java中线程的状态是怎么样的？
            8.wait()，join()，sleep()方法有什么作用？
            9.Thread.sleep(),Object.wait(),LockSupport.park()有什么区别？
            10.谈一谈你对线程中断的理解？
            11.线程间怎么通信？
            12.怎么实现实现一个生产者消费者？
            13.谈一谈你对线程池的理解？
            14.线程池有哪些状态？
        锁相关
            1.sychronize的实现原理是怎么样的？
            2.AbstractQueuedSynchronizer(缩写为AQS)是什么？
            3.悲观锁和乐观锁是什么？
    Redis
        基础
            1.Redis是什么？
            2.Redis过期key是怎么样清理的？
            3.Redis为什么是单线程的？
            4.Redis的性能为什么这么高？
            5.Linux中IO模型一共有哪些？
            6.同步与异步的区别是什么？
            7.阻塞与非阻塞的区别是什么？
            8.如何解决Redis缓存穿透问题？
            9.如何解决Redis缓存击穿问题？
            10.如何解决Redis缓存雪崩问题？
            11.如何解决缓存与数据库的数据一致性问题？
        数据结构
            1.Redis常见的数据结构有哪些？
            2.谈一谈你对Redis中简单动态字符串的理解？
            3.谈一谈你对Redis中hash对象的理解？
            4.谈一谈你对Redis中List的理解？
            5.谈一谈你对Redis中Set的理解？
            6.谈一谈你对Redis中有序集合ZSet的理解？
            7.布隆过滤器是什么？
        持久化(AOF和RDB)
            1.Redis的持久化是怎么实现的？
            2.AOF和RDB的区别是什么？
            3.怎么防止AOF文件越来越大？
            4.Redis持久化策略该如何进行选择？
        高可用(主从切换和哨兵机制)
            1.Redis主从同步是怎么实现的？
            2.Redis中哨兵是什么？
            3.客户端是怎么接入哨兵系统的？
            4.Redis哨兵系统是怎么实现自动故障转移的？
            5.谈一谈你对Redis Cluster的理解？
            6.RedisCluster是怎么实现数据分片的？
            7.RedisCluster是怎么做故障转移和发现的？
    MySQL
        原创面试题解答
            1.一条MySQL更新语句的执行过程是什么样的？
            2.脏页是什么？
            3.Checkpoint是什么？
            4.undo log，redo log，bin log是什么？
            5.MySQL中的事务是什么？
            6.MySQL的隔离级别是怎么样的？
            7.MVCC的实现原理是怎么样的？
            8.MySQL是怎么解决幻读的问题的？
            9.MySQL中有哪些锁？
            10.B树是什么？
            11.B树与B+树的区别是什么？
            12.索引是什么？
            13.字符串索引和数字类型索引的区别？
            14.union和union all的区别是什么？
            15.Join的工作流程是怎么样的，怎么进行优化？
            16.聚集索引是什么？
            17.联合索引是什么？
            18.覆盖索引是什么？
            19.哪些情况不要建索引？
            20.主键，唯一性索引，普通索引的区别是什么？
            21.InnoDB和MyISAM的区别是什么？
            22.什么是分库分表？
            23.怎么实现跨库分页查询？
            24.MySQL主从复制的工作流程是什么样的？
            25.char类型与varchar类型的区别？
            26.查询数量SELECT Count(*)怎么优化？
            27.如何优化MySQL慢查询？
            28.MySQL的join的实现是怎么样的？
        慢查询优化实践
    JVM
        原创面试题解答
            1.Java内存区域怎么划分的？
            2.Java中对象的创建过程是怎么样的？
            3.Java对象的内存布局是怎么样的？
            4.垃圾回收有哪些特点？
            5.在垃圾回收机制中，对象在内存中的状态有哪几种？
            6.对象的强引用，软引用，弱引用和虚引用的区别是什么？
            7.双亲委派机制是什么？
            8.怎么自定义一个类加载器？
            9.垃圾回收算法有哪些？
            10.Minor GC和Full GC是什么？
            11.如何确定一个对象可以回收？
            12.目前通常使用的是什么垃圾收集器？

    《剑指Offer》解题思考
    《LeetCode热门100题》解题思考(上)
    《LeetCode热门100题》解题思考(下)
    Kafka
    ZooKeeper
    HTTP
    大厂面试系列
        【大厂面试01期】高并发场景下，如何保证缓存与数据库一致性？
        【大厂面试02期】Redis过期key是怎么样清理的？
        【大厂面试03期】MySQL是怎么解决幻读问题的？
        【大厂面试04期】讲讲一条MySQL更新语句是怎么执行的？
        【大厂面试05期】说一说你对MySQL中锁的理解？
        【大厂面试06期】谈一谈你对Redis持久化的理解？
        【大厂面试07期】说一说你对synchronized锁的理解？
        【大厂面试08期】谈一谈你对HashMap的理解？

    读书笔记
        《Redis设计与实现》读书笔记 上
        《Redis设计与实现》读书笔记 下
        《MySQL必知必会》读书笔记
        《深入理解Java虚拟机-第三版》读书笔记

    好书推荐

如何为这个开源项目做贡献？


我平时比较喜欢看书，写技术文章，也比较喜欢讨论技术。这是我的网站主页https://jhrtech.cn
希望大家可以关注一下，谢谢了！大家如果有事需要联系我，或者想进技术群，一起讨论技术，也可以扫描下面我的微信二维码加我，一起讨论学习！
![微信图片_20210330180629](https://user-images.githubusercontent.com/44829600/112972292-b1d16c00-9182-11eb-99b4-08473d00c3cd.jpg)

