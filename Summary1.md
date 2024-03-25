**An integrated nomogram combining deep learning, Prostate Imaging–Reporting and Data System (PI-RADS) scoring, and clinical variables for identification of clinically significant prostate cancer on biparametric MRI: a retrospective multicentre study**
<br>
Hiremath, Amogh et al.
<br>
The Lancet Digital Health, Volume 3, Issue 7, e445 - e454
--
This study aims to develop a more accurate model to improve detection and severity of prostate cancer, using three main elements:

- Deep Learning Imaging Predictions
    - These image predictors were trained with multiple input configs with various scales, adding info from the peritumoural region
- PI-RADS Scoring
    - **Prostate Imaging–Reporting and Data System**
    - Scoring system used to intepret MRI scans, 1-5 how likely it is that an area has clinically significant cancer.
- Clinical Variables
    - PSA levels, prostate volume, and lesion volume

**Nomogram**: Prognostic tools used to understand risk of disease and predict outcome of treatment

The authors used multivariable logistic regression to combine these three tools into a single nomogram called ClaD


Pati, S., Baid, U., Edwards, B. et al. Federated learning enables big data for rare cancer boundary detection. Nat Commun 13, 7346 (2022). https://doi.org/10.1038/s41467-022-33407-5
--
**Federated Learning** - Decentralized way of training machine learning models where the model can be trained on the local device, improving patient privacy. (Performance is not sacrificed)

This is one of the largest FL studies, where the authors perform boundry detection for glioblastoma, an agressive form of brain cancer. 

The accuracy of the FL model demonstrates how hospitals and healthcare facilities can improve treatment of certain cancers without sacrificing patient privacy.

**Some key points from the study:**
- Amount of data doesn't necessarily mean a more accurate model. The effectiveness of more data flattens out, and the quantity doesn't matter if the model is dealing with low quality data. 
- Benefits of FL are "more pronounced" for more challenging regions of the tumor
- Several variables in deciding model to use: cost, some models may be more effective for certain compartments
    - ET: Enhancing Tumor, TC: Tumor Core, WT: Whole Tumor
