# SyrialTech_Project
SYRIATEL PREDICTIVE ANALYSIS OF CUSTOMER CHURN
Business Understanding
 
Introduction
   
SyriaTel, a telecom company based in Damascus, faces a significant challenge in reducing customer churn, which can have a negative impact on its revenue and overall profitability. Customer churn refers to when customers cancel their subscriptions, often moving to competitors or discontinuing the service altogether. Poor service and customer support are major reasons for churn. Additionally, the ease of switching providers and encountering unsatisfactory experiences, like needing multiple contacts for issue resolution, also contribute to churn rates. It's crucial for SyriaTel to focus on improving service quality and enhancing customer satisfaction to reduce churn effectively.

Business stakeholder

The main player in this project is SyriaTel, a telecom company located in Damascus, Syria. Their main focus is on grasping the patterns and causes behind customer churn. By deeply understanding why customers depart, SyriaTel can implement proactive strategies to keep them. This involves enhancing service quality, improving customer support, and providing personalized solutions to meet customer demands. Utilizing insights from data analysis, SyriaTel can make well-informed decisions, customize services, and efficiently allocate resources to decrease churn. This proactive approach not only boosts customer satisfaction but also saves money by reducing revenue loss from customers ending their services.

Main Objective

The primary goal of this project is to create a predictive model that helps SyriaTel Telecommunication company identify whether there are consistent patterns associated with customer churn.

Experimental Design

This outlines the processes to be undertaken in this project. They are:
Data Understanding
Data Cleaning
Exploratory Data Analysis
Data Preparation
Modelling
Evaluation
Conclusion
2. Data Understanding

2.1. Data Description

The data used for this project was obtained from Kaggle. It consists of 3333 entries and 21 columns, providing details such as state, account duration, area code, phone number, international plan, voicemail plan, voicemail message count, and various call-related metrics including daytime, evening, and nighttime minutes, calls, and charges. Additionally, it includes information on international calls and charges, customer service calls, and churn status.

The dataset includes key factors necessary for analyzing customer behavior and predicting churn for SyriaTel Company. Important attributes like customer subscriptions (e.g., international plans, voicemail plans) and call usage statistics (e.g., total day minutes, total night minutes) are available. The 'Churn' column serves as the target variable, distinguishing between customers who have discontinued service ('True') and those who haven't ('False'). With this comprehensive dataset, it's possible to develop a predictive model to accurately pinpoint churn risks and implement targeted retention tactics, aligning with the project's aim of reducing customer churn effectively.

Data cleaning was necessary to prepare the dataset for thorough and precise exploratory analysis. This step ensures that the data is dependable, consistent, complete, and free from errors, setting a solid foundation for further analysis.

Univariate analysis was conducted to predict customer churn based on the binary target variable "churn." This involved assessing the distribution of churn within the dataset to determine if it's balanced. Out of the 3,333 customers, approximately 14.5% (483) have churned from SyriaTel, indicating a notable loss. The distribution graph of churn illustrates an uneven distribution, with 85.5% of the data falling under the "False" class and 14.5% under the "True" class.





