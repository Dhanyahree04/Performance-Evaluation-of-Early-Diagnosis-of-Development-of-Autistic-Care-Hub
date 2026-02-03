# Performance Evaluation of Early ASD Diagnosis and Autism Care Hub

This repository contains the research and implementation of a data-driven framework for the early diagnosis of **Autism Spectrum Disorder (ASD)**. The project benchmarks various Machine Learning (ML) and Deep Learning (DL) architectures using **AQ-10 screening data** to identify the most accurate diagnostic models, which are then integrated into a comprehensive web platform called the **"Autism Care Hub."** 

## 📋 Project Overview

Traditional ASD diagnosis is often delayed due to costly and time-consuming subjective evaluations. This project addresses the gap by providing an objective, scalable, and automated screening solution. By evaluating multiple supervised, unsupervised, and deep learning models, the research identifies optimal algorithms for different age groups (children vs. adults) to ensure high-precision results.

## 🚀 Key Features

* 
**Comprehensive Benchmarking:** Comparison of 6 supervised ML classifiers, 5 unsupervised clustering models, and 6 deep learning architectures.


* 
**Data-Driven Feature Selection:** Utilization of Random Forest algorithms to isolate the most significant behavioral markers from AQ-10 data.


* **"Autism Care Hub" Platform:** A web-based ecosystem facilitating:
* 
**Early Screening:** Rapid processing of behavioral questionnaires.


* 
**Automated Results:** High-accuracy diagnosis powered by the best-performing models.


* 
**Resource Library:** Access to articles, guides, and educational tools for families.


* 
**Support Finder:** A "Locate Nearby Care" feature to find centers and experts.





## 🛠️ Tech Stack

* 
**Machine Learning:** SVM, Random Forest, XGBoost, KNN, Logistic Regression, Decision Trees .


* 
**Deep Learning:** Artificial Neural Networks (Dense), LSTM, Residual Networks, Dropout, and Batch Normalization layers .


* 
**Data Analysis:** Pandas, Scikit-learn, SMOTE (for class imbalance), and One-Hot Encoding.


* 
**Web Development:** HTML5, CSS3, JavaScript (Frontend).



## 📊 Dataset & Results

The models were trained on AQ-10 datasets for children (292 instances) and adults (704 instances).

| Group | Best Performing Model | Performance Highlight |
| --- | --- | --- |
| **Children** | SVM / Dense / LSTM | ~96.72% Accuracy, 100% Recall 

 |
| **Adults** | Logistic Regression / LSTM | ~89.26% Accuracy (LSTM) 

 |
| **Combined** | Dense / Dropout | >93% Accuracy, >98% ROC AUC 

 |

## 👥 Contributors

* 
**Authors:** Dhanya Shree M, Karishma Kaine T, Prithish Goutam S, Priyanka Panda 


* 
**Guide:** Dr. S. Jayanthi Sree 


* 
**Institution:** PSG Institute of Technology and Applied Research
