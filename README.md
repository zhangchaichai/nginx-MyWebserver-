# nginx-MyWebserver-
### 实现了一套通讯框架
1. 利用 IO 复用技术 Epoll 和线程池实现 Reactor 高并发模型
2. 基于小根堆实现的定时器，关闭超时的非活动连接
3. 利用 RAII 机制实现了 socket 连接池和 nginx 内存池
4. QPS达到1w+
