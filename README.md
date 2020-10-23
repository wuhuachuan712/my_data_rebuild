个人知识图谱

# 一些反思

1. [知乎的匿名回答：你为什么从阿里巴巴集团离职？](https://github.com/MikasaLevi/my_data_rebuild/issues/70)

# 一、基础知识

### 1. 英语

### 2. 数据结构与算法

1. [动态规划问题](https://github.com/MikasaLevi/my_data_rebuild/issues/25)
2. [KMP算法](https://github.com/MikasaLevi/my_data_rebuild/issues/5)

### 3. 计算机网络

1. [各种xx网的定义](https://github.com/MikasaLevi/my_data_rebuild/issues/67)
2. [物理层一般讨论什么问题](https://github.com/MikasaLevi/my_data_rebuild/issues/66)
3. [数据链路层](https://github.com/MikasaLevi/my_data_rebuild/issues/68)
4. [网络层：消息传输的关键-IP地址和路由器寻址问题](https://github.com/MikasaLevi/my_data_rebuild/issues/69)
5. [运输层：TCP 的三大特点：可靠传输/流量控制/拥塞控制](https://github.com/MikasaLevi/my_data_rebuild/issues/71)
6. [运输层：TCP 连接建立与释放：三次/四次握手](https://github.com/MikasaLevi/my_data_rebuild/issues/72)


### 4. 操作系统

1. [主存](https://github.com/MikasaLevi/my_data_rebuild/issues/62)
2. [操作系统的进程与线程](https://github.com/MikasaLevi/my_data_rebuild/issues/63)
3. [MySQL 的死锁和操作系统的死锁](https://github.com/MikasaLevi/my_data_rebuild/issues/64)

### 5. System Design

### 6. 重构与设计模式

1. [策略模式](https://github.com/MikasaLevi/my_data_rebuild/issues/8)
2. [装饰器模式](https://github.com/MikasaLevi/my_data_rebuild/issues/9)

### 7. 编程语言(Java)

#### 7.1 Java 集合

#### 7.2 Java 多线程

1. [并发问题的来源(Java内存模型与指令)](https://github.com/MikasaLevi/my_data_rebuild/issues/74)
2. [java.util.concurrent 包的研究1：整体结构](https://github.com/MikasaLevi/my_data_rebuild/issues/65)
3. [CAS && atomic 原子类包 && CAS 相关扩展](https://github.com/MikasaLevi/my_data_rebuild/issues/73)
4. [Java Thread 类解析](https://github.com/MikasaLevi/my_data_rebuild/issues/75)

#### 7.3 Java IO

#### 7.4 Java 内存模型与垃圾回收

1. [Java 内存区域结构](https://github.com/MikasaLevi/my_data_rebuild/issues/61)
2. [Java垃圾回收1：垃圾的判断&&基本的收集算法和垃圾回收器](https://github.com/MikasaLevi/my_data_rebuild/issues/6)
3. [Java垃圾回收2：G1 && Shenandoah && ZGC 垃圾收集器](https://github.com/MikasaLevi/my_data_rebuild/issues/7)

### 8. 数据库

1. [MySQL：锁相关概念：共享锁,排他锁以及意向锁,间隙锁,临键锁,插入意向锁](https://github.com/MikasaLevi/my_data_rebuild/issues/3)
2. [MySQL：select for update 语句会如何执行锁操作](https://github.com/MikasaLevi/my_data_rebuild/issues/4)
3. [MySQL：B+Tree 的学习与间隙锁为什么锁上下区间](https://github.com/MikasaLevi/my_data_rebuild/issues/2)
4. [MySQL：一些命令的使用](https://github.com/MikasaLevi/my_data_rebuild/issues/1)

# 二、大型软件经验

### 整体全局的思考

### 1. 分布式

#### 1.1 一些理论部分的学习

1. [《Time, Clocks, and the Ordering of Events in a Distributed System》](https://github.com/MikasaLevi/my_data_rebuild/issues/14)
2. [《Implementing Fault-Tolerant Services Using the State Machine Approach: A Tutorial》](https://github.com/MikasaLevi/my_data_rebuild/issues/15)
3. [Raft1：概念与算法核心](https://github.com/MikasaLevi/my_data_rebuild/issues/10)
4. [Raft2：Leader election 领导者选举](https://github.com/MikasaLevi/my_data_rebuild/issues/11)
5. [Raft3：Log Replication 日志复制](https://github.com/MikasaLevi/my_data_rebuild/issues/12)
6. [Raft4：Safety 两种特殊场景](https://github.com/MikasaLevi/my_data_rebuild/issues/13)
7. [Paxos：问题背景](https://github.com/MikasaLevi/my_data_rebuild/issues/16)
8. [Paxos：算法机制-choosing a value](https://github.com/MikasaLevi/my_data_rebuild/issues/17)
9. [Paxos：prepare&accept请求调用情况分析](https://github.com/MikasaLevi/my_data_rebuild/issues/18)
10. [Sagas论文翻译](https://github.com/MikasaLevi/my_data_rebuild/issues/26)
11. [Saga 论文总结](https://github.com/MikasaLevi/my_data_rebuild/issues/27)

#### 1.2 实际应用的总结

1. [分布式基础理论（ACID/BASE/CAP）](https://github.com/MikasaLevi/my_data_rebuild/issues/19)
2. [A系统->B系统的分布式一致性分析](https://github.com/MikasaLevi/my_data_rebuild/issues/20)
3. [分布式事务：TCC 概念与 Seata 中的 TCC 实现方案1](https://github.com/MikasaLevi/my_data_rebuild/issues/21)
4. [分布式事务： Seata 中的 TCC 实现方案2](https://github.com/MikasaLevi/my_data_rebuild/issues/22)
5. [TCC 模型下的三大问题：空回滚/悬挂/幂等](https://github.com/MikasaLevi/my_data_rebuild/issues/23)
6. [TCC 在项目中的实际应用以及可能出现的问题](https://github.com/MikasaLevi/my_data_rebuild/issues/24)

### 2. 高并发

1. [并发问题：并发问题的一些处理方案1](https://github.com/MikasaLevi/my_data_rebuild/issues/43)
2. [并发问题：并发问题的一些处理方案2](https://github.com/MikasaLevi/my_data_rebuild/issues/44)
3. [并发问题：并发问题的一些处理方案3: @Version 乐观锁](https://github.com/MikasaLevi/my_data_rebuild/issues/45)
4. [并发问题：记录持久化1-问题与解决方案](https://github.com/MikasaLevi/my_data_rebuild/issues/46)
5. [并发问题：记录持久化2-延时和透支](https://github.com/MikasaLevi/my_data_rebuild/issues/47)
6. [并发问题：记录持久化3-再谈透支(数据化解决方案)](https://github.com/MikasaLevi/my_data_rebuild/issues/48)
7. [并发问题：记录持久化4-积压问题和锁占用](https://github.com/MikasaLevi/my_data_rebuild/issues/49)
8. [并发问题：记录持久化5-热点配置](https://github.com/MikasaLevi/my_data_rebuild/issues/50)
9. [并发问题：记录持久化6-参考专利:一种缓冲记账方法及装置](https://github.com/MikasaLevi/my_data_rebuild/issues/51)
10. 并发问题：记录持久化7-异步化强制缓冲
11. 并发问题：记录持久化8-吞吐量比缓冲更大的处理方式

### 3. 技术风险

#### 3.1 容量

#### 3.2 弹性

1. [单元化部署](https://github.com/MikasaLevi/my_data_rebuild/issues/53)

#### 3.3 容灾

#### 3.4 预案

1. [预案与限流（偏组织层面）](https://github.com/MikasaLevi/my_data_rebuild/issues/52)

#### 3.5 限流

### 4. SRE

1. [K8S(一)：基础概念](https://github.com/MikasaLevi/my_data_rebuild/issues/54)
2. [K8S(二)：实际使用-部署](https://github.com/MikasaLevi/my_data_rebuild/issues/55)
3. [CICD 流程：GitLab->ArgoCD->K8S 搭建(一)](https://github.com/MikasaLevi/my_data_rebuild/issues/56)

### 5. 敏捷实践

1. [谈谈对敏捷开发的看法](https://github.com/MikasaLevi/my_data_rebuild/issues/36)
2. [从第一个敏捷项目后再看敏捷实践的一些坑](https://github.com/MikasaLevi/my_data_rebuild/issues/37)

### 6. 开源框架

1. [Airflow（一）： 基础概念](https://github.com/MikasaLevi/my_data_rebuild/issues/57)
2. [契约测试Pact:从理论到落地coding(一)：理论部分](https://github.com/MikasaLevi/my_data_rebuild/issues/58)
3. [契约测试Pact:从理论到落地coding(二)：Consumer 端落地 coding](https://github.com/MikasaLevi/my_data_rebuild/issues/59)
4. [契约测试Pact:从理论到落地coding(三)：不同参数怎么返回不同的响应](https://github.com/MikasaLevi/my_data_rebuild/issues/60)

### 7. 研发流程与质量保证

1. [研发质量：如何做一个需求的方法论](https://github.com/MikasaLevi/my_data_rebuild/issues/28)
2. [研发质量：如何做一个项目的方法论](https://github.com/MikasaLevi/my_data_rebuild/issues/29)
3. [研发质量：如何做一个全站性质项目的方法论](https://github.com/MikasaLevi/my_data_rebuild/issues/30)
4. [研发质量：研发质量体系思考](https://github.com/MikasaLevi/my_data_rebuild/issues/31)
5. [研发质量：团队质量意识的push](https://github.com/MikasaLevi/my_data_rebuild/issues/33)
5. [研发质量：蚂蚁金服(支付宝)-账务团队个人bug总结](https://github.com/MikasaLevi/my_data_rebuild/issues/32)

### 8. 项目管理

1. [项目管理：项目 owner 的一些职责](https://github.com/MikasaLevi/my_data_rebuild/issues/34)
2. [作为一个项目owner应该问自己的几个问题](https://github.com/MikasaLevi/my_data_rebuild/issues/35)

# 三、扩展视野

### 1. 区块链

1. [《比特币: 一个点对点的电子现金系统》- 摘要](https://github.com/MikasaLevi/my_data_rebuild/issues/38)
2. [《比特币: 一个点对点的电子现金系统》- 1引言](https://github.com/MikasaLevi/my_data_rebuild/issues/39)
3. [《比特币: 一个点对点的电子现金系统》- 2交易](https://github.com/MikasaLevi/my_data_rebuild/issues/40)
4. [《比特币: 一个点对点的电子现金系统》- 3时间戳服务器](https://github.com/MikasaLevi/my_data_rebuild/issues/41)
5. [《比特币: 一个点对点的电子现金系统》- 4工作量证明](https://github.com/MikasaLevi/my_data_rebuild/issues/42)

### 2. 5G

### 3. AI

### 4. 个人项目

