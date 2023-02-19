This repository contains three different classification models used to classify cough sounds. The three models are:

Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Convolutional Neural Network (CNN)
All three models take in a cough sound file in .wav format as input and predict whether the cough is indicative of COVID-19 or not. 
The models were trained on a dataset of cough sounds collected from the internet

Training Data
The dataset used to train the models can be found in the data directory linked to google drive. 
The directory contains two subdirectories: covid and non-covid. Each subdirectory contains cough sound files in .wav format.

Model Performance
The performance of each model on the test dataset is as follows:

SVM: 75% accuracy
KNN: 56% accuracy
CNN: 52% accuracy
Conclusion
Overall, the SVM model performed the best, achieving 75% accuracy on the test dataset. 

This is however on dummy data that was not tuned for the best accuracy.
The model parameters will be fine tuned to the TB cough sounds and this will guarantee better and more accurate performance.
