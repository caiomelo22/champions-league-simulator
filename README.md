# Champions League Simulator
Champions League knockout simulator based on ELO ratings and Monte Carlo simulation.

Monte Carlo Simulation is a way of predicting an uncertain event based on numerous random simulations with a bias. In our case, our bias will be the ELO Ratings. To maintain a certain unpredictability known in the sport of football, we'll keep the number of simulations at a lower range, since the law of large numbers dictates that the more simulations are run, the outcome prediction tends to converge to the bias values.

ELO Ratings are a way to define the strength of a team. First used for chess, it uses a 1500 score baseline, and for each game a team plays, it updates its score based on the opponent and the victory/defeat margin. So, if a team beats a stronger opponent, they'll be rewarded with more points. On the other hand, if the team loses to a weaker opponent, they'll be penalized with a considerable amount of points.
