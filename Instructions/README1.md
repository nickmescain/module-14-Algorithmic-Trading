# module-14-Algorithmic-Trading

### Evaluation Report

##Baseline Algo

The baseline algorithim was unsuccesful the actual returns were much higher than the strategic returns. The actual returns went peaked as high as 1.6 in 2021 were as the strategic returns failed to exceed 1.0 in the 6 year timespan.

'![alt text](Baseline-Algo.png)'

##Tune Adjusting (Size)

In this model, I adjusted the time frame of the model from 3 months to 9 months. This model was a rollercoaster. It was extremely volatile for some time it sharply rose mid 2018 exceeding the actual returns and took a steep dip in the start of 2019 and again outperforming the actual returns in 2021. If you timed it right one could have been profitable.

'![alt text](Tune-Adj.png)'

## Tune SMA Window

In this model, I adjusted the SMA windows for both the short and long timeframe. I made the short window 30 days and the long window 352 days.This model provided showed negative returns steadily over the years.

'![alt text](sma_window.png)'

## New Machine Learning Classfier

 I used logistic regression as a machine learning classifier. It was less profitable except for early 2020 were it broke even.

 '![alt text](LR-MODEL.png)'







#Answer the following question: What impact resulted from increasing or decreasing the training window?

