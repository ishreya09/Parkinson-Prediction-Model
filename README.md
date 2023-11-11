# Parkinson-Prediction-Model

This project focuses on a classification model.
We have applied different Machine Learning models 
to predict the presence of Parkinson’s disease in a patient.

# Parkinson’s disease

Parkinson’s disease is a progressive disorder that affects the nervous system and the parts of the body controlled by the nerves. Symptoms start slowly. The first symptom may be a barely noticeable tremor in just one hand. Tremors are common, but the disorder may also cause stiffness or slowing of movement. Although Parkinson’s disease can’t be cured, medications might significantly improve your symptoms. Occasionally, your health care provider may suggest surgery to regulate certain regions of your brain and improve your symptoms.

# Dataset
The dataset is available at Kaggle

https://www.kaggle.com/datasets/gargmanas/parkinsonsdataset

# Dataset Description
The dataset consists of 24 columns and 195 records.
The dataset contains 23 attributes and 1 target variable.


# Citation for the dataset
Citation:
'Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection',
Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM.
BioMedical Engineering OnLine 2007, 6:23 (26 June 2007)

# Attribute Information
1. name - ASCII subject name and recording number
2. MDVP:Fo(Hz) - Average vocal fundamental frequency
3. MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
4. MDVP:Flo(Hz) - Minimum vocal fundamental frequency
5. MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP - Several measures of variation in fundamental frequency
6. MDVP:Shimmer, MDVP:Shimmer(dB), Shimmer:APQ3, Shimmer:APQ5, MDVP:APQ, Shimmer:DDA - Several measures of variation in amplitude
7. NHR, HNR - Two measures of ratio of noise to tonal components in the voice
8. status - Health status of the subject (one) - Parkinson's, (zero) - healthy
9. RPDE, D2 - Two nonlinear dynamical complexity measures
10. DFA - Signal fractal scaling exponent
11. spread1, spread2, PPE - Three nonlinear measures of fundamental frequency variation
12. Tonnetz - The set of pitch classes used to characterize each note

# Target Variable
status - Health status of the subject (one) - Parkinson's, (zero) - healthy

# Models Used
1. Logistic Regression
2. Decision Tree
3. Pruned Decision Tree
4. Random Forest
5. Xgboost Classifier
6. Support Vector Machine
7. KNN
8. ANN

# Data Preprocessing methods used

1. Data Cleaning
2. Handling Missing Values
3. Feature Selection (Removing highly correlated data)
4. Feature Scaling
5. Feature Dimentionality Reduction (PCA)
6. SMOTE

# Model Evaluation Metrics

1. Accuracy
2. Confusion Matrix
3. Precision
4. Recall
5. F1 Score

# Conclusion

For our best performing artificial neural network (ANN) model, we employed a meticulous approach to enhance both 
feature quality and data balance, leading to superior predictive performance. The key steps involved in craŌing this 
robust model are detailed below: 
1.  Feature Selection: 
We prioritized the quality of input features by conducting feature selection, specifically removing 
highly correlated data. This process ensures that the model focuses on the most informative aspects 
of the dataset, contributing to improved generalization. 
2.  Data Standardization: 
To facilitate consistent and meaningful comparisons between features, we applied data 
standardization. This step ensures that all features are on a similar scale, preventing any single 
feature from dominating the learning process. Standardization contributes to a stable and efficient 
training process. 
3.  SMOTE Oversampling: 
Addressing class imbalance is crucial for training a model that is sensitive to all classes. We leveraged 
the Synthetic Minority Over-sampling Technique (SMOTE) to balance the class distribution. This 
approach involves generating synthetic samples of the minority class, creating a more representative 
dataset and preventing the model from being biased towards the majority class. 
4.  Model Training Configuration: 
For training the ANN, we chose Binary Cross Entropy as the loss function. This loss function is 
suitable for binary classification tasks, aligning with the nature of our problem. 
We employed the Adam optimizer, a widely used optimization algorithm known for its efficiency and 
effectiveness in optimizing neural networks. 
5.  Evaluation Metric: 
To measure the model's overall performance, we utilized accuracy as the evaluation metric. Accuracy 
provides a comprehensive view of the model's ability to correctly classify instances, making it a 
meaningful metric for our binary classification task. 

This meticulous combination of feature selection, data standardization, SMOTE oversampling, and thoughƞul model 
training parameters resulted in an ANN that excels in both training and generalization. The model demonstrates 
robustness, effectively addressing challenges such as class imbalance and high feature correlation. Its performance is 
summarized using accuracy, a metric that aligns with our goal of achieving accurate and balanced predictions. 
This approach not only enhances the model's predictive power but also ensures its reliability in real-world scenarios 
where class imbalances and correlated features are common challenges. 