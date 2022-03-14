# Women-hackthon-analytics-vidhya

## CHURN PREDICTION- nancy pandey

Question is to predict whether the customer will churn or not in coming 6 months. We explored data and did basic function to it.

I observed that dataset is imbalanced. So we are going to take approach for imbalanced classification. Dataset is small so we will go for oversampling method (**SMOTE**).We will also try SMOTEENN which will this method combines the SMOTE ability to generate synthetic examples for minority class and ENN ability to delete some observations from both classes that are identified as having different class between the observation’s class and its K-nearest neighbor majority class. Oversample using Adaptive Synthetic (ADASYN) algorithm. This method is similar to SMOTE but it generates different number of samples depending on an estimate of the local distribution of the class to be oversampled.

Before procededing with model I checked for outlier and converted all of them into numerical values. 
We will try different models and first get glimpse of it using **LazyPredict** . 
After finding optimal models, I used voting classifier to do prediction. 
