# DDoS Attack Traffic Analysis and Detection

### 📘 Overview
This project analyzes network traffic to detect **DDoS (Distributed Denial of Service)** attacks using machine learning.  
It’s my **AI/ML Week-2 project** under *Global Next Consulting India Pvt. Ltd.*

---

### 🎯 Objectives
- Perform data cleaning and exploratory analysis  
- Engineer time and protocol-based features  
- Detect anomalies using **Isolation Forest**  
- Classify attacks using **Random Forest**  
- Explain model behavior with **SHAP**

---

### ⚙️ Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, SHAP, UMAP

---

### 🧩 Workflow
1. Data loading & preprocessing  
2. EDA: label balance, top IPs, time-series plots  
3. Feature engineering (hour, protocol, etc.)  
4. Unsupervised anomaly detection  
5. Supervised classification & evaluation  
6. Explainability using SHAP  

---

### 📈 Results
- Accuracy: ~90–95%  
- ROC-AUC: ~0.95  
- Key indicators: total bytes, unique source IPs  

---

### 🧾 Conclusion
The model accurately detects DDoS-like traffic spikes and explains key contributing features.  
This pipeline can be extended for real-time intrusion detection.

---

**Author:** Himanshu  
*AI/ML Trainee – Week-2 Project*
