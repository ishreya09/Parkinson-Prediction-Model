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
3. Support Vector Machine

