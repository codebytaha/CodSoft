# Regression Model for Movie Ratings Prediction:
### Overview:
- This repository contains code for building a regression model to predict movie ratings based on features such as the release year, duration, and number of votes.
- The model uses a pipeline that includes standard scaling and Stochastic Gradient Descent (SGD) regression.

  ### Code Summary:
   - Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) are calculated to evaluate the performance of the pipeline.
 ```
mae_pipeline = mean_absolute_error(y_test, y_pred_pipeline)
mse_pipeline = mean_squared_error(y_test, y_pred_pipeline)
r2_pipeline = r2_score(y_test, y_pred_pipeline)
```
#### Prediction On Data:
- Add Your input, consisting of the movie's release year, duration, and number of votes.
  
   `Year`       Add your desired year.
  
  `Duration`     Add your desired duration in minutes.
  
    `Votes`        Add your desired number of votes.

### Conclusion:
- I have implemented a regression model for predicting movie ratings based on input features.
- The pipeline includes standard scaling and SGD regression, and the model's performance is evaluated using metrics such as MAE, MSE, and R2. 
- Additionally, I have provided a convenient way to predict ratings for new movie data, allowing users to input the release year, duration, and number of votes to obtain a predicted rating.
  
