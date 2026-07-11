# Network Intrusion Detection System

## Project Overview

Network security has become one of the most critical challenges in today's digital world. As organizations increasingly rely on interconnected systems, detecting malicious network activities before they impact critical infrastructure is essential. A Network Intrusion Detection System (NIDS) continuously monitors network traffic to identify suspicious behavior and support proactive cybersecurity.

This project presents a Machine Learning-based Network Intrusion Detection System developed using IBM watsonx.ai AutoAI and deployed on IBM Cloud using IBM Watson Machine Learning. By leveraging Automated Machine Learning (AutoAI), the solution streamlines the complete model development lifecycle, enabling efficient analysis of network traffic and accurate identification of suspicious network activity with minimal manual intervention.

---

# Problem Statement

**Problem Statement No. 40 – Network Intrusion Detection**

Develop a robust Network Intrusion Detection System (NIDS) capable of analyzing network traffic to distinguish malicious activities from legitimate communication. The objective is to strengthen communication network security by providing intelligent and automated intrusion detection.

---

# Objectives

- Develop a Machine Learning-based Network Intrusion Detection System.
- Analyze network traffic using multiple network communication features.
- Automatically generate and evaluate predictive models using IBM watsonx.ai AutoAI.
- Deploy the best-performing model on IBM Cloud.
- Detect suspicious network activity through automated prediction.
- Demonstrate an end-to-end AI deployment workflow on IBM Cloud.

---

# Solution Overview

The solution leverages IBM watsonx.ai AutoAI to automate every major stage of the Machine Learning workflow, including data preprocessing, feature engineering, model selection, hyperparameter optimization, pipeline generation, and performance evaluation.

Multiple candidate pipelines are generated and compared automatically. The highest-performing pipeline is selected and deployed using IBM Watson Machine Learning on IBM Cloud.

The deployed model analyzes network traffic records and classifies each connection as either **Normal** or **Anomaly**, providing an intelligent and automated approach for identifying potentially malicious network behavior.

---

# Technology Stack

- IBM Cloud
- IBM watsonx.ai AutoAI
- IBM Watson Machine Learning
- Python
- GitHub

---

# Dataset

The project utilizes the **Network Intrusion Detection** dataset obtained from Kaggle. The dataset contains multiple network traffic attributes that describe communication behavior between systems. These features enable the model to learn network patterns and classify network traffic as **Normal** or **Anomaly**.

**Dataset Source**

https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection

---

# Implementation Workflow

1. Imported the dataset into IBM watsonx.ai AutoAI.
2. Configured the target column for prediction.
3. Performed automated data preprocessing.
4. Applied automatic feature engineering.
5. Generated multiple Machine Learning pipelines.
6. Evaluated and compared pipeline performance.
7. Selected the highest-performing model.
8. Deployed the trained model using IBM Watson Machine Learning on IBM Cloud.
9. Tested the deployed model using sample network traffic records.
10. Verified the deployed model by testing it using sample network traffic records.

---

# Key Features

- Automated Machine Learning Workflow
- Intelligent Network Traffic Classification
- Automatic Data Preprocessing
- Feature Engineering
- Hyperparameter Optimization
- Multiple Pipeline Generation
- Model Performance Evaluation
- Cloud-Based Model Deployment

---

# Repository Structure

| File | Description |
|------|-------------|
| README.md | Complete project documentation |
| Data.csv | Dataset used for model training |
| ProblemStatement.pdf | Official IBM SkillsBuild project problem statement |
| ProjectPresentation.pptx | Final project presentation |
| PipelineNotebook.ipynb | AutoAI-generated pipeline notebook |

---

# Results

The developed Network Intrusion Detection System successfully analyzes network traffic and classifies each connection as **Normal** or **Anomaly**. The trained model was deployed on IBM Cloud using IBM Watson Machine Learning and verified by testing it using sample network traffic records.

This project demonstrates a complete end-to-end AI workflow, from dataset preparation and automated model generation to cloud deployment and prediction testing using IBM watsonx.ai AutoAI.

---

# Future Enhancements

- Extend the model to support multi-class attack classification such as DoS, Probe, R2L, and U2R.
- Integrate the solution with real-time network monitoring systems.
- Improve model performance using larger and continuously updated datasets.
- Enable automated alert generation for suspicious network activities.
- Deploy the solution for enterprise-scale cybersecurity applications.

---

# Author

**Anuj Shinde**

Electronics and Telecommunication Engineering

IBM SkillsBuild AI & Cloud Internship Project
