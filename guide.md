# 操作指南

{{indexmenu_n>2}}

## 资源池列表

在控制台，选择私有专区-\>资源池管理。进入资源池列表页面。展示所有的资源池。部分字段释义如下：

序列号：此序列号对应UCloud机房中唯一的物理机。

CPU，内存，磁盘：本资源池的CPU/内存/磁盘的踪迹资源和剩余资源。（包括专区主机的系统盘和数据盘都会消耗磁盘资源）

![image](/images/udset1.png)

## 资源池主机查看

选择对应资源池的“主机查看”选项，可查看该资源池下的所有主机。若需查看全部私有专区主机，或进行操作，需在控制台选择私有专区-\>主机管理，进入主机列表页。

![image](/images/udset2.png)

## 资源池申请

控制台暂未开放此功能，请联系我们的技术支持协助您完成此次申请。

## 资源池更改配置

控制台暂未开放此功能，请联系我们的技术支持协助您完成此次申请。

## 资源池删除

选中希望删除的资源池。选择面板左上角的删除按钮，执行删除操作。

注意，必须把该资源池上全部的主机都删除，才能删除该资源池。

## 私有专区主机列表

在控制台，选择私有专区-\>主机管理。进入私有专区主机列表页面，展示所有的主机。展示列与普通主机列表完全一致，除了不含计费方式与到期时间信息（因私有专区主机不计费，生命周期与资源池一致）。

![image](/images/udset3.png)

## 创建专区云主机

流程与创建普通主机基本相同。但请注意一下几点：

1）
根据整个私有专区所有资源池剩下的CPU，内存与磁盘情况，系统会实时计算您选择的当前配置与数量是否可以被满足。若无法被满足，您可以减小配置，减少申请数量，或升级/购买更多的资源池，以满足需求。

2） 创建的私有专区主机将根据UCloud的分配算法，自动分配到算法认为最优的资源池。

3） 暂不支持市场镜像，以及从市场镜像创建的自制镜像。

4） 专区主机仅支持标准机型，暂不支持开启数据方舟，热升级，网络增强等特性。暂不支持采用云硬盘的存储方式，仅支持本地盘。

![image](/images/udset4.png)

## 专区云主机升降级

流程与更改普通主机配置基本相同。但因专区所在资源池剩余CPU，内存，磁盘限制，可能无法升级到部分配置。

![image](/images/udset5.png)

## 专区云主机其他操作

其他操作和普通云主机完全一致。请参考 [云主机操作指南](..//uhost/guide/index)