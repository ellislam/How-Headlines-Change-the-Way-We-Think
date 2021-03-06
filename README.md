# How Headlines Change the Way We Think

## Introduction
Headlines are vital in both capturing readers’ attention and
in influencing their online reading experience of news. In
fact, approximately six in ten people limit their reading to
headlines only, without clicking on a link to the full article. Furthermore, there are many online
spaces where headlines are the only visible part of the news
article, for example, news feeds and social media.

Recently online news and social media data have been widely used in the financial market. Quants and modelers believe that these unstructured and non-traditional data should shed extra light on the prediction of the market. 

Both classification and regression methods to predict the market change were applied. Finally, which method is better in terms of performance of signal-based trading was evaluated.  

## Dataset
In this project,  historical news headlines from Reddit WorldNews Channel will be applied. All headlines are ranked by reddit users' votes, and only the top 25 headlines are considered for a single date. (**Range: 2008-06-08 to 2016-07-01**)

For stock data,  Dow Jones Industrial Average (DJIA) is used to "prove the concept". (**Range: 2008-08-08 to 2016-07-01**). 

## Library Used
```
import pandas as pd
import numpy as np
import seaborn as sn
import matplotlib.pyplot as plt
%matplotlib inline
import statsmodels.api as smf
from scipy.stats import chi2_contingency
from textblob import TextBlob
from sklearn.ensemble import RandomForestRegressor
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import roc_curve, auc, roc_auc_score
```

## Technologies
This project is created with:
* Jupyter Notebook 6.0.3
