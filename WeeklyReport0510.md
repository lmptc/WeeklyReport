# Ming Lian - Week of 05/10/2021

## 1. At least 2 of the 3 subsections should have material

### 1.1 Papers Read


### 1.2 Code Written

https://colab.research.google.com/drive/1X8Rmwmxi71peEV6IV43KlWSW2_AlDWZ9?usp=sharing: 

Interpolate the data with designated event names, bands, and the ranges of files and objects. Save the resutls as a serialized file. 


### 1.3 Other (algorithm, discussion with experts, went to conference)
https://docs.python-guide.org/scenarios/serialization/
https://docs.python.org/3/library/pickle.html#pickle-protocols

Introducing data serialization and the use of the pickle module.


## 2. Figures (at least 1 figure)

![](https://github.com/lmptc/WeeklyReport/blob/master/Images/Flux%20and%20Mag.png?raw=true)

Figure 1: The plots of the flux and magnitude of a SNIax object (a) and an AGN event (b). The problem of the negative flux can be avoided by using the magnitude. 

### 3 Results (required)

Made the code for interpolating the disignated data and save the results as a serialized file. Just realized that linearly interpolating the magnitude might be better 
than interpolating the flux, which also avoid the negative-flux problem. Ready to move to the high cadence data.

### 4 Planning (required)

Ready to move to the high cadence data now. Will try to get and understand the data from DESC server. 
