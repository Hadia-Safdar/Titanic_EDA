# Titanic Dataset EDA

This project contains an Exploratory Data Analysis (EDA) performed on the Titanic dataset as part of my internship task.

## Dataset
- **File Used:** `train.csv` from the Titanic: Machine Learning from Disaster dataset (Kaggle).
- The dataset includes passenger details such as demographics, ticket information, and survival status.

## Steps Performed
1. **Data Import & Basic Exploration**
   - Loaded dataset and displayed initial records
   - Checked dataset shape and column details

2. **Missing Data Handling**
   - Dropped `Cabin` column due to high missing values
   - Filled missing `Age` with median values
   - Filled missing `Embarked` with mode

3. **Summary Statistics**
   - Descriptive statistics for numerical features
   - Data type inspection

4. **Univariate Analysis**
   - Count plots for `Survived`, `Sex`, `Pclass`, `Embarked`
   - Distribution plots for `Age` and `Fare`

5. **Bivariate Analysis**
   - Survival rate by Gender
   - Survival rate by Passenger Class

6. **Correlation Analysis**
   - Heatmap to show relationships between numerical variables

## Key Insights
- Females had a higher survival rate compared to males.
- Passengers in higher classes (1st class) had better chances of survival.
- Higher fare generally correlated with a higher probability of survival.

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn

---
**Author:** *Hadia Safdar*
