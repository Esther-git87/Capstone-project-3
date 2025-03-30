## Capstone-project-3

##NYC Collision Analysis Report
---

![](https://github.com/Esther-git87/Capstone-project-3/blob/main/Collisionimage.PNG)
---


##Introduction:
---

The **NYC Collision** dataset contains motor vehicle collision reports recorded by the New York City Police Department from January to August 2020. The dataset includes details on accident locations, time, contributing factors, and accident severity. This analysis aims to identify trends and insights to improve traffic safety and reduce accident occurrences.



##Problem Statements
---
1.	What are the seasonal patterns in total accidents by month?

2.	When do accidents occur most frequently (day of the week and time of day)?

3.	Which street has the highest number of reported accidents? What percentage of total accidents does this represent?

4.	What is the most common contributing factor for accidents? What about fatal accidents specifically?



##Skills/ Concepts Demonstrated
---


the following power BI features were incorparated:

-DAX,

-Quick measures,

-Modelling,

-Filter,

-Tooltips,

-Button,

-Page navigation


##Modelling:
---

The Model is a star schema,
there are 2-dimension tables and a fact table and the dimension tables are all joined to the fact table with one-to-many relationship.

![](https://github.com/Esther-git87/Capstone-project-3/blob/main/Nyccollisionmodelling.PNG)



##Visualization
---

The Report comprises of 2 pages
1. The Accident's frequency
2. Top streets


Feature

the two tabs are button with hovering effect and each navigates to the page with similar name.


###Analysis
---

1. Monthly Accident Trends & Seasonal Patterns

•	The percentage of total accidents remains relatively stable across months, with a slight decline in certain months.

•	There are no extreme seasonal fluctuations in accident rates.

 Accident Frequency by Day and Time

•	Most accidents occur on Fridays, followed by Thursdays and Wednesdays.

•	Accidents peak between 12:00 PM and 6:00 PM, with another noticeable rise around 6:30 PM.

•	The lowest accident occurrences happen between midnight and early morning hours (12:00 AM - 6:00 AM).

![](https://github.com/Esther-git87/Capstone-project-3/blob/main/NYC%20Pg%201.png)
---



2. Streets with the Most Accidents

•	Belt Parkway has the highest number of reported accidents.

•	The accidents on this street account for a significant percentage of all reported incidents.

 Contributing Factors for Accidents

•	The most common contributing factor for all accidents is Driver Inattention/Distraction.

•	For fatal accidents, the top contributing factors include Unsafe Speed, Failure to Yield Right-of-Way, and Improper Lane Changes.

![](https://github.com/Esther-git87/Capstone-project-3/blob/main/Nys%20pg%202.png)
---


##Conclusion:

This analysis highlights accident trends, peak risk periods, and key contributing factors in NYC. Addressing these insights with strategic measures can significantly enhance road safety and reduce collision occurrences in the city.


##Recommendation:

1.	Enhance road safety measures on high-accident streets like Belt Parkway.

2.	Implement public awareness campaigns targeting driver inattention and speeding.

3.	Increase law enforcement presence during peak accident hours.

4.	Consider improved traffic control mechanisms to manage high-risk intersections.


