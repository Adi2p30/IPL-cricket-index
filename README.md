# IPL Cricket Index
A cricket batting index is a metric that is used to evaluate the performance of a cricket batsman. It is a composite measure that takes into account a variety of factors related to a batsman's ability to score runs, including batting average, strike rate, centuries, and other metrics.

There are various ways to calculate a cricket batting index, and different methods may place different emphasis on different factors. Some cricket batting indices may give more weight to batting average, while others may focus more on strike rate or other metrics.

The purpose of a cricket batting index is to provide a single, comprehensive measure of a batsman's performance that takes into account multiple aspects of their ability to score runs. It can be used to compare the performance of different batsmen, to rank batsmen within a team or league, or to evaluate the overall strength of a team's batting lineup.

#IPL 2022 Performance Cricket Index 
This cricket index has been made using multiple layers of weighted models
What is a weighted model?
A weighted model is a statistical model in which the contributions of different variables to the model's prediction are assigned different weights, or coefficients. These weights reflect the relative importance or influence of each variable on the outcome of the model.
For example, in a linear regression model, the weights are the coefficients that are assigned to each predictor variable. These coefficients indicate the strength and direction of the relationship between the predictor variable and the outcome variable, and they are used to make predictions about the outcome based on the values of the predictor variables.

Weighted models can be useful when some variables are more important or relevant than others in predicting the outcome of interest. By assigning higher weights to these variables, the model can better capture the relationship between the variables and the outcome.
Weighted models can also be used to downweight the influence of outliers or extreme values in the data, which can help to improve the accuracy and stability of the model.

Factors used to calculate the index
There are several factors that can be used to evaluate the performance of a cricket batsman. Some of the most important ones are:

Batting average: This is the average number of runs scored by a batsman per innings. It is calculated by dividing the total number of runs scored by the number of innings played.

Strike rate: This is the number of runs scored by a batsman per 100 balls faced. It is a measure of how quickly a batsman scores runs and is calculated by dividing the total number of runs scored by the number of balls faced and multiplying by 100.

Centuries and half-centuries: A century is a score of 100 runs or more in a single innings, while a half-century is a score of 50 runs or more. These are important milestones for batsmen and are often used as a measure of their ability to score runs consistently.

Boundary percentage: This is the percentage of runs scored by a batsman through boundaries (fours and sixes). It is a measure of a batsman's power and ability to hit the ball for maximum distance.

Run rate: This is the average number of runs scored by a batsman per over. It is calculated by dividing the total number of runs scored by the number of overs faced.

Consistency: A batsman's ability to score runs consistently over a long period of time is an important factor in their performance. Batsmen who are able to score runs consistently are more valuable to their team and are more likely to be successful in the long run.

Coefficients used in this model
For the Boundary Percentage we have used a 0.4 coefficient for the 4s and a 0.6 coefficient for 6s the coefficients add up to one that allows the model to give them equal weightage for final calculations 
For the Strike Rate we have given a 0.7 coefficient because the strike rate is a major factors that comes into play when calculating index
For the Stability and Consistency we can look for the number of 50s 100s and Avg score including the not outs 
For the Final Batting Strength we have taken an average of all 3 factors and we have also reduced outliers by adding a condition for the number of balls faced.

A percentile has been made with the highest batting strength being 10%

Contributors-
Aditya Pachpande
Aaryan Shah
Smayan Yambal 

Link to Project:- https://docs.google.com/spreadsheets/d/1RCmn6XXh-bUhStYrwT8-bMc0UOVQUr7ZeTWUqzH0jQY/edit?usp=sharing

