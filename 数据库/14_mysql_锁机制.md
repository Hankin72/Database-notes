# MySQL --- 锁机制

![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制.png)

![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制2.png)

![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制3.png)

![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制4.png)

## 锁机制 --  MyISAM 表锁

![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制-表锁.png)

> **创建表的时候需要指定 存储引擎 myisam**
>
> ![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制-表锁1.png)
>
> ![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制-表锁2.png)
>
> ![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制-表锁3.png)
>
> ![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制-表锁4.png)
>
> > write 锁是一种独享锁，互斥锁，排他锁； 对于同一张表，同一时间只可以加一个



## 锁机制 -- InnoDB 行锁

![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制-行锁.png)

![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制-行锁2.png)

> ![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制-行锁3.png)
>
> ![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制-行锁4.png)
>
> ![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制-行锁5.png)
>
> ![](/Users/guohaojin/Desktop/春招-招聘-计算基础总结/数据库/imgs/0锁机制-行锁6.png)
>
> ![]()
>
> 















