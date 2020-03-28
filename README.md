# Movie-Recommendation-Engine
User | Item Based Collaborative Filtering
* User Based - Avoiding cold start by making sure the users in the test dataset are present in the training dataset. Calculated
similarities between users using Pearson correlation coefficient, predicted ratings for movies in the test dataset, by using
the similarities and the ratings already given by users in the training dataset(model), used MAE and RMSE metrics to
check the accuracy of the model and the errors in the predicted ratings.
* Item Based CF - Used the above training dataset to find the user similarities in the test dataset and predicted ratings for
the items using item similarities metric and ratings already given by user to all the similar movies. used MAE and RMSE
to compute error and check accuracy.
