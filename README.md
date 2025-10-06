# Age, Weight, Height, BMI Analysis Using Machine Learning

## Project Overview
This project analyzes the relationship between Age, Weight, Height, and BMI using machine learning techniques. The goal is to predict BMI values and classify individuals into BMI categories (Underweight, Normal, Overweight, Obese), uncover trends in BMI distribution across different age groups, and provide actionable health insights.

The project demonstrates end-to-end data analysis, from exploration and visualization to model building and evaluation.

## Dataset
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/rukenmissonnier/age-weight-height-bmi-analysis)  
- **Columns:** 
  - `Age`
  - `Height`
  - `Weight`
  - `BMI`
- **Target Variable:** `BMI` (for regression) or `BMI Category` (for classification)

## Project Structure
Since the project is contained in a single notebook:

``` plaintext
age-weight-bmi-analysis/
│
├── Age_Weight_Height_BMI_Analysis.ipynb # Main notebook with full workflow
├── data/
│ ├── raw/ # Original dataset Kaggle Link
├── documentation/
├── Project Codes with Visualization/ # figures generated from analysis
└── README.md
```

## Workflow / Steps
1. **Data Exploration**
   - Summary statistics of Age, Height, Weight, and BMI
   - Missing value and duplicate checks
   - Visualization of distributions (histograms, boxplots)
   - Correlation analysis and scatterplots to understand relationships

2. **Data Cleaning & Preprocessing**
   - Handling missing values and outliers
   - Scaling/normalizing features for ML models
   - Creating BMI categories for classification

3. **Feature Selection**
   - Analyzing feature importance
   - Ensuring selected features improve model performance

4. **Machine Learning Modeling**
   - **Regression Models:** Linear Regression, Multiple Linear Regression, Random Forest Regressor
   - **Classification Models:** KNN, Logistic Regression, Decision Tree, Naive Bayes, Random Forest Classifier, SVM

5. **Model Evaluation**
   - Regression metrics: RMSE, MAE, R²
   - Classification metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix
   - Model comparison and selection of best-performing models

6. **Insights & Recommendations**
   - Key trends between Age, Height, Weight, and BMI
   - Groups at risk and actionable health recommendations

## Skills Showcased
- Python programming
- Data exploration and visualization (Pandas, NumPy, Matplotlib, Seaborn)
- Data preprocessing and feature engineering
- Regression and classification modeling (Scikit-learn)
- Model evaluation and insights extraction
- GitHub project structuring

## Conclusion
- Regression and classification models revealed [best-performing model] as the most effective for predicting BMI and BMI categories.
- Significant trends were identified, such as [e.g., BMI increasing with age or weight].
- Recommendations include monitoring high-risk groups, further data collection for lifestyle factors, and exploring more advanced models for better prediction.

## Optional Improvements
- Include additional features such as diet, physical activity, or gender for enhanced predictions.
- Deploy the model as a web app for interactive BMI predictions.
