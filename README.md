# Exploratory_Data_Analysis_On_Heart_Dataset
Complete preprocessing and EDA on the Heart Disease dataset including missing value handling, outlier treatment, encoding, scaling, and train-test split.

❤️ Heart Disease Dataset – Data Preprocessing & EDA
This repository presents a comprehensive data preprocessing and exploratory data analysis (EDA) workflow applied on the Heart Disease dataset. The dataset has been cleaned and transformed to make it suitable for training machine learning models.

📌 Objective
To study and apply data preprocessing techniques on the Heart Disease dataset and prepare it for machine learning algorithm training.

🛠️ Tasks Performed
✅ 1. Basic Exploratory Data Analysis
Used head(), tail(), describe(), info(), and shape to understand the structure and summary of the dataset.

✅ 2. Handling Missing Values
Checked for missing values using isnull().sum().

Imputed missing data using statistical methods like mean, median, and mode.

✅ 3. Handling Duplicates
Detected duplicate rows using duplicated().

Removed duplicates to avoid biased outcomes.

✅ 4. Outlier Detection and Handling
Detected outliers using IQR method and boxplots.

Handled outliers to maintain data quality.

✅ 5. Data Encoding
Applied encoding on categorical features:

Label Encoding for binary attributes.

One-Hot Encoding for categorical variables with more than two categories.

✅ 6. Univariate, Bivariate, and Multivariate Analysis
Univariate analysis: Histograms, countplots.

Bivariate analysis: Scatterplots, barplots.

Multivariate analysis: Heatmap and pairplot for correlation understanding.

✅ 7. Feature Scaling
Applied MinMaxScaler / StandardScaler on numerical attributes to bring all features to a similar scale.

✅ 8. Data Splitting
Divided the dataset into 80% training and 20% testing using train_test_split.

📁 Dataset
The dataset is available on Kaggle – Heart Disease UCI Dataset

💻 Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📊 Final Outcome
A clean, encoded, scaled, and preprocessed dataset.

Exploratory insights and visual analysis of key features.

Ready-to-use dataset for applying ML algorithms.
