# springcloud

#### 1. �����ע���뷢�֣�Eureka��  
eureka-server ע������ 8761 
service-hi ������������˿�8762 8763   
#### 2. ���������ߣ�rest+ribbon��  
service-ribbon ribbon���ؾ��� 8764 
#### 3. ���������ߣ�Feign��  
service-feign  feign���ؾ��� 8765
#### 4. ��·����Hystrix��  
��ribbon��ʹ�ö�·��  
��feign��ʹ�ö�·��

#### 5. ·�����أ�zuul��  
zuul����Ҫ���ܾ���·��ת���͹��ˡ�  
* filterType:����һ���ַ���������˵����ͣ���zuul�ж��������ֲ�ͬ�������ڵù�������  
1.pre: ·��֮ǰִ��filter  
2.routing: ·��֮ʱִ��filter  
3.post: ·��֮��ִ��filter  
4.error: ���ִ���ʱִ��filter  
* filterOrder: filterִ��˳��ͨ������ָ��  
* shouldFilter: filter�Ƿ���Ҫִ��  
* run: filter�����ִ���߼�
