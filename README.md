# Anomaly-Detection-in-Time-Series

1st : Anomaly Detection of ECG using AutoEncoders using Tensorflow

AutoEncoders is a neural network that learns to copy its inputs to outputs. In simple words, AutoEncoders are used to learn the compressed representation of raw data. Autoencoders are based on unsupervised machine learning that applies the backpropagation technique and sets the target values equal to the inputs
The encoder is a mapping from the input space into a lower dimensional latent space. This model predicted anomalies almost more than 98% for ECG dataset.

2nd : Anomaly Detection in Transactions using Python 

Anomaly detection in transactions means identifying unusual or unexpected patterns within transactions or related activities. These patterns, known as anomalies or outliers, deviate significantly from the expected norm and could indicate irregular or fraudulent behaviour.

Here, we perform anomaly detection in transactions using Machine Learning and Python.
So, we are training an anomaly detection model using the Isolation Forest algorithm. 

First, we selected the relevant features for detection, namely Transaction_Amount, Average_Transaction_Amount, and Frequency_of_Transactions. 
We split the dataset into features (X) and the target variable (y), where X contains the selected features and y contains the binary labels indicating whether an instance is an anomaly or not. Then, we further split the data into training and testing sets using an 80-20 split ratio. Next, we created an Isolation Forest model with a specified contamination parameter of 0.02 (indicating the expected ratio of anomalies) and a random seed for reproducibility. 
The model is then trained on the training set (X_train).
