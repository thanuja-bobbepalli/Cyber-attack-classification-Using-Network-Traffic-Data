# Cyber-attack-classification-Using-Network-Traffic-Data


## Project Overview  
This project focuses on **detecting and classifying cyberattacks** using **network traffic data**. We utilize **ML  models** to analyze network packets and identify malicious activity. The dataset used is **NSL-KDD**, a widely used benchmark for intrusion detection systems (IDS).  

##  Dataset: NSL-KDD  
We use the **NSL-KDD dataset**, which consists of normal and attack traffic data with 41 extracted features. The dataset is preprocessed and converted into a structured format for training and evaluation. 
**Dataset Link:** [NSL-KDD Dataset]((https://www.kaggle.com/datasets/hassan06/nslkdd)) 

-  **Training Data:** `KDDTrain+.txt`  
  
-  **Classes:** Normal Traffic (`0`), Attack Traffic (`1`)  

##  Model Implementations  
The project compares various **Machine Learning (ML) models** to evaluate their performance.  

###  **Implemented Models**  
### ** Machine Learning Models**  
 **Logistic Regression**  
**Decision Tree Classifier**  
**Random Forest Classifier**  
**K-Nearest Neighbors (KNN)**  
**Support Vector Machine (SVM)**  
 

## Evaluation Metrics  
To assess model performance, we use:  
**Accuracy**  
**Precision**  
**Recall (Sensitivity)**  
**F1-Score**  
**Confusion Matrix**  
**ROC-AUC Curve**  

## Conclusion 
In this project, I conducted a comparative study using six different machine learning models for cyberattack classification on network traffic data. By leveraging the NSL-KDD dataset, I evaluated model performance based on key metrics such as accuracy, precision, recall, F1-score, and ROC curves.

My analysis provided insights into the strengths and weaknesses of different ML approaches in detecting cyber threats. While traditional models like Logistic Regression and Decision Trees offered interpretability, ensemble methods such as Random Forest and Voting Classifier demonstrated improved classification performance. The results showed that machine learning can effectively identify cyberattacks, but challenges like imbalanced data and false positives remain.

Future improvements could involve integrating deep learning models for sequential pattern analysis, feature selection techniques for improved generalization, and real-time intrusion detection adaptations.

