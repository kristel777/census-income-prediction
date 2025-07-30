# Census Income Prediction (Logistic Regression)

## Project Overview
This project applies **Logistic Regression** to the 1994 Census dataset in order to predict whether an individual’s income exceeds **$50K per year**. The dataset contains demographic and work-related features such as age, education, occupation, and hours worked per week.  

The project follows the full **machine learning life cycle**:  
- Data preprocessing and cleaning  
- Exploratory Data Analysis (EDA)  
- Feature engineering and scaling  
- Model training and evaluation  
- Improving model performance  

---

## Dataset
- **Source**: 1994 U.S. Census dataset (`censusData.csv`)  
- **Target Variable**: `income` (`<=50K` or `>50K`)  
- **Features**: Age, Workclass, Education, Marital Status, Occupation, Relationship, Race, Sex, Hours per week, Native country, etc.  

---

## Methods & Tools
- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Model**: Logistic Regression  

---

##  Results
- Logistic Regression was able to classify income groups with good accuracy.  
- Evaluation metrics included **accuracy, precision, recall, and F1-score**.  
- Insights: Education level, hours per week, and occupation were among the most influential features for predicting income.  




