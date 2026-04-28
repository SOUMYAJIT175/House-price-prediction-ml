#  House Price Prediction

This project predicts house prices using Machine Learning techniques based on features like size, location, number of bedrooms, and other housing attributes.

##  Project Overview

The objective of this project is to build a regression model that can estimate house prices accurately using structured (tabular) data.

The project follows a complete Machine Learning workflow:
- Data loading and exploration
- Data preprocessing and cleaning
- Feature engineering
- Model training
- Model evaluation
- Prediction on unseen data

---

## Technologies Used

- Python
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Dataset

- Source: Kaggle (House Prices Dataset)
- Files used:
  - `train.csv` → Contains features + target (`SalePrice`)
  - `test.csv` → Contains features only

---

## Workflow

1. Load dataset using Pandas  
2. Perform Exploratory Data Analysis (EDA)  
3. Handle missing values (mean/mode imputation)  
4. Convert categorical data into numerical form (encoding)  
5. Normalize features using scaling  
6. Split data into training and validation sets  
7. Train model using Linear Regression  
8. Evaluate model using MSE and R² Score  
9. Predict house prices for test dataset  

---

## Model

- **Algorithm Used:** Linear Regression  
- A simple and effective baseline model for regression problems  

---

## Evaluation Metrics

- **Mean Squared Error (MSE):** Measures average squared difference between actual and predicted values  
- **R² Score:** Indicates how well the model explains the variance in data  

---

## How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/House-price-prediction-ml.git
cd House-price-prediction-ml
# Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn
## Run Jupyter Notebook
jupyter notebook
## Open `house_price_prediction.ipynb` and run the cells

## 📌 Conclusion

This project demonstrates a complete machine learning workflow for predicting house prices using regression techniques. It successfully applies data preprocessing, model training, and evaluation to generate meaningful predictions.

👨‍💻 Author
Soumyajit Bag
CSE (AI/ML) Student