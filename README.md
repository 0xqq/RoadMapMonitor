# RoadMapMonitor
基于云平台的大数据路网流量管控(Traffic Control of Large Data Road Network Based on Cloud Platform)
## 项目简介
本项目为硕一的工程实践项目，小组总共是四人，本人担任组长，组员为：付何山、郭焯荣、薛兆江，

## 课题内容
根据某一阶段（3个月）上海市区的出租车GPS和公交车GPS行驶信息，充分挖掘出交通路网交通流量信息，开发一款基于后台大数据技术的云平台，以便后期路网流量的管控。

### 在地图匹配算法方面
通过分析国外开源地图数据，采用抽取路网骨干节点数据，将海量GPS数据匹配到路网骨干节点中，通过坐标修正和地图分块保证数据处理的精度和速度。

### 在平台方面
选取开源分布式架构Hadoop作为系统集群代替了传统单机系统，通过Hadoop分布式文件系统（Hadoop Distributed File System）实现了对海量浮动车数据的分布式存储，运用Map Reduce编程模型进行了海量浮动车数据的并行地图匹配。

### 在道路信息提取方面
将获得城市道路交通拥堵情况、交通流量、各主要路段的平均速度等交通信息。将这种宏观范围内、随时间动态变化的交通流信息进行动态演示，可为交通决策、管理和交通信息服务提供有力的数据支持。

## 系统需求

### 预处理
对浮动车数据地图匹配之前的预处理，包括三部分，对无用数据的剔除，海量浮动车文本数据的分布式存储和预处理，最后通过百度地图实现上海市路网拓扑的生成。

### 地图匹配
大规模的浮动车数据地图匹配计算。在Hadoop平台进行海量浮动车数据地图匹配实验中，本文的算法在硬件条件有限的情况下，正确率和运行速度两方面均有较好的表现，尤其是运行速度较单机有较大提高。

### 平台搭建

完成 Hadoop 分布式平台搭建，完成具体匹配 Map Reduce 程序，在实际的实验结果上，对比单机和 Hadoop 集群在匹配速度上加以图表来说明和分析地图匹配算法的有效性及效率。

道路信息提取和分析，获得城市道路交通拥堵情况、交通流量、各主要路段的平均速度等交通信息。

系统管理员有权限对用户进行管理，对系统进行维护更新。

### 系统演示

[路网管控平台](https://linmufeng.github.io/RoadMapMonitor/DemoVedio/demo.html)

[Hadoop分布式集群](https://linmufeng.github.io/RoadMapMonitor/DemoVedio/demo1.html)

[系统演示文稿](https://linmufeng.github.io/RoadMapMonitor/presentation.pdf)

---
# 修改日志

## 2017/8/11
* 本来想上传代码的，但是挺大的，如果有需要源码的，可以联系我

## 2017/7/11
* 解决无法播放视频的问题
* 上传源代码
* 添加部分开发文档

## 2017/7/10
* 更新目录，添加演示视频的链接

