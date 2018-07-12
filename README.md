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
