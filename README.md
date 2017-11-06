# Nba Game Predictor

All NBA Seasons are saved in folders filled with the JSON data of each game for each team that season.

To create our model we need to multiply each feature by their coefficients:
* Home court advantage: 0.10218887
* Effective field goal percentage difference: 0.16118265
* Turnover percentage difference: -0.05958713
* Offensive rebound percentage difference: 0.07061777
* Free throws to field goals attempts difference: 0.03267933
* Distance traveled in last 7 days difference: -0.01459163
* Form in last seven matches difference: 0.0828436
* Offensive rating difference: 0.17885523
* Defensive rating difference: -0.33924331
* Effective field goal percentage difference (court): 0.10808104
* Turnover percentage difference (court): -0.09548481
* Offensive rebound percentage difference (court): 0.07055131
* Free throws to field goals attempts difference (court): 0.0748545
* Form in last seven matches difference (court): -0.00486437
* Offensive rating difference (court): 0.14822224
* Defensive rating difference (court): -0.21756487

#### The features marked (court) means considering court situation. For example if Team A is the home team and Team B is the visitor, then the effective field goal percentage would be: Team A's effective field goal percentage when playing at home and Team B's effective field goal percentage on the road.


