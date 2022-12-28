# Basic Machine Learning in R
This content will describe primary assignment for supervised machine learning methods.
# [Assignment 1: k-nearest neighbors in Ames Housing data set] (https://github.com/Dinh-Thien/Basic-Machine-Learning-in-R)
You have been hired as a consultant by a realtor in Ames, Iowa to analyze this data. They ask you for a short (1-2 paragraph) executive summary explaining what your model has demonstrated. Write this paragraph. In particular, focus on explaining how the model is making predictions, and what the associated uncertainty (i.e. error) in the predictions might represent to the realtor. You may write your summary in the space provided, or attach a file if the length exceeds the maximum provided space.

In this case, the algorithm which is k-nearest neighbours,  each observation is predicted based on its similarity with other observations.
We build the model and find out the best k value for the predictions. The results of knn algorithm shows that with k=7, we will get the minimize of error (MAE, RMSE) which helps understand the model performance over the whole datasets. Basically, the error is small, the predict house price in this model is more accurate.

After that, we based on best k-value and predict the response variable.
