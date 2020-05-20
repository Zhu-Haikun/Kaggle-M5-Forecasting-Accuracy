# [Kaggle-M5-Forecasting-Accuracy-Project](https://www.kaggle.com/c/m5-forecasting-accuracy/overview)


## Contents
![image](https://github.com/Zhu-Haikun/Kaggle-M5-Forecasting-Accuracy/blob/master/image/contents.png)

## Background
How much camping gear will one store sell each month in a year? To the uninitiated, calculating sales at this level may seem as difficult as predicting the weather. Both types of forecasting rely on science and historical data. While a wrong weather forecast may result in you carrying around an umbrella on a sunny day, inaccurate business forecasts could result in actual or opportunity losses. In this competition, in addition to traditional forecasting methods you’re also challenged to use machine learning to improve forecast accuracy.

The Makridakis Open Forecasting Center (MOFC) at the University of Nicosia conducts cutting-edge forecasting research and provides business forecast training. It helps companies achieve accurate predictions, estimate the levels of uncertainty, avoiding costly mistakes, and apply best forecasting practices. The MOFC is well known for its Makridakis Competitions, the first of which ran in the 1980s.

## Runtime 
Make sure the following software is installed
- python 3.7
- jupyter notebook
- [LightGBM](https://lightgbm.readthedocs.io/en/latest/index.html)


## Library
```python
# Basic
import pandas as pd
import numpy as np
import sys
# Time
from  datetime import datetime, timedelta

# View
%matplotlib inline
import matplotlib.pyplot as plt
import seaborn as sns
from itertools import cycle

# Machine learning
import lightgbm as lgb
```


## Maintainers
[@Zhu-Haikun](https://github.com/Zhu-Haikun)
