Solution for Problem C (Data Insights) in the 2024 [Mathematical Contest in Modeling](https://www.contest.comap.com/undergraduate/contests/mcm/). 

Broadly, the problem was about tennis games and the concept of "momentum" in sports. Contestants used 2023 Wimbledon men's singles data to:
- Develop a model and visualization for the flow of play in a tennis match. The model identifies which player is performing better at a given time in a match, as well as how much better they are performing.
- Assess the role of momentum in a match and determine if swings in performance are random.
- Identify indicators and develop a model to predict performance swings.

Our team used a **Markov chain** with **Bayesian logistic regression** to capture the flow of a single game. We also found no correspondence between "momentum" and swings in performance. 
<p align="center">
  <img src="https://i.imgur.com/WKbCrkL.png" />
</p>
