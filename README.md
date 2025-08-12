# Customer-Response-Prediction-using-Machine-Learning
This project applies Python-based machine learning and data analysis to predict customer responses to a marketing campaign.  
The dataset contains 31,649 training records and 13,562 test records, each with 17 features including demographic details, financial history, and prior campaign outcomes.

## Project Overview
- **Objective:** Classify whether a customer will respond positively to the marketing campaign.
- **Tech Stack:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Dataset Size:**  
  - Training: 31,649 rows × 17 columns  
  - Test: 13,562 rows × 17 columns  
- **Target Variable:** `y` (Yes/No response)

## Key Steps
1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling and selection
2. **Exploratory Data Analysis (EDA)**
   - Visualized relationships between features such as age, job, balance, and loan status with campaign outcomes.
3. **Model Development**
   - Applied supervised learning algorithms (Logistic Regression, Decision Trees, Random Forests, etc.)
   - Tuned hyperparameters for optimal performance.
4. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-Score
   - Compared multiple models to select the best-performing one.
