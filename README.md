# machine-learning-challenge
Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.
In this homework assignment, you will need to:

Preprocess the raw data
Tune the models
Compare two or more models



Instructions

Preprocess the Data

Preprocess the dataset prior to fitting the model.
Perform feature selection and remove unnecessary features.
Use MinMaxScaler to scale the numerical data.
Separate the data into training and testing data.


Tune Model Parameters

Use GridSearch to tune model parameters.
Tune and compare at least two different classifiers.


Analyses

Data Source Exoplanet_data.csv
 
 First of all data was uploded and cleaned up.
 Some columns were dropped off in order to get precise  results. 

koi_disposition was used for the y values.

In or first model we got results 
Before 
Training Data Score: 0.8445546442876216
Testing Data Score: 0.8506864988558352
After 
Training Data Score: 0.8836543963379745
Testing Data Score: 0.88558352402746
 We improved our results.


 Second Model 
 Before
 Training Data Score: 0.887659736791913
Testing Data Score: 0.8895881006864989
After 0.8882319282853328


The result is close with the second Model.

Conclusion

Second Model was more successfull  but difference is not grand