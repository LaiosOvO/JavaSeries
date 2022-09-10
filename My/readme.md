# Java 学习路线

## 阶段1 java 入门

## 阶段2 巩固基础

## 阶段3 Java 企业开发基础

## 阶段4 Java 企业开发进阶

### 缓存(14天)

2022/9/5 -- 2022/9/19

```
【1】    2022/9/5 - 2022/9/8 尚硅谷视频看完
* 感觉 it黑马的更全,更系统
```



#### 学习建议

鱼皮:
    学会如何简单地使用缓存并不难，和数据库类似，无非就是调用 API 对数据进行增删改查。

因此，建议先能够独立使用它，了解缓存的应用场景；再学习如何在 Java 中操作缓存中间件，并尝试和项目相结合，提高系统的性能。

跟着视频教程实操一遍即可，可以等到面试前再去深入了解原理和高级特性。

#### 资源

- 视频
  - ⭐ 尚硅谷 - 2021 最新 Redis 6 入门到精通教程：https://www.bilibili.com/video/BV1Rv41177Af （基于 Redis 6 的，推荐）
- 文档
  - Redis 命令参考：http://redisdoc.com/
  - Redis 面试题整理：https://github.com/lokles/Web-Development-Interview-With-Java/blob/main/Redis%E9%97%AE%E9%A2%98.md
- 书籍
  - 《Redis 实战》（经典）
- 工具
  - ⭐ Redis 在线练习：https://try.redis.io/ （强烈推荐）

#### 知识

- 什么是缓存？

- 本地缓存
  
  - Caffeine 库

- 多级缓存

- Redis 分布式缓存
  
  - 数据类型
  
  - 常用操作
  
  - Java 操作 Redis
  
  - Spring Boot Redis Template
  
  - Redisson
  
  - 主从模型搭建
  
  - 哨兵集群搭建
  
  - 日志持久化

- 缓存（Redis）应用场景
  
  - 数据共享
  
  - 单点登录
  
  - 计数器
  
  - 限流
  
  - 点赞
  
  - 实时排行榜
  
  - 分布式锁

- 缓存常见问题
  
  - 缓存雪崩
  
  - 缓存击穿
  
  - 缓存穿透
  
  - 缓存更新一致性

- 相关技术：Memcached、Ehcache



#### 经典面试题

1. Redis 为什么快？

2. Redis 有哪些常用的数据结构？

3. Redis RDB 和 AOF 持久化的区别，如何选择？

4. 如何解决缓存击穿、缓存穿透、雪崩问题？

5. 如何用 Redis 实现点赞功能，怎么设计 Key / Value？



### 🌖 消息队列（14 天）

2022/9/8 - 

```

```

[消息队列 尚硅谷](https://www.bilibili.com/video/BV1cb4y1o7zz/?spm_id_from=333.788.recommend_more_video.1&vd_source=79b4294ba1b51b78d8501db87f35d73d)



#### 学习建议

和缓存一样，学会如何使用消息队列并不难，无非就是调用 API 去生产、转发和消费消息。

因此，建议**先能够独立使用它，了解消息队列的应用场景**；再学习如何在 Java 中操作消息队列中间件，并尝试和项目相结合，感受消息队列带来的好处。

这里我建议初学者先学习 RabbitMQ，比 Kafka 要好理解一些。跟着视频教程实操一遍即可，可以等到面试前再去深入了解原理和高级特性。



#### 资源

- 视频
  
  - ⭐ 尚硅谷 - 2021 最新 RabbitMQ 教程：https://www.bilibili.com/video/BV1cb4y1o7zz （很新很全面）

- 文档
  
  - RabbitMQ 中文文档：http://rabbitmq.mr-ping.com/

- 书籍
  
  - 《RabbitMQ 实战：高效部署分布式消息队列》（经典）

- 工具
  
  - ⭐ RabbitMQ 在线模拟器：http://tryrabbitmq.com/
  
  

#### 知识

- 消息队列的作用

- RabbitMQ 消息队列
  
  - 生产消费模型
  
  - 交换机模型
  
  - 死信队列
  
  - 延迟队列
  
  - 消息持久化
  
  - Java 操作
  
  - 集群搭建

- 相关技术：Kafka、ActiveMQ、TubeMQ、RocketMQ



#### 经典面试题

1. 使用消息队列有哪些优缺点？

2. 如何保证消息消费的幂等性？

3. 消息队列有哪些路由模型？

4. 你是否用过消息队列，解决过什么问题？