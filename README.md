# 毕业设计：互联网新闻热点抽取系统
对于今日头条网页进行新闻标题抓取，分词向量化后进行文本聚类。

通过对新闻标题信息的抓取、预处理、特征提取等，提取中文分词后的关键短语，并利用对关键词的词频统计和排序，将向量化的标题信息进行聚类，最终得到相应的热点新闻话题。课题研究的主要工作包括以下几点：

（1）	基于Python语言，利用Selenium模拟普通浏览用户的方式进行网络爬虫，抓取相应的新闻数据信息，并保存到本地。

（2）	针对抓取出的数据进行中文分词，采用jieba分词对新闻标题进行切分，同时引入预设的字典以及停用词表配合分词筛选。

（3）	对于分词后的数据信息进行词频统计，采用TF-IDF词频统计方法，将结果保存到本地。同时输出纯词频个数统计并保存。

（4）	利用词频数据对文本信息进行向量化，建立数据矩阵，并保存。

（5）	采用k-means聚类算法，对数据矩阵进行聚类，将处理结果与原始文本信息进行合并处理，并输出聚类结果。

（6）	输出最大类簇，即热点类簇，并统计系统准确率与召回率。


