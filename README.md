 BOARD GAME REVIEW PREDICTION
 
      
In this project, a dataset of about 82000 rows and 20 columns was given regarding the reviews of various board games available. A supervised machine learning model as then been trained and evaluated to predict the ratings given to a particular board game based on several features of the datasets.In order to choose the machine learning algorithms best suited to make predictions of the average rating of the board games, number of regression or similar models were considered and the data has been investigated to choose the best possible model.

Linear Regression and random forest regression is used.

After using Linear Regression model, I found out that the Mean Squared Error(MSE)=2.078 which is greater than 0, making a Linear model unfit for this prediction, hence we tried the Random Forest Regressor, which was eventually generating prediction value close to the actual values by a tiny fraction.
