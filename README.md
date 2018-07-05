# Monte_carlo_Grid

<span style="font-family:Papyrus"> Monte Carlo simulations have been around for many years solving a variety of problems anywhere from physics to finance to game optimization. As a matter of fact, this type of modeling was created by scientists wanting to solve very complex physics problems at the time. The main premise behind Monte Carlo is that with many samplings of a uncertain distribution, we will eventually get a good enough estimate of the mean of that distribution. Thus, Monte Carlo leverages this idea of randomly sampling complex enviroments to understand means at given state spaces. More specifically, Monte Carlo Prediction models an enviroment with many state-action spaces like Gird World and iterate through many tests or episodes of calculating the values at those state-action spaces and determines the mean based off large samplings at that state-action space. Once a reasonable mean is acheived, than the algorithm compares these values to choose the maximum one. Ultimately, resulting in the optimal policy for the agent. In this experiment, I tested different values of epsilon and gamma to see how Monte Carlo Prediction would do.
</span>

### Small and Large Gamma and Epsilon
<span style="font-family:Papyrus"> When I set Gamma values low (i.e gamma < .2), regardless of how large or small I set epsilon, I would get very quick convergence and get bad policies on the bottom of the grid world. Conversly, when I 
</span>

<p align="center">
  <img src="monte_graph.png" )
</p>
