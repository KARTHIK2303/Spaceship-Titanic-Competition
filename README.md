# Spaceship-Titanic-Competition
Spaceship Titanic

### **Project Title: SPACESHIP TITANIC PREDICTION**
---------------------------------------------------------------
**Problem Statement**
---------------------------------------------------------------
In this article, we will attempt to solve one such problem using the Spaceship Titanic, a slightly modified version of the Titanic. This project's problem statement is like a spaceship carrying people from various planets on a journey, but for unknown reasons, some of them have been transported to another dimension. It is our job to predict who will be transported and who will remain on the spaceship.
---------------------------------------------------------------
**Approach**
---------------------------------------------------------------
The classical machine learning tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and Model Testing. Try out different machine learning algorithms, the best fit for the above case.
---------------------------------------------------------------
**Dataset** 
---------------------------------------------------------------
**The dataset is taken from Kaggle Competition
Link:- Click [Here](https://www.kaggle.com/competitions/spaceship-titanic/data)**

**We need to predict whether the passenger is transported or not for the test data as follow.**

**Features:**

- PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.
- HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.
- CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.
- Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.
- Destination - The planet the passenger will be debarking to.
- Age - The age of the passenger.
- VIP - Whether the passenger has paid for special VIP service during the voyage.
- RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
- Name - The first and last names of the passenger.
- Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.
---------------------------------------------------------------
**Tools Used**
---------------------------------------------------------------
**1. Python
2. Numpy, Pandas
3. Matplotlib, Seaborn
4. Sklearn
5. Scipy
6. Catboost
7. Xgboost**
---------------------------------------------------------------
**Platforms Used**
---------------------------------------------------------------
**Google colab, Github**
---------------------------------------------------------------
**Operation Performs:**
---------------------------------------------------------------
**1. Data Collection:**

Data is taken from kaggle which is a Spaceship Titanic

**2. Data Cleaning:**

This dataset consist of some missing values and outliers. The categorical missing value are filled with most frequent value i,e. mode while the numerical missing value are filled with mean.

**3. Data visualization:**

Visualization are performed using the libraries like Matplotlib and Seaborn by plotting Histogram and Countplots, etc.

**4. Feature Engineering:**

We use get_dummies and label encoder to convert categorical feature to numerical data.

**5. Model Training:**

Comparing various classification model by training them on the modified dataset.

**6. Hyperparameter Tuning:**

To gain more accuracy on the data we perform hyperparameter tuning. This process take much time but can give us better results.

**7. Model Evaluation and Selection:**

We choose Our model based on confusion matrix , f1 score and Classification report.



