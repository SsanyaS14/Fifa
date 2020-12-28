# FIFA
I am creating a new dataset with two different target variables that are used to determine which players to have on a team. Additionally, I was able to predict the top 10 players in the 2019 league based off those two target variables. After data cleaning, exploratory data 

## Overall Score
Overall scores are determined by the overall performance of a player in the league. After feature selection, those features helped me use a Random Forest Regressor with an r2 score of 0.92. That Regressor model was used to predict the Overall Score of the players and was added onto the dataset. 

## Work Rate
Work Rate was the categorical feature that I tested for the players. I used a tensorflow keras package to have a model with a high accuracy and low loss function. This was ideal for a Neural Network. I converted the array into the dataframe and added onto the new dataset. 

## Next Steps:
Although I finished the models, I still plan to eventually create a model for predicting position, however, that will be unnecessary since positions are assigned to players already. However, I will be creating a Tableau dashboard for gamers to use to see what player best fits their team based on the features I used in feature selection. 
