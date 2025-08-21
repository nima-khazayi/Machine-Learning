# House Pricing Regression Project

## Project Overview
This project predicts house prices using regression models. The dataset is a simplified version inspired by Kaggle’s House Prices dataset. The goal is to explore features that influence house prices and build regression models to predict them.

---

## Dataset
- **File used:** `housePrice.csv`  
- **Features:**
  - `Address` – location of the house  
  - `Area` – size of the house (square meters)  
  - `Room` – number of rooms  
  - `Warehouse` – presence/size of warehouse/storage  
  - `Elevator` – whether the building has an elevator (binary)  
  - `Parking` – availability of parking (binary)  
- **Target variable:** `Price`  

---

## Project Structure
```
  Regression/
  │
  ├── HousePricing.ipynb # Main Jupyter Notebook with analysis and model training
  ├── housePrice.csv # Dataset file
  └── README.md # Project documentation
```
---

## Methods
- **Data preprocessing**
  - Handle missing values
  - One-hot encode categorical features (`Address`, `Room`)
  - Scale numeric features if necessary
  - Polynomial feature expansion for selected numeric features (`Area`, `Address`)
- **Models**
  - Linear Regression
  - Polynomial Regression
  - Comparison of multiple regression approaches
- **Evaluation**
  - Split dataset into training and test sets
  - Measure performance using metrics like RMSE and R² score
  - Visualize predictions vs actual prices

---
