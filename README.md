# springcloud

#### 1. 服务的注册与发现（Eureka）  
eureka-server 注册中心 8761 
service-hi 服务可以起多个端口8762 8763   
#### 2. 服务消费者（rest+ribbon）  
service-ribbon ribbon负载均衡 8764 
#### 3. 服务消费者（Feign）  
service-feign  feign负载均衡 8765
#### 4. 断路器（Hystrix）  
在ribbon中使用断路器  
在feign中使用断路器

#### 5. 路由网关（zuul）  
zuul得主要功能就是路由转发和过滤。  
* filterType:返回一个字符串代表过滤得类型，在zuul中定义了四种不同生命周期得过滤类型  
1.pre: 路由之前执行filter  
2.routing: 路由之时执行filter  
3.post: 路由之后执行filter  
4.error: 出现错误时执行filter  
* filterOrder: filter执行顺序，通过数字指定  
* shouldFilter: filter是否需要执行  
* run: filter具体得执行逻辑
