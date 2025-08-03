🛡️ Network Intrusion Detection System (NIDS) using IBM AutoAI

This project implements a machine learning-based Network Intrusion Detection System (NIDS) to classify network traffic and detect various types of cyber-attacks such as DoS, Probe, R2L, and U2R. It uses IBM Watson AutoAI for automated model selection, training, and deployment.

---

 🚀 Project Overview

- Goal:Detect malicious network traffic and distinguish it from normal activity.
- Platform: IBM Cloud (Lite Tier)
- Model: Random Forest Classifier (AutoAI optimized using Snap ML)
- Dataset: [Kaggle NIDS Dataset](https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection)


---

🧠 Technologies Used

- IBM Watson Studio
- IBM AutoAI
- IBM Cloud Object Storage
- IBM Watson Machine Learning
- Python (for optional post-deployment API testing)

---

📂 Dataset Description

- Source: Kaggle
- Files:
  - `Train_data.csv` – Used for training in AutoAI
  - `Test_data.csv` – Used for batch or API testing
- Target column:** `class` ( `anomaly`)

---

 ⚙️ Workflow

1. Data Upload: to IBM Cloud Object Storage
2. AutoAI Experiment: for:
   - Automated preprocessing
   - Feature selection
   - Model training & optimization
3. Model Evaluation :using accuracy, precision, recall, F1-score
4. Deployment: of the best model to IBM Watson Machine Learning
5. Testing: using batch deployment or  API with `Test_data.csv`

---

 📈 Results

- Model Selected: Random Forest Classifier
- Key Metrics:
  - High accuracy and F1-score for binary classification (normal vs anomaly)
  - Low false positive rate, making it suitable for real-world deployment

---

 🔮 Future Scope

- Class-wise detection (e.g., DoS, R2L, Probe)
- Integration with live network feeds for real-time detection
- Edge deployment for faster response
- Continuous learning with online data

---

 📚 References

- IBM Watson Studio Documentation: https://www.ibm.com/cloud/watson-studio
- Kaggle Dataset: https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection
  

---

 👤 Author

Sampad Pal  
Department of Engineering and Technological Studies ,University of Kalyani  
Information Technology

---

