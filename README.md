#  Medical Heart Disease Prediction

##  Overview
This project predicts the likelihood of heart disease based on clinical and lifestyle indicators.  
It includes **data preprocessing**, **model training**, and **evaluation** using two machine learning algorithms —  
**Decision Tree** and **Logistic Regression** — with performance optimization through **F2-score threshold tuning**.

The notebook follows a clean **modular structure**, making it easy to reproduce, modify, and extend.

---

##  Project Structure
medical_heart_project/
│
├── medical_heart_project.ipynb # Main modular notebook
├── README.md # Project documentation
├── requirements.txt # Dependencies
├── src/ # Core reusable functions (optional)
└── models/ # Saved models and thresholds

---

##  Features
✅ Modular notebook organization (separate sections for config, preprocessing, training, evaluation)  
✅ Data scaling using StandardScaler  
✅ Missing values handled via median/mode imputation  
✅ Class balancing using weights  
✅ Optimized F2-score threshold selection  
✅ Evaluation metrics: Confusion Matrix, ROC-AUC, F2-score  

---

##  Metrics
| Metric | Decision Tree | Logistic Regression |
|:-------|:---------------|:--------------------|
| F2-score | Tuned threshold | Tuned threshold |
| ROC-AUC | ~0.85–0.90 | ~0.88–0.92 |

*(Exact values may vary depending on dataset and parameters.)*

---

##  Technologies Used
- Python 3.10+  
- scikit-learn  
- pandas  
- numpy  
- joblib  
- matplotlib  

---

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/AktanDikanbaev/medical_heart_project.git
   cd medical_heart_project

---

##  Dataset

The dataset used in this project comes from the **Tech Weekend Data Science Hackathon** on **Kaggle**:  
[Kaggle Competition](https://www.kaggle.com/competitions/tech-weekend-data-science-hackathon/overview)

- Format: CSV  
- Description: Patient medical data for predicting heart disease  
- License: Free for educational purposes  

Alternatively, the dataset archive can be downloaded from Dropbox:  
[Dropbox link](https://www.dropbox.com/scl/fi/zos8534bw8jxqq8gzs279/tech-weekend-data-science-hackathon.zip?rlkey=fglhtz05wycbz51rtsmeso1b1&st=2h5ubtux&dl=0)

