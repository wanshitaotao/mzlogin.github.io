---
layout: post
title: hbase impala VS carbonData Spark-SQL
categories: Impala
description: 底层数据存储改变
keywords: impala, carbonData
---

​	2018之前我们在生产环境中原本用hbase进行存储，hive做元数据管理，impala作为查询引擎，每天百亿级数据量，我们对每天的数据进行select操作，包括两个join的操作，查询的时间大约在20分钟左右。

