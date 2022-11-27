# SpringbootLucene
一个用Springboot框架实现的索引（？）

### 简介
这是一个Springboot框架+Lucene实现的简单搜索引擎，关于Lucene这里就不多赘述了，可以直接找博客去看

### 需求
首先在properites文件中配置好数据库，SQL代码跟爬虫的相同

如果要使用的话直接在Application函数重写了run函数，改变其中service调用的search函数即可


## 我必须要吐槽一下Lucene跟IKAnalyzer，Bean嘛注入不了，ApplicationContext嘛加载不到，版本嘛各种冲突，报错嘛天花乱坠，爷直接new了。

有时间会更新SOlr或ES的（~会吗？~）


### 实现结果
我直接输出在idea的控制台了（这里的数据用的是之前爬虫爬到的，没有多少）
![image](https://github.com/hypermuteki-Xue/SpringbootLucene/blob/main/QQ%E5%9B%BE%E7%89%8720221127202837.png)
