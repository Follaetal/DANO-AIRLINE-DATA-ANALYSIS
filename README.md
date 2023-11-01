# DANO-AIRLINE-DATA-ANALYSIS
Analysis of passenger satisfaction for an airline
## Table of content
- Introduction
  - [Project Overview](#project-overview)
  - [Data Source](#data-source)
  - [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data analysis and Insights](#data-analysis)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Reference](#reference)

### Introduction
#### Project Overview
This Project is an analysis for Dano Airlines, a Uk-based airline headquartered in London, United Kingdom. The latest passenger survey results just came in and it looks
like the satisfaction rate dipped under 50% for the first time ever. Hence, the need to take actions to reverse the decline. The survey was done with the use of ratings from 1-5. This analysis aims to find the dissatisfactory services of the airline and recommend solutions so as to improve the services of the airline.

#### Data Source
This data was provided at the completion of the Data Analytics cohort.

#### Tools
- Power Query (Data loading and Data transformation)
- Power BI (Data Visualization)
  
### Data Preparation
- Data cleaning : This is an important step in order to ensure an accurate analysis in order to draw helpful insights. In this case, the data was loaded into Power query where null values in the ratings were replaced with 0 which is synonymous to being neutral or dissatisfied. The data types were also corrected. This data cleaning allowed us to see the structure of the data for better understanding.
- The data was loaded into the visualization tool, Microsoft Power BI which was used to visualize the sums, counts, average and other functions in order to properly analyse the data.
  
### Exploratory Data Analysis 
EDA aims to answer important questions in the dataset.
1. What are the factors that must have led or contributed to over 50% of the passengers being dissatisfied?
2. What are the strenghts and weaknesses of the airline?
3. Are natural factors such as age and gender to be considered as possible reasons for the problems encountered?
4. Which of the staff group contributes to the satisfaction rate?
  -Having explored the dataset, I was able to deduce some facts necessary to understand the situation of the airline. Firstly, 56.45k satisfied customers and 73.45k were neutral or dissatisfied. I also observed that the age of passengers could have contributed to the poor ratings. However, only 18.31% of the first time customers were satisfied. Generally, there are more returning customers than first time customers.

     ![power bi 1](https://github.com/Follaetal/DANO-AIRLINE-DATA-ANALYSIS/assets/148357576/c7890780-37b6-4ea5-b060-7aa86a40475e)
![power bi 2](https://github.com/Follaetal/DANO-AIRLINE-DATA-ANALYSIS/assets/148357576/43d1f101-4753-4abe-990a-4e20f855705f)

The EDA was based on the Gender, Age, Satisfaction count and Customer type of the airline.

Although the dissatisfaction rate is high, the airline has provided good services which include Seat comfort, Food and drinks and On-board service. 

### Data Analysis
With the use of Power BI, I was able to visualize the present situation of the airline. Over 50% of the passengers were neutral or dissatisfied with the services of the airline. The ratings are as follows:

![power bi 3](https://github.com/Follaetal/DANO-AIRLINE-DATA-ANALYSIS/assets/148357576/2747a7c7-661e-49ae-b4d1-b3a5623fedbd)

Based on this visualization, we observe the low ratings especially for in-flight Wi-Fi, Gate Location, Ease of Online boarding and Departure and Arrival Time Convenience. The ratings for Gata Location and Departure and Arrival Time Convenience could be linked to inconvenience caused by airport authorites and Technical problems from the airline. However, other low ratings can be linked to the flight crew and other staff group of the airline. 

 -For long flights, many passengers couldn't access the In-flight Wi-Fi probably due to various reasons; Low speed, unavailabilty or connection difficulty. This could have resulted in uncomfortable flight experiences as some passengers may need to stay active with work or they may need to be able to connect with their loved ones and give their flight updates and Wi-fi conributes to the entertainment experience of the passengers.

 -Ease of Online boarding is very necessary especially for local flights and the ratings could have been as a result of people missing their flights while trying to board late due to some issues. Difficulty in online boarding causes anxiety and sometimes, the queue to board for older age groups and people traveling in groups can turn out to be a hassle. 

 - The poor ratings Departure and Arrival Time convenience can be linked to frequent delays due to the airline's technical problems or the flight schedules. Over 50% of the passengers are in the business class and this schedule inconvenience could result in them missing meetings and opportunities.

 - Just as Online boarding caused poor ratings, so did Online booking. Booking flights at the airport is fast becoming archaic and the airline seems to have fallen short of the technical needs of the passengers. Online booking problems can be a major reason for the low number of first time customers as majority of passengers prefer to book fights well in advance in order to save cost or book comfortable seats.

   ### Recommendations
   Having understood the caues of the poor ratings, The airline must bear in mind that all their services need improvement especially the ones that guarantee safe and comfortablle fligt experiences for passengers, Fortunately, the data shows high percentage of loyal customer. The airline must firstly invest in marketing strategies to increase new customers. Howver, referrals influence most people to chose a service, hence, the need to invest in improved technical services both pre flight and on board.

   -Firstly, the airline must be conscious of schedule mangement. with the percentage of Buisness class passengers, the airline should alway bear the needs of their customers in mind by reducing the change in schedule and if need be, properly convey these inconvenient flight schedules to the passengers beforehand. Flight and Arrival schedules must also be dependent of natural and social factors like seasons, weather conditions and social events in order to guarantee the safety of passengers.
   - Gate location is a major cause of missed connecting flights. Therefore, the airline must properly communicate the gate location of all flights with emphasis on connecting flights in order to ensure seamless flight experiences.
   - In flight Wi-Fi must also be improved and if possible, outsourced so as to guarantee efficiency.
   - All flight crew members must be resensitized and possibly re-evaluated for excellent communication and service skills. This is necessary for exceptional on board service especially for First class and Business class travellers who constitute the majority of the passenger group. These services include entertainment and comfort needs. The food and drinks options too must be inclusive of dietary preferences and allergy options.
   - Availabilty of comfort services for older age groups, children, nursing mothers and people with diabilities (physical or mental) in order to ensure safe and comfortable flight experiences for all passengers.

  ### Limitations
  The limitations I faced in the project is the nature of the dataset. The numerical rations didn't include precise and specific complaints of the passengers that gave low ratings for each service. However, the domain knowlege helped me to gain insights through the available data and provide helpful solutions which will definitely increase satisfaction despite not knowing the complaints of each passenger.
    
### Reference
[Dataset](https://docs.google.com/spreadsheets/d/15Kp-2yfQFNRGJPNOkpMwG-OMX8xVZOJ5VL7f35v7sR)
