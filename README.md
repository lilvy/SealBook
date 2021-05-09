# SealBook

> 欢迎关注b站账号/公众号【六边形战士夏宁】，一个要把各项指标拉满的男人。
屏幕前的**大帅比**和**大漂亮**如果有帮助到你的话请顺手点个赞、加个收藏这对我真的很重要。别下次一定了，都不关注上哪下次一定。
* [github](https://github.com/edanlx/SealBook)
* [gitee](https://gitee.com/seal_li/SealBook)
* [知乎](https://zhuanlan.zhihu.com/p/338222208)
* [csdn](https://blog.csdn.net/seal_li/article/details/111415366)

![公众号](http://seal_li.gitee.io/sealbook/pic/wechat.jpg)

  1. 优雅代码
        1. [lombok(最简单的简化代码注解)](./01graceCode/01lombok.md)  [视频版](https://www.bilibili.com/video/BV1yC4y1877R/)
        2. [使用get、set方法避免魔法值(java传个方法你会吗,不是Method对象)](./01graceCode/02method.md)  [视频版](https://www.bilibili.com/video/BV1ok4y1q7Be/)
        3. [Optional杜绝NPE(看完这个就不要再写空指针了)](./01graceCode/03optional.md)  [视频版](https://www.bilibili.com/video/BV1oy4y1r7r1/)
        4. [1行代码完成多线程，别再写runnable了](./01graceCode/04thread.md)  [视频版](https://www.bilibili.com/video/BV1jr4y1w7SH/)
        5. [异或、左移、右移到底该怎么用](./01graceCode/05symbol.md)
        6. [apache、spring下优秀的工具类](./01graceCode/06utils.md)
        7. 利用common-pool构建高效连接池，实测连接池访问baidu的效率
        8. 利用idea优化代码
        9. Swagger前后端分离api文档
        10. 借助aop构建全局日志
        11. 借助ErrorController无侵入验证字段
        12. stream的常用示例
        13. mybatisplus
        14. 更快的创建对象(clone)
        15. linkedList插入真的比arrayList快么
        16. 更快的序列化
        17. 更快的json(static)
        18. 为什么enum和localDate的工具类那么少
        19. final修饰集合后怎样无法让外部不能改变内部值
        20. 方法懒执行
        21. 不用部署中间件的本地缓存
  2. JVM深度剖析及调优
        1. [双亲委派及其破坏(双亲委派都会说，破坏双亲委派你会吗)](./02jvm/01classloader.md)  [视频版](https://www.bilibili.com/video/BV1Sz4y1f7FB/)
        2. [自定义类加载器(当我自己写一个java.lang.String自己加载会发生什么)](./02jvm/02myclassLoader.md)  [视频版](https://www.bilibili.com/video/BV1Y54y1274Y/)
        3. [JVM整体结构(写了final就是常量池了么)](./02jvm/03jv.md)  [视频版](https://www.bilibili.com/video/BV1LZ4y1N75R)
        4. [字节码(我偷偷改了你编译后的class文件)](./02jvm/04clazz.md)  [视频版](https://www.bilibili.com/video/BV1454y1r7mf/)
        5. [即时编译器(为什么你写的代码有时候和预期不一致)](./02jvm/05compile.md)  [视频版](https://www.bilibili.com/video/BV11i4y1L7BX/)
        6. [HotSpot创建对象(new一个对象到底占了多少内存?)](./02jvm/06HotSpotAndObject.md) [视频版](https://www.bilibili.com/video/BV1A54y1k7UW/)
        7. [并发的内存模型(偏向锁、轻量锁、重量锁到底是啥?)](./02jvm/07concurrence.md)  [视频版](https://www.bilibili.com/video/BV1LV411a7u7/)
        8. [垃圾收集器(垃圾回收器那么多傻傻分不清?)](./02jvm/08gcCollector.md)  [视频版](https://www.bilibili.com/video/BV1S5411V74U/)
        9. [GC调优(频繁full gc分析思路)](./02jvm/09gc.md) [视频版](https://www.bilibili.com/video/BV1Ey4y167HQ/)
  3. 并发
  4. tomcat深度剖析及调优
        1. [tomcat主流程](./04tomcat/01bootstrap.md)  [视频版](https://www.bilibili.com/video/BV1GK41137LQ/)
  5. mysql深度剖析及调优
  6. spring
  7. zookeeper
  8. rabbitmq
  9. 分库分表
  10. dubbo
  11. netty
  12. LVS
  13. springcloud-alibaba
  14. nginx
  15. redis
  16. k8s、Jenkins与分布式
  17. 设计模式
  18. 面试专题
  19. 算法专题
         1. [数据结构概述(注意区分jvm堆与堆/jvm栈与栈)](./arithmetic/structure.md)
         2. 二分查找
         3. 深度优先
         4. 广度优先
         5. 回溯算法
         6. 滑动窗口
         7. 动态规划
         8. 贪心算法
         9. 分治算法
  20. 大规模性能监控及链路追踪
  21. 计算机网络协议
  22. 分布式计算    