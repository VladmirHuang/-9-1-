# AI-Studio-【飞桨学习赛：个贷违约预测】9月第1名方案

## 项目描述
> 本方案主要参考了官方推荐的精选项目：https://aistudio.baidu.com/aistudio/projectdetail/3555696

1. 对于样本不平衡的问题，修改损失函数的权重，将负样本的权重设为0.2，正样本为1.2
2. 对于连续数值型变量进行均值-方差归一化
3. 对于分类变量，在网络中进行重编码（即增加一个全连接层，用于模拟embedding）
4. 对一些变量进行了简单的变换与特征工程。

## 项目结构
```
-README.MD
-【飞桨学习赛：个贷违约预测】9月第1名方案.ipynb
```
## 使用方式
A：在AI Studio上[运行本项目](https://aistudio.baidu.com/aistudio/projectdetail/4577707)  
B：下载ipynb文件和[训练集](https://aistudio.baidu.com/aistudio/datasetdetail/130186)、[测试集](https://aistudio.baidu.com/aistudio/datasetdetail/130187)后，更改文件路径进行训练、测试即可。
