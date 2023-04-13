## Statistical-Analysis-of-Diet-Types
In this project, we aim to develop a machine learning model to predict a user's diet type based on various features. With the growing trend of fitness application development and the increasing number of people adopting independent workout routines, there is a need for healthy nutrition plans to maintain overall well-being.

We utilized the Diet Recommendation dataset, which contains parameters such as age, height, weight, BMI, BMR, exercise lifestyle, and calories consumed, to determine the corresponding diet type. The paper conducts both parametric and non-parametric tests to analyze the dataset. One-way ANOVA analysis is used to estimate whether means are the same across multiple samples, and an ad hoc analysis is applied to identify which subset groups have different means. Additionally, the Chi-square test was performed to check the dependency between categorical features.

Finally, the best features are selected by using Fisher score and forward and backward elimination to fit the machine learning model. The AIC and BIC criteria are used for comparison purposes.

Our goal is to provide accurate and reliable recommendations that align with an individual's dietary preferences and goals. Utilizing statistical analysis and machine learning techniques, the findings indicate that the personalized diet advice system offers feasible and precise dietary recommendations based on the user's input data.

## Data
The Diet Recommendation dataset is used in this project, which contains parameters such as age, height, weight, BMI, BMR, exercise lifestyle, and calories consumed. The dataset is publicly available and can be accessed through the UCI Machine Learning Repository.

## Methodology
Our data analysis was conducted using various statistical methods to explore the relationship between our input and output variables. We began by performing exploratory data analysis, which involved visualizing and summarizing our data to gain insight into its underlying patterns and distribution. This process allowed us to identify any outliers, missing values, or other anomalies in our data set.

After exploring our data, we used non-parametric tests to determine if the means of our numeric input and categorical output variables were equivalent. We then used the chi-squared test of independence to examine the relationship between input and output categorical variables. To create a logistic regression model for predicting diet type, we utilized feature reduction techniques to select the best features for our model.

Finally, we tested the accuracy of our model on a separate test set and achieved an accuracy rate of 85.967%. The success of our analysis was due in large part to the use of exploratory data analysis, which helped us identify important trends and patterns in our data set and allowed us to develop a more accurate and reliable model.

## Conclusion
The personalized diet advice system developed in this research paper provides an effective solution for people looking to adopt a healthier lifestyle by guiding them towards dietary choices that align with their preferences and goals. By leveraging machine learning algorithms, the system provides accurate and personalized recommendations that can help individuals make informed decisions about their diet and overall health.
