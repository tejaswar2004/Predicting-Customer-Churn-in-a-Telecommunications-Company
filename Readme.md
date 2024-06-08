# [1] Predicting Customer Churn in a Telecommunications Company

Introduction

Customer attrition is one of the biggest expenditures of any organization. Customer churn otherwise known as customer attrition or customer turnover is the percentage of customers that stopped using your company's product or service within a specified timeframe.
For instance, if you began the year with 500 customers but later ended with 480 customers, the percentage of customers that left would be 4%. If we could figure out why a customer leaves and when they leave with reasonable accuracy, it would immensely help the organization to strategize their retention initiatives manifold.

In this project, the aim is to find the likelihood of a customer leaving the organization, the key indicators of churn as well as the retention strategies that can be implemented to avert this problem.

# [2] Data Understanding

The data for this project is in a csv format. The following describes the columns present in the data.

Gender -- Whether the customer is a male or a female

SeniorCitizen -- Whether a customer is a senior citizen or not

Partner -- Whether the customer has a partner or not (Yes, No)

Dependents -- Whether the customer has dependents or not (Yes, No)

Tenure -- Number of months the customer has stayed with the company

Phone Service -- Whether the customer has a phone service or not (Yes, No)

MultipleLines -- Whether the customer has multiple lines or not

InternetService -- Customer's internet service provider (DSL, Fiber Optic, No)

OnlineSecurity -- Whether the customer has online security or not (Yes, No, No Internet)

OnlineBackup -- Whether the customer has online backup or not (Yes, No, No Internet)

DeviceProtection -- Whether the customer has device protection or not (Yes, No, No internet service)

TechSupport -- Whether the customer has tech support or not (Yes, No, No internet)

StreamingTV -- Whether the customer has streaming TV or not (Yes, No, No internet service)

StreamingMovies -- Whether the customer has streaming movies or not (Yes, No, No Internet service)

Contract -- The contract term of the customer (Month-to-Month, One year, Two year)

PaperlessBilling -- Whether the customer has paperless billing or not (Yes, No)

Payment Method -- The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))

MonthlyCharges -- The amount charged to the customer monthly

TotalCharges -- The total amount charged to the customer

Churn -- Whether the customer churned or not (Yes or No)

Instructions

The task is to understand the data and prepare it for model building. The analysis or methods should incorporate the following steps.

Hypothesis formation and Data Processing - Importing the relevant libraries and modules, Cleaning of Data, Check data types, Encoding Data labels etc.

Data Evaluation -- Perform bivariate and multivariate analysis, EDA

Useful resources [ Exploratory Data Analysis: Univariate, Bivariate, and Multivariate Analysis , Univariate, Bivariate and Multivariate Analysis , Exploratory Data Analysis (EDA) Using Python]

Build & Select Model -- Train Model on dataset and select the best performing model.

Evaluate your chosen Model.

Model Improvement.

Future Predictions.

Key Insights and Conclusion.

Upon completion of the project, I'll write a blog post on my thought process on medium, LinkedIn, personal blog, or any other suitable blogging site.

# [3] Important Libraries
The following libraries shall be used in this project:

1. numpy
- NumPy is a Python library for numerical computations. It is widely used for scientific computing, data analysis, and machine learning.
2. pandas
- Pandas is a Python library that provides data structures and tools for data manipulation and analysis. It is commonly used for data wrangling and cleaning, and exploratory data analysis.
3. sklearn
- Scikit-learn (or sklearn) is a Python library for machine learning that provides tools for classification, regression, clustering, and dimensionality reduction, as well as for evaluating and tuning models. It offers a consistent API, handles various types of input data, and integrates well with other Python libraries such as NumPy, pandas, and matplotlib.
4. matplotlib
- Matplotlib is a Python library for creating static, animated, and interactive visualizations in Python. It provides a wide variety of plotting functions for creating line plots, scatter plots, bar plots, histograms, heatmaps, and more, and allows for customization of the style, labels, and axes of plots.
5. seaborn
-Seaborn is a Python library for creating statistical visualizations built on top of Matplotlib. It provides a high-level interface for creating informative and attractive statistical graphics such as heatmaps, scatter plots, line plots, bar plots, and distribution plots. It is commonly used for exploratory data analysis and data visualization.

# [4] Getting the Data
We shall use one csv file called WA_Fn-UseC_-Telco-Customer-Churn.csv in this project

# [5] Data Cleaning
See if there are any missing values in WA_Fn-UseC_-Telco-Customer-Churn.csv in this project
Check for duplicates in the dataset

# [6] Transformation and Feature Engineering
Check the data types of the TotalCharges and MonthlyCharges columns in the df_telco_cust dataframe


# Done By
Lingareddy Tejaswar Reddy
