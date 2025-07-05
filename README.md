#  Tumor Detection Project

##  Objective

- Load and clean the medical dataset.
- Perform Exploratory Data Analysis (EDA).
- Apply preprocessing and feature scaling.
- Train a machine learning model to classify tumors.
- Evaluate the model's performance.

## Dataset

File Name: `Tumor_Detection.csv`  
The dataset contains tumor-related features.

## Technologies Used

- Python
- Pandas & NumPy
- Seaborn & Matplotlib
- Scikit-learn (Random Forest, StandardScaler, train_test_split)


## Steps Performed

1. Data Cleaning  
   - Removed unnecessary columns like `id` and unnamed extras.  
   - Checked for missing values.

2. Data Visualization  
   - Count plot of diagnosis types.  
   - Correlation heatmap of features.

3. Preprocessing 
   - Converted diagnosis labels (`M`, `B`) to binary values.  
   - Feature scaling using `StandardScaler`.

4. Model Training  
   - Split data into training and testing sets.  
   - Trained `RandomForestClassifier`.

5. Model Evaluation  
   - Accuracy score  
   - Confusion matrix  
   - Classification report (Precision, Recall, F1-score)


## Results

- The Random Forest model was able to classify tumors with high accuracy.
- The dataset was balanced enough for binary classification.



