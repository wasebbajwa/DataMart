# DataMart

## The Data
This project is a mock data science project revolving around a fake retail chain, DataMart. The project was split into a few different phases, the first phase being data generation. The data was generated by using Kafka to randomize fake entries for consumer purchases and fake entries for distribution locations around the country. 
It also has entries for whether or not the product was shipped on time, what the consumer rated the product, and other details of the transactions such as shipping prices, the costs of goods, etc. To make the mock data more realistic, the data was skewed purposelly in order to model retail factors such as time of year, product type, and distance to shipping were all modified so that busier seasons had a larger amount of certain products being purchased and a larger amount of delays happening. 

## Goals

The goal of this project was also two fold. The first aspect was to create a prediction system that would predict whether or not a delivery would arrive on time as well as finding distribution centers and warehouses that were more likely to have package delays. This has many use cases in real life as large retailers perfform this type on analysis in order to increase their efficiency. The main approaches used in were techniques such as using ARIMA, implementing seasonality, and more complex neural networks.

The second goal of the project was to create a recommendation system. The recommender system would ideally suggest items that a customer would be more likely to purchase. Three main approaches were used, a colllobrative filtering system, a content-based recommender system, and a hybrid system. 


