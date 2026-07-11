# Network Intrusion Detection using IBM watsonx.ai AutoAI

## Introduction

As cyber threats continue to evolve, organizations require intelligent systems capable of identifying malicious network activities before they compromise critical resources. Network Intrusion Detection Systems (NIDS) play a vital role in monitoring network traffic and detecting suspicious behavior in real time.

This project demonstrates the development of a Machine Learning-based Network Intrusion Detection System using IBM watsonx.ai AutoAI on IBM Cloud. By leveraging Automated Machine Learning (AutoAI), the solution simplifies the complete model development process while delivering accurate classification of network traffic.

---

## Problem Statement

**Problem Statement No. 40 – Network Intrusion Detection**

Design and implement a Machine Learning solution capable of analyzing network traffic and distinguishing legitimate communication from malicious activities. The objective is to provide an automated intrusion detection mechanism that strengthens network security through early threat identification.

---

## Solution Overview

The solution utilizes IBM watsonx.ai AutoAI to automate the Machine Learning workflow. After importing the network intrusion dataset, AutoAI performs data preprocessing, feature engineering, algorithm selection, model training, hyperparameter optimization, and comparative evaluation of multiple pipelines.

The highest-performing pipeline is selected automatically, deployed on IBM Cloud, and tested using unseen network traffic records. The deployed model predicts whether an incoming connection represents **Normal** traffic or an **Anomaly**, enabling efficient intrusion detection with minimal manual effort.

---

## Technology Stack

- IBM Cloud 
- IBM watsonx.ai AutoAI
- Machine Learning
- Python
- GitHub

---

## Dataset

The project uses the **Network Intrusion Detection** dataset obtained from Kaggle. The dataset contains network connection records with multiple traffic features describing communication behavior. These attributes enable the model to learn network patterns and classify incoming traffic into appropriate categories.

**Dataset Source:**  
https://www.kaggle.com/datasets/sampadab17/networkintrusion-detection 

---

## Development Process

- Imported the dataset into IBM watsonx.ai AutoAI.
- Configured the prediction target.
- Generated multiple Machine Learning pipelines automatically.
- Evaluated pipeline performance using AutoAI.
- Selected the best-performing model.
- Deployed the trained model on IBM Cloud.
- Validated predictions using sample network traffic records.

---

## Key Highlights

- Automated data preprocessing
- Automatic feature engineering
- Multiple model generation and evaluation
- Hyperparameter optimization
- Cloud-based model deployment
- Online prediction testing
- Binary classification of network traffic

---

## Repository Contents

| File | Description |
|------|-------------|
| Data.csv | Training dataset used for model development |
| ProblemStatement.pdf | Official project problem statement |
| ProjectPresentation.pptx | Final project presentation |
| PipelineNotebook.ipynb | AutoAI generated pipeline notebook |
| README.md | Project documentation |

---

## Outcome

The developed model successfully performs binary classification of network traffic by identifying **Normal** and **Anomaly** connections. The complete workflow—from dataset preparation to cloud deployment and prediction testing—was implemented using IBM watsonx.ai AutoAI, demonstrating an efficient approach for developing intelligent cybersecurity solutions.

---

## Future Enhancements

- Support multi-class attack categorization (DoS, Probe, R2L, U2R)
- Integration with live network monitoring systems
- Continuous model retraining using updated datasets
- Real-time alert generation for detected intrusions
- Enterprise-scale deployment for organizational networks

---

## Author

Anuj Shinde
