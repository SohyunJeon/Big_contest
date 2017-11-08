# Big_contest 2017
<br>
### 1. Purpose for Project
To Predict Repayment Forecast
![poster](contest/blob/master/img/poster.png)

 1. 7th Aug 2017 ~ 13th Oct 2017
 2. URL : [2017빅콘테스트](http://contest.kbig.kr/)
 3. Feature of Dataset
 
| Name     | Counts |
|----------|--------|
| raw      | 100233 |
| columns  | 69     |
| features | 67     |
 
4. Target class of this dataset is very imbalanced. So, SMOTE algorithm has used for matching the ratio.

| # of data        | 100,233 |
|------------------|---------|
| # of repayment   | 95,946  |
| # of default     | 4287    |
| ratio of default | 0.04    |

      Atfer applying SMOTE

| # of data        | 191,892 |
|------------------|---------|
| # of repayment   | 95,946  |
| # of default     | 95,946  |
| ratio of default | 0.50    |


