# Credit_Risk_Analysis

## Overview 

The purpose of this weeks project is to use machine learning in order to help predict information pertaining to credit card usage, and whether or not a transaction will be fradulent or not. The data we will be using for this assignment is a csv that comes from Lending Club, a lending service company, that pertains to credit card transactions in the first quarter of 2019. This data set is heavily biased towards non fradulent charges, so we must resample the data first using a machine learning algorithm. We will try random sampling, under sampling, over sampling, combination sampling, random forrest and Easy ensemble to change our data. After this is done, we will be able to recommend the best machine learning algorithm to use for this data. 

## Results

### Random Sampling - Random Over Sampler

##### Balanced Accuracy Score

![random_acc_score](https://user-images.githubusercontent.com/87949792/153953246-7aa55fb9-5ba1-4b10-9368-dd83f35af235.png)

- The  balanced accuracy score is 64%

#### Imbalanced Classification Report

![random_class_report](https://user-images.githubusercontent.com/87949792/153953682-e97317d4-8a63-4209-8382-55f188be5db3.png)

- The "High Risk precision Rate was 1%, and the recall 69%
- The "Low Risk" precision rate was %100 and the recall 59%

### Random Sampling - Under Sampling - Cluster Centroids Model

#### Balanced Accuracy Score

![Un_Acc_score](https://user-images.githubusercontent.com/87949792/153955309-1f80b320-da52-4165-8629-b22952c44141.png)

- The balanced Accuracy score was 54%

#### Imbalanced Classification Report

![Un_Class_report](https://user-images.githubusercontent.com/87949792/153955445-3ce7288e-b598-4cc9-a532-3298003d6c70.png)

- The "High Risk precision Rate was 1%, and the recall 69%
- The "Low Risk" precision rate was %100 and the recall 40%

### Over Sampling - SMOTE 

#### Balanced Accuracy Score

![Smote_acc_score](https://user-images.githubusercontent.com/87949792/153954328-f1baaa20-7939-4801-ac4c-0650257f8264.png)

- The Balanced Accuracy Score was 66%

#### Imbalanced Classification Report 

![smote_class_report](https://user-images.githubusercontent.com/87949792/153954594-bd4afbed-2273-4303-9f4e-2a076b312821.png)

- The "High Risk precision Rate was 1%, and the recall 63%
- The "Low Risk" precision rate was %100 and the recall 69%

### Combinatation Sampling - SMOTEEN

#### Balanced Accuracy Score

![smoteen_acc_score](https://user-images.githubusercontent.com/87949792/153954772-42f942fb-69b1-443c-999f-a3ad5d6ac294.png)

- The balanced accuracy score was 64%

![smoteen_class_report](https://user-images.githubusercontent.com/87949792/153954923-b576fff5-5070-4cdf-9eb8-6229aa76a2c2.png)

- The "High Risk precision Rate was 1%, and the recall 72%
- The "Low Risk" precision rate was %100 and the recall 57%

### Balanced RandomForest Classifier Model

#### Balanced Accuracy Score

![rf_acc_score](https://user-images.githubusercontent.com/87949792/153955606-0e1fda6b-2b91-4037-a235-07a376bbbc99.png)

- The balanced accuracy score was 78%.

### Imbalanced Classification Report 

![rf_class_report](https://user-images.githubusercontent.com/87949792/153955736-e6195b7f-c44d-4007-bf22-c60fa7721d30.png)

- The "High Risk precision Rate was 3%, and the recall 68%
- The "Low Risk" precision rate was %100 and the recall 88%

### Easy Ensemble Classifier Model

#### Balanced Accuracy Model

![easy_acc_score](https://user-images.githubusercontent.com/87949792/153955959-5c07559b-4904-49fc-99fa-c452e18b46eb.png)

- The balanced accuracy score was 92%

#### Imbalanced Classification Report

![easy_class_report](https://user-images.githubusercontent.com/87949792/153956109-251866ad-d5a1-44b7-b8e5-9370c7090ae5.png)

- The "High Risk precision Rate was 9%, and the recall 89%
- The "Low Risk" precision rate was %100 and the recall 94%

## Conclusion

It would appear we saved the best model for last - based off of the findings, my official reccomendation would be to use the Easy Ensemble Classifier Modle, as it yeilded the highest accuracy, precision and recall.
