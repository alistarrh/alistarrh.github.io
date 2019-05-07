

---
layout:     post   				    # 使用的布局（不需要改）
title:      Hackerrank  				# 标题 
subtitle:   #副标题
date:       2019-05-06 				# 时间
author:     Alistarrh						# 作者
header-img: img/access-algorithm-binary-193349.jpg 	#这篇文章标题背景图片
catalog: true 						# 是否归档
tags:		- Easy	- Basic Select	- Hackerrack	- SQL		#标签

---

# Revising the Select Query I

Query all columns for all American cities in **CITY** with populations larger than 100000. The CountryCode for America is USA.



**Input Format**

The **CITY** table is described as follows:

 <center>CITY</center>

|Field|Type|
|---|---|
|ID|NUMBER|
|NAME|VARCHAR2(17)|
|COUNTRYCODE|VARCHAR2(3)|
|DISTRICT|VARCHAR2(20)|
|POPULATION|NUMBER|

**Solution**

```mysql
SELECT * FROM CITY
WHERE COUNTRYCODE = 'USA' AND POPULATION > 100000
```

