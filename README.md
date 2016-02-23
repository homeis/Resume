#简历

##个人概况

* 徐敏 / 男 / 1989 / 大专
* 工作年限：5 year
* 出生年月：1989年10月
* 期望职位：高级软件开发
* 期望城市: 深圳
* 电话：13916445873
* E-mail：skgin@sina.com


##工作经历 


中国民航信息网络股份有限公司(上海)  


2010/12 -- 2015/5 

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


深圳天牧伯爵科技有限公司


2015/7 -- 至今

**擎天助汽车后市场生态系统**

**项目简介：**

* 通过擎天助智能终端采集车辆数据，为云平台提供数据支撑，结合10余年线下运营经验
* 打造一个联合汽车服务提供商、保险公司、配件供应商与车主之间的汽车后市场生态系统。
* 缔造一个公平、开放、透明、共赢的擎天助汽车后市场云平台，以促进整个汽车后市场生态圈良性发展。

**技术选型：**
* 操作系统：centos
* 项目管理工具: maven/svn
* 后台服务处理：Java(JFinal)
* 后台CSS框架：metronic(基于Bootstrap)
* APP：Hybrid开发模式(原生APP+HTML5页面)
* 数据库：mysql
* 应用服务器：nginx+tomcat
* 缓存中间件：redis
* ETL：kettle
* APP消息推送服务：小米推送
* APP分享控件：友盟
* 地图：百度地图

**项目职责：**
>* 系统框架搭建(数据库,nginx,tomcat,redis,svn安装配置等)
>* 部分表结构设计
>* 部分接口定义实现
>* 使用kettle做数据清洗,实现报表统计
>* 运营后台和商家后台实现


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
