#  Titanic Data Analysis & Machine Learning

##  Project Overview
This project analyzes the **Titanic dataset** to explore data, clean missing values, visualize important patterns, and build machine learning models to predict passenger survival.  
It is implemented in a Jupyter Notebook: **Titanic.ipynb**.

---

##  Files in this Repository
- **Titanic.ipynb** → Main notebook with data cleaning, EDA, and modeling.  
- **train.csv** → Training dataset (with `Survived` values).  
- **test.csv** → Test dataset (without survival labels).  
- **gender_submission.csv** → Example submission file from Kaggle.  
- **README.md** → Project documentation (this file).  

---

##  Objectives
- Perform **data cleaning** (handle missing values in Age, Embarked, Cabin).  
- Conduct **exploratory data analysis (EDA)** with plots.    
- Train machine learning models to predict survival:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Gradient Boosting  
- Generate predictions for the test dataset in Kaggle format.  

---

##  Tools & Libraries
- Python  
- Pandas & Numpy → Data preprocessing  
- Matplotlib & Seaborn → Data visualization  
- Scikit-learn → Machine learning  

---

##  Workflow
1. **Exploratory Data Analysis (EDA)**
   - Age distribution, survival by gender, class, and embarkation.  
   - Correlation heatmap to identify key features.  

2. **Data Preprocessing**
   - Fill missing ages with median.  
   - Fill missing Embarked values with mode.  
   - Drop irrelevant columns (Cabin, Ticket, Name).  
   - Encode categorical variables (Sex, Embarked).  

3. **Model Building**
   - Train/test split.  
   - Logistic Regression, Decision Tree, Random Forest, Gradient Boosting.  
   - Evaluate performance using accuracy score.  

4. **Prediction**
   - Predict survival on the test dataset.  
   - Save predictions in Kaggle submission format.  

---

##  Example Insights
- **Gender**: Females had much higher survival rates than males.  
- **Class**: Passengers in 1st class survived more than those in 3rd class.  
- **Age**: Younger passengers had slightly better survival chances.  

---

##  Dataset
The Titanic dataset is publicly available on [Kaggle](https://www.kaggle.com/competitions/titanic).  

