---
gosearch是一个以web图像搜索应用

##搜索框架

1. 首先提取图像库first500中各个图像的sift特征，每幅图像会对应一个提取的特征文件。
2. 采用BOW模型构建词汇向量，并配以tf-idf权重。
3. 进行匹配。