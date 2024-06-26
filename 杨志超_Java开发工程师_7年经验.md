## 杨志超

**姓名**：杨志超		**手机**：18459195098		**生日**：1994.1		**工作经验**：7年		**学历**：本科

**邮箱**：yangzhichao1125@gmail.com		**GitHub**：[https://github.com/Yangzhichao1125](https://github.com/Yangzhichao1125)

**求职意向**：Java开发工程师

---

### 自我评价

**7年**Java开发经验，其中在**腾讯**有**3年系统架构设计**经验，以及**3年团队管理**经验，具有**分布式**，**高并发**，**高可用**，大数据量的系统架构设计和研发经验，最近负责基于**SaaS**模式的企业级管理平台开发和系统设计，日活跃用户达到**500万**、最大QPS超过**2000**。同时拥有扎实的技术功底，对**Spring Cloud**、**Spring**、**Spring Boot** 、**MyBatis**等开源框架均深度阅读过源码

---

### 专业技能
- 熟练使用 Java、设计模式、并发编程、JVM 内存管理及调优
- 熟练使用 Spring、Spring Boot、MyBatis，阅读过相关源码并根据需要扩展
- 熟练使用 Spring Cloud (Eureka、 Ribbon、 Feign、 Hystrix、zuul) 、dubbo，阅读过相关源码
- 熟练使用分布式事务，阅读过 2PC、TCC 相关组件的源码
- 熟练使用 Mysql，具有 sql优化、索引优化、性能调优、数据库灾备等丰富的实战经验
- 熟练使用 Redis，具有集群搭建，冷热备份，性能调优、数据迁移等实战经验
- 熟练使用rabbitMQ、TDMQ、kafka 原理及集群布署
- 熟练掌握 ElasticSearch，熟练使用 Logstash及 Kibana，搭建 ELK日志收集

---

### 工作经历

深圳市**腾讯**计算机系统有限公司		人力资源部		Java开发工程师 		2021.7 - 2024.1

```
1、设计、开发和维护 Java 后台系统，确保其高性能、稳定性和安全性。
2、确定项目需求和范围，完成技术选型，并制定相应的项目计划和时间表。
3、协调跨部门合作，解决项目中出现的问题和风险，并调整项目计划以应对变化。
```

朴朴电子商务有限公司（**朴朴超市**）		技术研发部 		Java开发工程师 		2020.7 - 2021.7

```
1、参与完成了系统技术调研选型，分析与建模、框架搭建、核心模块的开发、数据库设计。
2、负责公司服务器的规划、调试优化、日常监控、故障处理、数据备份、日志分析、性能瓶颈分析等工作。
```

宁德时代新能源科技股份有限公司		技术研发部 		Java开发工程师		2017.3 - 2020.7

```
1 需求调研，原型设计，对模块进行该要设计，实现代码编写，BUG修改。 
2 讨论项目相关需求，完成该要设计以及核心代码编写。
```



### 项目经历

#### 腾讯HR助手&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2021.7 - 2024.01

项目简介:腾讯HR助手是一款人力资源管理平台，旨在帮助企业进行全面的人力资源管理。该平台提供SaaS化核心人事管理系统。

技术栈：Spring Cloud + Spring Boot + TDMQ + Redis + MySQL + ELK

  - **技术选型：** 负责SaaS系统**数据隔离**方案设计，**上万租户**网关动态路由方案设计。
- **核心模块开发：** 负责员工管理，员工社保，员工薪酬等核心业务模块开发。
- **性能优化：**分析和解决线上问题，优化系统的性能，优化poi**百万级别**数据上传和下载功能。
- **项目管理与协调：** 作为**技术PM**管理项目的整体进度和资源分配，协调技术团队成员的工作。

业绩：该项目为SaaS化产品，目前租户**2W+**，用户**500W+**，最大QPS超过**2000**。



---

#### 朴朴超市app&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2020.7 - 2021.7

技术栈：Dubbo + Spring Boot + Redis + MySQL + Kafka + Elasticsearch 

项目简介:朴朴超市是一款即时电商，该项目基于**Dubbo**构建，**zookeeper**作为注册中心，**Redis**做热点缓存， **MySQL**集群存储数据。用户已过千万，日单量**10**万级

- 负责平台程序维护和新增功能二次开发，主要负责供应链模块业务开发。
- 对订单等链路较长等业务用MQ解耦，以及分布式事务实现。
- 订单，优惠券以及积分等模块由于数据量大，使用Sharding-JDBC做了分库分表。
- 针对库存模块内存泄漏导致频繁Full GC问题，做了业务优化。
- 商品等高频查询接口，用Redis集群做缓存，其中高频低变化接口用Guava Cache做本地缓存。
- 线上支持，现场部署，日志分析，优化慢sql索引等。	



---

#### 安灯系统&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**2018.11-2020.6**

项目简介:安灯系统，指企业用于分布式⻋间各处的灯光和声音报警系统，项目包含模块:消息服务，会话服务，
统计服务。后台提供对业务规则对数据管理;以及报表统计。通过大数据组与算法平台分析机器行为以及优化模
型。

技术栈: Dubbo + Spring Boot + SpringMVC + MyBatis + HANA + Redis + RabbitMQ 

数据库业务设计:分库分表，根据业务ID垂直切分，按月水平切分。 

多级缓存:Redis缓存消息数据并应用关注模型等，缓存热点数据，优化查询性能。 

异步解藕:应用RabbitMQ消息队列接受ME端消息，异步并发写入HANA数据库。 

线上支持:日志分析，现场部署。数据库建模等。
