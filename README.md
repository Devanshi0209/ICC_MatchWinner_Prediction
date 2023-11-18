# ICC_MatchWinner_Prediction

AIM:
The aim of this project is to predict the winner of an ICC world cup match, in this case the final match between India and Australia based on the venue and which team we are playing against using Logistic Regression. 

DATASET:
The dataset has been taken from Kaggle and consists of all the matches ever played in the history of ICC World cup as of now. https://www.kaggle.com/datasets/sujithmandala/credit-score-classification-dataset
The dataset contains all match data from 1975-2019 in separate files for each year.

STEPS:
To predict the winner of 2023 finals or any other match, we do the following steps:
1.	In this project we are taking the taking the data of all past ICC world matches from 1975 to 2019. We will combine data from different years into one data frame.
2.	We are going to preprocess the data by removing useless columns, removing null rows and removing rows with invalid scores. 
3.	We will show basic and statistic information about the data
4.	We are going to visualise the outliers in the runs scored column and then remove them using the IQR method.
5.	We are going to visualize the relationship between different columns in the dataset using bar chart, scatter plot and pie chart. This will be done using classes and objects.
6.	We will create a database and insert the table in it which will have attributes as the column names of our processed dataset. This will be done using sqlite
7.	We split our data into train and test dataset and create the logistic regression model and train it based on our data. Then we print the accuracy and classification report for our model. Confusion matrix and heat map are also plotted.
8.	We use this model to predict the winner of 2023 final match.

CONCLUSION:
The conclusion shows us that based on the team we are playing against- Australia and the Venue- Ahmedabad, India is going to lose the ICC World Cup 2023 Final. This model has 70% accuracy.
To reproduce the project, load the ipynb file in Google Collab, upload all the datasets and run the code.
