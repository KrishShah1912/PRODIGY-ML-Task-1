# House Price Prediction Project(Linear Regression Project) 

---

## Overview
PRODIGY ML Task 1 is a hands-on project demonstrating the full machine learning workflow. It covers **data exploration**, **preprocessing**, **feature engineering**, **model building**, and **evaluation** to predict [target variable, e.g., house prices] using regression techniques.

---

## Highlights
- Comprehensive **data analysis** with visualizations  
- Robust **data cleaning** and preprocessing  
- **Feature engineering** for improved predictions  
- Predictive modeling using **Linear Regression** and other ML algorithms  
- **Model evaluation** with RMSE and R² metrics  
- Step-by-step workflow in **Jupyter Notebook**  

---

## Setup & Usage
### Prerequisites
Python 3.10+ and essential libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Running the Project
## Clone the repository:
```git clone https://github.com/KrishShah1912/PRODIGY-ML-TASK-1.git```

---

## Open ML1.ipynb in VS Code or Jupyter Notebook
* Run each cell sequentially to reproduce the results
* Model Evaluation
* Models are evaluated using:
  - RMSE (Root Mean Squared Error): Measures prediction error
  - R² Score: Shows how well the model explains variance in the data
  
---
## Methodology

- The project follows these steps:

1. Data Loading and Inspection: The train.csv and test.csv files are loaded using pandas.
2. Exploratory Data Analysis (EDA): The relationships between the features and the target variable (SalePrice) are visualized using histograms, scatter plots, and heatmaps to identify trends and correlations.
3. Feature Engineering: FullBath and HalfBath are combined to create a single TotalBath feature.
4. Data Splitting: The training data is split into an 80% training set and a 20% testing set.
5. Model Training: A LinearRegression model from scikit-learn is trained on the training data.
6. Model Evaluation: The model's performance is assessed on the testing set using Root Mean Squared Error (RMSE) and the R-squared (R²) score.
7. Prediction: The final model is used to generate predictions on the test.csv dataset, which are then saved to a submission.csv file.
---

## Acknowledgments
* Dataset from [source, e.g., Kaggle “House Prices - Advanced Regression Techniques”]
* Some guidance generated with AI tools

---

## License
Open for learning, experimentation, and portfolio use.

---
