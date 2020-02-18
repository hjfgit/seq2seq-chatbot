
# seq2seq-chatbot
### **先上效果图**

<img src="./img/test.png" style="zoom:67%;" />

### 文件说明

**1.config.py参数配置文件**

主要进行模型超参数以及相关文件路径的配置

**2.DataProcessing.py 预处理文件

主要进行语料库的处理工作，包括语料处理、编码索引、生成语料库的词向量文件emb等。

**3.read_vecor.py 修改词向量文件**

主要加入了  
PAD = '<PAD>'  # 填充
UNK = '<UNK>'  # 未知
START = '<SOS>'

END = '<EOS>'

这四个的词向量，随机生成（设置随机种子）。

**4.SequenceToSequence.py Seq2Seq模型**

**5.Train.py 训练文件**

运算只需要运行此文件即可

**6.RestfulAPI.py

运行此文件，然后打开index.html，即可进行人机对话。

### **模型文件及相关数据文件请参考百度网盘：**

链接：https://pan.baidu.com/s/1tIyCmAQbhwuhiY9bq-A5Sw 

提取码：idvz

### **详细介绍请参考博客：**

[1.基于seq2seq的中文聊天机器人（一）](https://blog.csdn.net/daniellibin/article/details/103290169)

[2.基于seq2seq的中文聊天机器人（二）](https://blog.csdn.net/daniellibin/article/details/103290395)

[3.基于seq2seq的中文聊天机器人（三）](https://blog.csdn.net/daniellibin/article/details/103290756)


