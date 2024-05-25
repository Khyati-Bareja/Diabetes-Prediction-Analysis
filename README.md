# Team 12 - [Diabetes Prediction Analysis](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)



### About Dataset
Dataset is a collection of medical and demographic data from patients, along with their diabetes status (positive or negative). The data includes features such as age, gender, body mass index (BMI), hypertension, heart disease, smoking history, HbA1c level, and blood glucose level. Total size : 1,00,000 datapoints, out of which size of training data = 80,000 datapoints, size of test data = 10,000 datapoints, size of validation data = 10,000 datapoints.

Key attributes of the dataset:  
- **Age**: Represents age. 
- **Gender**: Categorical feature.  
- **Body Mass Index (BMI)**: Represents BMI.  
- **Hypertension**: a numerical field in the dataset, indicates high blood pressure, which is detrimental to cardiovascular health. 
- **Heart Disease**: A boolean field that signifies a bidirectional relationship with diabetes, as both conditions increase the risk of developing the other. 
- **Smoking History**: Categorical feature that tells if a person is a smoker or a non smoker.  
- **HbA1c Level**: Glycated hemoglobin is a measure of the average blood glucose level over the past 2-3 months.  
- **Blood Glucose Level**: Represents the amount of sugar in the blood at a specific moment. 
- **Diabetes**: Boolean field that represents if a person is diabetic or not.


<img width="965" alt="Screenshot 2024-03-27 at 2 56 55 PM" src="https://github.com/shashank6341/Big-Data-Team-12/assets/117713327/1b7c6721-a094-45c4-8920-4b26e989069f">



# Research Question

### Primary Question

1. How can the optimized selection of features from a given dataset can contribute accurately in diagnosis of diabetes ?

### Secondary Question

2. How does BMI (Body Mass Index) affect the likelihood of having diabetes? Are there differences in diabetes prevalence based on demographic factors such as gender and age, and does age and gender influence the likelihood of having diabetes?

3. How does lifestyle factors, such as smoking history, interact with physiological indicators like BMI and blood glucose levels in predicting diabetes ? Is there a correlation between hypertension and diabetes?

4. Does a history of heart disease increase the risk of diabetes?

5. How do demographic factors (gender, age) interact with other variables in predicting diabetes risk?

6. Does the presence of hypertension or heart disease exacerbate the effects of other risk factors on diabetes incidence?

# Algorithms

Implimentated Algorithms will include, **Regression technique of Supervised learning** for the diagnosis of diabetes from the dataset: 

Employed algorithms will be:
  1. Logistic regression
  2. Decision tree regression

Hyperparameter Tuning techniques will be used and performance will be assessed using test data, Accuracy will be evaluated with metrics like:

  1. RMSE
  2. F1-Score



<details>
  <summary>Old Project Description</summary>


# Team 12 - [Flight Fair Prediction](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh)

### About Dataset
Dataset details the flight journey data for the duration of 4 months in the year 2019, capturing various attributes that can be utilized to perform data analysis of air travel patterns. Data is partitioned in Training Data: 10,684 datapoints and Test Data: 2672 datapoints,to facilitate model training and evaluation. It consists of essential attributes required for understanding flight dynamics, passenger preferences and pricing structures,specifically the details about the airline, journey dates, departure and arrival locations, route information, and vital flight-related metrics. Each attribute can serves as a building block, and contribute towards providing invaluable insights into the complexities of air travel operations and passenger behavior.

Key attributes of the dataset:  
- **Airline**: Lists a diverse range of airlines. 
- **Date_of_Journey**: Travelling date. 
- **Source and Destination**: Departure and arrival locations for each flight journey.  
- **Route**: Specific route taken by each flight.
- **Arrival_Time and Duration**: Arrival time at the destination and the total duration of flight journey. 
- **Total_Stops**: Indicates number of layovers. 
- **Additional_Info**: Is the information such as onboard amenities, special services, and other relevant details that may influence passenger choices and overall travel experience.  
- **Price**: Crucial metric, price of each journey.

The **Outliers** related to additional information such as inflight meals and baggage policies, offering opportunities for exploring unique and nuanced aspects of the air travel experience. Price also acts as an outlier when plotted between airlines and locations.

![Screenshot 2024-03-13 at 4 07 09 PM](https://github.com/shashank6341/Big-Data-Team-12/assets/8446697/0fb46ff5-39d8-4a5c-8501-bc573d0e7587)

  
# Research Question

### Primary Question

  1. What is the relationship between duration of a flight journey and the ticket price?
     - It aims to understand if longer flights generally result in higher prices and to identify other factors that might impact pricing, by examining this relationship, we gain insights into airline pricing strategies and passenger preferences.

### Secondary Question

  2. How does the number of stops affect the price of a journey for same routes?
     - This question helps understand how the number of stops affects the ticket prices and the trade-offs passengers make between cost, convenience, and travel time. Analyzing this variation will help reveal routing strategies of airlines and passenger's preference regarding layovers.

  3. Which month experiences the highest volume of flight bookings/journeys, and which locations are most popular during that time?
     - This question helps identify the busiest month for flight journeys and the top destinations during that period which can be used by airlines to plan their routes.

  5. Visualizing the co-relation between **Feature Importance** and **SelectK-Best** feature selection techniques using **Heatmap**?
     - This assessment will evaluate the consistency and alignment of feature selection techniques and provide insights into the relevance of selected features for predictive modeling.

# Algorithms

Implimentated Algorithms will include, **Regression technique of Supervised learning** for the Flight fare prediction dataset due to its continuous outcome prediction nature. 

Employed algorithms will be:
  1. Linear regression
  2. Decision tree regression
  3. Random forest regression

Hyperparameter Tuning techniques will be used and performance will be assessed using test data, Accuracy will be evaluated with metrics like:

  1. RMSE
  2. MAE
  3. F1-Score

Matplotlib will be used to compare the performance of the algorithms.

</details>


