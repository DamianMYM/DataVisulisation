# Week5 Lab
本节课我们将巩固使用Python进行数据可视化分析的基础。  
从Numpy、Pandas和Matplotlib官方文档看起。 

https://numpy.org/doc/stable/user/quickstart.html
## Quiz-01 Loading a sample dataset and calculating the mean.
In this Quiz, we will be loading the normal_distribution.csv dataset and calculate the mean of each row and each column with it.
Our dataset will have several rows each containing floating point numbers around 100 with a standard deviation of 5.
Just to refresh your knowledge, a Gaussian normal distribution resembles the plot
这个练习，将加载normal_distribution.csv数据集，并计算其中每行和每列的平均值。
## Lab01 使用Numpy计算平均值、中位数、方差和标准偏差
本节练习将练习巩固之前学习的技能。
## Lab02 使用Numpy索引、切片、分割和迭代
当前操作将使用Numpy中的相关特性对ndarray进行索引、切片、分割和迭代，进而巩固之前所学的知识。当前，需要证明数据集完美地围绕均值100分布。
## Lab03 使用Numpy过滤、排序、组合和重构
作为最后一项Numpy任务，该操作相对复杂。

## Pandas
这一节会介绍Pandas，当与复杂数据协同工作时，pandas表现得十分优秀。pandas还支持数据集中不同的数据类型。以下是pandas的官方文档。
https://pandas.pydata.org/
## Quiz-02 Loading a sample dataset and calculating the mean.
In this exercise, we will be loading the world_population.csv dataset and calculate the mean of some rows and columns.
Our dataset holds the yearly population density for each country. We can, therefore, use Pandas to get some really quick and easy insights.

## Lab04 使用Pandas计算平均值、中位数和给定数字的方差
当前操作导入数据集，执行某些基本的计算，并利用pandas实现之前的任务。
## Lab05 基于Pandas的索引、切片和迭代
当前操作将使用之前讨论的pandas特性，并通过pandas的Series对DataFrame进行索引、切片和迭代。为了获得数据集中的洞察结果，需要显式地索引、切片和迭代数据。  
例如，可在人口密度增长方面对多个国家进行比较。随后，我们将显示德国、新加坡、美国和印度在1970年、1990年和2010年的人口密度。
## Lab06 使用Pandas过滤、排序和重构
最后一项Pandas操作稍显复杂，并整合了之前所介绍的大多数方法。在该操作讨论完毕之后，大家应该可以阅读大多数pandas代码。


## Matplotlib的回顾
https://matplotlib.org/
我们来看一个官网的例子。  

## Quiz-03 Creating visualization--Water usage.
Open page78 创建耗水量饼图
## Quiz-04 Creating visualization--Radar Charts.
数据集包含4名员工5个不同属性的评分数据。
A radar chart is basically a line plot with a polar projection. There are two major things we have to do. First, we have to repeat the first values at the end to close the line. Second, we have to create a subplot with polar projection.
