# 注册中心

## 1.为什么需要注册中心？
    在目前微服务盛行的情况下，管理服务和服务地址之间的关联关系。
    注册中心主要有两点：
        1.服务注册
        2.服务发现

## 2.注册中心需要那些功能
     1).高可用
         如果注册中心服务异常后续如果维护？
     2).服务拓展
         如何快速加机器、加服务？
     3).服务发现
         如何发现服务有那些可用？
     4).服务路由
         请求服务的时候怎么路由？
     5).服务降级
         服务的异常的时候怎么处理？
         
## 3.目前环境有那些注册中心
     1).dubbo体系
          (1)Zookeeper     
          (2)redis      
     2).spring cloud体系
          (1)[Eureka](/distributed_framework/register/eureka.md)  
          (2)Consul  
     2).其他
         (1)etcd     