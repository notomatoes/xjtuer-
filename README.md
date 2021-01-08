# xjtuer-eat-report
# 西交人年度吃饭报告
[数据地址](card.xjtu.edu.cn) 



## 登录网站 
- requests+post
- selenium
- ...


## 爬取网页代码 -> 数据处理
- beautifulsoup
- [提取完对应的数据长这样子](http://htmlpreview.github.io/?https://github.com/notomatoes/xjtuer-eat-report/blob/main/img/consumption_data.html)

## 必要数据获取及存储
- 刷卡点名称
- 金额
- 时间
- ...

## 数据可视化
### 词云
- [wordcloud](http://amueller.github.io/word_cloud/auto_examples/index.html)   根据词频生成词云
![简单的效果图](https://github.com/notomatoes/xjtuer-eat-report/blob/main/img/result1.jpg)
- [jieba](https://pypi.org/project/jieba/)    用于中文分词,本项目暂时用不到 
### 统计图
- [matplotlib](https://matplotlib.org/gallery/index.html)   数值上可视化
### 抽取某些数据进行网易云style
- 2020年12月21这天 凌晨03:57 已经很晚了,你还在洗澡,这一天你一定学习到很晚吧
- C2铁板炒饭是你做喜欢的食物,阿姨一定认识你吧
- B2香锅曾经是你最喜欢的地方,但你好像很久没去了......
### 进行数据预测
- 洗澡时间 扔到神经网络里预测后面的时间
- ...
