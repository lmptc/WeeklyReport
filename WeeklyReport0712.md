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





Figure 1 : Figure 1 with a caption that describes what is being plotted. Add link to code on github that created the plot.

Figure 2 : Figure 2 with a caption that describes what is being plotted. Add link to code on github that created the plot.

.
.
.
### 3 Results (required)

This section should be a discussion of what you did, how you did it, why you did it, and what you found.  For example,

_In order to explore the extent to which dimensionality reduction plus a classifier can be used to tag each spectrum with a known spectral type, I wrote pca_classify.py (link to code) which first whitened the spectra and then used scikit-learn’s PCA functionality to decompose the sample into N=20 principle components.  The first 5 are shown in Figure 1.  The figure shows that these components are dominated by only a few spectral lines.  Figure 2 shows the explained variance as a function of the number of included principle components and suggests that N=20 is insufficient.  Nevertheless, by projecting onto these components and training an SVM classifier (using grid search on the parameters Cand ; see Figure 3) with training and testing sets of size 3,500 and 1,500 respectively, I achieved an accuracy of 80% on the testing set._
