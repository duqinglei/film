# 三层架构
1. 控制层 **controller**

   1.职责 
   1. 调用业务层,封装数据
   2. 调用业务层,实现功能
   3. 拿到业务层的返回数据,响应给前端
   
2.业务层 : 实现功能代码**service**

    1.调用持久层
    2.连接控制层和持久层
   
3.数据持久层: 和数据库打交道    
1. 真正做事情的层

# 延伸阅读

