
# ✈️ AeroCare Phase 1: Remaining Useful Life (RUL) Prediction

🚀 A machine learning & deep learning project focused on predicting the **Remaining Useful Life (RUL)** of aircraft engines using the NASA C-MAPSS dataset.

---

## 📌 Overview

Predicting the Remaining Useful Life (RUL) of engines is critical for:
- Preventive maintenance
- Reducing operational costs
- Improving safety in aviation systems

This project explores **multiple machine learning and hybrid deep learning models**, including **stacked architectures**, to accurately estimate RUL.

---

## 🧠 Models Implemented

### 🔹 Traditional Machine Learning Models
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- XGBoost
- AdaBoost

### 🔹 Deep Learning Models
- LSTM (Long Short-Term Memory)

### 🔹 Hybrid / Stacked Models (Key Contribution 🚀)
- Random Forest + LSTM (Simple & Optimized)
- XGBoost + LSTM (Simple & Optimized)

---

## 📂 Project Structure

```

AeroCare_Phase_1/
│
├── Basic_Models_FD003.ipynb
├── Outlier_Removal_FD001.ipynb
├── Outlier_Removal_FD003.ipynb
├── Outlier_Removal_FD004.ipynb
│
├── RandomForest_LSTM_Stacked_Model_Simple_FD002.ipynb
├── RandomForest_LSTM_Stacked_Model_Optimized_FD002.ipynb
├── RandomForest_LSTM_Stacked_Model_Simple_FD004.ipynb
├── RandomForest_LSTM_Stacked_Model_Optimized_FD004.ipynb
│
├── XGBoost_LSTM_Stacked_Model_Simple_FD002.ipynb
├── XGBoost_LSTM_Stacked_Model_Optimized_FD002.ipynb
├── XGBoost_LSTM_Stacked_Model_Simple_FD004.ipynb
├── XGBoost_LSTM_Stacked_Model_Optimized_FD004.ipynb

````

---

## 📊 Dataset

- **NASA C-MAPSS Dataset**
- Simulated turbofan engine degradation data
- Multiple subsets: FD001, FD002, FD003, FD004

### Features include:
- Sensor readings
- Operational settings
- Engine cycles

---

## ⚙️ Methodology

1. **Data Preprocessing**
   - Outlier detection & removal
   - Normalization / scaling
   - Windowing for time-series modeling

2. **Feature Engineering**
   - Time-based degradation trends
   - Sequence preparation for LSTM

3. **Model Training**
   - ML models trained on tabular features
   - LSTM trained on sequential data
   - Hybrid stacking combines both

4. **Evaluation**
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Square Error)
   - Engine-wise prediction evaluation

---

## 📈 Key Highlights

✨ Implemented both **baseline and advanced models**  
✨ Developed **stacked hybrid architectures**  
✨ Compared performance across multiple datasets (FD001–FD004)  
✨ Focused on **real-world predictive maintenance use-case**

---

## 🚀 Results (Example Insights)

- Hybrid models outperform standalone ML models  
- LSTM captures temporal degradation effectively  
- Optimized stacking improves prediction accuracy  

---

## 🛠️ Tech Stack

- Python 🐍
- Scikit-learn
- TensorFlow / Keras
- XGBoost
- Pandas, NumPy
- Matplotlib / Seaborn

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/AeroCare_Phase-1.git

# Navigate to project folder
cd AeroCare_Phase-1

# Open Jupyter Notebook
jupyter notebook
````

---

## 📜 License

This project is for academic and research purposes.

---

## 👩‍💻 Author

**Shruti Patel**
🎓 Computer Engineering Student
💡 Interested in AI, ML, and Predictive Systems

---

## ⭐ If you like this project...

Give it a ⭐ on GitHub and support the work!

```

::contentReference[oaicite:2]{index=2}
```
