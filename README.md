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


Upon analyzing the services subscribed to by customers identified as at risk of churn, it was found that a significant majority, 91%, have enrolled in phone services. Among these, half (50%) have opted for multiple lines, while the other half (50%) have single-line subscriptions. Additionally, 29% of at-risk customers have subscribed to device protection services, and 28% have chosen online backup services. Online security services are utilized by 16%, whereas 44% have subscribed to streaming movie services, and an equal percentage, 44%, have subscribed to streaming TV services. Tech support services are the least subscribed among this group, with 17% of at-risk customers availing themselves of this service.

This distribution indicates that the majority of at-risk customers are engaged with core services such as phone services, device protection, and online backup. The high subscription rates to streaming services suggest a strong preference for entertainment options among this group.

Additionally, i analyzed the internet service subscriptions of customers at risk of churn, it was found that a significant majority, 69%, have opted for fiber-optic internet services. This indicates a strong preference for high-speed, reliable internet connections among this group. In contrast, 25% have subscribed to DSL services, which offer more moderate speeds and are widely available in many areas, especially urban and suburban locations. A smaller segment, 6%, have not subscribed to any internet service, highlighting a potential area for engagement and service expansion.
The high adoption rate of fiber-optic internet among at-risk customers suggests that they value fast and reliable internet connections. 

A snapshot of services customers signed up for


![services customers signed up for](https://github.com/user-attachments/assets/eded87e2-211b-489a-ae27-7dbc099831e1)



###  2. Customer Risk Analysis


In analyzing the customer service metrics, the data revealed a total of 7,043 customers, with 2,955 technical support tickets and 3,682 administrative support tickets submitted. The annual charges for this group amounted to $16.06 million, and the churn rate was calculated at 27%.

The 27% churn rate suggests that approximately 27% of the at-risk customers have terminated their contracts within the analyzed timeframe. This rate is notably higher than the average churn rates observed in the telecommunications industry, which typically range from 11% to 22% 
The elevated churn rate among this segment underscores the urgency for implementing targeted retention strategies. By addressing the specific needs and concerns of these at-risk customers, the company can work towards reducing churn and enhancing customer loyalty.


A snapshot of churn rate


![churn rate](https://github.com/user-attachments/assets/67180915-c3c9-4b49-bec0-7e83cd273b57)




#### Churn by Internet Service

The churn analysis by internet service shows that fiber optic customers have the highest churn rate at 42%, followed by DSL at 19%, and “No internet” at just 7%. This suggests that, while fiber optic typically offers premium speeds and reliability, its higher cost or unmet service expectations may drive customers to switch providers. Meanwhile, DSL’s more moderate churn rate likely reflects a balance between affordability and acceptable performance. The minimal churn among customers with no internet service could stem from a simpler billing structure or fewer perceived alternatives, reducing their incentive to cancel or change services.


A snapshot of churn by internet service 



![churn by internet service](https://github.com/user-attachments/assets/c5a5288b-e684-4a60-b70c-249f070e36bb)




#### Number of Customers by Internet Service

The dashboard’s breakdown of customer distribution by internet service reveals that fiber optic has the highest number of customers at 3.1K, followed by DSL with 2.42K customers, while 1.53K customers have not subscribed to any internet service. The higher adoption of fiber optic services suggests that customers prioritize high-speed and reliable connectivity, making it a preferred choice despite potentially higher costs. In contrast, DSL still retains a substantial customer base, likely due to its affordability and availability in areas where fiber infrastructure is limited. The presence of a significant number of non-subscribers may indicate customers using alternative mobile or satellite internet solutions or those who do not require home internet services. Understanding these trends is crucial for the telecom provider to focus on retention strategies, upgrade incentives, and infrastructure investments that cater to the varying needs of different customer segments.


A snapshot of number of customers by internet service 



![No  of customers by internet service](https://github.com/user-attachments/assets/70cb2ba1-6172-4a74-b37e-cba678ae7f81)



#### Monthly Charges by Internet Service

The sum of monthly charges by internet service highlights that fiber optic customers contribute the highest revenue at $283.28K, followed by DSL users at $140.67K, while customers without an internet subscription generate $32.17K. This distribution suggests that fiber optic users typically subscribe to premium plans with higher costs, reflecting the value they place on speed and reliability. In contrast, DSL customers, who pay significantly less, may opt for budget-friendly plans due to either financial considerations or limited availability of high-speed alternatives. The lower revenue from non-internet subscribers indicates that they primarily rely on other telecom services, such as phone or TV, or may be minimal-service customers. These insights emphasize the importance of retaining high-value fiber subscribers while creating compelling upgrade incentives for DSL users to boost revenue further.


A snapshot of  sum of monthly charges by internet service

![Sum of monthly charges ](https://github.com/user-attachments/assets/24ffdf62-a23b-40b5-ae1d-430d23cedcf0)



#### churn Rate by Type of Contract

The churn analysis by contract type reveals that month-to-month subscribers, who number 3,875 experience a significantly high churn rate of 43%. This indicates that the lack of a binding commitment makes these customers more likely to switch providers in response to competitive offers, pricing changes, or dissatisfaction with service.
In contrast, one-year contracts, with approximately 1.5K customers, show a much lower churn rate of 11%, suggesting that even a modest commitment period can substantially enhance customer retention by reducing the ease of switching. The most striking performance is seen in the two-year contracts, which have 1.7K customers and an impressively low churn rate of just 3%. This low churn rate likely reflects the stability and security that longer-term contracts provide, as customers benefit from consistent pricing and service quality while incurring higher switching costs, thereby fostering long-term loyalty.


A snapshot of churn rate by contract type


![churn by type of contract](https://github.com/user-attachments/assets/40b2fd88-5173-4b4d-9e69-dd7ac8cefb90)


#### Churn by Years of Contract 

The churn rate decreases dramatically as the duration of the contract increases: customers with contracts lasting less than 1 year churn at a rate of 48%, which drops to 30% for contracts under 2 years, 22% for those under 3 years, 20% for contracts under 4 years, 15% for those under 5 years, 8% for contracts under 6 years, and finally just 2% for contracts under 7 years. This trend suggests that newer customers are more likely to leave as they are still evaluating the service or may be more sensitive to initial pricing and service issues, whereas long-term customers, having built a stronger relationship and incurred higher switching costs, tend to remain loyal, reflecting increased satisfaction and stability over time.


A snapshot of churn by years of contract 



![churn by years of contract](https://github.com/user-attachments/assets/3c58e65e-9635-428a-8121-77993dcf454a)



#### Churn by Payment Method

The churn analysis by payment method highlights that customers using electronic checks experience the highest churn rate at 45%, contributing $0.18M in monthly charges. In contrast, mailed check users have a significantly lower churn rate of 19% with $0.07M in monthly charges, while bank transfer (automatic) and credit card (automatic) payments show the lowest churn rates at 17% and 15%, respectively, each generating $0.10M in monthly charges.


The high churn rate among electronic check users suggests that these customers may prefer flexible or temporary payment arrangements and may not have automatic payments set up, making it easier for them to cancel services. On the other hand, customers using automatic payment methods, such as bank transfers or credit cards, likely experience lower churn due to the convenience and consistency of payments, reducing the likelihood of service disruption or reconsideration. This insight suggests that encouraging automatic payment setups could enhance customer retention by minimizing churn


 A snapshot of churn by payment method


![churn by payment method](https://github.com/user-attachments/assets/aa1512da-9b94-41f1-bbc5-13d8ca080c08)

 
## Conclusion


The churn analysis reveals that month-to-month contracts, electronic check payments, and fiber optic services contribute to higher churn due to flexibility, payment inconvenience, and service costs. In contrast, longer contracts, automatic payment methods, and affordable options like DSL or no internet reduce churn by providing stability and cost-effectiveness. To enhance retention, telecoms should promote long-term contracts, incentivize automatic payments, and carefully balance the pricing and quality of premium services 


## Recommendations


1.  Offer attractive incentives, such as discounts or added benefits, to encourage customers to opt for one- or two-year contracts instead of month-to-month plans, reducing the likelihood of churn.
2.  Provide discounts or loyalty rewards for customers who switch to automatic payment methods like bank transfers or credit cards, as these customers show lower churn rates compared to those using electronic checks.
3.  Since fiber optic customers have the highest churn rate, telecoms should assess pricing, improve service reliability, and introduce personalized retention offers to maintain customer satisfaction. 

4.  Use predictive analytics to identify customers at risk of churning, particularly those with short contracts or electronic check payments, and engage them early with personalized offers or support.

5.  Provide better guidance on contract benefits, payment options, and service features to improve customer satisfaction and reduce churn driven by misunderstandings or dissatisfaction with pricing and service expectations.


