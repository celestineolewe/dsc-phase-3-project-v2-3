# SYRIALTEL CUSTOMER CHURN



**Authors**: Celestine A. Imelda

## Overview
We use the SyraTel cUstomer data to help in analyzing the possible causes of customer attrition. Customer churn can be caused by better deals from competitors, customer service issues and also customers personal preference. By identifying potential churners, Syria Tel can take proactive measures to retain customers and improve customer satisfaction.
## Business Problem

Syria Tel is experiencing a high rate of customer churn. Many customers are leaving the service for various reasons, impacting the company's revenue and market position. Syria Tel needs to identify potential churners and implement strategies to retain these customers and improve overall customer satisfaction

## Key Objectives
Reduce Churn Rate: The primary goal is to reduce the customer churn rate by predicting which customers are likely to leave and taking proactive measures to retain them.

Improve Customer Satisfaction: Understanding the factors contributing to churn will help Syria Tel make improvements in service quality, customer support, and pricing plans.

Increase Revenue: By retaining more customers, Syrian Tel can increase its revenue and market share.

I will use data science and machine learning techniques to build a predictive model that can identify potential churners. This model will analyze customer data and predict whether a customer is likely to churn or not. By doing so, Syrian Tel can take specific actions to retain these customers.

## Modelling

In this phase, we will build a model that can predict the customer churn based on the features in our dataset. The model will be evaluated on the recall score. Specifically, if it achieves an recall score of 80% or higher, it will be considered a success.

In order to achieve the targets stipulated in the project proposal, we will be using the following algorithms:

Logistic Regression
Decision Tree
Random Forest
XG Boost
We will also be using the ROC_AUCmetric to evaluate the performance of our models

To deal with class imbalance, we will be using SMOTE to generate synthetic examples of the minority class in our dataset

### Visual 1
![Alt text](image.png)
## Conclusions

In conclusion, Syria Tel faces a significant challenge with a high customer churn rate. To address this issue and improve overall business performance, several key recommendations have been identified:

Targeted Discounts: Offering discounts in area codes 415 and 510 can incentivize customers to stay with the company.

Enhanced Customer Service: Investing in improved customer service and reducing the number of service calls can lead to higher customer satisfaction and reduced churn.

Pricing Structure Evaluation: Evaluating pricing plans, especially for day, evening, night, and international charges, is essential to address concerns about high charges.

Customer Retention: Prioritizing customer retention strategies in states with high churn rates, such as Texas, New Jersey, Maryland, Miami, and New York, is crucial for reducing churn.

Voicemail Plan Enhancement: Improving the value proposition of voicemail plans and offering additional features or discounts can encourage higher adoption among customers.

Implementing these recommendations can help Syria Tel reduce churn, enhance customer satisfaction, and ultimately drive business growth and success.


## For More Information

Please review my full analysis in [[my Jupyter Notebook](./dsc-phase3-project.ipynb)](https://github.com/celestineolewe/dsc-phase-3-project-v2-3/blob/442756fc159fd2d43bb941705d692b0bab910588/presentation3.pdf) or our [presentation](./DS_Project_Presentation3.pdf).

For any additional questions, please contact **Celestine A. Imelda & celestineolewe@gmail.com **

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── __init__.py                         <- .py file that signals to python these folders contain packages
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase3-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation3.pdf         <- PDF version of project presentation
├── code
│   ├── __init__.py                     <- .py file that signals to python these folders contain packages
│   ├── visualizations.py               <- .py script to create finalized versions of visuals for project
│   ├── data_preparation.py             <- .py script used to pre-process and clean data
│   └── eda_notebook.ipynb              <- Notebook containing data exploration
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
