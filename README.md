# bank-fraud-detection

Overview:

The project aimed to develop a fraud detection system for banking transactions using supervised machine learning techniques, specifically focusing on the Random Forest Classifier algorithm. Given the inherent imbalance in fraud detection datasets where fraudulent cases constitute a minority class, the challenge was to accurately identify fraudulent transactions while minimizing false positives. The dataset comprised synthetic bank transaction records, containing both discrete and continuous variables. 

Technologies Used: 
1. Python: Primary language for data manipulation and analysis.
2. Pandas: Data manipulation library for tabular data.
3. Matplotlib: Visualization library for creating plots.
4. NumPy: Package for numerical computations and array manipulation.
5. Scikit-learn (sklearn): Library for machine learning algorithms and tools.
6. Seaborn: Statistical data visualization library.
7. Random Forest Classifier (sklearn.ensemble.RandomForestClassifier): Machine learning algorithm for classification tasks.
8. RandomizedSearchCV (sklearn.model_selection.RandomizedSearchCV): Utility for hyperparameter optimization.

Approach: 
1. EDA: To begin exploring the banking dataset, I conducted EDA to identify relationships among variables and to gain insight into feature distributions.  
2. Preprocessing: The dataset then underwent preprocessing to encode categorical variables and drop columns in the dataset that would not contribute to our predictive modeling.
3. Model Selection and Training: Random Forest Classifier was chosen because of its ability to handle imbalanced datasets effectively. The Random Forest Classifier was trained on the preprocessed dataset, utilizing techniques such as cross-validation to optimize hyperparameters and prevent overfitting. The model was trained to maximize sensitivity to capture fraudulent transactions while maintaining a low false positive rate.

Impact: 
Implementing the developed Random Forest Classifier model can significantly enhance a bank's fraud detection capabilities. By identifying fraudulent transactions, the bank can mitigate financial losses and protect its customers from fraudulent activities, thereby fostering trust and confidence in its services.