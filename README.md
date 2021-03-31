# Data-Mining
For DM homework
互评作业1: 数据探索性分析与数据预处理
数据预处理方法
数据摘要

标称属性，给出每个可能取值的频数 数值属性，给出5数概括及缺失值的个数

数据可视化

使用直方图、盒图等检查数据分布及离群点

数据缺失值处理
观察数据集中缺失数据，分析其缺失的原因。分别使用下列四种策略对缺失值进行处理:

将缺失部分剔除
用最高频率值来填补缺失值
通过属性的相关关系来填补缺失值
通过数据对象之间的相似性来填补缺失值
注意：在处理后，要可视化地对比新旧数据集。

数据集
1 Wine Reviews
130k wine reviews with variety, location, winery, price, and description

description
Context
After watching Somm (a documentary on master sommeliers) I wondered how I could create a predictive model to identify wines through blind tasting like a master sommelier would. The first step in this journey was gathering some data to train a model. I plan to use deep learning to predict the wine variety using words in the description/review. The model still won't be able to taste the wine, but theoretically it could identify the wine based on a description that a sommelier could give. If anyone has any ideas on how to accomplish this, please post them!

Content
This dataset contains three files:

winemag-data-130k-v2.csv contains 10 columns and 130k rows of wine reviews.

winemag-data_first150k.csv contains 10 columns and 150k rows of wine reviews.

winemag-data-130k-v2.json contains 6919 nodes of wine reviews.
