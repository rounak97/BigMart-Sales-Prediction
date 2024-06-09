# BigMart Sales-Prediction
This project uses the Big Mart Sales data. We predict the sales of items using Xgboost Regressor algorithm.

Libraries Used:

pandas numpy seaborn matplotlib klib dtale scikit-learn joblib pandas-profiling

Data Points:

Datasets: 'Train.csv' and 'Test.csv'

Shape: Train: (8523, 12), Test: (5681, 11)

Missing Values Imputation:

Item_Weight: Mean imputation

Outlet_Size: Mode imputation

Dropped Columns: 'Item_Identifier', 'Outlet_Identifier'

Models and Techniques:

EDA: dtale, ydata_profiling, seaborn, klib

Data Cleaning: klib

Label Encoding: LabelEncoder for categorical features

Data Split: Train-test split

Standardization: StandardScaler

Models & Key Metrics::

Linear Regression: 𝑅^2 = 0.56

R^2 = 0.56, MAE: 852.34, RMSE: 1137.32

Random Forest Regressor (5000 trees): 𝑅^2 = 0.65

R^2 =0.65, MAE: 745.50, RMSE: 987.20

Hyperparameter Tuning: GridSearchCV for Random Forest

File Handling: Models saved using joblib.
