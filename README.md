# Value Iteration


A 5x5 grid world environment is created and value iteration is opted to find the optimum policy. The aim of the agent in grid world environment is to gain maximum reward in long-term. The final destination of grid world is to reach terminal states. There are two terminal states : water which has a reward of +10 and fire which provide a reward of -10. Each step taken by the agent a reward of -1 is received.


It is implemented in stochastic environment, where the probability of agent's movement is already expected is 0.7, whereas probability that the agent will move randomly is 0.3. The below shown is the Value grid environment(transition value grid).

![WhatsApp Image 2022-06-14 at 9 47 27 AM](https://user-images.githubusercontent.com/86656428/173492549-aef40418-cc72-4aa0-a610-208cba4a8ccc.jpeg)


The state space of the grid world environment is represented in 5x5 grid. The grid shown below is depicts the Policy to be taken to acquire maximum reward.
The agent can move either U,D,L or R inorder to reach terminal state with maximum reward.

U : Up,

D : Down,

L : Left,
 
R : Right,

![WhatsApp Image 2022-06-14 at 9 47 59 AM](https://user-images.githubusercontent.com/86656428/173492631-a814d3e7-423a-40f3-93ee-1d6483fd69ae.jpeg)
