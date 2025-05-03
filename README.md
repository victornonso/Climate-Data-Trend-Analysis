# 🦠 COVID-19 Risk Prediction Model

This project uses machine learning to predict the likelihood of a COVID-19 infection based on symptoms and demographic factors. Developed as part of a healthcare data science initiative by eHealth Africa, this model provides insights into risk factors and serves as a foundation for building intelligent screening tools.

---

## 🎯 Objective

Build and evaluate predictive models that can classify individuals as COVID-19 positive or negative based on self-reported symptoms and demographic details.

---

## 📊 Features & Highlights

* ✅ **Predictive Models**: Implements Logistic Regression , Random Forest, XGBoost and Gradient Boosting classifiers.
* 🔁 **Cross-Validation**: Prevents overfitting and ensures reliable results.
* 📈 **Performance Metrics**: Includes accuracy, precision, recall, F1-score, and AUC-ROC.
* 🧪 **API Integration**: Flask-powered REST API for inference.
* 📉 **Visualizations**: ROC curve, confusion matrix, and feature importance charts.

---

## 🧠 Machine Learning Pipeline

1. **Data Cleaning**: Remove pending results and missing values.
2. **Feature Engineering**: Convert birth year to age, encode categorical fields.
3. **Modeling**: Train and evaluate Logistic Regression & Random Forest.
4. **Evaluation**: Use test data to compare metrics and choose the best model.

---

## 🗃️ Dataset

Collected from Hocus Pocus town by eHealth Africa. Fields include:

* **Demographics**: Age, Sex
* **Symptoms**: Binary indicators like cough, fever, loss of smell, etc.
* **Result**: COVID-19 test result (Positive or Negative)

---

## 🚀 How to Use

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/covid-risk-prediction.git
cd covid-risk-prediction
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the App

```bash
Covid Prediction Model.ipynb
```


## 📈 Sample Output

* 🔵 ROC AUC: 0.92 (Random Forest)
* ✅ Accuracy: 90.3%
* 🧠 Top Predictors: Fever, Loss of Taste/Smell, Difficulty Breathing

---

## 🛠 Tools & Libraries

* Python, Pandas, NumPy
* Scikit-learn
* Flask (API and web)
* Matplotlib, Seaborn (visuals)

---

## 🤝 Contribute

Pull requests and feedback are welcome!

---

## 📄 License

MIT License. See `LICENSE` for more details.

---

## 🧑‍💻 Authors

Built with ❤️ by the eHealth Africa Data Science Team.

For inquiries: [email@example.com](mailto:victornonso44@gmail.com)
