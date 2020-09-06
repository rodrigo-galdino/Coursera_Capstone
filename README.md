





# Predicting vehicle collisions for the area of Seattle 

This is the capstone project for Data Science Certificate Program.

Abstract: This is a machine learning project to predict the probability of vehicle collisions on the roads of the city of Seattle. it uses classification model to learn to predict the type of the collision based on accident reports provided by the Seattle Police Department and provided by Coursera via a download link.

## 1. Introduction: Business Problem 
1.1 Background

The Seattle Department of Transportation’s annual traffic report poses a significant challenge to governments to review their road safety policies and take new initiatives that make drivers' lives safer.
1.2 Problem/Opportunity Statement

Given this scenario, the objective of this project is to provide the best classification model to predict the type of collision (an auto accident involving injury or property damage) based on the weather and road conditions during the collision, the geographical area where the collision took place, the type of the collision and the day of the week that the collision occurred.
1.3 Interest

The information produced through this model may serve as an instrument for decision support in the prioritization of actions, such as changing road infrastructure, the procurement and installation of the road signs to reflect the weather conditions. Moreover, these informations could alert drivers, given the weather and road conditions about the possibility of a car accident and the severity of it, which would allow the driver to drive more carefully or, even change his itinerary.

## 2. Data 
2.1 Data sources

The data used corresponds to the Seattle Department of Transportation's annual Traffic Report Dataset.

After this verification, the variables given below were used for machine learning purposes, where the target variable was the column SEVERITYCODE:

| Attribute    | Description                                                                  |
| ------------ | ---------------------------------------------------------------------------- | 
| SEVERITYCODE | A code that corresponds collision: • 2—injury, • 1—prop damage.              |
| SEVERITYDESC | A description of the collision corresponding to the collision code.          |
| WEATHER      | A description of the weather conditions during the time of the collision.    |
| ROADCOND     | The condition of the road during the collision.                              |
| LOCATION     | The geographical area where the collision took place.                        |
| INCDATE      | The date of the incident.                                                    |
| ADDRTYPE     | Collision address type: • Block • Intersection.                              |

__For more details on the data used__, please consult the following link: [Data Set Summary](https://www.seattle.gov/Documents/Departments/SDOT/GIS/Collisions_OD.pdf)
