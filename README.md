# Titanic-Survival-Classification

## 📌 Project Overview
## 👨‍💻 Author
Muhammad Zohaib 
*Internship:* Data Science Intern at [Arch Technologies]

## 🎯 Task
- Load and preprocess the Titanic dataset.  
- Handle missing values (especially Age).  
- Encode categorical variables (Sex).  
- Select important features (Pclass, Sex, Age, Fare).  
- Train classification models (Random Forest, Logistic Regression).  
- Evaluate models using accuracy, confusion matrix, and classification report.  
- Visualize feature importance.  
- Save the trained model for future use.

## ⚙ Steps Performed
1. *Data Loading* – Loaded Titanic dataset using Pandas.  
2. *Data Cleaning* – Handled missing values (Age filled with median).  
3. *Feature Encoding* – Converted categorical column Sex into numeric values.  
4. *Feature Selection* – Used Pclass, Sex, Age, Fare as model inputs.  
5. *Train-Test Split* – 80% training, 20% testing.  
6. *Model Training* –  
   - Random Forest Classifier  
   - Logistic Regression (for comparison)  
7. *Model Evaluation* – Checked accuracy, confusion matrix, and classification report.  
8. *Feature Importance Visualization* – Plotted which features affect survival most.  
9. *Model Saving* – Saved trained model using joblib.  

## 📊 Results
- *Random Forest Classifier Accuracy:* ~83%  
- *Logistic Regression Accuracy:* ~79%  
- Key influential features: *Sex, **Pclass, **Age*  

✅ Female passengers had a higher survival rate.  
✅ Higher-class passengers were more likely to survive.  
✅ Younger passengers had better survival chances.  

## 🛠 Tech Stack
- *Python*  
- *Pandas, NumPy* – Data manipulation  
- *Scikit-learn* – Machine learning models  
- *Matplotlib, Seaborn* – Data visualization  
- *Joblib* – Model saving/loading  

## 📌 Conclusion
This project demonstrates how *machine learning can predict survival outcomes* based on passenger data.  
It shows the importance of *feature engineering, preprocessing, and model evaluation* in real-world datasets.  
