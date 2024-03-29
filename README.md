# BlackWidow

### 黑寡妇

用于管理本地代码，联网获取题目，管理题目作为题库进行刷题

考虑到本地数据库有一百多兆，压缩后也有15M左右，离线数据库放置于release中。

## Function

### 1、题目插入

![avater](img/insert.png)

### 2、网络爬虫

获取在线平台 Online Judge上的题目，例如vijos，POJ

![avater](img/spider.png)

获取题目数据中

![avater](img/retriving.png)

题目获取结束

![avater](img/done.png)

### 3、数据处理

查询

![avater](img/query.png)

答案、提示

![avater](img/answer.png)

### 4、离线题库

![avater](img/database.png)

### 5、生成试卷

### 6、其他

皮肤--->提供亮色、黑色、灰色

![avater](img/skins.png)

Qmake：5.12.2

OS：5.0.2-2-MANJARO x86_64 GNU/Linux

Qt Creator：4.8.2

GCC：8.2.1

## Structure

### OJ columns

Platform Name Detail Level Type answer tip Language Submit Passed Rate

## Version

2019.7.20:

移除webview部件；

合并insert 和 query 

2019.5.4:

由BlackWidow拆分为两个：insert和query

2019.4.21:

添加所有平台数据，题目数为27117道，题目显示完全

2019.4.20:

添加POJ数据，题目数为20355道

2019.4.19:

添加大视野数据，题目数为16111道。

2019.4.18:

添加LUOGU数据，题目数为13814道;

添加多种字符集支持

2019.4.14:

删除27个子项目，调整软件架构

2019.4.4:

代码结构调整，将平台代码拆分开来

2019.3.2:

采集vijos平台1000-2050编号的数据

2019.2.21:

将项目拆分为两个，一个查询，一个添加题目

2018.8.23：

合并项目ant，改名为Blackwidow；

界面为Ant，黑寡妇作为爬虫模块；

软件结构重构；

2018.8.21:

OJSpider 改名为BlackWidow（黑寡妇）；

删除界面文件，仅保留功能模块；

将所有功能函数整合到两个文件中，作为爬虫模块调用；

添加json库；

2018.8.18

删除UI界面，对软件进行重构，全部采用代码

2018.8.15：

添加图片和图标

2018.8.14：

创建菜单和动作

2018.8.13：

初始化

2018.7.11

删除未使用的功能

2018.6.30

实现列排序，添加GNU GCC编译器;

优化代码显示；

2018.6.22

将正则表达式、网址作为配置文件读取，精简代码

2018.6.21

重构代码结构

2018.6.18

添加代理获取、验证和使用

2018.6.17

添加poj平台

2018.6.16

增加自动判断是否结束；完成vijos平台。

2018.6.14

题目格式、写入、读取

2018.6.3

初始界面、网络连接、文件操作、菜单、菜单栏

## 参考文档

[1]3D数学基础：图形与游戏开发.Fletcher Dunn,Ian Parberry著.史银雪，陈洪，王荣静译.清华大学出版社.2005.7

[2]版本控制之道----使用Git 程序员修炼三部曲 第一部.Travis Swicegood 著.董越 付昭伟 等译.电子工业出版社.2010.5.

[3]SQLITE 常用函数.https://www.w3cschool.cn/sqlite/sqlite-tutorial.html.Copyright © 2018 w3cschool.cn All Rights Reserved.

[4]C++ STL Reference Last modified on 6/23/2007 by Nate Kohl.

[5]https://blog.csdn.net.tax10240809163com/article/details/50610637.

[6]https://www.cnblogs.com/yjd_hycf_space/p/7495640.html

[7]https://blog.csdn.net/damage233/article/details/81116115
