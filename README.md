# AI_ML_internship_task1
The Titanic dataset contains information about passengers aboard the RMS Titanic, including demographic, travel, and survival details.
 Steps Performed:
### Data Loading & Inspection
Loaded the CSV using pandas.
Inspected columns, data types, and missing values.
### Missing Value Handling
Imputed missing values in:
Age using median.
Embarked using most frequent value.
Dropped the Cabin column due to excessive missing data.
### Feature Encoding
Converted categorical columns (Sex, Embarked) to numeric using Label Encoding.
### Feature Scaling
Applied StandardScaler to normalize numerical features: Age, Fare, SibSp, and Parch.
### Outlier Visualization
Used boxplots to identify outliers in numerical features.
### Outlier Removal
Removed outliers using the IQR (Interquartile Range) method for all scaled numerical features.
### Tools Used:
Python Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

Final dataset was free from missing values and extreme outliers, ready for modeling or further analysis.

🔧 Tools Used:
Python Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn


