# ABIDE_ML
SOCR Machine Learning methods and tools using the ABIDE Dataset

# Project Description
---

Multi-source, heterogeneous and multifaceted data for 11,000 participants were acquired for a large scale study. Imaging, genetics, clinical assessments and demographic information was recorded at multiple times. The data was preprocessed, derived neuroimaging morphometry measures were computed, and a single computable data object was created by harmonizing and aggregating all the available information. The final sample size was reduced to 9,914, as some cases were removed due to preprocessing errors, extreme missingness, or inconsistencies.

**The goal of the study was to examine thousands of data elements (3,300), predict specific clinical outcomes, determine the most salient features associated with computable clinical phenotypes, and interpret the joint data holistically, in a lower dimensional space**

## Feature Extraction

Description: For each participant with a structural MRI brain scan, we derived a set of [3,000 neuroimaging biomarkerss](https://surfer.nmr.mgh.harvard.edu/fswiki/FsTutorial/AnatomicalROI). These represent a quantitative signature vector of the 3D stereotactic brain anatomy. Additionally, each participant had [clinical assessment, demographic, and phenotypic data,](http://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1001779) which was harmonized and integrated with the derived neuroimaging biomarkers.

Data after feature extraction: 

Number of Observations: 9,914  
Number of features: 3,297  

Details on different machine learning methods and tensorboard that are explored on the data set can be found [here](http://socr.umich.edu/HTML5/SOCR_TensorBoard_UKBB/)

This reporsitory contains,

| File | Description |Link|
| --- | --- |---|
| ABIDE_Article_code.ipynb | Notebook with complete code and theory discussed in [Autoencoder article](http://socr.umich.edu/HTML5/ABIDE_Autoencoder/) | [Link](https://github.com/SOCR/ABIDE_ML/blob/master/ABIDE_Article_code%20.ipynb) |
| ABIDE_Data_preprocessing  | Folder contains information about ABIDE dataset, preprocessing code for autoencoder | [Link](https://github.com/SOCR/ABIDE_ML/tree/master/ABIDE_Data_preprocessing)
| Readme for try it on your own.ipynb | Contains code to setup google collaboratory and clone ABIDE_Data_preprocessing to google drive| [Link](https://github.com/SOCR/ABIDE_ML/blob/master/ABIDE_Data_preprocessing/Readme%20for%20try%20it%20on%20your%20own.ipynb)|
| ABIDE_Data_preprocessing.ipynb | Starter code. Contains detailed ABIDE data preprocessing to train Autoencoders | [Link](https://github.com/SOCR/ABIDE_ML/blob/master/ABIDE_Data_preprocessing/Readme%20for%20try%20it%20on%20your%20own.ipynb)|
