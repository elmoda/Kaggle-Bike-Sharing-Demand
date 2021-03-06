# Bike Sharing Demand

#### Competition Description
Bike sharing systems are a means of renting bicycles where the process of obtaining membership, rental, and bike return is automated via a network of kiosk locations throughout a city. Using these systems, people are able rent a bike from a one location and return it to a different place on an as-needed basis. Currently, there are over 500 bike-sharing programs around the world.

The data generated by these systems makes them attractive for researchers because the duration of travel, departure location, arrival location, and time elapsed is explicitly recorded. Bike sharing systems therefore function as a sensor network, which can be used for studying mobility in a city. In this competition, participants are asked to combine historical usage patterns with weather data in order to forecast bike rental demand in the Capital Bikeshare program in Washington, D.C.

##### Data
train.csv : 10886 datetime and 12 attributes,  including the 'count'<br>
test.csv : 6493 datetime and p attributes<br>
sampleSubmission.csv : default form of files to submit<br>
submission.csv : submission file I created<br> 

##### Used libraries
- numpy
- pandas
- matplotlib
- seaborn
- calendar
- datetime
- linear regression
- gridsearchCV
- metrics
- ridge
- lasso
- random forest
- gradient boosting