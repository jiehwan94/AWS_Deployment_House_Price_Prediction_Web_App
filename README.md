# Deploying ML Model Serving Web Application to AWS

![image](https://user-images.githubusercontent.com/15040724/149602771-cdc68587-1f54-4705-85d3-b0f4a5c498b8.png)

### Steps taken:

1. EDA, data cleansing, feature engineering, dimensionality reduction, Grid Search CV for hyperparamter tuning, k-fold cross validation.

2. Build a model using linear regression and save it as a pickle file.

3. Build back-end by writing a python Flask server that uses the pickled model to serve http requests.

4. Build a website front-end (html, css, javascript) that allows users to enter house information including home sqr ft area, # bed, # bath, and location.

5. Deploy the Flask web application to an [AWS EC2](http://ec2-3-133-88-210.us-east-2.compute.amazonaws.com/) instance using Nginx.


Please refer to my blog for more info:

https://94light.wixsite.com/mysite/post/deploying-house-price-prediction-flask-web-app-to-aws

Youtube video:

https://www.youtube.com/watch?v=GpIe-P_0FLk
