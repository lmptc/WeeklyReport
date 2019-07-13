# Ming - Week of 07/12/2019

## 1. Papers and code

### 1.1 Papers Read

[A Cadence to Reduce Aliasing in LSST](https://docushare.lsstcorp.org/docushare/dsweb/Get/Document-30582/bell_antialiasing_wfd.pdf): 
Different from traditional continuous observations, the intermittent observation of an object by LSST can lead to alias, 
the spurious periods caused by the observation. The paper suggests that random spacing should be introduced within observations, 
which will not affect the purposes of most investigations. An existing MAF can be used to measure the strenth of aliases of 
the observations, but it needs modifications to be more comprehensive.

### 1.2 Code Written

[No. of Visits with Conditions.ipynb](https://github.com/lmptc/MAF/blob/master/No.%20of%20Visits%20with%20Conditions.ipynb): 
Count the number of visits that satisfy certain conditions. 

## 2. Figures

![](https://github.com/lmptc/WeeklyReport/blob/master/Images/0712_1.png?raw=true)

Figure 1 : The number of visit when airmass is larger than 1.1 and fiveSigmaDepth is larger than 23.


![](https://github.com/lmptc/WeeklyReport/blob/master/Images/0712_2.png?raw=true)

Figure 2 : The situation when the point of deep drilling in the figure above is removed. 


### 3 Results (required)

Writed the first metric that realizes a simple function. Read the codes for metricBundle and metricBundleGroup and figured out 
the broad process of MAF.
