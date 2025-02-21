# Churn-and-Customer-Risk-Analysis-Dashboard



## Table of Contents 

- [Project Objective](#project-objective)
- [Dataset Used](#dataset-used)
- [Questions (KPIs)](#questions-(KPIs))
- [Dashboard Link](#dashboard-link)
- [Steps Followed](#steps-followed)
- [Dashboard](#dashboard)
- [Project Insights](#project-insights)
- [Answered Calls](#answered-calls)
- [Resolved calls](#resolved-calls)
- [Average Speed of Answer](#average-speed-of-answer)
- [Average Customer Satisfaction](#average-customer-satisfaction)
- [Agent Statistics](#agent-statistics)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)


## Project Objective


The objective of this project is to create an advanced customer retention dashboard for the telecom company that enables the identification of at-risk customers before contract termination occurs. This dashboard will utilize predictive analytics and data visualization techniques to provide actionable insights into customer behavior, engagement patterns, and potential churn indicators. By moving away from the current reactive approach, the goal is to empower the retention department with the tools to proactively engage with customers, enhance retention efforts, and reduce churn rates. The dashboard will be designed with clarity and ease of use in mind, ensuring it is self-explanatory for management and provides a comprehensive overview of customer retention metrics, ultimately contributing to better decision-making and more effective retention strategies.


## Dataset used


- <a href = "https://github.com/tonyvolen/Churn-and-Customer-Risk-Analysis-Dashboard/blob/main/02%20Churn-Dataset.xlsx">Dataset</a>

## Questions (KPIs)




- What is the total number of customers?
- What is the total number of customers at risk?
- What is the churn rate?
- What is the total number of tech tickets?
- What is the total number of admin tickets?
- What is the total yearly and monthly charges?
- What is the total percentage of male and female customers?
- What is the percentage of senior citizen customers?
- What is the percentage of customers with partners?
- What is the percentage of customers with dependents?
- What is the percentage of customers in each payment method?
- What is the percentage of customers using paperless billing?
- What is the percentage of customers in each contract type?
- What is the percentage of customers signed up for each service?
- What is the total number of customers in each internet service?
- What is the sum of monthly charges in each internet service?
- What is the churn rate by contract type?
- What is the churn rate by payment method?



  ## Dashboard Link


- <a href = "https://github.com/tonyvolen/Churn-and-Customer-Risk-Analysis-Dashboard/blob/main/churn%201.pbix">View Dashboard</a>


## Steps Followed


- Load data into Power BI Desktop, dataset is a csv file.
- Verified data for any missing values and anomalies and sort out the same.
- Made sure data is  consistent and clean with respect to data types , data format and values used.
- Used DAX to create calculated measures for KPIs such as Total number of answered customers, Total yearly charges,Total number of tech tickets and churn rate.
- Visual filters (Slicers) were added for four fields named "Risk of churn", "Internet service", "Months subscribed" and "Contract type".
- In the Report view, I selected and customized appropriate visualizations from the Visualizations pane to effectively represent the KPIs. This process involved tailoring each visualization to accurately display the data, ensuring clarity and alignment with the project's objectives
  



  ## Dashboard


![Churn dashboard](https://github.com/user-attachments/assets/acfd0146-a045-4db9-8ff1-60b4a91a584f)






![customer risk analysis dashboard](https://github.com/user-attachments/assets/071c1105-8874-4f77-b101-84d75b51faf1)






## Project Insights 

### 1. Churn Analysis


#### customers at risk



To gain a clearer understanding of the current customer landscape, I used a visual card to summarize key metrics related to customers who are at risk of churn. The data revealed the following insights:



- Total Number of At-Risk Customers:
  
There are 1,869 customers identified as being at risk of churn. These are customers who exhibit signs of potential termination based on historical behavior patterns or predictive modeling.

A snapshot of total number of at-risk customers.


![customers at risk](https://github.com/user-attachments/assets/cddbd0c0-7189-4792-98bc-8f2847a90a73)


- Total Tech Support Tickets:

  These at-risk customers have generated 2,173 tech support tickets, highlighting potential service or technical issues that may be contributing to their dissatisfaction.

A snapshot of total tech support tickets 


![number of tech tickets](https://github.com/user-attachments/assets/2bf66ea0-d0e4-4199-9d40-2716f707d58f)


- Total Admin Support Tickets:
  
 Additionally, there are 885 admin support tickets raised by these at-risk customers, which could point to issues related to billing, account management, or service terms.

A snapshot of total admin support tickets 


![admin tickets](https://github.com/user-attachments/assets/356ea535-f7fc-4896-aec8-7f0adc69f04d)



- Yearly Charges:
  
 The total yearly charges for these at-risk customers amount to $2.86 million. This reflects the total revenue generated from this segment, which emphasizes the significant impact that losing these customers could have on the company's bottom line.

A snapshot of the yearly charges


![yearly charges](https://github.com/user-attachments/assets/d5b1f28d-5f1b-4f4e-b073-4f3e5e11de79)



- Monthly Charges:
  
The monthly charges from these customers total $139.13k, providing a sense of the recurring revenue at risk if retention efforts are not prioritized.

A snapshot of the monthly charges


![monthly charges](https://github.com/user-attachments/assets/a7dca9a3-4a2e-42e2-8d26-2f740ae9f5ec)






#### At-risk Customer's Demegraphics


Analyzing the demographics of customers who are at risk of churn reveals that the customer base is nearly evenly split, with 49.8% male and 50.2% female customers. Approximately 25% of these customers are senior citizens, indicating a significant portion of the at-risk group is in the senior demographic. Additionally, 36% have partners, suggesting that a substantial segment of this group is in relationship, and 17% have dependents, highlighting that a substantial segment of this group has additional family responsibilities.

A snapshot of at-risk customers demograghics


![customers demoghraphics](https://github.com/user-attachments/assets/7b30773f-38ac-4c69-83e8-d73235f06f22)


####  Subscription Time


Analyzing the subscription durations of customers who are at risk of churn revealed that 53.45% of at-risk customers have been subscribed for less than a year, 16.53% have subscriptions under two years,10.33% have been with the service for less than three years, 7.81% have subscriptions under four years,6.58% have been subscribed for less than five years, 4.98% have subscriptions under six years, 0.32% have been with the service for less than seven years.

This distribution indicates that a significant portion of at-risk customers have relatively short subscription tenures, with over half (53.45%) having been subscribed for less than a year.


A snapshot of subscription time 


![subscription time ](https://github.com/user-attachments/assets/bdc8695e-95db-486d-8afa-05f7ae2699c3)



#### Customer Account Information



Upon analyzing the payment methods of customers identified as at risk of churn, it was observed that a significant portion utilizes electronic checks, accounting for 57.30% of the at-risk customer base. Mailed checks are used by 16.48% of these customers, while 13.80% prefer bank transfers. Credit card payments are the least common among this group, comprising 12.41% of the at-risk customers.This distribution suggests that electronic checks and mailed checks are the predominant payment methods among at-risk customers

A snapshot of Payment method 


![payment method](https://github.com/user-attachments/assets/3470bb31-3e76-44dd-9727-6ebc0893bbc8)



Upon analyzing the billing preferences of customers who are at risk of churn, it was found that a significant majority, 75%, have opted for paperless billing. This indicates a strong preference for electronic billing among this group. Conversely, 25% of at-risk customers continue to receive traditional paper bills.
The high adoption rate of paperless billing among at-risk customers suggests that electronic billing is a common practice within this segment.

A snapshot of paperless billing

![paperless billing](https://github.com/user-attachments/assets/43aaab31-8d71-48d7-b28a-b138d993326d)


Upon analyzing the contract types of customers at risk of churn, it was observed that a substantial majority, 88.55%, are on month-to-month contracts. A smaller segment, 8.88%, have one-year contracts, while the remaining 2.57% are committed to two-year contracts.
This distribution indicates that the majority of at-risk customers are on flexible, short-term agreements, which may contribute to their higher likelihood of churn. In contrast, customers with longer-term contracts, such as one or two years, often exhibit lower churn rates due to the commitment involved.

 A snapshot of contract type


![contract type](https://github.com/user-attachments/assets/5bfdfcde-8aa0-474f-b917-33ba34c2ed17)



#### Services Customers Signed up For









###  Agent Statistics


I analyzed agent performance statistics and found the following:

- Call Handling: Jim answered the highest number of calls at 536, while Steward answered the fewest at 477.

- Call Resolution: Jim also led in resolved calls with 485, whereas Steward had the lowest at 424.

- Customer Satisfaction: Martha achieved the highest average satisfaction rating of 3.47, while Joe had the lowest at 3.33.

- Response Time: Joe had the highest average speed of answer at 70.99 seconds, while Becky had the lowest average speed of answer at 65.33 seconds.

These findings highlight variations in agent performance across key metrics, indicating areas for potential improvement in call handling efficiency and customer satisfaction.

A snapshot of Agent Statistics


![Agent Statistics](https://github.com/user-attachments/assets/8e2cf4e6-2536-4395-90c1-10fda0925526)




## Conclusion


The analysis of the customer service team's performance has provided valuable insights into key operational metrics. While certain agents, such as Jim, demonstrated high call handling and resolution rates, others, like Steward, exhibited lower performance in these areas. Additionally, the average customer satisfaction score of 3.40 fell short of the target of 4.50, indicating a need for improvement in service quality. The variation in average speed of answer among agents further highlights inconsistencies in response times. 


## Recommendations


1. Implement tools such as Interactive Voice Response (IVR) systems to streamline call routing and reduce wait times, enhancing customer experience. 

2. Offer regular performance reviews and constructive feedback to agents, coupled with coaching sessions to support their professional development. 

3. Establish achievable targets for agents, allowing flexibility to accommodate varying workloads and reduce stress, thereby improving overall performance. 

4.  Develop and promote self-service channels, such as online FAQs and chatbots, to empower customers and reduce call volumes, allowing agents to focus on more complex inquiries.

5. Continuously track metrics like average handle time, first call resolution, and customer satisfaction scores to identify areas for improvement.
