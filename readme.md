# torchtext数据预处理库实践
## 项目结构
 - CNN_分类：
 > 利用pytroch深度学习库，模拟了运用卷积神经网络进行分类的大体过程
 > 训练集词汇表，word2id（dict）的生成，word2id映射，搭建网络结构，选择损失函数，优化器，
 读取数据，预测，计算loss，反向传播。
 - LSTM_分类：
 > 测试以预训练的词向量文件为基础构造词向量文件，然后与train数据集进行融合得到整个vocabulary，
 然后利用预训练的词向量文件生成词向量。
 - LSTM:
 > 在aclImdb数据集上，使用torchtext模块与glove.6B.100d词向量，对评论进行分类。
 - txt2csv:
 > 将aclImdb中的结构分散的为清洗数据，进行正则化清洗，整合。
 - torchtext教程：
 > [ Torchtext官方文档 ]( https://torchtext.readthedocs.io/en/latest )
 > [ Torchtext 入门教程，轻松玩转文本数据处理 ](https://zhuanlan.zhihu.com/p/31139113)
 > [ Torchtext 详细介绍 Part.1 ](https://zhuanlan.zhihu.com/p/37223078)
