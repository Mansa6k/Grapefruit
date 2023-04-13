# # Telecom customer churn prediction

## Overview
In this project, the goal is to predict customer churn for a telecom company using advanced data analysis and machine learning techniques. By accurately identifying at-risk customers, targeted retention strategies can be implemented, enhancing customer satisfaction and boosting revenue.

# Visualizations

# * Proportion of churned and retained customers 

<img width="999" alt="contract x churn" src="https://user-images.githubusercontent.com/118853744/231636002-ab43b7ba-d71f-4d91-8a0d-2ba81bfa03b7.png">

* Customers with month-to-month contracts have the highest churn rate, while those with two-year contracts have the lowest churn rate.


<img width="999" alt="paymentmethod x churn" src="https://user-images.githubusercontent.com/118853744/231636326-925d3bac-beae-4295-b0f7-a7d48cd15a4c.png">

* Customers using electronic check payments have the highest churn rate, while those using credit card (automatic) payments have the lowest churn rate.


<img width="1001" alt="tech x churn" src="https://user-images.githubusercontent.com/118853744/231636503-a90e46e7-cc05-480c-8a37-af1b70487024.png">

* Customers without tech support have the highest churn rate, while those with no internet service have the lowest churn rate.


<img width="994" alt="internet x churn" src="https://user-images.githubusercontent.com/118853744/231636614-42ce5212-ce2b-4b7e-be29-a02e567dbffc.png">

* Customers with Fiber optic service have the highest churn rate, followed by those with DSL service.

# * Segmentation showing the relationship between tenure and MonthlyCharges
![bokeh_plot](https://user-images.githubusercontent.com/118853744/231637821-ca386e20-e325-479c-adbe-de90ca6e5f25.png)

* Segment 0 has high monthly charges and long tenure, which may indicate high-value customers who are willing to pay more for the service and have been loyal to the company for a longer time.

* Segment 1 has low monthly charges and short tenure, which may indicate that these customers are not as valuable to the company and may be more likely to churn.

* Segment 2 has high monthly charges but short tenure, which may indicate that these customers are not fully satisfied with the service and may be at a higher risk of churning.

* Segment 3 has low monthly charges and long tenure, which may indicate customers who have been loyal to the company for a long time despite lower pricing.

# Model performance comparison
<img width="812" alt="report" src="https://user-images.githubusercontent.com/118853744/231640832-b5f644de-f795-4146-a1a6-656aad96099f.png">

* The Random Forest model performs better in predicting customer churn compared to the Logistic Regression model. It has higher precision, better recall for the 'Yes' class, and a higher F1-score. Random Forest models are generally more robust and can capture complex interactions between features, making it a more suitable choice for predicting churn in this case.

## Technologies
The following technologies were used in this project:
- Python
- pandas
- scikit-learn
- imbalanced-learn
- Matplotlib
- Seaborn
- hvplot
- warning
- pathlib 

# Installation Guide

 pip install pandas

 pip install scikit-learn

pip install imbalanced-learn

 pip install Matplotlib

pip install Seaborn

pip install hvplot

pip install warning

pip install pathlib 

# Usage 
To run this project, simply clone the repository to your local machine and run the jupyter notebook file named "Fresh2.ipynb".

# License 
This project is licensed under the MIT license.

# Contributor 
Andre Johnson
