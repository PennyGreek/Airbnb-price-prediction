Airbnb Rental Price Prediction
Results
Key factors influencing house prices on Airbnb have been identified through the analysis: location, accommodation capacity, and amenities. In particular, the impact of "accommodates" is the most substantial, as indicated by a correlation coefficient of 0.64, revealing that higher prices tend to be commanded by larger properties. To enhance customer loyalty, a focus can be placed on the delivery of high-quality services, adaptability to changing circumstances, and the facilitation of effective communication, as suggested by Lee and Deale (2021). The implementation of this strategy can lead to profitability and customer loyalty for Airbnb, especially in a post-pandemic context.

Methodology
An outline is provided for the approach taken in predicting Airbnb's home rental prices using various machine-learning models. The objective is to determine the best-performing model for this task. The model selection encompasses Ordinary Least Squares (OLS), Ridge, Lasso, Random Forest, and XGBoost. To establish a baseline for comparison, a straightforward yet effective method—multi-linear regression—is also employed.

To evaluate the performance of the models, Root Mean Square Logarithmic Error (RMSLE) is utilized. This metric places a greater emphasis on the penalty associated with underestimating true values, a consideration of greater significance in a business context than overestimation.

Model Performance
The RMSLE results for our models are presented in the following table, with the lowest error achieved by XGBoost:

Model	XGBoost	Random Forest	Ridge	OLS	Lasso
RMSLE	0.386	0.389	0.410	0.410	0.410
The prediction process entails the importation of the necessary libraries, the execution of a train-test split, and the generation of final predictions using the test dataset. Subsequently, the model's output is submitted to Kaggle for the acquisition of validation scores.







