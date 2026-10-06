# CodeAlpha Data Science Internship - Tasks

Four data science projects completed for the CodeAlpha internship (September batch).

## Results

| Task | Folder | Result |
|------|--------|--------|
| Iris Flower Classification | `CodeAlpha_IrisClassification` | Test accuracy: 0.9333 |
| Unemployment Analysis | `CodeAlpha_UnemploymentAnalysis` | Rose from 9.51% (pre-Covid) to 17.77% during Covid, peak 24.88% in May 2020 |
| Car Price Prediction | `CodeAlpha_CarPricePrediction` | 5-fold CV R2: 0.85, MAE: 1.36 |
| Sales Prediction | `CodeAlpha_SalesPrediction` | Test R2: 0.9831 |

## Projects

### 1. Iris Flower Classification
- **Goal:** classify Iris flowers (setosa, versicolor, virginica) from their measurements.
- **Method:** compared Logistic Regression, KNN, SVM and Random Forest with cross-validation, tuned the best model with GridSearchCV, and evaluated it on a held-out test set.

### 2. Unemployment Analysis
- **Goal:** analyze unemployment trends and the impact of Covid-19.
- **Method:** data cleaning, national trend, before/during Covid comparison, regional impact, seasonality, and correlation analysis.

### 3. Car Price Prediction
- **Goal:** predict a car's selling price from its features.
- **Method:** created a Car_Age feature, one-hot encoded categorical columns, compared Linear Regression, Ridge, Random Forest and Gradient Boosting, tuned Random Forest, and evaluated with R2, MAE, RMSE and 5-fold cross-validation.
- **Note:** the test-split R2 is lower because a few high-priced cars with low resale value are hard to predict, so the cross-validated R2 is reported.

### 4. Sales Prediction
- **Goal:** predict sales from advertising spend on TV, Radio and Newspaper.
- **Method:** exploratory analysis, model comparison, and linear regression coefficients to measure the impact of each channel, plus a what-if budget simulation.

## How to run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook
```

Open the notebook inside any project folder and run all cells. Each folder contains its own dataset.

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook