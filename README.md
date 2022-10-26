# surfs_up
Module 9
### Overview of the analysis:
#### This project is to analyze June and December temperatures for clients by transforming the data into dataframe with descriptive statisics through retreval of Hawaii sqlite table using python library SQLAlchemy. 

### Results:
#### 1. Historical data displays a total number 1700 records in June, the average of temperatures in June is 74.94 with standard deviation of 3.26.
![image](https://github.com/jilldvn/surfs_up/blob/main/Image/June_temp%20table.png)

#### 2. Historical data shows a total number of 1517 records, with its average of temperatures in December is 71.04 degree  with standard deviation of 3.75. 
![image](https://github.com/jilldvn/surfs_up/blob/main/Image/December_temp%20table.png)

### Summary: 
#### According to the descriptive statistical finding, it is found that there the difference of average temperature is 3.90 degree and both standard deviations seems to in a likelihood, however, to confirm whether the difference between June and December temperatures exists, here I provided additional statisic test results provided here: 

#### 1. Perform 2 sample T test: 
#### Null hypothesis is there is no difference between both mean temperatures in June and December. Test result (below) shows p-value is 3.9025129038616655e-191, close to 0.0 less than alpha risk, therefore null hypothesis is rejected, meaning there is a significant difference between temperature in June and December. 
![image](https://github.com/jilldvn/surfs_up/blob/main/Image/t_test%20result.png)

#### 2. Distirbutions of both June and December temperatures: 
![image](https://github.com/jilldvn/surfs_up/blob/main/Image/June.png)

![image](https://github.com/jilldvn/surfs_up/blob/main/Image/December.png)

#### As shown above, June temperature maximal value is closed to 85 degree with lowest degree of 65, comparing to temperature in December btween 55 to lower 80 degree, the overall shape of temperature in June is skewed to the right (higher temperature) than December. Both historgrams seem to be centralized and tend to be bell curves, meaning is both in June and December are less in temperature variation.
