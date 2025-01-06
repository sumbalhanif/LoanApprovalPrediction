# LoanApprovalPrediction
The first step in building a "Loan Approval Prediction" model is data collection. This involves gathering the dataset, which typically contains features such as personal details (e.g., gender, marital status), financial information (e.g., income, credit history), and the target variable (Loan_Status, representing whether a loan was approved or not). 

Next, I handled any missing values in the Data Preprocessing stage by removing the incomplete entries. Categorical variables, such as gender or marital status, were encoded into numerical values using Label Encoding because it is a binary classification problem.

After preprocessing, the next step was Exploratory Data Analysis (EDA), where I analyzed the relationships between features and the target variable. 
In the Model Selection and Training phase, I chose suitable classification algorithms, including K-Nearest Neighbors (KNN), Random Forest, Support Vector Machine (SVM), and Logistic Regression, and trained all four models. The test set accuracies for these models were as follows: KNN (0.66), Random Forest (0.78), SVM (0.82), and Logistic Regression (0.85). 

Finally, in the Model Comparison step, I compared the models based on their performance and selected Logistic Regression as the best-performing one.
