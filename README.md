# Car_Price_Prediction_Using_LinearRegression_Algorithm 🚗
![Image Alt](1712922090733.png)

# Introduction:

A car price prediction project uses machine learning to estimate the value of a vehicle based on various features. This project aims to provide accurate price predictions, benefiting both buyers and sellers in the automotive market. By analyzing factors like  Fuel Type,Kms Driven, Manufacture Year,  Transmission Type (Manual, Automatic, number of Owners etc..., the project helps in setting competitive prices and facilitating informed decisions. 

#  📂 About Dataset:
Used Car Price Prediction Dataset is a comprehensive collection of automotive information extracted from the popular automotive marketplace website, https://www.cars.com. This dataset comprises 309 data points, each representing a unique vehicle listing, and includes fuel type, Owner, Kms_Driven, Present_Price, Car_Name, year, Seller_Type, Transmission etc...

## Description:
* Car_Name : Name of Car or Model Name
* Year : which Year Car Manufactured
* Selling Price : Price of Car
* Present_Price : Present Car Price
* Kms_Driven : How many Kilometer Driven
* Fuel_Type : Type of Fuel (e.g.Petrol, Diseal, CNG)
* Seller_Type : Type of Seller (e.g. Dealer, Individual)
* Transmission : Car is Manual or Automatic
* Owner : Number of Owners used this car previously

## 📊 Technology Used:
* Python
* Pandas,numpy
* Seaborn, matplotlib
* scikit-learn
* joblib(for saving the model and scaler)


## 🔍 Project Flow:
1. Load and Understand data.
2. Exploratory Data Analysis.
   * Value count and bar plots for categorical features.
   * Descriptive statistics for numerical columns.
3. Data Cleaning & Preprocessing
   * Check null values
   * Converted categorical variables using label mapping and one- hot encoding
   * Removed irrelevant columns like Car_Name.
4. Feature Scaling
   * Applied StandardScaler to normaize features.  
5. Model Building
   * Used LinearRegression from sklearn
   * Trained the model with an 80/20 train-test split
   * Saved the model and scaler using Joblib.
  
 6.Prediction
   * Collected user input from the terminal
   * Transformed input using the saved scaler
   * Predicted car price using the trained model

# 📌 Learnings:
* Performed full-cycle regression modeling from scratch.
* Learned how to encode categorical data and scale features.
* Practice basic EDA with visualization.
* Used user input to test a trained regression model.
* Gained hands-on experience with joblib, train_test_split, and model deployment basics.
