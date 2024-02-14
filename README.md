Algerian Forest Fire Data Analysis using Multiple Linear Regression

The objective of this project is to analyze the FWI in the Algerian forest fire dataset using multiple linear regression, evaluate the model's performance, create pickle files, and test the model on unseen data.

Dataset columns:
Date : (DD/MM/YYYY) Day, month ('june' to 'september'), year (2012) Weather data observations
Temp : temperature noon (temperature max) in Celsius degrees: 22 to 42
RH : Relative Humidity in %: 21 to 90
Ws :Wind speed in km/h: 6 to 29
Rain: total day in mm: 0 to 16.8 FWI Components
Fine Fuel Moisture Code (FFMC) index from the FWI system: 28.6 to 92.5
Duff Moisture Code (DMC) index from the FWI system: 1.1 to 65.9
Drought Code (DC) index from the FWI system: 7 to 220.4
Initial Spread Index (ISI) index from the FWI system: 0 to 18.5
Buildup Index (BUI) index from the FWI system: 1.1 to 68
Fire Weather Index (FWI) Index: 0 to 31.1
Classes: two classes, namely Fire and not Fire
Region: two values 0 and 1 

Interpretation and Assessment:

•	All models including Multiple Linear Regression model,tuned models- Ridge, Lasso, and ElasticNet exhibit outstanding predictive performance with R-squared values around 91%, indicating strong explanatory power.
•	Low MSE and MAE values signify accurate predictions with minimal errors.
•	The Final Lasso and Elastic Net Regression models slightly outperform than Multiple Linear Regression and Tuned Ridge Regression.

Model Evaluation on Unseen Data:

•	Elastic Net Regression on Unseen Data:
•	The Final Elastic Net Regression model, with the best alpha of 0.01 and L1 ratio of 0.9, performs well on unseen data.
•	The R-squared value of 0.947 indicates that approximately 95% of the variance in fire intensity is explained by the model.
•	The MSE and MAE values are relatively low, suggesting accurate predictions on the unseen dataset.

