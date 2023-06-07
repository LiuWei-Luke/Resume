# 个人简历
## 联系方式
- TEL: 13629662492
- Email: lw19921@hotmail.com
- Github: https://github.com/LiuWei-Luke

## 相关技能

- 熟练使用JAVA开发复杂程序以及企业框架
- 熟练使用工具分析、定位JAVA以及Golang应用内存泄露，性能瓶颈等异常
- 熟练使用Docker, k8s, Istio进行基于云原生的架构设计以及功能开发
- 熟练使用各种中间件，针对不同业务需求，设计开发企业框架
- 熟练使用各语言根据企业需求对开源软件进行二次开发

## 个人项目
#### 基于OpenGL从零实现的C++吃豆人
- 地址: https://github.com/LiuWei-Luke/LuckPackMan 
- 关键字： 粗糙、简陋、OpenGL、A*算法
- 内容： 使用C++基于OpenGL实现的一个吃豆人游戏，包括简单Shader的使用，图形的显示，
地图的设计；以及核心玩法：角色控制，AI的Search Pattern，物理碰撞的实现
#### 玩具级RPC实现
- 地址: https://github.com/LiuWei-Luke/LuckRpc
- 关键字：帮助理解工作原理、Zookeeper、Netty、kryo、动态代理
- 内容：对协议进行封装，使用Zookeeper进行服务注册和发现；使用Netty作为传输层进行请求的传送；对内容的序列化方式使用的是kryo；最后使用Proxy动态代理的方式对服务接口进行代理; Netty传输层的使用参考了Motan的代码进行学习

## 目前工作内容

### 日常工作
- 使用Node.js、Java(Spring)、TypeScrpt 根据业务需要进行CRM系统以及子服务的开发
- 为了支持移动业务，开发基于以上系统的接口服务

### 工作成果
#### 使用Node.js基于redis的队列功能实现发送消息

#### 实现Api GateWay的服务  
- 使用Filter配合RSA身份加密实现身份验证
- 根据请求路由进行转发
#### 优化业务中遗留下来的问题SQL
- 主要是对大部分的慢查询进行优化

#### 排查数据采集时的死锁问题
- 由于架构的问题，目前的数据采集经常产生的死锁问题并造成数据丢失，分析死锁日志等对问题代码进行了修复
- 对目前数据采集方法产生疑问， 自主了解Hadoop以及Spark的使用，但仅限于了解，在自己环境下跑的OLAP任务比原来还慢...

