# Credit_Risk_Analysis
`Predicting credit risk with machine learning models that I have built and evaluated using Python.`

## Resources
- Jupyter Notebook (Python 3.7.11)
- Data - LoanStats_2019Q1.csv

## Overview of the Analysis
Due to such an influx of data regarding loans and other personal finances, there is a substantial need for machine learning in order to both analyze this data, and predict trends for optimal lending. Therefore, as an aspiring Data Analyst, I will need to be familiar and utilize these machine learning algorithms and in this project, I will use machine learning with the purpose of predicting credit risk. Credit risk is generally unbalanced, with good loans existing in much higher volumes than risky ones. As such, I will use machine learning algorithms like SMOTE, RandomOverSampler, ClusterCentroids, SMOTEEN, BalancedRandomForestClassifier and EasyEnsembleClassifier to oversample, undersample and reduce bias. After this is done, I will then evaluate the efficacy of these models and recommend whether they should be used to predict credit risk.

## Results

My results consist and can be observed through the following 4 Deliverables:

I will do so through the following 4 Deliverables:

### Deliverable 1: Use Resampling Models to Predict Credit Risk

#### RandomOverSampler Model
<img width="1040" alt="RandomOverSampler" src="https://user-images.githubusercontent.com/95828604/164144682-d875a018-9c91-422c-a5d6-1b9c59f38a56.png">

- The Balanced Accuracy Score for this Model is 65%
- The Average Precision Score for this Model is 99% (High - 1%, Low - 100%)
- The Average Recall/Sensitivity Score for this Model is 68% (High - 62%, Low - 68%)

#### SMOTE Model
<img width="1043" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/95828604/164144739-ecf2363e-4595-46d5-ae64-3946c7cd88e6.png">

- The Balanced Accuracy Score for this Model is 64%
- The Average Precision Score for this Model is 99% (High - 1%, Low - 100%)
- The Average Recall/Sensitivity Score for this Model is 66% (High - 63%, Low - 66%)

#### ClusterCentroids Model
<img width="1041" alt="ClusterCentroids" src="https://user-images.githubusercontent.com/95828604/164144808-37a26172-351f-4ecb-84fb-0917dee2ea01.png">

- The Balanced Accuracy Score for this Model is 52%
- The Average Precision Score for this Model is 99% (High - 1%, Low - 100%)
- The Average Recall/Sensitivity Score for this Model is 40% (High - 63%, Low - 40%)

### Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

#### SMOTEENN Model
<img width="1033" alt="SMOTEEN" src="https://user-images.githubusercontent.com/95828604/164144994-634aa5e0-ec0f-4be4-bb32-a43e73aa3407.png">

- The Balanced Accuracy Score for this Model is 62%
- The Average Precision Score for this Model is 99% (High - 1%, Low - 100%)
- The Average Recall/Sensitivity Score for this Model is 57% (High - 68%, Low - 57%)

### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

#### BalancedRandomForestClassifier Model
<img width="1053" alt="BalancedRandomForest" src="https://user-images.githubusercontent.com/95828604/164145151-03bcaa4f-e5f6-427f-bf2f-5dfb09a062d8.png">

- The Balanced Accuracy Score for this Model is 79%
- The Average Precision Score for this Model is 99% (High - 4%, Low - 100%)
- The Average Recall/Sensitivity Score for this Model is 91% (High - 67%, Low - 91%)

#### EasyEnsembleClassifier Model
<img width="1024" alt="EasyEnsemble" src="https://user-images.githubusercontent.com/95828604/164145316-cfced14a-43f8-4043-b453-0e6a449445fc.png">

- The Balanced Accuracy Score for this Model is 93%
- The Average Precision Score for this Model is 99% (High - 7%, Low - 100%)
- The Average Recall/Sensitivity Score for this Model is 94% (High - 91%, Low - 94%)

### Deliverable 4: A Written Report on the Credit Risk Analysis (README.md) (As seen here)

## Summary

In summation, each model that I used in my pursuit of analyzing credit risk is not useful when it comes to high risk of credit. Out of all the models, the model of most use when it comes to high credit risk would be the EasyEnsembleClassifier Mode, with a precision score of 7%/ a sensitivity score of 91%, when it comes to high tisk. However, while this model would be the best of those analyzed in the pursuit of credit risk analysis, I would not advise any business to use any of the aforementioned models. Further models are needed for the assurance of business who want to minimize risks. 
