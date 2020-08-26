# FindJob
Java：熟练使用Java编程，掌握集合、多线程等基础框架。
JVM：对JVM有初步的理解，包括内存模型、垃圾回收机制等。
数据库：掌握MySQL、Redis，熟悉MongoDB，并有MySQL调优经验，熟悉Redis集群搭建。
开发框架：掌握SSM开源框架、Spring Boot框架开发。了解JFinal框架。
分布式框架：掌握Dubbo框架和Zookeeper服务注册中心开发，掌握FastDFS文件管理。
安全框架：了解SpringSecurity和Shiro安全框架。
搜索技术：熟练应用Solr、ElasticSearch。
消息中间体：掌握RabbitMQ。
Web前端：了解Html5、CSS、JavaScript、JQuery、EasyUI、Themeleaf、Vue.js。
Web架构：应用SOA分布式架构、SpringCloud微服务架构进行项目开发。
SpringCloud技术栈：掌握Eureka服务注册中心、Gateway网关服务，熟悉TX-LCN分布式事务处理、OpenFeign 接口通信、Config配置中心，了解Hystrix服务容灾。
容器：掌握项目部署到Docker和Linux。
项目管理：掌握maven构建项目，熟悉Git分布式版本控制。                        

项目：租房网
 开发工具和环境：   
 Maven、Linux、IDEA、FastDFS、Nginx、ElasticSearch、RabbitMQ、Redis、Docker、MongoDB、Tomcat。
   技术选型： 
 Spring Boot、Spring Cloud、Spring Data MongoDB、 Spring Data Elasticsearch、SpringMVC、Spring Cache、Vue.js
   项目描述：
  本项目为移动端项目，主页展示轮播图、展示热门推荐、展示热销商品。实现用户登录和注册功能。实现商品搜索并对结果分页和高亮功能。点击商品转到商品详情页面并展现商品详细信息。实现商品抢购、订单生成和商品评论功能等。
   技术描述：        
1.为了实现高效的开发，整个项目采用SpringCloud微服务架构。拆分颗粒度为接口，每个接口对应一个项目。
2.对比Solr，本项目搜索使用效率更高的ElasticSearch搜索工具。
3.使用Redis对高访问量的数据进行缓存，比如商品详情、首页轮播图等，提高了访问速度。并且接合RabbitMQ实现抢购功能。
4.相比MySQL使用了性能更高的MongoDB数据库进行数据存储。
5.项目中房屋的图片存储使用高性能FastDFS文件系统。项目部署到Docker容器进行性能测试。
    项目地址：
https://github.com/walle1321/livegoods/tree/walle


项目：分布式高并发电商项目
   开发工具和环境：   
  Maven、Linux、IDEA、Zookeeper、FastDFS、Nginx、Solr、RabbitMQ、Redis、MyCat、MySQL、Tomcat。
   技术选型：   
  Spring Boot、Spring MVC、MyBatis、MyBatis Generator、Druid、MyBatis PageHelper、Dubbo、FastDFS-java-client、Spring Data for Apache Solr、Spring AMQP、Spring Data Redis、Spring Security、SpringSession、HttpClient/RestTemplate。
   项目描述：
  1. 本项目分为前台系统和后台系统。
 2.前台有商城首页系统、商品搜索系统、SSO单点登录系统、购物车系统、订单系统等。完成用户浏览首页并且首页展示轮播图和商品分类、登录、注册、商品搜索、点击商品展示详情页面、添加商品到购物车、购物车结算、订单提交并发送订单成功的邮件等功能。
3.后台有CMS内容管理系统和商品的增删改查等。
   技术描述：        
1.采用SOA分布式架构，dubbo远程调用，SSM框架，SpringBoot开发。
2.保证Redis、Solr库和MySQL中商品数据的一致性，后台对MySQL中商品的增删改会结合RabbitMQ消息队列同步到对应的Redis和Solr库中。
3.为了加快响应速度，商品详情等高访问量的数据用Redis缓存。
4.处理抢购时的高访问量问题，项目结合Redis和RabbitMQ实现秒杀系统。
5.使用Solr进行商品搜索，采用Ik中文拆分器强化分词。
5.利用SpringSession的数据共享特点实现用户SSO单点登录。
6.购物车分为用户登录和未登录，利用cookie创建临时购物车，利用Redis创建用户购物车，结算时用户必须登录且合并临时购物车。
7.改善数据库性能，对MySQL性能调优，对MySQL进行分库分表、读写分离。并使用Mycat实现数据水平切分。  
项目地址：
https://github.com/walle1321/ego/tree/WALLE

教育经历：
学习编程两年半，2018/2月份学习C语言并考取C语言计算机二级，2018/7月份学习JavaWeb至今。
书籍：《C语言程序设计》《Java从零到精通》《JavaWeb从零到精通》
网课：北京理工大学-《C语言程序设计》，华东师范大学-《JAVA核心技术》，北京尚学堂-《JAVA+架构全套视频》
培训：2020.02-2020.08北京尚学堂培训机构学习《百战程序员》。

自我评价：
逻辑思维能力较强，具有较强的学习能力及适应能力，善于思考。
具备良好的团队合作意识及良好的沟通能力。
非常热爱编程，敢于面对和克服困难。
有很强的需求分析、代码编写能力。

        
