# Maxent-Nash-Implementation
This is Philip Felizarta's attempt to implement the ideas presented in Re-evaluating evaluation (https://arxiv.org/pdf/1806.02643.pdf) with the algorithms presented in Maximum Entropy Correlated Equilibria (http://rob.schapire.net/papers/correl-equil.pdf). 

The Maxent Nash jupyter notebook takes a .csv file of head-to-head matchup results, generates a payoff matrix, then uses the matrix and gradient ascent to approximate a maximum entropy nash equilibrium strategy.

The Neutral Calculator notebook also takes a .csv file of head-to-head results, but both players can have different action spaces!
