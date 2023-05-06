# Churn_pred

## Result
The best predictive algorithms turned out to be Random Forest and Gradient Boosting, with an accuracy of 93%, while K-Nearest Neighbors (KNN) was slightly worse with an accuracy of around 90%.

The most important features that can be inferred from the data are that customers are more likely to stay if they have a contract, a TV subscription, a movie package subscription, and use a reasonable amount of download (internet). These are the key factors for retention. 
## Recomendation
Therefore, my recommendation is to focus on these factors. For example, offer contracts with a predetermined term, such as 2 years, which include movie and TV subscriptions. This way, we have the highest chances of retaining our customers.

A common practice among competitors is to use a strategy that offers a free month for switching to their service, while signing the customer up for a 2-year contract. We may consider this option as a way to attract and retain customers.

## Clean Data
In the first part of the analysis, I cleaned the data by removing empty values and fixing null values in the 'remaining_contract' column. Additionally, I created a new 'is_contract' column to indicate whether a contract is active.
## EDA (Exploratory Data Analysis)
I conducted a preliminary analysis by creating various plots and looking for relationships among the data features.
## Modeling
In this step, I used data preprocessing techniques such as normalization, dimensionality reduction, and undersampling. I applied machine learning algorithms including K-Nearest Neighbors (KNN), Random Forest (RF), Gradient Boosting (GB), and Linear Regression. By comparing the quality of the results, I found that using dimensionality reduction led to much better outcomes, with an improvement of up to 30% in some cases.

Additionally, I identified the most highly correlated columns with churn, which have already been mentioned in the Results section. These insights help in understanding the key factors contributing to customer churn.

As for the machine learning algorithm results, the performance metrics (accuracy, precision, recall, and F1 score) for each algorithm can be found in the images at the bottom of the README. Based on these results, it's evident that Random Forest and Gradient Boosting algorithms performed the best, followed by K-Nearest Neighbors, while Linear Regression yielded less accurate predictions. These findings can guide future efforts to improve customer retention and prevent churn.
![Tableau result](https://github.com/Jkfre247/Churn_pred/blob/master/comparison_chart.png)
