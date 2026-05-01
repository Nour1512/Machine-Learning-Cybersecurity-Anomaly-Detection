#  Machine Learning Project (Phase 1 & Phase 2)

This repository contains two separate machine learning projects developed as part of a university course. Each phase addresses a different problem and demonstrates the application of core machine learning concepts, including data preprocessing, model training, and evaluation.

---

##  Overview

This repository presents a two-phase machine learning project focused on network threat detection and classification. The project demonstrates the progression from a basic detection system to a more advanced and granular attack classification model.

In Phase 1, a binary classification model was developed to determine whether a network connection is normal or malicious, serving as a foundational intrusion detection system.

In Phase 2, the model was extended into a multiclass classification system capable of identifying specific types of cyberattacks, including DDoS, DoS, Reconnaissance, Man-in-the-Middle (MITM), and Mirai attacks.

Together, both phases showcase the application of machine learning techniques in cybersecurity, covering data preprocessing, model development, and performance evaluation across increasingly complex problem settings.

---

##  Phase 1: Problem Description

    Design a system to detect whether a network connection is safe (normal) or dangerous (anomaly) based on data collected from a military network. The data initially included only anomalies, which posed challenges due to class imbalance.

### Key Steps:

* Data cleaning and preprocessing
* Feature selection / engineering
* Model training
* Performance evaluation

---
##  Phase 2: Problem Description

In this phase, the goal was to detect not just if the connection is malicious, but also to classify the type of attack into one of the following:

    * BenignTraffic
    * DDoS
    * DoS
    * Recon
    * MITM
    * Mirai

### Key Steps:

* Dataset preparation
* Model building
* Hyperparameter tuning (if applicable)
* Evaluation and analysis

---

##  Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-learn
* Matplotlib / Seaborn

---

## 📁 Project Structure

```id="n3k2sd"
.
├── phase1.ipynb
├── phase2.ipynb
└── README.md
```

---

##  How to Run

1. Clone the repository:

```bash id="t2pl8x"
git clone https://github.com/Nour1512/Machine-Learning-Cybersecurity-Anomaly-Detection.git
cd ml-project
```

2. Install dependencies:

```bash id="7k1b0m"
pip install numpy pandas scikit-learn matplotlib seaborn
```

3. Open the notebooks:

```bash id="f6zq3r"
jupyter notebook
```

---

##  Learning Outcomes

* Applied machine learning workflows end-to-end
* Gained experience with different types of ML problems
* Practiced model evaluation and comparison
* Improved data preprocessing and feature engineering skills

---

##  Future Improvements

* Model optimization and tuning
* Deployment as a web application
* Experiment tracking (e.g., MLflow)
* Adding more datasets and problems

---
