# Python End-to-end Multiclass Classification Project
![](banner-picture.jpeg)
## Description
This is a multiclass classification project to classify the severity of road accidents into three categories. This project is based on real-world data, and the dataset is also highly imbalanced. There are three types of injuries: minor, severe, and fatal.

Road accidents are the major cause of unnatural deaths around the world. To reduce accidents and fatalities, all governments work hard to raise awareness about the rules and regulations that must be followed when driving a vehicle on the road.

In this campaign, we will look at the end-to-end project with source code to develop a machine-learning solution to predict the severity of road accidents to take necessary precautions by the investigation agency. 

Partnership: This campaign was created in collaboration with Avikumar Talaviya - a Mumbai chapter lead at OmdenaAI.

## Learning Outcomes
By the end of this campaign, you will be able to:
* Apply EDA techniques to get insights of a dataset
* Perform feature engineering and feature selection techniques
* Treat an imbalanced dataset using the SMOTENC technique
* Build, evaluate and export a random forest classification model
* Build and deploy a Streamlit web application

## Project Description
This dataset was collected from Addis Ababa Sub-city, Ethiopia, police departments for students’ master’s research work. The dataset has been prepared from manual records of road traffic accidents for the years 2017–20. All the sensitive information has been excluded during data encoding, and finally, it has 32 features and 12316 instances of an accident. 

Then it is preprocessed for the identification of major causes of the accident by analyzing it using different classification algorithms. Machine learning models are evaluated and thereafter deployed on a cloud-based platform in order to make them usable for end users.

## Problem Statement
The target feature is “Accident_severity”, which is a multi-class variable. The task is to classify this variable based on the other 31 features step-by-step by going through each data science process and task. Your metric for evaluation will be your “F1 score.”

This is an intermediate-level project with an imbalanced multiclass classification problem. 

Concepts that will be covered in this project include:
Classification machine learning algorithms
Knowledge of the Python programming language and Python frameworks like Pandas, NumPy, Matplotlib, and Scikit-Learn, as well as the basics of Streamlit library, is recommended.

## Dataset Description
The following are metadata regarding the dataset:
* `Time` — Time of the accident (in 24 hours format)
* `Day_of_week` — Day of the week when the accident occurred
* `Age_band_of_driver` —The age group of the driver
* `Sex_of_driver` — Gender of driver
* `Educational_level` — Driver’s highest education level
* `Vehical_driver_relation` — What’s the relation of a driver with the vehicle
* `Driving_experience` — Number of years of driving experience the driver has
* `Type_of_vehicle` — What’s the type of vehicle
* `Owner_of_vehicle` — Who’s the owner of the vehicle
* `Service_year_of_vehicle` — The last service year of the vehicle
* `Defect_of_vehicle` — Is there any defect on the vehicle or not?
* `Area_accident_occured` — Locality of an accident site
* `Lanes_or_Medians` — Are there any lanes or medians at the accident site?
* `Road_allignment` — Road alignment with the terrain of the land
* `Types_of_junction` — Type of junction at the accident site
* `Road_surface_type` — A surface type of road
* `Road_surface_conditions` — What was the condition of the road surface?
* `Light_conditions` — Lighting conditions at the site
* `Weather_conditions` — Weather conditions
* `Type_of_collision` — What is the type of collision
* `Number_of_vehicles_involved` — Total number of vehicles involved in an accident
* `Number_of_casualties` — Total number of casualties
* `Vehicle_movement` — How the vehicle was moving before the accident occurred
* `Casualty_class` — A person who got killed during an accident
* `Sex_of_casualty` — What the gender of a person who got killed
* `Age_band_of_casualty` — Age group of casualty
* `Casualty_severtiy` — How severely the casualty was injured
* `Work_of_casualty` — What was the work of the casualty
* `Fitness_of_casualty` — Fitness level of casualty
* `Pedestrain_movement` — Was there any pedestrian movement on the road?
* `Cause_of-accident` — What was the cause of an accident?
* `Accident_severity` — How severe an accident was? (Target variable)
