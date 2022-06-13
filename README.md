# Algorithmic_Trading_Bot

An algorithmic trading strategy is combined with machine learning (ML) methods to develop a trading both.

Results from some of the tunning carried out is presented later.

The settings in the current notebook represent fairly good model parameters but are non-exhaustive.

## Algorthm and ML tuning results

### Algorithm (SMA long windows)

- 4_85 window ![](https://github.com/Femi-0/Algorithmic_Trading_Bot/blob/main/Resources/4_85_window.png)

- 4_90 window ![](https://github.com/Femi-0/Algorithmic_Trading_Bot/blob/main/Resources/4_90_window.png)

- 4_95 window ![](https://github.com/Femi-0/Algorithmic_Trading_Bot/blob/main/Resources/4_95_window.png)

- 4_100 window ![](https://github.com/Femi-0/Algorithmic_Trading_Bot/blob/main/Resources/4_100_window.png)


### ML (Training dataset)

- 2 months 
![](https://github.com/Femi-0/Algorithmic_Trading_Bot/blob/main/Resources/2_months.png)

- 3 months 
![](https://github.com/Femi-0/Algorithmic_Trading_Bot/blob/main/Resources/3_months.png)

- 5 months 
![](https://github.com/Femi-0/Algorithmic_Trading_Bot/blob/main/Resources/5_months.png)

- 6 months 
![](https://github.com/Femi-0/Algorithmic_Trading_Bot/blob/main/Resources/6_months.png)

## Conclusion 

At the quater-hour scale, the SMA strategy with a short and long window of 4 and 95 respectively, gives a good performance when trained with 3 months worth of data. The was little difference when the alternate ML method, AdaBoost was deployed in contrast to a SVM.

