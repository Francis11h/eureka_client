# eureka_client
eureka_client

## 注册
先新建工程
![1](https://github.com/Francis11h/eureka_client/blob/master/image/1.png)

pom先配置 
然后yml配置连到哪个eureka server

![2](https://github.com/Francis11h/eureka_client/blob/master/image/2.png)

然后主函数加注解
***@EnableDiscoveryClient***
![3](https://github.com/Francis11h/eureka_client/blob/master/image/3.png)




## eureka 的高可用
为了防止 一个 server down掉 我们可以 启动两个 server 然后互相注册 构建联系 
  三节点两两注册即可 同理
