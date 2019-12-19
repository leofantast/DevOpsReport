[TOC]

# 竞品分析：华为DevCloud vs 阿里云效 vs 腾讯Coding Devops

## 1. 产品介绍
### 华为Devcloud
<a href="https://www.huaweicloud.com/devcloud">DevCloud</a> 是集华为研发实践、前沿研发理念、先进研发工具为一体的研发云平台。面向开发者提供研发工具服务，让软件开发简单高效。

![image-20191207164317391](https://tva1.sinaimg.cn/large/006tNbRwgy1g9o92wnadcj30wl09pask.jpg)

### 阿里云效
<a href="https://rdc.aliyun.com">云效</a>，一站式企业协同研发云，源于阿里巴巴多年先进的管理理念和工程实践，提供从“需求->开发->测试->发布->运维->运营”端到端的协同服务和研发工具支撑。云效将战略规划、敏捷研发、持续集成、持续交付、DevOps等理念引入银行、保险、民航等大型企业和互联网初创企业，支持公有云、专有云和混合云的协同研发，助力企业产品快速创新迭代和研发效能升级。

![image-20191207165403870](https://tva1.sinaimg.cn/large/006tNbRwgy1g9o9e3feiwj31020g3k2t.jpg)

### 腾讯云Coding DevOps
<a href="https://cloud.tencent.com/product/coding">CODING DevOps</a> 包括代码托管、项目管理、测试管理、持续集成、制品库等多款产品和服务，涵盖软件开发从构想到交付的一切所需，使研发团队在云端高效协同，实践敏捷开发与 DevOps，提升软件交付质量与速度。 

![image-20191207165622226](https://tva1.sinaimg.cn/large/006tNbRwgy1g9o9gh8y1mj312s0d7djo.jpg)

Coding DevOps比较特殊，是由腾讯云对Coding完成全资收购后，Coding入驻腾讯云平台。具体为2019年8月Coding进驻腾讯云官网「开发者工具」系列，给腾讯云用户提供 DevOps 研发管理协作工具。

> 腾讯云开发者平台：https://dev.tencent.com/

## 2. 市场分析

在10月份，全球领先的专业市场调查机构国际数据公司（IDC）发布了《IDC MarketScape：中国DevOps云服务市场2019厂商评估》报告，目前华为云在市场表现与现有能力两大维度均排名第一，全面领跑DevOps云服务市场，排名第二第三的分别是阿里云和腾讯云。

![IDC：华为云市场份额第一，领跑中国DevOps云服务市场](http://img.zhiding.cn/5/195/liuWf6qcy5Q_600.jpg?rand=100)

插个有趣的故事，在笔者创业期间，由本人牵头对接华为云，在贵阳为合作公司免费争取到价值￥48000，为期一年的云服务器和DevCloud服务；其中大部分由政府补贴，在贵阳只要是创业公司都可以申请，几乎没有门槛，可以看出DevCloud的市场份额也得益于与政府相关部门合作。

阿里云效的市场份额则得益于阿里巴巴强大的TO B基因，拥有和大量中小企业合作的基础，这不单是DevOps产品层面，整个阿里云的市场都因此收益。

由于2019年8月Coding才正式进驻腾讯云，用户群体主要是Coding以前积累的存量用户，所以在三大DevOps产品中排名靠后也在情理之中，相信Coding入驻腾讯云后，能借力腾讯生态占领更高的市场份额。

## 3. 产品定位
||主要用户群|主要功能|
|:--:|:--:|:--|
|DevCloud|项目经理、产品经理、开发人员、测试人员、运维人员|项目管理、代码托管、流水线、代码检查、编译构建、云测、移动应用测试、部署、发布、CloudIDE、Classroom、开源镜像站|
|阿里云效|项目经理、产品经理、开发人员、测试人员、运维人员|1. 项目：项目管理、指挥部<br>2. 研发：代码服务、配置管理、应用管理、交付管理<br>3. 测试：单测持续集成、测试环境管理、WebUI自动化、性能压测自动化、接口自动化、集成自动化、用例管理、缺陷管理、Mock中心<br>4. 运维：CMDB、资源管理、发布部署、作业平台、P2P文件分发、堡垒机、运维通道、掌上运维、智能监控|
|Coding DevOps|项目经理、产品经理、开发人员、测试人员、运维人员|代码托管、项目管理、测试管理、持续集成、制品库、持续部署|

## 4. 信息架构

### DevCloud

![image-20191208130549593](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p8ewfukoj31bs07gdgf.jpg)

DevCloud将十二个子服务和项目并列，意味着在项目层面以外可以创建单独的子服务，适用于只需要使用DevOps体系中某个子功能的场景。

### 阿里云效

从信息架构图就可以看出，阿里云效并不像产品首页宣传的那样包含20几个功能，其定义的功能看似大而全，其实是将阿里云其他独立的云服务也在概念上囊括进了DevOps体系，不过也有可能在以后的产品规划中将所描述的所有功能整合到云效。

![image-20191208131118817](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p8km516xj30pt05u3ys.jpg)

### Coding DevOps

由于Coding DevOps定位是专注于研发项目管理，所以产品路径是直接进入到某个项目进行操作。

![image-20191208142342186](https://tva1.sinaimg.cn/large/006tNbRwgy1g9panxjfc4j30ky06gaaa.jpg)


## 5. 产品体验
### DevCloud

DevCloud没有授权、创建团队或创建企业等步骤，而是直接进到项目管理页创建项目，团队成员可在需要的时候添加。

DevCloud以项目维度为默认首页。菜单栏涵盖工作台、管理看板、服务和华为镜像站四大模块。

![image-20191208122804724](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p7bma4xcj30at0epwfp.jpg)

![image-20191208121207891](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p6v186oqj31aa0a5q46.jpg)

项目分细分为两种项目类型，Scrum和看板。Scrum适用于研发维度的项目管理，集成了需求规划、里程碑、Feature、Backlog等完善的Scrum模块；看板则适用于产品和业务维度的项目管理，市场竞品如teambition、tapd。

![image-20191208122025304](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p73nsyd9j31gx0a1dhp.jpg)

![image-20191208125839991](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p87g3mcvj31gt08mwgy.jpg)

### 阿里云效

![image-20191208152147352](https://tva1.sinaimg.cn/large/006tNbRwgy1g9pcccw1wnj30mg0423yq.jpg)

云效首页以持续交付和项目管理为两大入口，其中持续交付对应流水线，项目管理又分为研发项目和业务空间。

![image-20191208123903784](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p7n1vm0jj30sm09gmxx.jpg)

![image-20191208123531488](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p7jdercgj313s0lmtbk.jpg)

> 这里不得不吐槽的是，云效的产品首页提供了太多入口，导致新用户体验不好友，第一次进入不能快速构建想要的项目类型。

![image-20191208123731078](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p7lftuacj30n209l3z5.jpg)

研发项目对应DevCloud的Scrum项目，业务空间在产品逻辑上不是对应DevCloud的看板，在云效的业务空间中只是将研发项目的需求和缺陷(bug)两大模块抽离出来，所以这里笔者不明白云效的产品设计逻辑。

![image-20191208124547228](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p7u1taboj30bq0gcwfm.jpg)

![image-20191208124610054](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p7ufrqxjj30ba08waaw.jpg)

### Coding DevOps

![image-20191208152057158](https://tva1.sinaimg.cn/large/006tNbRwgy1g9pcbi205hj30mm03maaa.jpg)

由于Coding专注于研发项目管理，所以产品结构树最清晰，从首页开始创建项目后，直接进入研发项目管理流程。

![image-20191208125227713](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p80zvernj31vg0ieac7.jpg)



> DevOps工具链涵盖的子产品较多，功能丰富，每个子产品写竞品分析都需要另立篇章，由于时间和精力限制，本文只从关键的产品入口和项目管理维度进行了宏观的产品体验。这也作为自己的一个小目标，在以后的工作时间输出更深度的产品体验和分析报告。

## 6. 文档和社区建设

### DevCloud

![image-20191207182214761](https://tva1.sinaimg.cn/large/006tNbRwgy1g9pla6gavyj30d006sq7m.jpg)

文档入口设置在banner页，包含以下几大模块：

* 产品介绍
* 购买指南
* 快速入门
* 最佳实践
* API参考
* 常见问题
* 理论实践

除了完善的文档，华为云课堂开发了《DevCloud介绍和实战》、《华为DevOps实践》、《7天玩转性能&接口测试实战营》三大视频课程。

社区建设部分，DevCloud有独立的论坛模块，整体活跃度一般，活跃度较高的帖子几乎都是官方的公告或活动。

![image-20191207181537504](https://tva1.sinaimg.cn/large/006tNbRwgy1g9obqx8eplj31010d1q7i.jpg)

![image-20191207181905209](https://tva1.sinaimg.cn/large/006tNbRwgy1g9obuiyipkj31110ildlc.jpg)

### 阿里云效
文档入口在产品首页最底部，包含以下几大模块：

* 产品简介
* 快速入门
* 使用指南
* 开发指南
* 常见问题
* 最佳实践
* 视频专区
* 相关协议
* 云效公有云资费

阿里云效文档简洁，视频专区也只有三个部分，总共不到10分钟的课程。

阿里云效没有单独的社区，官网的云栖社区几乎没有用户贡献内容和互动。

![image-20191208104150043](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p4935wxxj30oq0pj7a6.jpg)



### Coding DevOps

![image-20191207183719711](https://tva1.sinaimg.cn/large/006tNbRwgy1g9ocdisyxaj30mw04ct8s.jpg)

Coding DevOps的文档入口相对DevCloud和阿里云效多了一个步骤，文档包含如下模块：

* 产品简介
* 购买指南
* 快速入门
* 操作指南
* 常见问题
* 服务等级协议
* 词汇表

> Coding DevOps在腾讯云呈现的文档是最简略的，Coding其实有专门的help入口：https://help.coding.net/。 这和Coding的定位有关系，腾讯云只提供入口，底层服务由Coding提供。在进入到Coding的帮助页之后，可以看到文档就相当丰富了。

![image-20191207184538053](https://tva1.sinaimg.cn/large/006tNbRwgy1g9ocm66fjuj30qm0qsgqn.jpg)

在Coding官网没有社区入口，只提供了一对一的客服服务。腾讯云官方社区跟云效类似，几乎没有用户贡献内容和互动。

![image-20191208104836410](https://tva1.sinaimg.cn/large/006tNbRwgy1g9p4g4golxj30vs0rf44v.jpg)

## 7. 服务

||邮件|电话|社群|建议反馈|
|:--:|:--:|:--:|:--:|----|
|DevCloud|无|华为云统一客服入口|独立论坛|华为云统一的反馈入口“云声平台”|
|阿里云效|无|阿里云统一客服入口|钉钉用户交流群：群人数318，活跃度一般|文档页提供反馈表单|
|Coding DevOps|enterprise@coding.net（企业用户）<br>support@coding.net（个人用户）|400-830-6861|没有用户社群，但提供团队微信为用户答疑|腾讯云提供工单反馈入口|


## 8. 总结

本文从产品概要、市场、定位、信息架构、产品体验、文档和社区建设和服务七个维度对三大DevOps云产品进行分析。三个产品的定位大同小异，模式都是云+DevOps，旨在为用户提升研发效能，目前华为云占据最大的市场份额，阿里云效和腾讯云分别次之。信息架构和产品体验层面，华为DevCloud和Coding DevOps易上手，阿里云效需要一定的时间去熟悉名词定义、交互及页面逻辑。DevCloud和Coding DevOps文档都很丰富，阿里云效就相对差强人意。此外，三个产品的社区建设都不理想，但阿里云效借助钉钉即时通讯工具，为用户提供即时的答疑服务，DevCloud和Coding DevOps在服务层面反馈就相对较慢。


## 9. 参考

IDC：华为云市场份额第一，领跑中国DevOps云服务市场：http://soft.zhiding.cn/software_zone/2019/1030/3122166.shtml

蓝鲸DevOps深度解析系列（1）：蓝盾平台总览：https://cloud.tencent.com/developer/article/1375793

华为云 DevCloud 首席产品布道师：AIOps 不是 DevOps 的下一代：https://www.infoq.cn/article/KmAt932YKhIIdH77QBwI

CODING 获腾讯云一亿元战略融资，让云资源触手可及：https://blog.coding.net/blog/financing

阿里1682亿背后的协同研发云——云效正式商业化：https://yq.aliyun.com/articles/409024?spm=5176.11065265.1996646101.searchclickresult.7a8e271afseily&aly_as=HbdAEOBz


































