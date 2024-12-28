
 Credit Card Fraud Detection  

 Project Overview  
This project is a machine learning-based solution for detecting fraudulent credit card transactions. The dataset used is highly imbalanced, so techniques like SMOTE (Synthetic Minority Oversampling Technique) and undersampling were applied to balance the classes and improve model performance. Several classification models were trained, and their performance was evaluated using metrics like accuracy, F1 score, and other relevant metrics to ensure the best possible model for fraud detection.  

 Features  
- Trains multiple machine learning models to predict fraudulent transactions.  
- Handles imbalanced data using SMOTE and undersampling techniques.  
- Evaluates model performance using accuracy, F1 score, precision, and recall.  

 Technologies Used  
- Machine Learning Models: Random Forest, SVM, or any classifier (depending on your choice)  
- Data Preprocessing: Pandas, NumPy  
- Data Balancing: SMOTE and Undersampling  
- Metrics: Accuracy, F1 Score, Precision, Recall  

 Dataset Handling  
The dataset was imbalanced, so the following methods were applied to address this:  
- SMOTE was used to generate synthetic samples for the minority (fraudulent) class.  
- Undersampling was used to reduce the majority class (legitimate) transactions.  
- These techniques were crucial for improving the model’s ability to detect fraudulent transactions.  

 Impact of SMOTE  
To address the issue of class imbalance in the dataset, SMOTE was applied, which significantly improved the model’s performance. By generating synthetic samples for the minority class (fraudulent transactions), SMOTE helped balance the dataset, allowing the model to learn better and predict fraud more accurately. The application of SMOTE resulted in a noticeable improvement in F1 scores and other evaluation metrics like precision and recall, which are crucial for detecting fraud in imbalanced datasets.  

 Model Evaluation  
The trained models were evaluated using the following metrics:  
- Accuracy: Measures the percentage of correct predictions.  
- F1 Score: A balance between precision and recall, especially useful in imbalanced datasets.  
- Precision and Recall: Used to evaluate how well the model identifies fraudulent transactions.  

