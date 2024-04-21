**RAINFALL PREDICTION IN AUSTRALIA USING LOGISTIC REGRESSION**

This project aims to build a Logistic Regression classifier to predict whether or not it will rain tomorrow in Australia. The dataset contains weather-related features and the target variable "RainTomorrow," indicating whether it will rain the following day.  

**Steps to Prepare and Train the Model**  

**Data Exploration and Preprocessing**  
Identify Categorical Variables: Explore the dataset to identify categorical variables.  
Check for Null Values: Determine which categorical variables have null values.  
Frequency Count of Categorical Variables: Get the frequency count of each categorical variable.  
Print First Five Rows: Print the first five rows of the dataset.  
Available Columns: List the available columns of the dataset.  
Drop RISK_MM Variable: Drop the RISK_MM variable column.  
Summary of Dataset: Get the summary statistics of the dataset.  
Print First Five Rows of Categorical Variables: List the first five rows only for categorical variables.  
Decompose Date Field: Decompose the date field into year, month, and day fields, then drop the original date field.  
Unique Locations: Determine the number of unique locations in the dataset.  
Frequency of Each Location: Print the number of times each unique location appears in the dataset.  
**Data Preprocessing and Model Training**  
One Hot Encoding: Perform One Hot Encoding for each categorical variable.  
Handle Missing Values: Use median imputation for numerical columns and the most frequent value for categorical columns to fill null values.  
Normalization: Normalize each numerical column to bring it to a value between 0 and 1.  
Train-Test Split: Split the dataset into training and test sets (70% train, 30% test).   
Train Logistic Regression Model: Train the Logistic Regression model on the training dataset.  
Predict RainTomorrow: Predict the RainTomorrow for the test set.  
Evaluate Model Performance: Describe the performance of the model using the confusion matrix and provide accuracy and F1 score.   
