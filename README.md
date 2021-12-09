# Redis-Like-Distributed-Cache
一个由Golang实现的类redis分布式缓存

支持特性有：
1、单机缓存和基于 HTTP 的分布式缓存
2、最近最少访问(Least Recently Used, LRU) 缓存策略
3、使用 Go 锁机制防止缓存击穿
4、使用一致性哈希选择节点，实现负载均衡
5、使用 protobuf 优化节点间二进制通信

		

