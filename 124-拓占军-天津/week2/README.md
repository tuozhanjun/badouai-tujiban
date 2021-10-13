第一次调整:
1.调整激活函数sigmod为relu
2.调整dropout = 0.2
3.优化器用Adam
4.池化层采用Maxpool

第二次调整:
1.调整激活函数sigmod为relu
2.调整dropout = 0.5
3.优化器用Adam
4.池化层采用Avgpool

第三次调整:
1.调整激活函数sigmod为relu
2.调整dropout = 0.46
3.优化器用SGD
4.池化层采用Maxpool

第一次最优,第二次次之,第三次最差