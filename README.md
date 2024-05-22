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

A lot of techniques were used for analysis including; both univariate and multivariate analysis, train-test splitting, K-Nearest Neighbors (KNN), Decision Trees, Random Forest Classifier, and mainly classification.

EVALUATION

Best Overal Model

Among the various models tested, including Logistic Regression, K-Nearest Neighbors (KNN), Decision Trees, Random Forest Classifier, and XGBoost, the XGBoost model emerged as the top performer overall. It achieved the highest accuracy, with a test accuracy of 91.97% and training accuracy of 95.64%. Additionally, based on the Test ROC and AUC score, which assesses the model's ability to differentiate between positive and negative outcomes, XGBoost achieved a score of 90%, further confirming its effectiveness.

The top five features crucial for determining customer churn were identified as follows:

Customer Service Calls: The number of calls made to customer service by a customer.

Total Day Minutes: The total duration of daytime calls made by the customer.

Number of Voicemail Messages: The count of voicemail messages left by the customer.

Total Evening Minutes: The total duration of calls made during the evening by the customer.

Total International Calls: The total number of international calls made by the customer.

Regarding the objectives:

The main objective was achieved by developing multiple predictive models and selecting the best-performing one, XGBoost, for effectively predicting customer churn patterns.

Specific goals, such as identifying key factors influencing churn and evaluating classifiers using various metrics, were successfully met.

Actionable recommendations based on the analysis were provided.

Overall, all objectives were fulfilled.

CONCLUSION
   
RECOMMENDATIONS

Improve Customer Service: Enhance various aspects such as reducing wait times and increasing overall customer satisfaction.

Provide Tailored and Affordable Call Plans: Offer personalized and cost-effective plans for both daytime and nighttime usage.

Prioritize Service Quality: Continuously monitor metrics like network reliability, call quality, and data speed, investing in infrastructure upgrades when necessary.

Ensure Transparent Pricing: Implement clear pricing structures and billing processes to prevent disputes and improve customer satisfaction.

Proactive Customer Engagement: Regularly communicate with customers to gather feedback, address concerns, and offer assistance to prevent churn.

Strengthen Security Measures: Implement robust protocols to protect voicemail messages and ensure customer privacy and data security.

Expand International Plan Options: Offer a wide range of countries covered by international plans to meet diverse customer needs.

Conduct Regular Churn Analysis: Analyze customer churn patterns and trends regularly to inform proactive retention strategies.

NEXT STEPS:

Deploy the Model: Integrate the churn prediction model into the operational system to provide real-time predictions on customer churn, enabling proactive retention strategies.

Monitor and Update the Model: Continuously monitor the model's performance and accuracy, regularly updating it with new data to ensure it effectively predicts churn over time.

Interpret Model Insights: Analyze the model's predictions to identify the main drivers of customer churn, providing valuable insights for targeted retention efforts and strategic decision-making.

Diversify Data: Expand the dataset by collecting a wider range of customer attributes, behaviors, and interactions to enhance the model's predictive capabilities and capture more nuanced churn patterns.










