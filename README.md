# FoodHubs-Project

# FoodHub Project
This is a project I did as a part of the MIT Data Science and Machine Learning Certification. The emphasis of this project is in utilizing data manipulation and visualization techniques such as numpy, pandas, matplotlib, and seaborn to analyze New York City restaurant orders. 

Conclusion and Recommendations:  There appears to be a noticeable trend in the types of restaurants customers prefer. many businesses may need to adjust their operations by taking into account factors such as cost, food preparation time, and delivery time, with special attention to differences between weekends and weekdays.
 
Targeted Promotion for Higher Cost items
-Items that cost $20 or more generate 25% of the revenue.
-Identify high-cost, fast-delivery items that already receive the highest ratings. 
-Create combo meals or premium bundles priced above $20 that would encourage larger purchases.

Streamline Delivery Operations:
-The data shows that weekday delivery times average 28.3 minutes vs 22.47 minutes on weekends. 
-Hire more delivery staff or optimize delivery routes, especially for weekdays, to reduce wait times and enhance customer experience.
-Use demand forecasting to anticipate periods with high demands and allocate resources accordingly.

Changes in Thai Cuisine 
-Average Cost of Order and  average food preparation time are both high for Thai food compared to others.
-Negotiate better prices with supplier or change lead times for food delivery to reduce logistic costs.

Description
Context
The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.

The app allows the restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants.

Objective
The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Suppose you are hired as a Data Scientist in this company and the Data Science team has shared some of the key questions that need to be answered. Perform the data analysis to find answers to these questions that will help the company to improve the business. 

Data Description
The data contains the different data related to a food order. The detailed data dictionary is given below.

Data Dictionary

order_id: Unique ID of the order
customer_id: ID of the customer who ordered the food
restaurant_name: Name of the restaurant
cuisine_type: Cuisine ordered by the customer
cost: Cost of the order
day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
rating: Rating given by the customer out of 5
food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information
