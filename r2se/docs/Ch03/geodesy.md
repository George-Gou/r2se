# 概述

!!! abstract "导言"

    本章主要介绍大地测量的专业知识。大地测量是研究地球形状及表面特性的测量工作，目的是获取地球表面空间及其地球重力场的静态或动态信息。    

## 大地测量基准框架

### 坐标框架

大地测量的测量成果要有基准框架来实现。根据其原点的不同，大地测量坐标系统分为**参心坐标系统和地心坐标系统**。  

参心坐标系统是定义在惯性系下的，其假设地球是静态的，满足牛顿惯性定律，原点在参考椭球体的中心。但实际上地球是有自转的，  **地心坐标框架**就是一个全球性的、三维动态的坐标框架，我国的2000国家大地坐标系就是地心坐标框架，原点在地球质心。

### 高程系统

高程基准定义了陆地上高程测量的起算点。我国的高程基准是1985国家高程基准，水准原点的高程为72.2604m。我国使用的正常高的基准是大地水准面，相关信息可以参考我的博文[一文扫盲“大地水准面”](https://mp.weixin.qq.com/s/D7XHfKJRb-4cPn7_Thgfhg)。  

### 深度基准

深度基准面的选择与海区潮汐情况相关。一般将验潮站数据进行调和分析，得到各个潮波的振幅和相位来确定。

### 重力框架

重力系统是值采用的椭球常数及其相应的正常重力场。



### 时间系统

大地测量常用的时间系统有：1）世界时（UT）、2）原子时（AT）；3）力学时（DT）；4）协调时（UTC）；5）GPS时；    

建立一个时间系统通常需要借助一个可重复观测、连续、稳定的周期运动现象作为基准。  

世界时是基于地球自转而建立的时间系统。那么地球转一周是严格的一圈吗？实际上不是，由于极移（地球自转轴本身运动）、季节性变化、地球自转速度等原因，经极移校正的世界时按照每年约1s的速度变慢。  

原子时作为高精度的时间基准，其原理是：当物质内部的原子在两个能级上跃迁时，原子会辐射或吸收一定频率的电磁波能量，原子钟是以这种高度稳定的电磁波振动频率来工作的。  

那么原子时与世界时存在的差距怎么办呢？  

**协调世界时（UTC）**就是来解决这个问题的。它是世界时与原子时的一种折中方案。一方面它严格以精确的原子时秒长为基础，但在协调时与世界时差距超过0.9 s时，就采用跳秒的方式来实现同步（即在某个时刻等世界时 1s）。

GPS 时与国际原子时保持有 19s 的常数差。

## 常用坐标系及其转换

地球不但随太阳公转，还会自转，这就给我们在地球上建立的参考系增加了难度。因此，定义一个坐标系是一件复杂但很重要的事。  

### 大地坐标系

原点在地球质心，大地纬度B为过地面点的椭球法线与椭球赤道面的夹角，大地经度L为过地面点的椭球子午面与格林威治大地子午面之间的夹角，大地高H为地面点沿椭球法线到椭球面的距离。

### 空间直角坐标系

坐标原点位于参考椭球的中心，Z轴指向参考椭球的北极，X轴指向起始子午面与赤道的交点，Y轴位于赤道面上按右手系于X轴呈90°夹角。更多是一个定义在数学上的坐标系。  

### 高斯平面直角坐标系





## 引用来源 {#references .no-underline}
<div id="refer-anchor"></div>
 [1]《一级注册计量师基础知识及专业实务》  