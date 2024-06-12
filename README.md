# Intrusion-Detection-System-

This project uses Gaussian Mixture Models (GMM) for anomaly detection and Decision Tree and K-Nearest Neighbors (KNN) for intrusion detection to improve network security.

![gif_title](https://github.com/jasserchtourou/Intrusion-Detection-System-/assets/124272855/451aaf9e-ae97-4897-bdc8-991f462b48d9)

## Anomaly Detection and Intrusion Detection System
This project combines the concepts of anomaly detection using Gaussian Mixture Models (GMM) and intrusion detection using Decision Tree and K-Nearest Neighbors (KNN) algorithms. The project aims to enhance cybersecurity measures by identifying both anomalies and potential intrusions in network traffic.


## Anomaly Detection Using Gaussian Mixture Models (GMM):

### Objective: Identify anomalies in network traffic that could indicate suspicious activities.
### Methodology: Implemented GMM to model normal behavior in network data and detect deviations.
### Steps Involved:
Data preprocessing to clean and prepare the dataset.
Training the GMM on the prepared dataset.
Evaluating the model to identify anomalies based on the learned Gaussian distributions.
Applications: Can be used for fraud detection, system health monitoring, and network security.


## Intrusion Detection System Using Decision Tree and KNN:
### Objective: Detect intrusions and classify them into different types such as DoS, U2R, R2L, and Probe attacks.
### Methodology: Utilized Decision Tree and KNN algorithms to build a robust intrusion detection system.
Dataset: NSL-KDD, a refined version of the KDD Cup 99 dataset, was used for training and evaluation.
### Steps Involved:
Data preprocessing, including handling missing data and one-hot encoding of categorical variables.
Feature selection using Univariate feature selection with ANOVA to identify the most significant features.
Training Decision Tree and KNN classifiers on the NSL-KDD dataset.
Evaluating the models using metrics such as accuracy, precision, recall, and F-score.
Performance Comparison: Compared the performance of Decision Tree and KNN to determine the most effective algorithm for intrusion detection.


### Results:
Anomaly Detection Results:
     The model successfully identified anomalies with high precision and recall.
Intrusion Detection Results:
    The comparison shows that both algorithms perform well, with slight variations in their metrics.
    
### Contributing:
    Contributions are welcome! Please fork this repository and submit a pull request with your enhancements.

### License:
    This project is licensed under the MIT License - see the LICENSE file for details.


![image](https://github.com/jasserchtourou/Intrusion-Detection-System-/assets/124272855/0ae25d2a-d975-44fa-8dd6-4e443c21b2be)

