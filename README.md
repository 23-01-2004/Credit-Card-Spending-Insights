# Income Prediction – Exploratory Data Analysis (EDA) 

## 📌 Problem Statement  
In this dataset, we have demographic and employment data of individuals,  
including details such as age, education, occupation, and marital status,  
among other features. The income level of these individuals is influenced  
by various personal and work-related factors. Understanding these factors  
is crucial for better decision-making, particularly for policy-making,  
financial services, and targeted interventions aimed at improving financial well-being.

---

##  Dataset  
This EDA used a credit card data to predict a customer's income is > $50K vs. <= $50K. The dataset includes critical fields such as:

| **Category**               | **Feature**         | **Description**  |
|----------------------------|---------------------|------------------------------------------------|
| **Customer Demographics**  | `age`              | Age of the individual. |
|                            | `sex`              | Gender (Male, Female). |
|                            | `race`             | Race of the customer (e.g., White, Black, Asian). |
|                            | `native-country`   | Country (Origin). |
| **Education & Employment** | `education`        | Highest level of education (e.g., Bachelors, HS-grad). |
|                            | `education-num`    | Education level. |
|                            | `workclass`        | Type of work (e.g., Private, Government, Self-Employed). |
|                            | `occupation`       | Occupation category (e.g., Exec-managerial, Craft-repair). |
|                            | `hours-per-week`   | Number of hours worked per week. |
| **Financial Information**  | `capital-gain`     | Income gained from capital returns. |
|                            | `capital-loss`     | Losses from capital investments. |
| **Income**                 | `income`           | Binary target variable directing whether income is >$50K or <=$50K per year. |
| **Household & Social Status** | `marital-status` | Marital status (e.g., Married, Never-married, Divorced). |
|                            | `relationship`     | Relationship status within a family (e.g., Husband, Wife, Not-in-family). |
| **Additional Information** | `fnlwgt`           | Final sample weight, indicating how many customers it represents. |

---

##  Methodology  

### Data Collection  
- A sample dataset, **CreditCard.csv** for performing **Exploratory Data Analysis (EDA)** applying all the **Univariate, Bivariate, and Multivariate Analysis** methods.  

### Data Preparation  
- A brief conclusion of the dataset was taken.  
- Missing values were treated correctly.  
- Duplicate values are removed.  
- Data conversion to convert to categorical data.  

---

##  Exploratory Data Analysis  

###  Univariate Analysis (Single Variable)  
- Visualization of every feature and how they are affecting my specific problem along with the target feature.  

###  Bivariate Analysis (Two Variables)  
- Checked the relationship between the target variable and each numerical and categorical variable.  

###  Multivariate Analysis (Multiple Variables)  
- Features with the highest correlation with the target variable are taken and the relationship between multiple features and the target feature are observed.  

---

##  Tools Used  
- **Python** (Pandas, Matplotlib, Seaborn, NumPy, scikit-learn) for data manipulation, visualization, and statistical analysis.  
