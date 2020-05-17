# Kaggle-M5-Forecasting-Accuracy-Project

## 目录
![image](https://github.com/Zhu-Haikun/Kaggle-M5-Forecasting-Accuracy/tree/master/image/contents.png)

## 项目背景
由预测专家[Spyros Makridakis](https://en.wikipedia.org/wiki/Makridakis_Competitions)组织的M竞赛，旨在通过比较在不同预测方法下解决现实问题的性能，从而更好地理解和改进预测方法。 第一届M比赛于1982年举行。第四届[M4比赛](https://www.sciencedirect.com/science/article/pii/S0169207019301128)于2018年举行，其特色是“ 100,000个时间序列和61种预测方法”。 根据预测研究人员和从业者[Rob Hyndman](https://robjhyndman.com/hyndsight/)所说，“M竞赛对预测领域产生了巨大影响。 他们将注意力集中在哪些模型产生了良好的预测，而不是那些模型的数学特性上。” 这种目的与Kaggle的目标非常相似，后者是最佳的机器学习社区，可以在各种数据集上进行激烈的竞争。 M5是在Kaggle举行的第一场M比赛。

## 运行环境
确保操作系统已安装以下软件
- python 3.7
- jupyter notebook
- [LightGBM](https://lightgbm.readthedocs.io/en/latest/index.html)机器学习算法


## 库
- pandas, numpy——python 数据处理基本库
- seaborn, matplotlib.pyplot——python 可视化库
- import sys
- from  datetime import datetime, timedelta
- import lightgbm as lgb
- from sklearn.metrics import mean_squared_error
- from scipy.sparse import csr_matrix
- import gc


## 维护者
[@Zhu-Haikun](https://github.com/Zhu-Haikun)
