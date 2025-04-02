# Loan Application Predictor

## Overview
This project aims to predict loan defaults and automate the loan eligibility process using machine learning. By analyzing historical loan data, we identify key risk factors and build predictive models to enhance decision-making.

## Dataset
The dataset contains information about loan applicants, including:
- **Credit History**
- **Income & Balance Information**
- **Loan Amount & Duration**
- **Employment & Property Details**

## Technologies Used
- **Python**
- **Pandas, NumPy** (Data Preprocessing & Analysis)
- **Scikit-Learn** (Machine Learning Models)
- **Matplotlib, Seaborn** (Data Visualization)

## Approach
1. **Exploratory Data Analysis (EDA)**  
   - Identified key factors affecting loan approval.
   - Handled missing values and outliers.
   
2. **Data Preprocessing & Feature Engineering**  
   - Encoded categorical variables.
   - Scaled numerical features for better model performance.

3. **Model Training & Evaluation**  
   - Trained models: **Logistic Regression, Decision Tree, Random Forest**.
   - Achieved **75% accuracy** in predicting loan defaults.
   - Evaluated models using **Confusion Matrix, F1-score, and ROC-AUC Score**.

## Results
- **Automated loan eligibility prediction**, improving efficiency.
- **Detected high-risk applicants**, reducing loan default risks.
- Achieved **F1-score of 0.72** and **75% accuracy**.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Mausham-Sharma/loan-application-predictor.git
   ```
2. Navigate to the project directory:
   ```bash
   cd loan-application-predictor
   ```
3. Run the Jupyter Notebook or script:
   ```bash
   jupyter notebook
   ```

## Future Improvements
- Incorporate advanced machine learning techniques like **XGBoost**.
- Deploy the model as a web-based loan eligibility checker.

## Contributors
- **Mausham Sharma**  
  [LinkedIn](https://www.linkedin.com/in/mausham-sharma/) | [GitHub](https://github.com/Mausham-Sharma)
