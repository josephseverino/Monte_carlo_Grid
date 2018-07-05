# Monte_carlo_Grid

<span style="font-family:Papyrus"> Monte Carlo simulations have been around for many years solving a variety of problems anywhere from physics to finance to game optimization. As a matter of fact, this type of modeling was created by scientists wanting to solve very complex physics problems at the time. The main premise behind Monte Carlo is that with many samplings of a uncertain distribution, we will eventually get a good enough estimate of the mean of that distribution. Thus, Monte Carlo leverages this idea of randomly sampling complex enviroments to understand means at given state spaces. More specifically, Monte Carlo Prediction models an enviroment with many state-action spaces like Gird World and iterate through many tests or episodes of calculating the values at those state-action spaces and determines the mean based off large samplings at that state-action space. Once a reasonable mean is acheived, than the algorithm compares these values to choose the maximum one. Ultimately, resulting in the optimal policy for the agent. In this experiment, I tested different values of epsilon and gamma to see how Monte Carlo Prediction would do.
</span>

### Small and Large Gamma and Epsilon
<span style="font-family:Papyrus"> When I set Gamma values low (i.e gamma < .2), regardless of how large or small I set epsilon, I would get very quick convergence and get bad policies on the bottom of the grid world. Conversly, when I set gamma to be high (i.e. gamma = .9), I would get two different types of predictions depending on my epsilon value. For epsilon large, I would get poor policies for my agent and slower convergence. Alternatively, when I used smaller values of epsilon I would get quick convergence and optimal policies. 
</span>

<p align="center">
  <img src="monte_graph.png" )
</p>

## Conclusion

<span style="font-family:Papyrus"> Monte Carlo Prediction is not nearly as quick as other models like value iteration or Policy iteration. However, it is still a useful tool for predicting given the appropriate values of epsilon and gammma. The reason the Monte Carlo Prediction converges so slowly is due to its episodic nature. Randomly sampling many state-action combinations requires a larger amount of exploration to understand the mean at those given state-action spaces. Thus, like the multi-arm bandit, it requires exhaustive exploration. However, the most important factor for Monte Carlo is setting the gamma and epsilon values so that good exploration to undstand the means at each state-action, thus getting the most accurate value function and ultimately choosing the right policy for the agent. 
</span>
