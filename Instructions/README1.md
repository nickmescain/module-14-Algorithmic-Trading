# module-14-Algorithmic-Trading

### Evaluation Report

##Baseline Algo

The baseline algorithim was unsuccesful the actual returns were much higher than the strategic returns. The actual returns went peaked as high as 1.6 in 2021 were as the strategic returns failed to exceed 1.0 in the 6 year timespan.



![Baseline-Algo](https://user-images.githubusercontent.com/112914705/228449164-144b5c8b-ffb5-40ca-9f07-db617ea105ab.png)

##Tune Adjusting (Size)

In this model, I adjusted the time frame of the model from 3 months to 9 months. This model was a rollercoaster. It was extremely volatile for some time it sharply rose mid 2018 exceeding the actual returns and took a steep dip in the start of 2019 and again outperforming the actual returns in 2021. If you timed it right one could have been profitable.

![Tune-Adj](https://user-images.githubusercontent.com/112914705/228450575-5f8a8871-9988-4477-ae01-ccf6e44b7d73.png)



## Tune SMA Window

In this model, I adjusted the SMA windows for both the short and long timeframe. I made the short window 30 days and the long window 352 days.This model provided showed negative returns steadily over the years.

![sma_window](https://user-images.githubusercontent.com/112914705/228449708-7d7a783b-3c3b-410d-b012-133a28b690f2.png)
## New Machine Learning Classfier

 I used logistic regression as a machine learning classifier. It was less profitable except for early 2020 were it broke even.

 
![LR-MODEL](https://user-images.githubusercontent.com/112914705/228449884-c1fe20ba-7deb-4310-aa69-51066036d9ea.png)




