# 🌌 Pulsar Detection using Machine Learning

## 📘 Overview
This project applies supervised machine learning models to identify *pulsar candidates* from radio astronomy data (HTRU2 dataset).  
The models were evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

---

## 🧰 Requirements
- Python 3.8+
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- imbalanced-learn

---

## ⚙ Setup Instructions

### 1. Clone the Repository
bash
git clone https://github.com/YourUsername/pulsar-detection-ML.git
cd pulsar-detection-ML


### 2. Install Dependencies
bash
pip install -r requirements.txt


---

## 🚀 How to Run the Project

### Using Google Colab
1. Upload the Pulsar_AM223_AM218.ipynb file to *Google Colab*.  
2. Ensure the dataset path is correct or upload it directly in Colab.  
3. Run all cells sequentially.

---

## 🧠 Models Used
The following supervised learning models were implemented and compared:  
- *Logistic Regression*  
- *Random Forest Classifier*  
- *Support Vector Machine (SVM)*  

Each model was evaluated using:  
- Accuracy  
- Confusion Matrix  
- Precision, Recall, F1-score  
- ROC-AUC Curve

---

## 📊 Dataset Description
- *Source:* HTRU2 Pulsar Dataset  
- *Features:* 8 real-valued attributes describing statistical characteristics of radio signal profiles  
- *Target Variable:*  
  - 1 → Pulsar Star  
  - 0 → Non-Pulsar (Noise)

---

## 📂 Repository Structure

pulsar-detection/
├── Pulsar_AM223_AM218.ipynb     # Jupyter notebook with full code
├── README.md                    # Project overview and setup instructions
├── requirements.txt             # List of dependencies for installation
└── data/                        # (Optional) Folder for dataset(s)
    └── HTRU_2.csv          # Dataset file (if stored locally)


### Notes
- Keep all files inside the **main folder (pulsar-detection/).  
- The data/ folder is optional if you store the dataset locally.  
- Uploading this structure to GitHub keeps it organized and easy for faculty or TAs to navigate.

---

## 📈 Project Workflow
1. *Data Preprocessing* – Handling missing values, scaling, and feature selection  
2. *Exploratory Data Analysis (EDA)* – Distribution plots and correlation analysis  
3. *Model Training* – Logistic Regression, Random Forest, SVM  
4. *Hyperparameter Tuning* – Using GridSearchCV for optimal performance  
5. *Evaluation* – Generating confusion matrices, classification reports, and ROC curves

---

## 👩‍💻 Contributors
- *Rachana A (PES1UG23AM223)*  
- *Priyanka MP (PES1UG23AM218)*

---

## 🔒 Repository Access
This repository is *private* and shared only with:  
- Assigned *Faculty*  
- *Teaching Assistants (TAs)*  

To grant access:  
1. Go to *Settings → Collaborators* on GitHub  
2. Add their usernames  
3. They’ll receive an email invitation

---

## 🧾 License
This project is created for *academic purposes only* under the university’s submission guidelines.  
Unauthorized distribution or reuse is not permitted.

---

## ✅ End Result
A private GitHub repository named pulsar-detection containing:  
- Pulsar_AM223_AM218.ipynb — Google colab 
- README.md — setup, run, and documentation  
- requirements.txt — dependencies list
