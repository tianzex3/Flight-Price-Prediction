# Flight Ticket Price Prediction using Quantile Regression
__Flight ticket prices are always dynamic along the time. In this project, we will analyze and predict the dynamic flight ticket price in India based on various features.__

![image](https://user-images.githubusercontent.com/90085137/222812255-9a0176f0-0cae-4b51-8bd4-b46ff0c9735b.png)

## Methodology
Tool: Quantile Regression <br>
File Type: csv <br>
Language: Python <br>

## Available Data
The flight booking dataset obtained from “Ease My Trip” website has 300,154 rows in total. It contains flight ticket data in six major airports in India: Mumbai, Bangalore, Kolkata, Hyderabad, Chennai, and Delhi. There are six airlines in this data which are SpiceJet, AirAsia, Vistara, GO FIRST, Indigo, and Air India. In addition, we are also considering adding more features to the dataset which might include: the population of the source city and destination, airports capacity, population's average salary and some other related features.

## The Objective & Response Variable
__The objective is to create an algorithm to provide a range prediction for airline ticket price.__

The response variable would be the Ticket Price, and we plan to apply Generalized Linear Model to predict it. The specific type of GLM that will be using would depend on the distribution of our data, and we still need to explore more about the GLM we will use since we need to complete some exploratory data analysis first. For example, if the ticket price of the final dataset is normally distributed, the linear regression model can be used. If the ticket price of the final dataset is not normally distributed, a Poisson or negative binomial distribution regression model might be appropriate. We will also check the assumptions of the model before using it.  

## Literature Review
Literature reviews are also been performed to gain insight for developing new theories or conceptual frameworks that can be applied in future research; Identifying research gaps and inconsistencies that can inform the design of new studies; Understanding the historical context and evolution of a particular research area or discipline.

Source Site: https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction
