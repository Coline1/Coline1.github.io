# 8.1 无处不在的推荐

## Recommendation Systems

- Content-Based Filtering
- Collaborative Filtering

## Targeted Advertisement

Ads Engine



各种例子。

# 8.2 隐含语义分析

## TF-IDF

> 三个公式...
>
> **T**erm **F**requency：词频
>
> **I**nverse **D**ocument **F**requency：逆文档频率
>
> TF-IDF，越高越好。

Term-Document Matrix...



## Vector Space Model

将整篇文档转化为向量：$p=(w_{1,p},w{2,p},...,{w_{t,p}})$。（`w` stands for `word`，单词）

通过`cos`公式计算两篇文档的相似度，值越大越相似。

该模型存在的问题：

- Synonymy（同义词），导致 poor recall。
- Polysemy（一词多义），导致 poor precision。



## Latent Semantic Analysis

> Latent Semantic Analysis,隐含语义分析

举了个例子...

# 8.3 PageRank传奇

> google的衡量方法

取决于两个指标：

- PageRank（指向与自己网站的网页数量？）
- number of outbound links（指向自己网站的网页的出站连接总数）



# 8.4 协同过滤

> Collaborative Filtering,协同过滤

核心想法...

存在的问题...

## User-Based CF

在讲公式...



## Item-Based CF

举了一个例子。



## Model-Based CF



# 8.5 告诉你一个真实的推荐



Netflex案例。

KDD，数据挖掘顶会

淘宝推荐案例

Reality Mining