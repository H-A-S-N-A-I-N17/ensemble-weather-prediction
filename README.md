# Ensemble Weather Prediction

## 📌 Overview
This project focuses on **enhancing weather prediction accuracy** by combining two powerful machine learning models: **Support Vector Machine (SVM)** and **Random Forest**.  
By leveraging an **ensemble approach**, the model achieves higher accuracy than using either algorithm individually.

The work was inspired by real-time weather information platforms such as **Google Weather**, and is part of a research contribution showcased in a **conference paper**.

---

## 🚀 Features
- **Ensemble Learning:** Combines SVM and Random Forest for robust predictions.
- **Data Preprocessing:** Cleans and handles missing values in historical weather datasets.
- **Feature Engineering:** Extracts relevant features such as temperature, humidity, wind speed, and more.
- **Model Evaluation:** Compares individual models vs. ensemble results.
- **Visualization:** Generates plots for trends, model accuracy, and feature importance.

---

## 📂 Dataset
- **Source:** Historical weather dataset (CSV format).
- **Features Used:**
  - Temperature
  - Apparent Temperature
  - Humidity
  - Wind Speed
  - Pressure
  - Summary / Weather Condition
- **Target:** Predicted real-time weather conditions.

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Libraries:**
  - `scikit-learn` – SVM, Random Forest, model evaluation
  - `pandas` – Data manipulation
  - `numpy` – Numerical operations
  - `matplotlib` & `seaborn` – Visualization

---

## 📊 Methodology
1. **Data Loading:** Import historical weather dataset.
2. **Data Cleaning:** Handle missing/null values, remove duplicates.
3. **Feature Engineering:** Encode categorical features and scale numerical features.
4. **Model Training:**
   - Train SVM classifier.
   - Train Random Forest classifier.
5. **Ensemble Model:** Combine both models using a voting classifier.
6. **Evaluation:**
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix
7. **Visualization:** Compare model performances.

---

## 📈 Results
- The ensemble model achieved **higher accuracy** compared to standalone SVM and Random Forest models.
- Demonstrated improved **generalization** and **robustness** to noisy data.

---

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/H-A-S-N-A-I-N17/ensemble-weather-prediction.git
   cd ensemble-weather-prediction
    ```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Open the notebook:
```bash
jupyter notebook climate-new.ipynb
```
4.Run all cells to reproduce results.

---

