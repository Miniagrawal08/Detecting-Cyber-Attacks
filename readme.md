#  Detecting and Preventing Cyber Attacks Using Machine Learning

## Project Overview

Cybersecurity threats are increasing rapidly across modern digital infrastructures, making accurate and real-time attack detection a critical requirement. This project leverages Machine Learning techniques to identify malicious network activities and distinguish cyber attacks from normal network traffic.

Using the **UNSW-NB15 Cybersecurity Dataset**, this project performs comprehensive data analysis, feature engineering, visualization, and predictive modeling to build an intelligent intrusion detection system capable of identifying network attacks with high accuracy.

The project demonstrates how data science and machine learning can be applied to strengthen cybersecurity defenses, improve threat detection capabilities, and support proactive incident response strategies.

---

##  Objectives

* Analyze network traffic data to identify suspicious activities.
* Explore attack patterns through data visualization.
* Build and compare multiple machine learning models.
* Detect malicious traffic and classify cyber attacks.
* Improve cybersecurity monitoring through predictive analytics.
* Evaluate model performance using industry-standard metrics.

---

##  Dataset Information

**Dataset:** UNSW-NB15 Network Intrusion Dataset

The UNSW-NB15 dataset contains modern network traffic records including both legitimate and malicious activities.

### Dataset Characteristics

* **Total Records:** 82,332+
* **Features:** 45 network traffic attributes
* **Target Variable:** `label`

  * 0 = Normal Traffic
  * 1 = Attack Traffic
* **Attack Categories:** Multiple attack types including:

  * Fuzzers
  * Analysis
  * Backdoors
  * Denial of Service (DoS)
  * Exploits
  * Generic Attacks
  * Reconnaissance
  * Shellcode
  * Worms
  * Normal Traffic

---

##  Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Imbalanced-Learn (SMOTE)

### Machine Learning Algorithms

* Logistic Regression
* Random Forest Classifier
* Support Vector Machine (SVM)

### Development Environment

* Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

The project includes detailed exploratory data analysis to understand network behavior and attack distributions.

### Key Analyses Performed

✔ Data Inspection

✔ Missing Value Analysis

✔ Statistical Summary

✔ Feature Type Analysis

✔ Class Distribution Analysis

✔ Attack Category Distribution

✔ Protocol Distribution

✔ Duration Analysis

✔ Source and Destination Byte Analysis

✔ Network Traffic Pattern Visualization

---

##  Machine Learning Workflow

### 1. Data Preprocessing

* Data Cleaning
* Handling Missing Values
* Feature Selection
* Label Encoding
* Feature Scaling
* Dataset Transformation

### 2. Data Splitting

* Training Set: 70%
* Testing Set: 30%
* Stratified Sampling for balanced evaluation

### 3. Class Imbalance Handling

The project utilizes **SMOTE (Synthetic Minority Oversampling Technique)** to address class imbalance and improve model performance.

### 4. Model Training

The following machine learning models were trained and evaluated:

#### Logistic Regression

A baseline classification model used for comparison.

#### Random Forest Classifier

An ensemble learning model capable of capturing complex attack patterns.

#### Support Vector Machine (SVM)

A robust classification algorithm effective for high-dimensional cybersecurity data.

### 5. Hyperparameter Optimization

Grid Search Cross Validation was applied to optimize Random Forest parameters including:

* Number of Trees (`n_estimators`)
* Maximum Tree Depth (`max_depth`)

This resulted in an improved and optimized detection model.

---

##  Model Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report
* ROC Curve Analysis
* AUC Score

These metrics provide a comprehensive assessment of cyber attack detection performance.

---

##  Visualizations Included

The project provides several visual insights, including:

* Class Distribution Charts
* Attack Category Distribution
* Protocol Usage Analysis
* Duration Distribution
* Source Bytes Distribution
* Confusion Matrices
* Model Performance Comparison
* ROC Curves

These visualizations help identify attack trends and improve interpretability of machine learning results.

---



##  Key Insights

* Network attack traffic represents a significant portion of the dataset.
* Certain protocols are more frequently associated with malicious behavior.
* Ensemble learning methods such as Random Forest demonstrate strong performance in intrusion detection.
* Proper preprocessing and balancing techniques improve classification accuracy.
* Machine learning can significantly enhance proactive cybersecurity monitoring.

---

##  Business Value

This project demonstrates how machine learning can support cybersecurity operations by:

* Detecting threats in real time
* Reducing manual monitoring effort
* Improving incident response efficiency
* Enhancing network security posture
* Supporting Security Operations Centers (SOC)
* Minimizing risks associated with cyber attacks

---

##  Future Enhancements

* Deep Learning-Based Intrusion Detection
* Real-Time Threat Monitoring Dashboard
* Stream Processing with Apache Kafka
* Explainable AI (XAI) for Attack Detection
* Multi-Class Attack Classification
* Integration with SIEM Platforms
* Cloud-Based Cybersecurity Analytics

---



Aspiring Data Analyst | Machine Learning Practitioner

### Connect with Me

* LinkedIn: https://www.linkedin.com/in/mini-agrawall
* GitHub: https://github.com/Miniagrawal08

---

##  Repository Highlights

✔ End-to-End Cybersecurity Analytics Project

✔ Real-World UNSW-NB15 Dataset

✔ Advanced Data Visualization

✔ Machine Learning-Based Intrusion Detection

✔ Model Comparison and Optimization

✔ Cyber Threat Detection Framework

If you found this project useful, consider giving the repository a ⭐ and sharing your feedback.
