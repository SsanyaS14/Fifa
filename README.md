# FIFA
I am creating a new dataset with two different target variables that are used to determine which players to have on a team. Additionally, I was able to predict the top 10 players in the 2019 league based off those two target variables. 

## Data Cleaning and Exploration
I worked on imputatng the missing data so data exploration and feature selection would be easier. First I imputated the position numbers, as they were ratings of the players at those positions. I imputed those to zero since players with no score played those positions. Then, for the rest of the numerical values, I imputed the mean value and converted some of the numerical values to caateorical values since it better fit those values. Finally, I imputed the most frequent categorical value for categorical variables. 

I did a couple of exploration visuals. I did some interactive maps and parallel coordinate plots. This was just to help me understand the data a bit more. Finally, I moved onto feature selection, for Overall and Work Rate target variables. 

## Overall Score
Overall scores are determined by the overall performance of a player in the league. After feature selection, those features helped me use different models to find the best model for predicting score. I did a multilinear regression, random forest regression, lasso regression, and ridge regression. The Random forest regression had a R2 score of 0.92 so that was used for predictions. I replaced the Overall column with the predicted overall score. 

## Work Rate
Work Rate was the categorical feature that I tested for the players. I did a Random Forest Classifer, Decision Tree Classifer, and TensorFlow NN. The tensorflow NN had an ideal high accuracy and low loss thus, I used the predicted work rate from the NN and replaced Work rate with the predicted values. 

## Top 10 Best Players
Based on Work Rate and Overall Score, I looked for the top 10 FIFA 2019 players:

L. Messi
E. Hazard	
Cristiano Ronaldo	
Neymar Jr	
L. Suárez	
K. De Bruyne	
L. Modrić	
David Silva	
S. Agüero	
R. Lewandowski

## Dashboard
After having a brand new dataset with my predictions and feature selection, I created a Dashboard that gamers can interat with to help them see who is the best player to add to their team. https://public.tableau.com/profile/sanya.srivastava#!/vizhome/FIFA2019Dashboard/Dashboard1
