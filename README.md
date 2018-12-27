# 实战SpringCloud
  
# 1.feign
功能：在不引入eureka的情况下，使用feign来进行服务间的调用

分为三个模块  
provider：服务提供者，提供一个生成随机数的服务
api：将服务提供者的接口暴露出来
consumer：服务消费方，依赖API通过feign调用提供者

eg:将provider进行启动，将consumer启动；访问http://localhost:8080/consumer/getNum

# 2.SpringCloud其他组件---待完善