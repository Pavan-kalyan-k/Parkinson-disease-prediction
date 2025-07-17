# 🧠 Parkinson's Disease Prediction Using ML

This project detects **Parkinson’s Disease** using a dataset of biomedical voice measurements and machine learning techniques.

---

## 🚀 Features

✅ **CSV File Handling** – Reads and processes structured `.csv` files efficiently.  
✅ **Cutting-edge Libraries** – Uses `pandas`, `numpy`, `seaborn`, `sklearn`, and `matplotlib`.  
✅ **Classification Models** – Applies multiple ML models for high-accuracy Parkinson’s prediction.  
✅ **Data Visualization** – Creates visual plots for `Actual vs Predicted` comparison.  
✅ **Data Preprocessing** – Handles nulls, outliers, and scales features for optimal model performance.  
✅ **Feature Engineering** – Selects and transforms features to boost accuracy.  
✅ **Performance Metrics** – Evaluates models using metrics like **Accuracy**, **Precision**, **Recall**, and **F1-Score**.

---

## 🧩 Modules Used

| 📦 Library    | Purpose                              |
|--------------|--------------------------------------|
| 🐼 Pandas     | Data handling and manipulation       |
| 🔢 Numpy      | Numerical computation                |
| 📊 Seaborn    | Statistical visualization            |
| 🎨 Matplotlib | Custom plots and graphs              |
| 🤖 Sklearn    | ML models and preprocessing          |

---

## 🔁 Model Workflow

1. **Load Dataset** (`CSV`)  
2. **Preprocess Data** (nulls, scaling, etc.)  
3. **Feature Selection** (filter irrelevant features)  
4. **Train/Test Split**  
5. **Train ML Models** (SVM, RF, KNN, etc.)  
6. **Evaluate Performance**  
7. **Visualize Predictions**  
8. *(Optional)* Deploy with a simple UI

---

## 📌 Dataset Information

- **Total Samples**: 195  
- **Features**: 22 voice-based features  
- **Target**: `status`  
  - `1` = Parkinson’s positive  
  - `0` = Healthy individual

Source: [UCI Parkinson's Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons)

---

## 📈 Performance Metrics

✔ Accuracy  
✔ Precision  
✔ Recall  
✔ F1-Score  
✔ Confusion Matrix  

---

## 🛠️ How to Run

```bash
git clone https://github.com/your-username/parkinsons-prediction
cd parkinsons-prediction
pip install -r requirements.txt
python train_model.py
