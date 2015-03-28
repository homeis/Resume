#简历

##个人概况

* 徐敏 / 男 / 1989
* 工作年限：5 year
* 出生年月：1989年10月
* 期望职位：高级开发或架构师
* 期望城市: 深圳(现居住于上海)
* 电话：13916445873
* E-mail：skgin@sina.com


##工作经历 


中国民航信息网络股份有限公司    


2010/12 -- 至今 

**中国航信旅行社信息化解决方案(ETA平台)**

**项目简介：**

* ETA平台是集机票,酒店,景点门票等旅游资源为一体的旅游产品集散平台,系统和各大航空公司对接,
* 提供大量优惠的机票资源:和全国多家酒店合作，实现酒店实时预订;
* 并已经（或即将）与携程、去哪儿、艺龙、淘宝/天猫、京东等代理商接口对接,
* 实现产品一次生成，全网可卖；并实现全网配额动态、实时共享!这在旅游系统中,尚属首次.
* 系统已先后为上航假期、上海航空、厦门航空、香港航空等客户提供优质服务.

**项目架构：**

* ETA项目庞大复杂，已持续开发五年多，使用了多种技术、框架;
* 使用CAS实现一键登录，处处可用，方便在各个子系统中切换;
* 使用Apache+tomcat、Nginx+Tomcat实现代理和负载均衡，提高系统的稳定性;
* 使用ElasticSearch,优化系统日志查询速度；
* 使用Kettle替换存储过程,降低Oracle数据库的压力；
* 使用Oracle + TimesTen搭建数据库层级缓存,提供数据的实时计算，时时响应；
* 使用Maven+Bamboo+Linux Shell，实现项目代码的自动化编译、打包、发布.

**项目职责：**

>(2013 ~ 2015) 项目组长.
>* 部分模块的设计和开发.编写公共模板代码.
>* 给小组成员分配任务并指导完成开发
>* 负责git代码审核及合并.测试环境,生产环境的部署和发布.
>* 消息通知解决方案(RPC解决方案);
	* 使用thrift/rabbitmq完成多个系统间的数据同步(消息通知/通讯),解决不同进程间相互调用、通讯的问题.在分布式开发,大大降低系统之间的耦合度.
>* SSO-单点登录;
	* CAS(Central Authentication Service)+Spring-Security 使得在多个应用系统中，用户只需要登录一次就可以访问所有相互信任的应用系统.
>* 缓存解决方案;
	* 使用redis + 动态代理(spring aop)实现产品查询的缓存及统计;
	* 使用rabbitmq 异步消息通知实现缓存数据库与实体数据之间数据同步;
	* 使用timesten 实现缓存数据库分库,oracle triggers + java + jotm 实现数据同步;

>(2011 ~ 2013) 软件开发工程师 
主要任是根据项目需求完成各个模块的开发.
主要使用技术:spring hibernate struts2 jquery dwr
.系统登陆
.酒店管理
.渠道管理
.优惠管理
.产品导入
.价格配额管理
.google map(已弃用)
.行程管理
.酒店订单管理
.团队成本结算(报表)
.缓存管理
.用户消息通知 等;
>


##技能清单

* 编程语言：java/j2ee/javascript/jquery/dwr
* 内存数据库:redis/timesten
* sso: yale cas
* 消息通知:thrift/rabbitmq
* 开发工具: Inteillj idea/Myeclipse/pl sql/powerDesigner/tomcat
* 服务端框架: spring/struts2/hibernate
* 数据库:oracle
* 项目管理:svn/git+maven/jira
* 缓存框架:oschache


##自我评价

* Java基础扎实，有良好的开发规范，并重视开发规范在项目开发中的主要作用;
* 对工作认真仔细，负责缓存数据的维护工作；
* 掌握缓存技术、消息通知技术的设计和开发； 
* 编写过框架性的代码，具备做架构的潜力；
* 具有管理才能，作为组长带领组员负责各个模块相关功能的设计、开发与维护工作；
* 对工作全心投入，获得部门"明星员工"称号；
* 善于发现问题，解决问题,一切问题都在日志中。


##致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。

<!--
------------------------------------------------------------------------------------------------------------------
  不知不觉在公司已经干了5年了.前三年一直在增删改查之类的,没什么特别.
  三年下来不知不觉也有一些收获.比如类和类的关系,在第一年我只知道用继承;第二年我了解到需要组合;第三年发现还可以委托;
  有时候也会有一些顿悟,比如写过一些架构性代码之后才明白 原来private ,protected,final修饰词用来保护代码中脆弱的模块;
  由于数据也越来越多,数据同步必须异步去做,查询也会变慢,所以要用到缓存.
  项目越来越大,不得把许多模块,拆分成子项目,所以要用统一的登陆系统.
  一次由多线程没有正确shutdown从而导致服务器挂掉.使意识到项目,服务器监控的重要性.
  也有不好地方就是习惯了java那种条条框框的面向对象后,写javascript的面向对象总怪怪的.语言特性方面无法满足,总写不好;
  你技术的高度最主要的是你做的项目的高度决定的，和你平时自学了多少关系不大。
  也就是说你平日的网上的自学最多提高知识面的广度，而技术的高度主要是由你做的产品的特性决定的。
  所以有机会去开发一个好的产品是幸运的，需要机遇。好的产品才养人。 
  技术提高并不需要特别的努力。由于平时的工作内容就是最好的提升材料.  
  技术积累就像一种修行.要一步一个脚印日积月累的改善和提高.
------------------------------------------------加油----------------------------------------------------------------
-->
