# Fraud-Transactions

### Overview:
This project addresses the problem of credit card fraud detection using both traditional machine learning models and a GPU-accelerated deep learning approach.  
The dataset contains transactional data with numeric and categorical features, as well as a binary target variable indicating fraudulent transactions.  
The workflow involves data preprocessing, model training, evaluation, and temporal analysis of fraud patterns.

### Dataset:
Credit Card Transactions Fraud Detection Dataset – (Kaggle link)  
I selected this dataset because it provides a realistic simulation of credit card transactions, including fraudulent and legitimate activities.
The dataset is large and diverse (over 1.29 million transactions, 23 features), which makes it suitable for:  
•	Fraud detection model development  
•	Exploratory data analysis (EDA)  
•	Handling real-world issues like class imbalance  
Additionally, it contains both customer information and transaction details, which allows for rich and varied analysis.
In addition, The dataset is imbalanced, it reflects real-world fraud detection challenges, making this dataset particularly interesting and valuable.

### Models:
We implemented and compared several machine learning models using both classical and deep learning approaches.  
Each model was trained on a large, imbalanced dataset where fraudulent transactions were rare compared to legitimate ones.

- Logistic Regression	with accurecy 0.8241
- Random Forest	with accurecy 0.9442
- Neural Network (sklearn) with accurecy	0.9870	
- PyTorch Neural Network	with accurecy 0.9864	

The models demonstrated the best performance in both AUC and F1 scores, suggesting a good fit to the data. However, they are not easily explainable, which is a trade-off when compared to simpler models like Logistic Regression. Random Forest serves as a middle ground, offering reasonable performance with partial explainability.
