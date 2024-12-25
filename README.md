# FOODHUB

##PROJECT OVERVIEW :

-Background of Study :

The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app. 
The app allows the restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants. 

-Objective 
The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Suppose you are hired as a Data Analyst in this company and the Data Science team has shared some of the key questions that need to be answered. Perform the data analysis to find answers to these questions that will help the company to improve the business



Description: Conducted Statistical Analysis On Using Excel for Comprehensive Report and Visualization to Aid Decision Making. The data contains the different data related to a food hub



##DATA DICTIONARY

1-order_id: Unique ID of the order 

 2-customer_id: ID of the customer who ordered the food

3-restaurant_name: Name of the restaurant 

4- cuisine_type: Cuisine ordered by the customer

5- cost: Cost of the order 

6- day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)

7- rating: Rating given by the customer out of 5
8- food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.

9- delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information 


## Tool :
-Excel


## Data cleaning / preparations
-Handling missing values


## Exploratory Data Analysis:

-Section A: Understanding the Structure of the data. 

1.	How many transactions do we have from the food hub data set? 
2. Classify the attributes as either numerical or categorical data 
3. Which of the attributes is/are unique?
4. Are they any transactions with null values? If yes which columns?

-Section B: Exploring the Customer purchasing behavior 

1. How many customer id is/are unique? 
2. Find the four (4) highest customers that placed orders.
3. How many customers ordered ones? 
4. How many customers ordered between 5 to six times?

-Section C: Restaurant type analysis 
1. The logistic Manager wants to know the total number of restaurant name in order to plan for the best transportation techniques to apply in the dispatch of orders from customers. 
2. Which is the most frequently ordered restaurant and how many times were orders placed on this restaurant?
3. Create a visual for the highest ten restaurants based on their frequency of orders. 
4. Which restaurants is mostly sorted after during weekend and how many orders were placed? 
5.  With the aid of a chart, compare the number of orders between weekday and weekends. 


-Section D: Cuisine type 
1. How many type of cuisine do we have?  
2. Present a visual that shows the cuisine type and the number of times they were ordered?
3. Which cuisine type is the most expensive?
4. Find the average food preparation time for each of the cuisine type, this should be presented in form of visual. 
5. Which of the mails are ordered more during weekend? 



-Section E: Rating analysis of Customers 
1. How many customers did not rate?
2. Which of the restaurants has the most rating of 5?
3. The FoodHub logistic company is considering dropping restaurants whose rating is below
4. perform this task and present the rest of the restaurants to the front Desks. 


### RESULTS 
-SECTION A :
1.	There are nine(9) transctions in the data set.
2.	 Numerical attributes:

i)Order id

ii) Customer id

iii) Cost of order

iv)Rating

v)Food preparation time

vi) Delivery time

Catergorical attributes :

I)	Resuturant name

II)	Cusine type

3.	Unique attributes :

i)	Oder id

4.	Transaction with null values:

i)	none


-SECTION B:
1.	Count of unique customer id:

1200 unique customer id

2. Top 4 customer order:

a)	 customer id shows vs cost of order chat :
customers with id below order the most:
52832
47440
83287
250494

3.	How many customers odered once:

i) 784 customers order once, considering the count of customer id against cost of order

ii)	Between 5&6:

131 customers order between 5 & 6 times



-Section C :

      i)	The total number of restaurant:
There are 161 restaurant base on the data.


ii)	The most ordered restaurant :
Shake shark with a count of 216







iii) 10  Highest resturant base on frequency of order visual:


![image](https://github.com/user-attachments/assets/c83a1dc0-7944-4677-9864-4750f591d225)



IV)	Most orderd by weekend:
The most ordered by weekend is shake shark with a count of 145.


v)weekend vs weekdays


![image](https://github.com/user-attachments/assets/de81c0e4-5639-4cb3-b8ec-dbe44ac71695)   ![image](https://github.com/user-attachments/assets/2203829e-401d-4b50-91c6-627e1ceda1ab)


-Section D :

I)	There are 14 unique cuisine type


iii)	Count of cuisine by order

![image](https://github.com/user-attachments/assets/d6e90e91-08eb-48e4-94a6-89de8cc3570a)


iii)          most expensive cusine :
Mediterranean

![image](https://github.com/user-attachments/assets/1a7e38ae-6f82-474b-9166-0a23585b9438)


iv)	CUISINE AVERAGE PREPARATION TIME


![image](https://github.com/user-attachments/assets/bddb0eca-777a-47d3-aa9c-fb3194b08054)


v)	Most ordered cuisine by weekend


![image](https://github.com/user-attachments/assets/db84ade3-4c62-4167-8ba1-99d48f21fd1b)


Section E:
I)	How many customers did not rate ?

736 customers did not rate



ii)	Most rated restaurant with 5

Shake shark with 66 count

![image](https://github.com/user-attachments/assets/e151978e-ab80-4d7b-bf02-5737416ca103)




iii)	Rating of restaurant below 4 :

Total of 136 restaurant has a rating below 4




