# Reinforcement_Learning
Initialization and Validation:
The code starts by setting up an environment for the "Taxi" problem, where a taxi needs to pick up and drop off passengers. It then prints information about the state and action spaces. A random action is taken to see how the environment reacts.

Simulation with Random Agent:
A simulation is run where a random agent makes decisions in the environment. The agent takes random actions, and each step is recorded. The simulation is visualized with an animation, and the number of moves and failed drop-offs are printed.

Q-Learning Training:
The code implements Q-Learning, a method for the agent to learn a strategy over time. The agent updates its strategy based on the outcomes of its actions. This is done for a number of training episodes. Plots show how well the agent is learning.

Test Policy Performance After Training:
The trained agent is tested to see how well it performs. The results are visualized with an animation, and the average number of moves and failed drop-offs per test episode are printed.

Results (Based on the Provided Output):
Simulation with Random Agent:
Number of Moves: Around 679 moves.
Failed Drop-offs: 208 times.
Q-Learning Training:
After training for 10,000 episodes:
Cumulative Rewards: Plots show an increasing trend, indicating the agent is learning.
Number of Moves: Plots show a decreasing trend, indicating the agent is becoming more efficient.
Test Policy Performance After Training:
For a single test episode:
Number of Moves: 13 moves.
Failed Drop-offs: 0 times.
