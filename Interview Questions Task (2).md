1. What is the purpose of EDA?
EDA (Exploratory Data Analysis) helps you:
Understand the structure and quality of your data
Detect patterns, trends, or anomalies
Spot missing or incorrect values
Form hypotheses and guide feature engineering
Choose the right machine learning models and preprocessing steps

2. How do boxplots help in understanding a dataset?
Boxplots:
Show central tendency (median)
Show spread (interquartile range)
Detect outliers
Help compare distributions across categories (e.g., Fare by Pclass)

3. What is correlation and why is it useful?
Correlation measures how two numeric variables move together.
Value ranges from -1 (perfect negative) to +1 (perfect positive)
0 means no linear relationship
It helps:
Detect relationships between features
Identify redundant features
Understand dependencies that may affect model accuracy

4. How do you detect skewness in data?
You can detect skewness by:
Histogram shape: if it's lopside
Skewness metric:
0: Right-skewed (tail on the right)
< 0: Left-skewed
Boxplots: asymmetric whiskers often indicate skew

5. What is multicollinearity?
Multicollinearity means two or more features are highly correlated.
Why it's a problem:
Inflates the variance of coefficients
Makes model interpretation difficult
May degrade performance in linear models

6. What tools do you use for EDA?
Common tools:
Python Libraries:
pandas, matplotlib, seaborn, plotly, sweetviz, pandas-profiling
Jupyter Notebook or Google Colab
R: ggplot2, dplyr 
Tableau / Power BI for business-facing analysis

7. Can you explain a time when EDA helped you find a problem?
Sure! Once while analyzing customer churn:
A column for "tenure" had zero values for many customers
Boxplot and histogram showed a spike at 0
Found a data logging issue — those users hadn’t activated yet
Fixing that changed the model's accuracy significantly

8. What is the role of visualization in ML?
Visualization helps:
Understand data structure & quality
Identify trends, patterns, and correlations
Communicate insights to non-technical stakeholders
Validate model outputs and assumptions