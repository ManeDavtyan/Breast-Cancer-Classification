# Breast-Cancer-Classification using SVM
## Introduction
Breast cancer is the most common cancer affecting women and is the most diagnosed cancer worldwide. Breast cancer is also the most common cancer in women in the United States, except for skin cancers. It is about 30% (or 1 in 3) of all new female cancers yearly.
Based on  the data, a stage-specific interpretation system was designed, and this information serves as the primary resource for guiding patients' treatment methods. Following confirmation of the disease's stage and subtype, the healthcare provider initiates chemotherapy to mitigate  the growth of cancer cells. This can be done by  modifying the expression of several genes. Text mining has helped to find biologically relevant alternative therapeutic candidates. It is also true that  drug development remains a lengthy and expensive procedure.


## Description of Data
The data has 30 main features, of which 29 are numerical, while the only categorical column is diagnosis. The diagnosis column is a target column, resulting in either M - Malignant or B - Benign, depending on the other 29 numerical column values.
Number of Instances: 569

## Main Process
The support Machine Vectores model was applied to data to classify Malignant and Benign breast cancer diagnoses. The best working 9 features were found using feature architecture, and so on, the Kernel trick of SVM was used. The Kernel Trick has increased the accuracy from 97% to 99% using the Linear Kernel transformation function on the 9 best features.
