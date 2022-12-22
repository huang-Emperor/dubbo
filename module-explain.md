## dubbo-registry
    是注册中心实现的源码
## remoting
    Dubbo网络通信的核心实现，其底层使用到了netty进行开发
## rpc
    Dubbo的远程调用模块，抽象各种协议，以及动态代理，只包含一对一的调用，不关心集群的管理
## cmmon
    Dubbo的公共逻辑模块，包括 Util 类和通用模型
## cluster
    Dubbo的集群模块。将多个服务提供方伪装为一个提供方，包括：负载均衡, 容错，路由等，集群的地址列表可以是静态配置的，也可以是由注册中心下发
## monitor
    Dubbo的监控模块。统计服务调用次数、调用时间、调用链跟踪等
## dubbo-demo 
    dubbo使用案例
