# Project: Disaster Response Pipeline
# Project overview
For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. 
# Installation
The code should run using Python versions 3.*. The necessary libraries are:


# Quick Start
Run the following commands in the project's root directory to set up database and model.

```
python process_data.py disaster_messages.csv disaster_categories.csv DisasterResponse.db
python train_classifier.py ../data/DisasterResponse.db classifier.pkl
python run.py
```
## 1. Exploratory Data Analysis
Explore the data you are working with for the project. Dive in to see some basic information
## 2. Rank Based Recommendations

Find the most popular articles simply based on the most interactions. 
Assume the articles with the most interactions are the most popular. 

## 3. User-User Based Collaborative Filtering
Look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. 
This is a step in the right direction towards more personal recommendations for the users.

## 4.Matrix Factorization
Complete a machine learning approach to building recommendations.
Using the user-item interactions,I built out a matrix decomposition. 
 
# files

Here's the file structure of the project:

- data
|- disaster_categories.csv  # data to process 


- models
|- train_classifier.py

- README.md


# Result:




# Licensing, Acknowledgements
Must give credit to figure-8 that provided the data used in this repository. Feel free to use the code in this repository as you would like!


