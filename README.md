# Data-Mining

## 互评作业1: 数据探索性分析与数据预处理
### 1. 问题描述
本次作业中，自行选择2个数据集进行探索性分析与预处理。
### 2. 数据集
所选数据集为：<br>  
* [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews)
* [Chicago Building Violations](https://www.kaggle.com/chicago/chicago-building-violations)

### 3. 数据分析要求
#### 3.1 数据可视化和摘要
* 数据摘要<br> 
标称属性，给出每个可能聚会的频数<br> 
数值属性，给出5数概括及缺失值的个数<br> 

* 数据可视化<br> 
使用直方图、盒图等检查数据分布及离群点<br> 

#### 3.2 数据缺失的处理
观察数据集中缺失数据，分析其缺失的原因。分别使用下列四种策略对缺失值进行处理:<br> 

* 将缺失部分剔除
* 用最高频率值来填补缺失值
* 通过属性的相关关系来填补缺失值
* 通过数据对象之间的相似性来填补缺失值<br> 
注意：在处理后，要可视化地对比新旧数据集。<br> 

#### 4 数据集
* [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews) <br> 
130k wine reviews with variety, location, winery, price, and description<br> 

* [Chicago Building Violations](https://www.kaggle.com/chicago/chicago-building-violations)
From City of Chicago Open Data

## 互评作业2: 频繁模式与关联规则挖掘
### 1. 问题描述
利用所学数据挖掘技术，选择1个数据集进行频繁模式和关联规则挖掘，并撰写分析报告。
### 2. 数据集
所选数据集为：<br>  
* [Oakland Crime Statistics 2011 to 2016](https://www.kaggle.com/cityofoakland/oakland-crime-statistics-2011-to-2016)
### 3. 数据分析要求
* 对数据集进行处理，转换成适合进行关联规则挖掘的形式；
* 找出频繁模式；
* 导出关联规则，计算其支持度和置信度;
* 对规则进行评价，可使用Lift、卡方和其它教材中提及的指标, 至少2种；
* 对挖掘结果进行分析；
* 可视化展示。

## 互评作业3: 分类、预测与聚类
### 1. 问题描述
本次作业中，将从下面的3个问题中任选一个进行。
### 2. 数据集
所选数据集为：<br>  
* [Hotel booking demand](https://www.kaggle.com/jessemostipak/hotel-booking-demand)
### 3. 数据分析要求
该数据集包含城市酒店和度假酒店的预订信息，包括预订时间、停留时间，成人/儿童/婴儿人数以及可用停车位数量等信息。<br>

数据量：32列共12W数据。<br>

基于这个数据集，可进行以下问题的探索：<br>

* 基本情况：城市酒店和假日酒店预订需求和入住率比较；
* 用户行为：提前预订时间、入住时长、预订间隔、餐食预订情况；
* 一年中最佳预订酒店时间；
* 利用Logistic预测酒店预订。
也可以自行发现其他问题，并进行相应的挖掘。


