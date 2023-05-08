# 个人信息

姓名: 杨东霖

教育: University of Regina, 2010 - 2013 (Electronic Engineering)

Github: https://github.com/Krysme

# 职业技能
* 熟练使用Rust和C++，并且对一些优秀的其它编程语言有所涉猎，比如Clojure, typescript 等等。
* 对GNU/Linux非常熟悉。
* 从一些加密货币挖矿项目中熟悉了cuda和通用GPU编程。
* 非常快速的掌握行业新知识。
* 对zk-snark有一定的理解。

# 近期参与的项目

## Filecoin 节点的二次开发
Filecoin区块链的主网节点 [lotus](https://github.com/filecoin-project/lotus)是由Filecoin创办方实现的挖矿软件，其性能并没有达到理论的极限，有优化空间。我们把它fork下来并且进行了二次开发用来给公司客户使用。我们自己的内部实现在速度上和内存空间消耗上，与开源版本相比，有非常明显的优势，尤其是在zk-snark的证明流程的算法优化上。

## 个人外包项目
一个嵌入式设备的自动灌溉项目，在ARM Linux设备上部署一个基于MQTT通讯的灌溉系统。这个项目需要用到Rust和C共同开发，由于MQTT当时没有Rust的实现，所以是一个Rust和C相互调用的一个进程。这个常驻进程会根据MQTT通讯内容来进行灌溉调度，以及雨量检测等活动。
  


# Misc
我在知乎上也回答过一些Rust和C++相关的问题，这些回答也会在一定程度上反映我对这些技术的理解。

[知乎](https://www.zhihu.com/people/krys-1998/answers)




# 工作经历

## 系统工程师 2014.8 - 2015.7 (广西支付通商务服务有限公司）
在这份工作中我负责维护一个金融后台，以及一些常见的服务器软件。这个后台是一个支付平台，以及一些互联网购物功能。

### 工作内容描述
* 负责维护支付系统后台。
* 负责排查系统故障，以及辅助主力开发人员。
* 系统管理，升级等。

## C++ 开发工程师 2015.7 - 2016.2 (上海新跃物流企业管理有限公司）
在这份工作中主要维护公司的电话VOIP系统，专门处理客户的咨询，投诉，等等。是一个C/S架构的软件模型。
In this job, I'm responsible for the client application of a voip calling system developed with WxWidget. The app interacts with the server to 
make/transfer calls and log customer complains.

### 工作内容描述
* 软件系统客户端的维护，BUG修复，开发新功能。
* 与其它部门的需求的沟通，并且讨论实现功能的时间表。
* 一些服务器软件的部署和研发。


## 技术负责人 2016.2 - 2017.11 (上海慎独信息科技有限公司）
该公司为一个刚成立的创业公司，成员大概10人不到，我的主要职责是负责整个软件部门的管理工作以及软件架构的设计和研发。软件的功能主要是服务与工业工程专业人员对制造业进行优化和效率提升。

### 技术细节
软件产品分为两部分，一个是是一个由Qt开发的人桌面客户端软件。另一个是由node.js开发的服务端。


### 工作内容描述
* 所有软件产品的架构设计和研发。
* 对员工进行定期技术培训。
* 和客户交流关于软件需求的事项。
* 团队管理、领导。


## 首席工程师 (Principal Engineer) 2017.11 - 2020.5 ([STAr Technologies(Wuhan)](http://www.star-quest.com))
### Abstract
STAr Technologies 是一个总部在台湾的半导体测试解决方案提供商，以及探针卡提供商。在这份工作中，我主要负责该公司的`Sagittarius`系列产品。 
产品链接：https://www.star-quest.com/english/info/category/SagittariusTMSIntelligentTest&MeasurementSoftware 。

该产是半导体中的参数测试的集成解决方案。


### 技术细节
`Sagittarius` 是一个由多个进程组成的高度集成项目，主要由C++编写。


### 工作职责
* 项目进度管理
* 项目架构设计
* 周期性的员工培训和技术分享。
* 与客户和其它部门沟通需求。
* 团队领导和员工管理。
* 与印度分公司团队沟通合作研发事宜，与分工。


## Rust主力开发 (星际无限/神算云科技)2020.9 - 2022.11
### Abstract
负责Filecoin的节点软件lotus的二次开发。我是该公司的唯一的rust开发人员，而lotus的密封算法是由rust模块编写，上层控制由go语言实现。
于是我便全权负责整个项目的性能优化工作。
* Filecoin密封挖矿算法的优化。
* bug修复以及负责矿机稳定性。
* 根据bip44/bip39规范开发数字钱包。


### 技术细节
算法优化主要用到以下技术
1. 实现一个效率更高的zk-snark证明系统。
2. 实现一个更加高效的利用CPU/GPU的算法，最大限度的分配任务给不同类型的硬件。
3. 利用CPU的拓扑结构来调整任务的硬件绑定，从而达到更大限度的缓存利用。
4. 尽量利用服务器的多核CPU进行并行运算，加速任务。

## Rust开发（北醌云科技）2022.12 - 2023.5

负责远程桌面控制APP的后端，用来控制云主机桌面。

### 技术细节
远程桌面主要用到：
1. ffmpeg 的rust/C FFI, 硬件/软件H.264编码。
2. WebRTC协议。
3. X11相关桌面控制，包括程序控制鼠标，键盘操作等，剪切板同步。
