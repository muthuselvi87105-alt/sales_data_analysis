 sales_data_analysis

📊 Sales Data Analysis - Classification Project

📌 Project Overview
Target variable: Payment Method (Gift Card / Credit Card).  
Goal: Transaction details (Product, Price, Quantity, Manager, City) 

📂 Dataset Details
File Name: `9. Sales-Data-Analysis.csv`  
Columns:
  - Order ID
  - Date
  - Product
  - Price
  - Quantity
  - Payment Method (Target)
  - Manager
  - City  

⚙️ Workflow Steps
1. Import Libraries → pandas, scikit-learn, seaborn, matplotlib  
2. Load Dataset → `pd.read_csv()`  
3. Explore Data → `df.head()`, `df.columns`  
4. Feature Selection → Product, Price, Quantity, Manager, City  
5. Target Selection → Payment Method  
6. Encoding → LabelEncoder for categorical variables  
7. Train-Test Split → 80% training, 20% testing  
8. Model Training → RandomForestClassifier  
9. Evaluation → Accuracy, Classification Report, Confusion Matrix  

📈 Results
- Accuracy: Printed using `accuracy_score()`  
- Classification Report: Precision, Recall, F1-score  
- Confusion Matrix: Visualized with seaborn heatmap  

 🚀 Future Improvements
- Add regression model for predicting sales amount.  
- Try other classifiers (Logistic Regression, SVM, XGBoost).  
- Perform feature engineering (e.g., time-based features).  
- Hyperparameter tuning for better accuracy.  



Muthu, உங்களுக்கு நான் **README.md Tamil-English mix** version (bilingual, easy for local + global audience) கொடுக்கட்டுமா?
