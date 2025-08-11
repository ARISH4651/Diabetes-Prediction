# Diabetes Prediction using Machine Learning

This project leverages **Machine Learning** techniques to predict the likelihood of diabetes in patients based on diagnostic health measurements.  
The aim is to demonstrate end-to-end ML workflow: data preprocessing, model training, evaluation, and deployment-ready code.

---

## 📊 Dataset
The project uses the **Pima Indians Diabetes Dataset** from Kaggle, which contains medical predictor variables and a binary target variable indicating diabetes status.

**Features:**
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

---

## 🛠️ Tech Stack
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
- **Model:** Support Vector Machine (SVM)

---

## ⚙️ Project Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Feature scaling with `StandardScaler`

2. **Model Training**
   - Trained an SVM classifier

3. **Evaluation**
   - Achieved accuracy of **XX%** on the test dataset
   - Confusion Matrix & Classification Report for deeper insights

---

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/diabetes-prediction.git
cd diabetes-prediction

# Install dependencies
pip install -r requirements.txt
