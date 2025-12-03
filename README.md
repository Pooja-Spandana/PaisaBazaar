# PaisaBazaar Banking Fraud Analysis - EDA

### **_Problem Statement_**
In today’s financial landscape, accurate credit score assessment is vital for both financial institutions and customers. Paisabazaar, a financial services company, helps individuals find and apply for banking and credit products. A key aspect of their business involves assessing customers’ creditworthiness to provide personalized financial recommendations and ensure sound risk management practices. This case study focuses on analyzing, classifying, and predicting credit scores based on a range of customer data, such as income, credit card usage, and payment behavior. The goal is to help Paisabazaar improve their credit assessment processes, reduce loan defaults, and optimize customer services through better-informed decisions.

### **_Project Summary_**
- **Library Import:** Imported essential Python libraries for data manipulation, visualization, and analysis.
  - pandas, numpy for data handling
  - matplotlib, seaborn for visualization
    
- **Data Loading & Basic Inspection of Data:**
  - Loaded the dataset into a pandas DataFrame.
  - Took a comprehensive look at the dataset to understand its structure and content.
    1) Data Overview: Checking the shape of the dataset (number of rows and columns), data types, and non-null values for each feature.
    2) Duplicate and Missing Value Check: The analysis confirmed that there were no duplicate records or missing values in the dataset.
    3) Feature Analysis: This included performing descriptive analysis of each feature
  
- **Data Wrangling:**
  - Based on the insights gained performed data wrangling
  - Removed pure identifier columns
  - Fixed anomalies

- **Feature engineering:**
  - Handled missing categoried in features
  - Split numerical & categorical features
  
- **Exploratory Data Analysis:**
  - Used visual tools to gain deeper insights into the relationships between different variables. This included:
  - Univariate Analysis: Understood individual feature distribution & detected outliers. Handled outliers based on domain knowledge.
  - Bivariate Analysis: Compared features with target varible and other features
  - Multivariate Analysis: Examined the relationships and interactions between three variables simultaneously to uncover complex patterns and insights.
    
#### **_The project concluded by using these findings to provide recommendations for improving Paisabazaar's credit assessment processes._**
