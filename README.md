# Car Price Prediction Generator Project

A front end programming project to generate car price predictions based on multiple variables
## The Problem and Objectives

This project idea was born out of my own frustrations when trying to sell my own car and wanting to receive a fair price, without being undercut. A common issue I found when in this process, was that current car price generators on websites tend to have agendas, as ultimately they want to be able to make a profit if you were to use their service, so undercut the value of your car in accordance.

With this issue in mind, the objectives of this project are to create an application in which I would be able to generate a car price prediction, based off the true value so not as to undercut the user, and give them an accurate depiction of what their car could be worth. In order to do this I wanted to experiment with and use the databutton service aswell as the streamlit package in python to produce a front end application that was accessible to the public.
## Solution Strategy

The solution for this project will be the development of a simple, easy to use application where the user can input the specifications of their car and output a price prediction based off this criteria.

Step 1 - Data Collection: First I will need car pricing data to input into the application. This will need to include the prices of different car make and models brand new to then be able to work backwards when put through my code.

Step 2 - Car Price Generator: This stage will include creating a function in python that will generate a price for the users specific car, taking into account the make, model, mileage and age of the car.

Step 3 - App development: In this section I will combine the powers of databutton and the streamlit package in Python to create a front end application where the user will be able to input the specifications of their car and output a price for them based off of this criteria.
## The Application

Link to Application - https://databutton.com/v/vuv8ceh8

### Example of Application:
![Alt text](https://github.com/mattyh1010/Car-Price-Prediction-Generator-Project/blob/main/Car%20Price%20Predictor%20App.png)
## Car Price variables

- Mileage: The mileage of the car decreased the price value by 1% for every 1000 miles the car had done
- Colour: More popular colours such as white or black added some extra value to the cars
- Gearbox: An extra 10% was added to price if the gearbox was automatic
- Age: The age of the car decreased the price value by 10% per year
## Conclusions and Improvements

To conclude, I was successful in developing an application that was able to input a cars make, model, model variant, mileage, colour, gearbox and year and output a price prediction based of this criteria. An improvement I would like to make would be to make the original car pricing data more automated using an API, however this was difficult due to API's generally focusing on number plates rather than the specific car specifications. 
