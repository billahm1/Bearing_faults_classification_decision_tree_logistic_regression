# Contents
- Overview
- Problem Formulation
- Data Visualization
- Logistic Regression
- Decision Tress
- Summary
- References
# Overview
Induction machine is the most commonly used machines in domestic and industrial applications. When faults occur in an induction machine, it reduces the efficiency, consequently, decreases the performance of the machine. Bearing faults are the most frequent one among other faults that occur in an induction machine with a 40-45% probability. Therefore, it is essential to diagnose the bearing faults accurately. In this report, a classification problem is carried out by using two ML-based classifiers namely decision tree and logistic regression in order to predict the healthy and faulty state of the induction machine. 
# Problem Formulation 
The time-series vibration data of healthy and faulty bearings are used in this classification problem. The dataset is downloaded from [1]. The main dataset can be found in [2]. Bearing faults are implemented by making single point defects with different diameters in the inner raceway, outer raceway, and ball regions. The vibration data are collected through the accelerometer sensor with a sampling frequency of 48kHz. Therefore, the time-domain signal has time-step 2083.3ms and is recorded for in total of 9.2s. For simplicity, the healthy state data from baseline (BA) and faulty state data of ball fault with diameters of defects 0.021 inches from the drive end (DE) at 1hp load and rotating speed 1772 rpm of the machine is used to extract the features. Each time-domain signal is divided into a certain number of segments having 2048 samples (0.04s) per segment. Each segment of vibration signal is utilized to extract 7 features such as maximum value, minimum value, mean value, standard deviation, RMS value, skewness, and kurtosis to train and test the decision tree and logistic regression classifiers. The main target is to predict the faulty state of the machine which is defined by the label '0' and healthy state by the label '1'.

# Data Visualization
# Logistic Regression
# Decision Tress
# Summary
# References
For further readings:
1. https://medium.com/@ashwin8april/dimensionality-reduction-and-visualization-using-pca-principal-component-analysis-8489b46c2ae0

