# 🚀 Spaceship Titanic – Missing Crew Members

**Project developed within the course _Supervised Machine Learning_ by first-year students of the Bachelor's Degree in Digital Technologies and Artificial Intelligence at ISCTE-Sintra during the 2022–2023 academic year.**

## 📜 Project Overview

This project was inspired by the [Kaggle Spaceship Titanic Competition](https://www.kaggle.com/competitions/spaceship-titanic), which presents a fictional, sci-fi scenario:  
In the year 2912, the luxurious interstellar liner _Spaceship Titanic_ collides with a spacetime anomaly. Many passengers vanish, some transported to another dimension, others stranded in orbit around Alpha Centauri.  
Our mission: **predict whether each passenger was transported** using the available passenger data.

## 🗂 Dataset

The dataset consists of passenger records, including:  
- **Demographics**: `HomePlanet`, `Age`, `VIP` status.  
- **Cabin Info**: deck, number, side.  
- **Onboard Spending**: `RoomService`, `FoodCourt`, `ShoppingMall`, `Spa`, `VRDeck`.  
- **Travel Info**: `CryoSleep`, `Destination`.  
- **Target**: `Transported` (boolean).  

Two datasets are used:  
1. **Training set** – used for data exploration and model training.  
2. **Test set** – used for generating predictions for Kaggle submission.

## 🔍 Methodology

1. **Data Wrangling**  
   - Handling missing values.  
   - Encoding categorical features.  
   - Creating new features (e.g., `TotalSpending`).  
   - Removing anomalies and infinite values.  

2. **Exploratory Data Analysis**  
   - Understanding distributions.  
   - Visualizing relationships between variables and `Transported`.  

3. **Modeling**  
   - Random Forest Classifier.  
   - Multi-layer Perceptron (MLP).  
   - K-Nearest Neighbors (KNN).  
   - Bagging Classifier.  

4. **Evaluation**  
   - Accuracy score.  
   - Classification report.  
   - Confusion matrix.  

5. **Kaggle Submission**  
   - Predictions generated on the test dataset in the required format.

## 🛠 Technologies Used
- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn

## 📈 Results
The final trained models achieved competitive accuracy on the Kaggle leaderboard, demonstrating effective feature engineering and model selection.
