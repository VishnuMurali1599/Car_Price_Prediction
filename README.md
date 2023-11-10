# Car_Price_Prediction

# Aim

This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.

## How to use?

1. Clone the repository
2. Install the required packages in "requirements.txt" file.

Some packages are:
 - numpy 
 - pandas 
 - scikit-learn

3. Run the "application.py" file
And you are good to go. 

# Description

## What this project does?

1. This project takes the parameters of an used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
2. It then predicts the possible price of the car. For example, the image below shows the predicted price of our Cheverlot spark LT.

![bd8423da-a0e3-4cae-83db-0f16eb7c23b6](https://github.com/VishnuMurali1599/Car_Price_Prediction/assets/133478960/fa827799-1174-4029-b635-c1226598959e)


## How this project does?

1. First of all the data was scraped from Quikr.com (https://quikr.com) 

2. The data was cleaned (it was super unclean :( ) and analysed.)

3. Then a Linear Regression model was built on top of it which had 0.92 R2_score.

4. This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.

5. Deployed the web application on Amazon Web Services (AWS) Elastic Beanstalk for scalable and reliable hosting.
   
6. Configured the environment and managed dependencies to ensure smooth deployment.

## Technologies Used:

 1. Python, scikit-learn, pandas for machine learning model development.
 2. Flask for web application development.
 3. AWS Elastic Beanstalk for deployment.

## Impact:
      The project demonstrates my proficiency in end-to-end machine learning development, including data preprocessing, model building, and web application deployment.
      The skills gained include data analysis, feature engineering, model selection, web development, and cloud deployment.


 ![bd8423da-a0e3-4cae-83db-0f16eb7c23b6](https://github.com/VishnuMurali1599/Car_Price_Prediction/assets/133478960/53bcf8fa-1e73-4788-bcb5-e7297d2d1975)

![98cb8a3a-fdec-4c43-98d0-5838344d279c](https://github.com/VishnuMurali1599/Car_Price_Prediction/assets/133478960/396fc3f3-f7ff-4798-a228-a81246a3fdf6)

