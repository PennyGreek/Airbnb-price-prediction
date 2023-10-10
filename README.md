# Airbnb rental price prediction
## Results
Based on our analysis, we identify key factors influencing house prices on Airbnb: location, accommodation capacity, and amenities. Particularly, accommodates has the most substantial impact, with a correlation coefficient of 0.64, indicating that larger properties tend to command higher prices. To enhance customer loyalty, hosts can focus on delivering high-quality services, adapting to changing circumstances, and effective communication, as suggested by Lee and Deale (2021). This strategy can foster profitability and customer loyalty for Airbnb, especially in a post-pandemic context.
## Methodology
In this section, we outline our approach to predicting Airbnb's home rental prices using various machine learning models. We aim to identify the best-performing model for this task. Our model selection includes Ordinary Least Squares (OLS), Ridge, Lasso, Random Forest, and XGBoost. To establish a baseline for comparison, we also employ a simple yet effective method—multi-linear regression.

To evaluate the models' performance, we use Root Mean Square Logarithmic Error (RMSLE). This metric emphasizes the penalty for underestimating true values, which is more detrimental in a business context than overestimation.

## Model Performance
The following table displays the RMSLE results for our models, with XGBoost achieving the lowest error:

Model	XGBoost	Random Forest	Ridge	OLS	Lasso
RMSLE	0.386	0.389	0.410	0.410	0.410
The prediction process involves importing the necessary libraries, performing a train-test split, and generating the final predictions using the test set. The model's output is then submitted to Kaggle to obtain validation scores.








