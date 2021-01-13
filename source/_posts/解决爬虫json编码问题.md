---
title: 解决爬虫json编码问题
date: 2021-01-13 22:59:23
tags:python
---

# 乱码问题

在爬取中国工程科技知识中心时，json格式返回出现乱码

中文=？

解决方法

```python
r=requests.get(url=url,headers=head)
```