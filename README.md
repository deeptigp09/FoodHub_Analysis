# FoodHub_Analysis

## Context

The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.

The app allows the restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants.

## Objective

The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Suppose you are hired as a Data Scientist in this company and the Data Science team has shared some of the key questions that need to be answered. Perform the data analysis to find answers to these questions that will help the company to improve the business.

## Data Description

The data contains the different data related to a food order. The detailed data dictionary is given below.

## Data Dictionary

order_id: Unique ID of the order
customer_id: ID of the customer who ordered the food
restaurant_name: Name of the restaurant
cuisine_type: Cuisine ordered by the customer
cost: Cost of the order
day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
rating: Rating given by the customer out of 5
food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information

## Conclusion and Recommendations

### Conclusions:

- Customer Preferences American Cuisine is the most popular, followed by Japanese, Italian and Chinese cuisines.
- Orders are significantly higher on weekends compared to weekdays.
- Order Cost, majority of the orders cost between 10 and 20 dollars. About 30% of the orders cost more than $20.
- Delivery Time The mean delivery time is approximately 24 minutes. Delivery times are shorter on weekends (22.47 minutes) compared to weekdays (28.34 minutes).
- Preparation Time The average time to prepare the food is approximately 27.37 minutes. The time taken is relatively uniform across the cuisines with a median of around 27 minutes.
- Customer Ratings, a significant portion of the orders (736) were not rated. Among the rated orders, ratings of 4 and 5 are more frequent, indicating overall satisfaction.
- Popular Restaurants, Shake Shack, The Meatball Shop, Blue Ribbon Sushi, Blue Ribbon Fried Chicken and Parm are the top 5 restaurants by order volume.
- Revenue Highlights, The net revenue generated by the company from comissions is approximately 6166.30 dollars. Orders costing more than 20 dollars contribute significantly to the revenue due to higher commission rates (25%).

### Recommendations:

- Enhancing Cuisine-Specific Strategies:
	- Promote Popular Cuisines: focus on marketing American, Japanese, Italian, and Chinese cuisines. Feature these prominently in the app with special promotions or discounts.
	- Boost Lesser-Known Cuisines: Collaborate with restaurants offering Vietnamese, Korean, and Mediterranean cuisines to enhance their menus and promote unique dishes through targeted campaigns.
- Leverage Customer Ratings:
	- Encourage Ratings: implementing incentives for customers to rate their orders, such as discount vouchers or loyalty points.
	- Analyze and Act on Feedback: use the feedback to identify areas of improvement and work with the restaurants to address the issues, enhancing overall customer satification.
- Support Top Restaurants:
	- Highlight Top Performers: Give more visibility to top restaurants like Shake Shack and The Meatball Shop in the app, using features like "Top Rated" or "Most Popular".
	- Collaborate for Promotions: - Work with these restaurants to offer exclusive deals, boosting their sales and attracting more customers.
- Enhance Customer Engagement:
	- Follow-Up Surveys Send follow-up surveys to customers who did not rate their orders.
	- Loyalty Programs Implement loyalty programs to reward frequent customers, particulars who consistently order from highly rated restaurants.
- Improve Operational Efficiency:
	- Streamline Preparation and Delivery Collaborate with restaurants to reduce preparation times and enhance delivery logistics, ensuring timely deliveries especially on weekends.
	- Maintain Quality Standards Provide training and resources to restaurant partners to ensure consistent food quality and service, focusing on highly rated dishes.
By leveraging cuisine preferences and customer feedback, FoodHub can enhance its marketing strategies, improve customer satisfication and drive businees growth catering to customer preferences more effectively.
