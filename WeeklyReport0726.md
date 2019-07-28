# Ming - Week of 07/26/2019

## 1. Papers and code

### 1.1 Code Written

[No. of Visits with Conditions.ipynb](https://github.com/lmptc/MAF/blob/master/No.%20of%20Visits%20Under%20Conditions%20by%20Seasons.ipynb): 
Count the number of visits that satisfy certain conditions.

The code now can count the number of visits in different seasons with certain conditions, with arbitrary beginning and ending year. 
The code can be modified to cound the number of data that the values fall into multiple intervals. 

### 1.2 Other 

Read the MAF tutorials [Slicers.ipynb](https://github.com/LSST-nonproject/sims_maf_contrib/blob/master/tutorials/Slicers.ipynb) and
[Complex Metrics.ipynb](https://github.com/LSST-nonproject/sims_maf_contrib/blob/master/tutorials/Complex%20Metrics.ipynb), but seems
not really helpful.

## 2. Figures

![](https://github.com/lmptc/WeeklyReport/blob/master/Images/0726.png?raw=true)

Figure 1 : The number of visit by seasons for WFD in from 2022 to 2032, when airmass is larger than 1.1 and 
fiveSigmaDepth is larger than 23. The blank areas are either not covered by the investigation or the number of visit is 0. It seems
there is no obvious trend with seasons. 

### 3 Results

Improved the code of last week so that it can investgate more than one year. The metric for measureing ailiasing is on the half way.
