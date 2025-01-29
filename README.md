# AI-Based-Malicious-Content-Detector-Web-Application

# ThreatSense: AI-Powered Cybersecurity Solution

## Project Overview
ThreatSense is an advanced web application designed to classify and detect phishing emails and malicious URLs using **machine learning**. By leveraging **Natural Language Processing (NLP)** and the **RandomForest algorithm**, ThreatSense enhances cybersecurity measures by providing automated and accurate predictions. Unlike traditional security tools that rely heavily on databases, ThreatSense utilizes AI models trained on real-world datasets to proactively identify potential threats.

## Objectives
- Develop a **machine learning-based** phishing detection system.
- Train an AI model to classify **emails and URLs** as safe or malicious.
- Build a **user-friendly web application** for threat analysis.
- Overcome data quality challenges through effective dataset sourcing.

## Key Features
- AI-powered phishing detection using **RandomForest**
- Web application built with **Flask, HTML, and CSS**
- Trained on real-world datasets from **Kaggle and Hugging Face**
- Secure, scalable, and adaptable for enterprise cybersecurity solutions

---

## Project Implementation

### 1. **Data Collection and Preprocessing**

#### Dataset Sources:
- Kaggle: Malicious URLs dataset
- Hugging Face: Email phishing datasets

![Dataset Preview](https://github.com/0xFroggi/AI-Based-Malicious-Content-Detector-Web-Application/blob/main/images/dataset1.png)
![Dataset Preview2](https://github.com/0xFroggi/AI-Based-Malicious-Content-Detector-Web-Application/blob/main/images/dataset2.png)

Challenges:
- Access to high-quality phishing data was limited.
- **Solution:** We sourced structured and balanced datasets from open-source platforms.
- URL preprocessing required extensive cleaning and normalization.

### 2. **Machine Learning Model Development**
- **Algorithm Choice:** RandomForest for classification and regression.
- **Why RandomForest?**
  - Reduces overfitting by using multiple decision trees.
  - Handles high-dimensional cybersecurity data effectively.

![Jupyter Notebook Training](https://github.com/0xFroggi/AI-Based-Malicious-Content-Detector-Web-Application/blob/main/images/2.1.png)
![Jupyter Notebook Training2](https://github.com/0xFroggi/AI-Based-Malicious-Content-Detector-Web-Application/blob/main/images/3.1.png)

- **Steps:**
  1. Data loaded into **Pandas DataFrame**.
  2. Text preprocessing applied (lowercasing, tokenization, and vectorization).
  3. Dataset split into **80% training / 20% testing**.
  4. Model trained and accuracy evaluated.

![Training Accuracy](https://github.com/0xFroggi/AI-Based-Malicious-Content-Detector-Web-Application/blob/main/images/2.2.png)
![Training Accuracy2](https://github.com/0xFroggi/AI-Based-Malicious-Content-Detector-Web-Application/blob/main/images/3.2.png)

### 3. **Technical Implementation**

#### Environment Setup
- **Virtual Environment:** Managed via **Anaconda**.
- **Programming Language:** Python (Flask, Pandas, Scikit-learn).
- **Deployment Tools:**
  - Jupyter Notebook for model training.
  - Flask for web application development.

![Project Directory](https://github.com/0xFroggi/AI-Based-Malicious-Content-Detector-Web-Application/blob/main/images/files.png)

#### Model Deployment
- Web app developed using **Flask, HTML, and CSS**.
- Users can input **URLs or email text** for classification.
- AI model returns a result: **Safe or Malicious**.

### 4. **Website Development**
- Frontend designed with **HTML & CSS**.
- Routes for user input and result display created using Flask.
- Implements **whitelisting for known safe websites** to improve accuracy.

![Flask Backend Code](https://github.com/0xFroggi/AI-Based-Malicious-Content-Detector-Web-Application/blob/main/images/1.1.png)
![Flask Backend Code2](https://github.com/0xFroggi/AI-Based-Malicious-Content-Detector-Web-Application/blob/main/images/1.2.png)

---

## Challenges and Solutions

### Challenge 1: Limited Computing Resources for Model Training
**Possible Solution:** Utilizing **cloud-based platforms like AWS SageMaker** for scalability.

### Challenge 2: Dataset Availability
**Possible Solution:** Gathering data from multiple sources such as **Kaggle, Hugging Face**, and preprocessing them manually.

### Challenge 3: Hosting and Scalability
**Possible Solution:** Future plans to deploy on **AWS/GCP** for real-world application.

---

## Conclusion
ThreatSense presents a **novel approach** to phishing detection by leveraging AI. Unlike traditional URL analyzers (e.g., VirusTotal), which rely on static databases, ThreatSense predicts **new and evolving threats** using **machine learning**. Future improvements include **cloud deployment, real-time data collection, and model enhancement with deep learning techniques**.

![ThreatSense Detection](https://github.com/0xFroggi/AI-Based-Malicious-Content-Detector-Web-Application/blob/main/images/phishing_email.png)
![ThreatSense Detection2](https://github.com/0xFroggi/AI-Based-Malicious-Content-Detector-Web-Application/blob/main/images/phishing_url.png)

---

## References
- Kaggle: Malicious URLs dataset
- Hugging Face: Email phishing dataset
- Python Libraries: Sklearn, Pandas, Flask

---


