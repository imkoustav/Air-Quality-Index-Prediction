# Air-Quality-Index-Prediction
* Prediction of Air Quality Index using Linear Regression 

Within the last few years, an intense curiosity has been progressed by the people in the daily air quality circumstances to which they are encountered. Directed by the growing consciousness of the physical state of air pollution exposure, especially by most sensitive sub–populations such as children and the elderly, short–term air pollution forecasts are being accentuated progressively by local authorities. The Air Quality Index (AQI) is the value implemented to estimate the quality of the air at a certain location. The components are estimated with the implementation of the covariance of the input data matrix. Only those elements, having Eigenvalues≥ 1, were used to anticipate the AQI implementing the linear regression technique.

# Method

1) Analysing the data: Data has been collected from the AQI.csv file and implemented in the estimation of Air Quality Index.
2) Seaborn pairplot: Seaborn pairplot has been implemented to plot pairwise relationships from the dataset.The pairplot function generates a grid of axes in such a way that each variable in data will be shared in the y-axis across a single row and in the x-axis across a single column.
3) Generating Heat Map: Heat Map is generated to determine the features which are mostly familiar to the target variable
4) Generating Extra Trees Regressor: This module is imported and generated in the model to determine the significance of each and every particular feature of our dataset.
5) Implementation of linear regression: After bringing all the parameters into the learning circumstance, the linear regression is implemented to estimate the Air Quality Index. 
6) Train and Test Split: 70% data of the dataset has been utilized for training and 30% has been enabled for the testing process. 
7) Estimating the coefficients: Keeping the other features fixed,1 single unit increase in T is related with a decrease of 2.690 in AQI PM2.5. Similarly, keeping the other features fixed,1 single unit increase in TM is related with an increase of 0.46 in AQI PM2.5 .
8) Regression Evaluation Metrics: Mean Absolute Error (MAE),Mean Squared Error(MSE) and Root Mean Squared error (RSME) are calculated.
9) Generating byte stream file using pickle module :- For further evaluation, the object ”regression_model.pkl” file is dumped into byte stream file and then again done “unpickling” to reconvert the analyzed byte stream file into object file.

# Result
The Mean Absolute Error (MAE) was found to be 44.84 approximately, Mean Squared Error(MSE)was found to be 3687.54 approximately, Root Mean Squared error(RMSE) was found to be 60.73 approximately. The Heatmap has been plotted to predict the familiar features of the target variable using the seaborn library .Pickle module is implemented to convert the regressor file(object)into byte stream and dump function is used to dump the converted byte stream of the file ”regressoion_model.pkl” into a file for further evaluation. After the processing and evaluation of the dumped file ,the byte stream file is again converted into object hierarchy using load function.
