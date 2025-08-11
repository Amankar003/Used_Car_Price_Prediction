# 🚗 Used Car Price Prediction

## 📌 Project Overview

The Used Car Price Prediction project aims to accurately predict the prices of second-hand cars based on various features using machine learning techniques. This helps both buyers and sellers estimate fair market prices, making negotiations easier and reducing the chances of fraud.

The project uses real-world data including car model, manufacturing year, mileage, fuel type, transmission, ownership history, and more. Various regression models have been applied to predict car prices effectively.

---

## 🛠️ Technologies & Tools

- **Programming Language:** Python 3.x  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment:** Jupyter Notebook  
- **Version Control:** Git & GitHub  

---

## 📊 Dataset Description

The dataset consists of approximately [mention dataset size if known] used car listings with the following features:

| Feature            | Description                               |
|--------------------|-------------------------------------------|
| Car Make & Model   | Manufacturer and model name of the car     |
| Year               | Manufacturing year of the car               |
| Kilometers Driven  | Total kilometers driven by the car          |
| Fuel Type          | Petrol, Diesel, CNG, Electric, etc.         |
| Transmission       | Manual or Automatic                         |
| Owner Type         | First, Second, or Third owner, etc.          |
| Mileage            | Car mileage (km per litre or km per kWh)    |
| Engine             | Engine capacity in CC                        |
| Max Power          | Maximum power of the car in bhp              |
| Seats              | Number of seats                              |
| Price              | Market price of the car (target variable)    |

The data is sourced from the [Kaggle Used Car Dataset](https://www.kaggle.com/datasets/atharvaingle/used-car-dataset-ford-and-mercedes), which includes Ford and Mercedes car listings.

---

## ⚙️ Features & Workflow

1. **Data Cleaning & Preprocessing**  
   - Handling missing values  
   - Dropping irrelevant columns  
   - Encoding categorical variables (Label Encoding / One-Hot Encoding)  
   - Applying normalization/scaling where necessary  

2. **Exploratory Data Analysis (EDA)**  
   - Visualizing data distributions, outliers, and correlations  
   - Analyzing feature impact on price  

3. **Model Building**  
   - Training multiple regression models like Linear Regression, Random Forest, XGBoost, etc.  
   - Hyperparameter tuning to select the best performing model  

4. **Model Evaluation**  
   - Using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score to evaluate model accuracy  

5. **Prediction**  
   - Predicting prices for new car data using the finalized model  

---

## 🚀 Installation & Usage

### Requirements

Make sure Python 3.x is installed along with these libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

### 📈 Results & Performance
The Random Forest Regression model showed the best performance with an R² score of approximately 0.85 (update this based on your results).

MAE and RMSE values were low, indicating good accuracy.

The model consistently predicted prices close to actual values, making it reliable for practical use.
