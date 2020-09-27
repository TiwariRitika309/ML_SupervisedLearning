<h2>Exploring Supervised Learning</h2>


This project is part of my internship at The Sparks Foundation. In this project, I have attempted to build a Linear Regression model to predict scores of students based on the number of hours they put in to study. 

<H5>What does the <a Href='http://bit.ly/w-data'>dataset</a> include?</h5>

The dataset, as provided by TSF, includes two set of columns. One is 'Hours' that holds values for the number of hours a student studied for and another is 'Score' that holds values for 
score of each student. The data for individual student is stored by rows. 

<h5>About the Linear Regressor</h5>

I used the language of Python to build the model. Initially, I performed exploratory analysis on the data using Matplotlib and Seaborn libraries of Python. Further, I split the 
data into Training and Testing sets, with a test_size of '0.33', using train_test_split function from Sklearn library. The model is then tested for predictions on the test data. The
accuracy of the model stands at 96%. I have also added error calculations and residual graph for evaluation of the model. 

In the end, I use the model built to predict the score of a student who studies for 9.5 hours. 

<h6> Take a look at the code and feel free to suggest improvements!</h6>
