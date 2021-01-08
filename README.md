# xjtuer-eat-report
# 西交人年度吃饭报告
[数据地址](https://card.xjtu.edu.cn/) 
![看起来是这样子的](https://github.com/notomatoes/xjtuer-eat-report/blob/main/img/%E7%95%8C%E9%9D%A2.jpg)
![test](https://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=douban&step_word=&hs=0&pn=2&spn=0&di=990&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=0&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=undefined&cs=1599985166%2C1948935260&os=2097405593%2C1627484187&simid=3350026996%2C429053443&adpicid=0&lpn=0&ln=1938&fr=&fmq=1610081031172_R&fm=&ic=undefined&s=undefined&hd=undefined&latest=undefined&copyright=undefined&se=&sme=&tab=0&width=undefined&height=undefined&face=undefined&ist=&jit=&cg=&bdtype=0&oriquery=&objurl=https%3A%2F%2Fgimg2.baidu.com%2Fimage_search%2Fsrc%3Dhttp%3A%2F%2Fcrawl.nosdn.127.net%2Fe207652a99b8878e430bfac891dbca6d.jpg%26refer%3Dhttp%3A%2F%2Fcrawl.nosdn.127.net%26app%3D2002%26size%3Df9999%2C10000%26q%3Da80%26n%3D0%26g%3D0n%26fmt%3Djpeg%3Fsec%3D1612673034%26t%3D37a07fbdaa9c3429cf19dd7baf5ca8d6&fromurl=ippr_z2C%24qAzdH3FAzdH3F1y_z%26e3B8mn_z%26e3Bv54AzdH3FedAzdH3Fw6ptvsjAzdH3F1jpwtsAzdH3FDVSnUIEUac88A8RI_z%26e3Bip4s&gsm=3&rpstart=0&rpnum=0&islist=&querylist=&force=undefined)


## 登录网站 
- requests+post
- selenium
- ...


## 爬取网页代码 -> 数据处理
- beautifulsoup  解析网页获取数据对应的tag
- [提取完对应的数据长这样子](http://htmlpreview.github.io/?https://github.com/notomatoes/xjtuer-eat-report/blob/main/img/consumption_data.html)

## 必要数据获取及存储
- 刷卡点名称
- 金额
- 时间
- ...
- 处理完下面这样子 

![img](https://github.com/notomatoes/xjtuer-eat-report/blob/main/img/table.png)

## 数据可视化
### 词云
- [wordcloud](http://amueller.github.io/word_cloud/auto_examples/index.html)   根据词频生成词云
- 下图是简单实现的效果
![简单的效果图](https://github.com/notomatoes/xjtuer-eat-report/blob/main/img/result1.jpg)
- [jieba](https://pypi.org/project/jieba/)    用于中文分词,本项目暂时用不到 
### 统计图
- [matplotlib](https://matplotlib.org/gallery/index.html)   数值上可视化
### 抽取某些数据进行网易云style
- 2020年12月21这天 凌晨03:57 已经很晚了,你还在洗澡,这一天你一定学习到很晚,或许你遇到了什么兴奋的事情
- C2铁板炒饭是你做喜欢的食物,阿姨一定认识你吧
- B2香锅曾经是你最喜欢的地方,但你好像很久没去了......
### 进行数据预测
- 洗澡时间 扔到神经网络里预测后面的时间
- ... 
## todolist 
### 写一个接口,登录直接在h5页面获取以上数据 年度报告风
### 写完开源,目前散装
### ...
