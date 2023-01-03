# (go-cn) Senior Engineer

## Preview

### 语言深度

调度原理、调试技巧、汇编反汇编、内部数据结构实现、常见syscall、函数调用约定、内存管理与垃圾回收、并发编程

### 应用深度

框架原理、社区架构分析、模块分层、linter规范、中台场景实现、性能调优

### 框架广度

模块拆分、CI/CD、监控与可观测性、服务发现/信息检索/定时任务/MQ等基础设施、稳定性保障、未来架构、语言前言

### 转Go开发

- 例如 “node.js”转“golang”同样也是趋势，nodejs底层是C语言，想把整套系统学精通有一定难度，但Golang不一样，大部分底层也是Golang自己实现了自己！！！(⭐️Get⭐️)

### 学习与进步

- 多写代码，积累代码量，总结和思考、如何对过去的工作进行改进；积累自己的代码库、笔记库、开源库
- 读好书，简历知识体系（DDIA、CSAPP等）
- 持续关注靠谱的信息源
- 锻炼口才和演讲能力
- 通过输出促进输入
- 信息源要广！！！

### Golang适合的场景

- 服务类：API、IO密集型、且网络IO多
- 运行成本低，无VM
- 强类型，易上手
- 云的基础设施：k8s、etcd、istio、docker等

## Go程序的启动和执行流程

### 可执行文件

- 文本 -> 编译 -> 二进制可执行文件

<img width="1072" alt="image" src="https://user-images.githubusercontent.com/10555820/210329183-29e59593-d0f0-4479-8d11-bdf32ed3ae39.png">
<img width="1302" alt="image" src="https://user-images.githubusercontent.com/10555820/210329256-4b1eafed-9f73-48da-b052-86d8967176d2.png">
<img width="1271" alt="image" src="https://user-images.githubusercontent.com/10555820/210329302-b90b1e3a-88cc-4468-9545-62d34d5cbec3.png">
<img width="892" alt="image" src="https://user-images.githubusercontent.com/10555820/210329332-621ff16c-93b3-4851-8197-53c3f0b8ce75.png">
<img width="1115" alt="image" src="https://user-images.githubusercontent.com/10555820/210329358-a88d0255-74d6-402f-a4b2-a7d2411b52e2.png">

## 调度组件与调度循环

- Go的调度流程本质上是一个生产-消费流程

<img width="1452" alt="image" src="https://user-images.githubusercontent.com/10555820/210328684-fb2b0bad-332b-47f2-9296-8cf0d031b708.png">

<img width="1378" alt="image" src="https://user-images.githubusercontent.com/10555820/210328730-7226b2a2-7020-4432-991a-f7c5541132c6.png">

<img width="1177" alt="image" src="https://user-images.githubusercontent.com/10555820/210328791-66fec85d-740b-4b45-b366-1fd6cdd95647.png">

<img width="1275" alt="image" src="https://user-images.githubusercontent.com/10555820/210328858-1cb13ad6-9bc8-4c1d-8f2b-fe96af666233.png">

> 01 54:35
