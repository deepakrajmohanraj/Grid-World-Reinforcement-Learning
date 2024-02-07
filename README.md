# Reinforcement Learning Assignment

## Abstract
This project focuses on defining and solving a reinforcement learning (RL) environment using Gym standards. The assignment includes three main parts. In the first part, an RL environment based on a Markov decision process (MDP) is defined. The second part applies the SARSA algorithm to solve a pre-defined environment, while the third part utilizes the Q-learning method to solve a grid-world environment.

### Part I: Define an RL Environment
In this part, a grid-world RL environment is defined as an MDP. The environment features a mouse, cheese, home, and obstacles. The mouse navigates a 5x5 grid, avoiding shocks, collecting cheese, and reaching home to maximize rewards. Safety measures are implemented, and the episode terminates after a fixed number of time steps.

### Part II: Applying SARSA
The SARSA algorithm, an on-policy RL algorithm, is implemented to solve the environment defined in Part I. Key features, advantages, and disadvantages of SARSA are discussed. Hyperparameters are tuned, and the algorithm's performance is evaluated through reward, epsilon, and timestep plots.

### Part III: Solving Environment using Q-Learning
This section implements the Q-learning algorithm, an off-policy RL algorithm, to address the environment specified in Part I. Similar to Part II, hyperparameters are tuned, and the algorithm's performance is evaluated and compared with SARSA.

## Conclusion
The project provides a comprehensive exploration of RL algorithms in solving complex environments. Each part discusses the implemented algorithms, their advantages, disadvantages, and the impact of hyperparameter tuning on performance.
