# IBM Project Collision Prediction
This project is a case study to predict the severity of an accident.
A public data set is used to demonstrate Data Analysis and Machine Learning skills obtained in the IBM Data Science Program. Coursera has provided the data set which includes records of accidents and their severity level. 

## Objective
The objective of this project is to: understand the data, define relevant attributes that cause the accident and build a predictive model. This analysis will help in potential driving hazard identification and can help drivers choose the best rout based on weather and road condition.

## EDA and Modeling
The collision data set provided by Coursera includes all collision reports in Seattle since 2004. The data set has 194673 records and 37 attributes, each record is labelled by the accident's severity level.

After proper data evaluation and plotting, 10 features were finalized for modeling purposes. Therefore, the effect of Address Type, Collision Type, Weather Condition, Road Condition, Light Condition, Speed Violation, Number of Pedestrians, Vehicles, Cyclists and Total Number of People Involved in the Accident were used to estimate severity of accidents.

Results show that most accidents are labeled as category “1” or less sever accidents. It is also evident that most accidents seem to happen at the block type address, however, they are less severe than the accidents happening at intersections. Also most reported accidents did not involve speed violation. 
Number of pedestrian, cyclist, and persons involved in the accident have positive relationship with the severity level of the accident and all accidents have less than 10 people involved and mostly no pedestrian. 
It is also found that most collisions are labeled as parked car type and they happen at clear weather and dry road condition during daylight hours.

All four models predicted the severity code for the test set with relatively high accuracy score. However, KNN and SVM algorithms required longer computation time compared to the other two methods.
