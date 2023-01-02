## Factors used to calculate the index
There are several factors that can be used to evaluate the performance of a cricket batsman. Some of the most important ones are:

  1. Batting average: This is the average number of runs scored by a batsman per innings. It is calculated by dividing the total number of runs scored by the number of innings played.

  2. Strike rate: This is the number of runs scored by a batsman per 100 balls faced. It is a measure of how quickly a batsman scores runs and is calculated by dividing the total number of runs scored by the number of balls faced and multiplying by 100.

  3. Centuries and half-centuries: A century is a score of 100 runs or more in a single innings, while a half-century is a score of 50 runs or more. These are important milestones for batsmen and are often used as a measure of their ability to score runs consistently.

  4. Boundary percentage: This is the percentage of runs scored by a batsman through boundaries (fours and sixes). It is a measure of a batsman's power and ability to hit the ball for maximum distance.

  5. Run rate: This is the average number of runs scored by a batsman per over. It is calculated by dividing the total number of runs scored by the number of overs faced.

  6. Consistency: A batsman's ability to score runs consistently over a long period of time is an important factor in their performance. Batsmen who are able to score runs consistently are more valuable to their team and are more likely to be successful in the long run.

## Coefficients used in this model
  1. For the Boundary Percentage we have used a 0.4 coefficient for the 4s and a 0.6 coefficient for 6s the coefficients add up to one that allows the model to give them equal weightage for final calculations 
  
  2. For the Strike Rate we have given a 0.7 coefficient because the strike rate is a major factors that comes into play when calculating index
  
  3. For the Stability and Consistency we can look for the number of 50s 100s and Avg score including the not outs. 
  
  4. For the Final Batting Strength we have taken an average of all 3 factors and we have also reduced outliers by adding a condition for the number of balls faced.

https://docs.google.com/spreadsheets/d/1RCmn6XXh-bUhStYrwT8-bMc0UOVQUr7ZeTWUqzH0jQY/edit#gid=492532668
