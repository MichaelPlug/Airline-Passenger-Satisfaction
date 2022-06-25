# Big Data Computing’s Project proposal 2021/22
This repository contains my individual project for the course Big Data Computing of the academic year 2021/22, held by professor Gabriele Tolomei at La Sapeinza univerisity.

## The task:
The goal of this project is to predict if a passenger is satisfied air travel, based on travel and costumer data.
This is an example of binary classification: satisfied or not.
## The dataset:
Airline Passenger Satisfaction.
Source: https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction?select=train.csv
This dataset contains nearly 130,000 rows, and 23 attributes.

This is a short description of dataset’s attributes:
-	Gender: Gender of the passengers (Female, Male)
-	Customer Type: The customer type (Loyal customer, disloyal customer)
-	Age: The actual age of the passengers
-	Type of Travel: Purpose of the flight of the passengers (Personal Travel, Business Travel)
-	Class: Travel class in the plane of the passengers (Business, Eco, Eco Plus)
-	Flight distance: The flight distance of this journey
- nflight wifi service: Satisfaction level of the inflight wifi service (0:Not Applicable;1-5)
- Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient
- Ease of Online booking: Satisfaction level of online booking
- Gate location: Satisfaction level of Gate location
- Food and drink: Satisfaction level of Food and drink
-	Online boarding: Satisfaction level of online boarding
-	Seat comfort: Satisfaction level of Seat comfort
-	Inflight entertainment: Satisfaction level of inflight entertainment
-	On-board service: Satisfaction level of On-board service
-	Leg room service: Satisfaction level of Leg room service
-	Baggage handling: Satisfaction level of baggage handling
-	Check-in service: Satisfaction level of Check-in service
-	Inflight service: Satisfaction level of inflight service
-	Cleanliness: Satisfaction level of Cleanliness
- Departure Delay in Minutes: Minutes delayed when departure
-	Arrival Delay in Minutes: Minutes delayed when Arrival
-	Satisfaction: Airline satisfaction level (Satisfaction, neutral or dissatisfaction)

## The methods:
To reach the goal I’m going to apply these methods:
-	Logistic Regression
-	Gaussian Naïve-Bayes
-	Random Forest
## The evaluation framework:
To evaluate the performance, I’m going to use the evaluation metrics:
-	AUROC
-	Precision
