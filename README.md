This script aims to derive an expected number of goals for (a) home team and (b) away team by using the home/draw/away probabilities implied by the Betfair market odds.

How does it do this? It aims to find the optimal values for 𝜇𝐴 (mean/averge goals scored by team A) and 𝜇𝐵 that best match the target win probabilities

...and then uses these values to calculate the expected goals for the Home and Away teams.
