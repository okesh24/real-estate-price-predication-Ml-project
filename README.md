# 🏠 Real Estate Price Prediction – Machine Learning Project  

## 📌 Project Overview  
This project focuses on building a **Machine Learning model** to predict **real estate prices** based on various features such as location, area, number of bedrooms, and amenities.  
The goal is to demonstrate data preprocessing, feature engineering, and regression modeling to solve a real-world problem.  

---

## 🔑 Key Features  
- 📊 **Data Cleaning & Preprocessing**: Handled missing values, outliers, and inconsistent entries  
- 🏗 **Feature Engineering**: One-hot encoding for categorical variables (location, amenities, etc.)  
- 🤖 **Machine Learning Models**:  
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
- 🎯 **Model Evaluation**: Compared models using R² score, RMSE, and MAE  
- 📈 **Visualization**: Used Matplotlib & Seaborn for analyzing distributions and correlations  

---

## 📊 Insights  
- Location and area are the most significant factors influencing property prices  
- Random Forest Regressor performed better compared to simple Linear Regression  
- Larger properties in premium locations had a disproportionately higher price trend  

---

## 🛠️ Tech Stack  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🚀 How to Run  
1. Clone the repository:
   ```bash
   git clone https://github.com/okeshchoudhary/Real-Estate-Price-Prediction.git
   ```
2. Navigate to the folder:
   ```bash
   cd Real-Estate-Price-Prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook:
   ```bash
   jupyter notebook notebooks/real_estate_price_prediction.ipynb
   ```

---

## 📂 Project Structure  
```
Real-Estate-Price-Prediction/
│
├── data/
│   └── real_estate.csv           # Dataset (or link to source)
│
├── notebooks/
│   └── real_estate_price_prediction.ipynb
│
├── models/
│   └── random_forest.pkl         # Saved trained model
│
├── README.md
└── requirements.txt
```

---

## 👨‍💻 Author  
**Okesh Choudhary**  
GitHub: [okeshchoudhary](https://github.com/okeshchoudhary)  
