<h1 align="center">
    <p>Prediction for distant metastasis in follicular thyroid carcinoma:
        A radiomics study based on thyroid ultrasound</p>
</h1>

### key words : thyroid, svm, machine learning, lasso


### Objectives
This experiment aimed to evaluate whether __radiomics analysis based on gray-scale ultrasound (US) can predict the distant metastasis in follicular thyroid cancer (FTC)__. Using radiomics features performed by matlab, the radiomics signature from thyroid ultrasound is an independent biomarker for predicting distant metastasis in FTC noninvasively.

### Tasks
We extracted a total of **60 radiomics features** derived from the first order, shape, gray-level co-occurrence matrix, and gray level size zone matrix features using US imaging. A radiomics signature was generated by using the **least absolute shrinkage and selection operator(LASSO)** and further used to **train a support vector machine (SVM) classifier in five-fold cross-validation**. Univariate and multivariate logistic regression analyses were used to determine the association of the radiomics signature, US findings, clinicopathological variables with distant metastasis. Another SVM classifier was built using significant variables from the multivariate analysis.

### Study design
<div align="center">
  <img src="./overall flow.png" width=720 alt="IMAGE ALT TEXT"></a>
</div>

#### Study Information
Kwon MR, Shin JH, Park H, Cho H, Kim E, Hahn SY. Radiomics Based on Thyroid Ultrasound Can Predict Distant Metastasis of Follicular Thyroid Carcinoma. J Clin Med. 2020 Jul 8;9(7):2156. doi: 10.3390/jcm9072156. PMID: 32650493; PMCID: PMC7408789.

### Dependencies
- matlab 2018b
- pyradiomics 3.0.1

### Code description 
 This repository is written by using by matlab code and performed the analysis of thyroid medical images.

### LICENSE
/*******************************************************

 Copyright (C) 2019-2020 Eunjin Kim, Hwanho Cho <dmswlskim970606@gmail.com, nara9313@gmail.com>
 
 This file is part of Radiomics Based on Thyroid Ultrasound Project.
 
 Radiomics Based on Thyroid Ultrasound Project can not be copied and/or distributed without the express
 permission of MRK, JHS, HJP, HHC, EJK and SYH
 
 *******************************************************/

### Acknowledge
- Pyradiomics from van Griethuysen, J. J. M., Fedorov, A., Parmar, C., Hosny, A., Aucoin, N., Narayan, V., Beets-Tan, R. G. H., Fillon-Robin, J. C., Pieper, S., Aerts, H. J. W. L. (2017). Computational Radiomics System to Decode the Radiographic Phenotype. Cancer Research, 77(21), e104–e107. `https://doi.org/10.1158/0008-5472.CAN-17-0339 <https://doi.org/10.1158/0008-5472.CAN-17-0339>`
