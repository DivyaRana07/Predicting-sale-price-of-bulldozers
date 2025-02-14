
# Bulldozer Price Prediction

This project is an **end-to-end machine learning regression model** to predict the sale prices of bulldozers using historical auction data. The dataset comes from the **Blue Book for Bulldozers** competition on Kaggle.

## Project Overview

The goal of this project is to build a regression model to predict the price of bulldozers based on various features like equipment type, sale date, machine usage, and more. 

## Steps Followed

1. **Data Collection & Exploration**  
   - Loaded historical auction data.  
   - Performed exploratory data analysis (EDA) to understand key trends.  

2. **Data Preprocessing**  
   - Handled missing values.  
   - Converted categorical variables using encoding techniques.  
   - Feature engineering to extract useful information.

3. **Model Training**  
   - Implemented regression models such as **Random Forest Regressor**.  
   - Tuned hyperparameters for improved performance.  

4. **Evaluation**  
   - Used **Root Mean Squared Log Error (RMSLE)** as the evaluation metric.  
   - Compared different models' performances.  

5. **Predictions & Conclusion**  
   - Generated final predictions on test data.  
   - Provided insights into feature importance.

## Dependencies

- Python 3.x
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-Learn
- Jupyter Notebook

## How to Run

1. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
2. Open Jupyter Notebook and run the cells in sequence.

## Dataset Source

- [Blue Book for Bulldozers - Kaggle](https://www.kaggle.com/c/bluebook-for-bulldozers/data)

## Results

- The model provides a **reasonably accurate** prediction for bulldozer prices.  
- Further improvements can be made using **deep learning models** or additional feature engineering.

---
