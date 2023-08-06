# Case_Study_Using_Advance_Sql


This session offers two case studies, each comprising 5 real-life SQL problems. These problem statements test various SQL concepts and demand resourcefulness and a structured approach for their solutions. In the next segment, you'll be introduced to the different problem statements available in the Supply Chain dataset.

## Case Study II – Supply Chain


1.“Get the number of orders by the Type of Transaction excluding the orders shipped from Sangli and Srinagar. Also, exclude the SUSPECTED_FRAUD cases based on the Order Status, and sort the result in descending order based on the number of orders.”

2.Get the list of the Top 3 customers based on the completed orders along with the following details:
•	Customer Id
•	Customer First Name
•	Customer City
•	Customer State
•	Number of completed orders
•	Total Sales

3.“Get the order count by the Shipping Mode and the Department Name. Consider departments with at least 40 closed/completed orders.”

4. Create a new field as shipment compliance based on Real_Shipping_Days and Scheduled_Shipping_Days. It should have the following values:
•	Cancelled shipment: If the Order Status is SUSPECTED_FRAUD or CANCELED
•	Within schedule: If shipped within the scheduled number of days 
•	On time: If shipped exactly as per schedule
•	Up to 2 days of delay: If shipped beyond schedule but delayed by 2 days
•	Beyond 2 days of delay: If shipped beyond schedule with a delay of more than 2 days
Which shipping mode was observed to have the highest number of delayed orders?”

5. “An order is canceled when the status of the order is either CANCELED or SUSPECTED_FRAUD. Obtain the list of states by the order cancellation% and sort them in the descending order of the cancellation%.
Definition: Cancellation% = Cancelled order / Total orders”

## Case Study II - Commodities' Prices

•	Determine the common commodities between the Top 10 costliest commodities of 2019 and 2020.

•	What is the maximum difference between the prices of a commodity at one place vs the other for the month of June 2021? Which commodity was it for?

•	Arrange the commodities in an order based on the number of variants in which they are available, with the highest one shown at the top, which is the third commodity in the list.

•	In a state with the least number of data points available, which commodity has the highest number of data points available?

•	What is the price variation of commodities for each city from January 2019 to December 2020? Which commodity has seen the highest price variation and in which city?



