[![返回目录](https://user-images.githubusercontent.com/5803001/38079637-ff0abcf0-3371-11e8-9b76-ad651620afc7.jpg)](https://github.com/wxyyxc1992/Awesome-Links)

# Redis Links

- [Redis 存储海量小数据，如何优化内存使用](http://zzyongx.github.io/blogs/redis-memory-optimization-when-store-small-data.html) s

* [Redis 的内存优化](https://cachecloud.github.io/2017/02/16/Redis%E5%86%85%E5%AD%98%E4%BC%98%E5%8C%96/)

- [Redis 架构之防雪崩设计：网站不宕机背后的兵法](http://mp.weixin.qq.com/s/TBCEwLVAXdsTszRVpXhVug)：互联网系统中不可避免要大量用到缓存，在缓存的使用过程中，架构师需要注意哪些问题？本文以 Redis 为例，详细探讨了最关键的 3 个问题。

- [2017-Kafka & Redis Streams](https://parg.co/UsQ): Let’s talk about queue design.

# Engineering Practices

- [2017-Redis 集群实现原理探讨](https://parg.co/by5)：Redis  集群是一个 distribute、fault-tolerant 的 Redis 实现，主要设计目标是达到线性可扩展性、可用性、数据一致性。

- [如何部署高可用的 Redis 集群架构](http://rdc.hundsun.com/portal/article/669.html)：本文主要介绍 redis 在不同模式下的部署方式，并且对几种模式进行了一些简单的对比。

# Internals

## Communication

- [深入浅出 Redis client/server 交互流程](http://www.infoq.com/cn/articles/communication-redis-clientserver)

## Event Loop

- [2016-Redis 中的事件循环](https://draveness.me/redis-eventloop): 在目前的很多服务中，由于需要持续接受客户端或者用户的输入，所以需要一个事件循环来等待并处理外部事件，这篇文章主要会介绍 Redis 中的事件循环是如何处理事件的。

- [2018-Redis 源码阅读——基于 epoll 的事件模型](https://blog.csdn.net/idwtwt/article/details/79460217): Redis 的事件模型实现基于 linux 的 epoll，sun 的 export,FreeBSD 和 Mac osx 的 queue，还有 select。
