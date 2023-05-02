# MachineLearning-N_ArmedBandit
If you're curious about machine learning and decision-making, then the multi-armed bandit problem is an exciting concept to explore. As I developed my latest Git page, I delved deep into this fascinating model that captures the essence of an agent seeking to acquire new knowledge while optimizing their decisions based on that knowledge.

To mimic a multi-armed bandit scenario, I utilized the epsilon-greedy method in my code, considering 8 arms and 1000 bandit problems. By using a normal distribution with a mean of 0 and a standard deviation of 1, I calculated the reward values for each arm and plotted the maximum reward per arm for 1000 bandits.

My "choose arm by egreedy" function implements the epsilon-greedy method by selecting the arm with the highest estimated value with probability 1-epsilon or a random arm with probability epsilon. I defined the value of epsilon as a parameter for the "TestBed" function, which simulated the bandit problem for 1000 time steps after initializing the estimated values and number of pulls for each arm. For each time step, it selected an arm using the epsilon-greedy algorithm, obtained the reward for that arm using a normal distribution, updated the estimated value and number of pulls for that arm, and calculated the average prize collected by all bandits at that time step.

In my code, I also presented the average reward per step and the proportion of ideal behaviors for various epsilon values. To refer to the multi-armed bandit example provided in Sutton & Barto’s book, I obtained the average rewards with respect to the steps for the epsilon values 0, 0.01, and 0.1 in the Jupyter notebook submitted along with this report.

Overall, exploring the multi-armed bandit problem and the epsilon-greedy method has been a captivating journey, and I hope that others will find it just as fascinating as I did.
