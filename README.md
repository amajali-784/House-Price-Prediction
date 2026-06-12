# 🏠 House Price Prediction System

## 📌 Project Overview

This project is a Machine Learning-based House Price Prediction System that estimates the market value of residential properties in Bengaluru based on property features such as location, total square feet, number of bedrooms (BHK), and bathrooms.

The application is developed using Python, Machine Learning, and Streamlit to provide an interactive web interface for users to predict house prices instantly. 

---

## 🎯 Features

* Predict house prices using a trained Random Forest model.
* User-friendly Streamlit web interface.
* Location-based price estimation.
* Market comparison with similar properties.
* Price insights (Underpriced, Fairly Priced, Overpriced).
* Histogram visualization for market comparison.
* Responsive and clean UI. 

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Streamlit 

---

## 📂 Project Structure

```text
House_Price_Prediction/
│
├── app.py
├── cleaned_df.csv
├── Bengaluru_House_Data.csv
├── rf_model.joblib
├── model_columns.joblib
├── requirements.txt
├── house_logo.png
├── README.md
│
└── notebooks/
    └── eda.ipynb
```

---

## 📊 Machine Learning Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Model Training
6. Model Evaluation
7. Model Serialization using Joblib
8. Streamlit Deployment

---

## 📥 Input Parameters

The user provides:

* 📍 Location
* 📐 Total Square Feet
* 🛁 Number of Bathrooms
* 🏠 Number of Bedrooms (BHK)

These inputs are converted into the required model format before prediction. 

---

## 📈 Output

The application displays:

* Estimated Property Price (₹)
* Market Value Analysis
* Similar Property Comparison
* Price Distribution Visualization

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## 📦 Requirements

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
streamlit
```



---

## 🎓 Learning Outcomes

* Data Preprocessing
* Feature Engineering
* Machine Learning Model Building
* Random Forest Regression
* Model Deployment with Streamlit
* Data Visualization
* Real Estate Price Analytics

---

## 🔮 Future Enhancements

* Integration with live real estate APIs.
* Advanced feature selection.
* Property recommendation system.
* Interactive dashboards.
* Cloud deployment (AWS/Azure/GCP).
* User authentication and history tracking.

---

## 👨‍💻 Developed By

**Rohit Gada**
Data Analyst & Machine Learning Enthusiast

---

## 📄 License

This project is developed for educational and learning purposes.
