# 个人信息

- 林战波 / 男 / 1989 
- 本科 / 太原工业大学
- 工作年限：5年
- 期望职位：技术专家，云计算开发工程师
- 手机：15120079724
- Email：lynzabo@hotmail.com
- QQ/微信号：lin_zhanbo
- Github：https://github.com/Lynzabo



# 个人评价

喜欢钻研新技术；有责任心；有耐心；工作中追求完美、细心，能抗压能加班；待人热情。 



# 专业技能

- 精通 Java/Golang/C++语言，了解Python；
- 熟悉Dubbo微服务框架，熟悉Spring、SpringMVC、SpringBoot等基础框架；
- 熟悉Docker、Kubernetes底层原理、实现；
- 熟悉kernel技术，如namespace、cgroup、lxc等；
- 熟悉常用CNI、CNM跨容器网络方案；
- 熟悉使用ZooKeeper/Etcd、Redis、ActiveMQ；
- 熟悉使用四层LVS、Haproxy、Nginx、Keepalived；
- 熟练常用设计模式；
- 熟悉Java传统加锁编程和CAS无锁编程；
- 熟悉Java NIO/AIO编程。




# 工作经历

## 乐视云计算有限公司 （ 2015年6月 ~ 至今 ）

### 乐视私有云PaaS平台 
**项目介绍**

乐视私有云PaaS平台是基于Docker轻量级容器，开源Kubernetes容器管理引擎开发的PaaS平台。在Kubernetes 2015年开源之前，我们就自主研发了容器管理编排引擎Beehive，为容器化MySQL数据库服务提供了资源调度、部署运行等一套功能，Beehive承载了乐视集团内部各个子生态数据库服务，线上已经为1100+的业务线提供数据库服务，4500+的容器规模，乐视RDS在集团内部数据库使用率已经达到70%以上。考虑到Kubernetes动态伸缩容快捷，RC灵活性等诸多优点，我们基于Kubernetes调度引擎，结合乐视现有状况，采用桥接容器大二层网络方案，提供了一套完整的代码构建、镜像仓库、应用管理、无DevOps一键式CI/CD解决方案，主要面向无状态Web服务、使用Dubbo/SpringCloud实现的微服务等等。各个业务线开发人员只需要提交代码，剩下的就会根据打包和构建规则自动生成特定的镜像版本，测试和运维人员只需要拿着对应的镜像版本进行测试和线上升级即可，极大简化开发运维工作。现在已经承接了乐视云计算、乐视体育章鱼TV、风云直播、乐视网乐看搜索、云相册等近200+重要业务，线上有300+计算节点，容器数量达到8000多。

**工作内容**

- 负责原平台单体应用的微服务拆分；
- 设计接入新服务代码模板、基础服务的抽象，简化接入新服务的难度和开发周期；
- 负责平台基础服务，用户通知中心、TCC分布式事务中心、有状态服务编排工作流引擎的开发工作；
- 负责接入disconf配置中心、Dubbox SOA框架、Zipkin分布式跟踪等中间件的指导工作；
- 负责平台基础服务、App服务、mysql 服务数据库读写分离、表分片的设计工作；
- 为满足乐视现状，容器内外服务在大二层网络可以互通，开发Kubernetes网络插件CNI；
- 参与自助研发容器管理引擎Beehive的容器选举、健康检查等核心功能的开发工作；
- 参与平台业务系统MySQL服务、App服务的开发，主要对Kubernetes、Docker进行二次开发；
- 参与mysql服务的用户端Web、管理端Web的Rest接口开发工作；
- 参与app服务的用户端Web、管理端Web的Rest接口开发工作；
- 参与App服务服务发现组件Leengine-sd组件开发。

**相关技术**

- 开发技术	

  Java,Go,Maven,Spring,SpringMVC,Dubbox,beego

- 依赖服务        Jenkins,SonarQube,SaltStack,Tomcat,MQ,Redis,MyCat,MySQL,Nginx,Haproxy,LVS,Keepalived,ZipKin,Zookeeper,Docker,Kubernetes,Etcd,Open-falcon,Grafana

### 火星一号

**项目介绍**

乐视火星一号是一套提供应用上线CI/CD的发版流程化、规范化的系统，提供了系统申请、拉取代码、编译打包、测试、填写上线计划、责任人审批、一键部署，验证及反馈结果，使得上线流程更加透视化，达到无DevOps。该套方案底层使用Jenkins Rest API和SaltStack Rest API开发。目前已经承接了乐视网、乐视体育、乐视云、风云直播等重要业务的上线工作，目前线上应用有400+，每天执行任务3000+次。

**工作内容**

- 参与系统应用管理、编译设置、部署设置的开发工作；
- 设计CI/CD上线、构建、部署一体化发版流程；

**相关技术**

- 开发技术	

  Java,Maven,Spring,SpringMVC

- 依赖服务        

  Jenkins,SaltStack,MySQL,Tomcat,Haproxy,Nginx,LVS,Keepalived,Vagrant,Prometheus,Grafana,Ansible



## 上云科技有限公司 （ 2014年6月 ~ 2015年6月 ）

### 上云数据分发平台 
**项目介绍**

上云是我和几位朋友创业的单位，核心服务是在公共场所提供免费wifi，吸引用户，提供免费新闻/视频等2C服务。上云数据分发平台和App是公司的两大核心系统，该平台最核心的工作就是将静态文件包括图片、视频、静态网页下发到节点服务器，也支持结构化文件下发，远程操作节点上Web服务的数据库，还支持远程执行命令或脚本，如SaltStack/Ansible，用到的最核心技术包括，使用Zookeeper临时节点实现的服务注册、服务发现，使用可靠消息服务实现消息最终一致性数据下发通知，使用Prometheus+Grafana做的服务监控。公司在2016年因为资金问题已经倒闭，平台曾经支撑过线上50+计算节点正常运行，每天平均下发5000+任务。

**工作内容：**

- 负责节点服务的服务注册、中心服务的服务发现开发；
- 基于可靠消息服务实现消息最终一致性，完成数据下发服务核心代码抽象；
- 编写prometheus格式的数据节点监控exporter；
- 负责平台用户中心，用户通知中心，报表中心等基础服务的指导和开发工作；
- 负责数据下发服务非结构化任务、结构化任务、远程CD任务的下发、执行工作。
- 负责Web管理端、其他系统调用的Rest接口开发工作。

**相关技术：**

- 开发技术	

  Java,Maven,Spring,SpringMVC,Dubbox

- 依赖服务        

  Jenkins,SonarQube,Tomcat,MQ,Redis,MyCat,MySQL,Nginx,Haproxy,LVS,Keepalived,Zookeeper,Vagrant,Prometheus,Grafana,Ansible

## 中国软件与技术服务有限公司 （ 2012年6月 ~ 2014年6月 ）

### 党政SaaS云原型系统

**项目介绍**

党政SaaS云原型系统是做政府OA业务，提供线上审批、领导日程、值班管理、会议管理等OA服务，该项目是为了解决传统MVC架构单体应用高并发时I/O瓶颈问题，公司成立党政云技术研发组，对公司现有传统框架进行服务化改造。

**工作内容：**

- 参与原系统单体应用的微服务拆分；
- 负责领导日程、值班管理、CMS开发工作；
- 参与用户中心，数据交换中心，CMS中心，报表中心等服务的开发工作；
- 参与审批工作流引擎的开发工作。

**相关技术：**

- 开发技术	

  Java,Maven,Spring,SpringMVC,Dubbox

- 依赖服务        

  Tomcat,MQ,Redis,MySQL,Nginx,LVS,Keepalived,Zookeeper
