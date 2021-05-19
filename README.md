# SpringCloud

https://www.cnblogs.com/xing-12/p/9889153.html


使用ribbon实现负载均衡
Published on 2018-11-01 14:42 in 分类: spring cloud with 做个俗人、贪财好色
分类: spring cloud

使用ribbon之前的准备工作：

　　1.你要有两个服务，一个是服务消费方（下图的xing-movie是消费方），一个是服务提供方（xing-user是服务提供者），并且服务提供方要有两个实例，也就是xing-user有两个实例，分别运行在8070和8071端口。

　　2.所有服务注册到eureka server中。
