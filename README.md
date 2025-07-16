# Predictive-Pulse-Harnessing-Machine-Learning-for-Blood-Pressure-Analysis

The dataset contains patient medical data used to predict blood pressure categories (e.g., Normal, High BP, Low BP). File format is `.csv`.

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Flask
- Pickle

---

## 🧪 Machine Learning Models

- Logistic Regression
- Random Forest Classifier ✅ *(Best model)*
- Decision Tree
- Gaussian Naive Bayes
- Multinomial Naive Bayes *(if applicable)*

---

## 📈 Evaluation Metrics

- Accuracy Score
- Classification Report (Precision, Recall, F1-score)

---

## 📦 Model Deployment

The model is saved as `model.pkl` using `pickle`, and integrated with a Flask app for real-time prediction.

To run the app:

```bash
pip install -r requirements.txt
python app1.py
