
Certainly! Here's the revised LinkedIn project description with a mention of the epsilon-greedy policy:

Project: Tic Tac Toe RL Bot using Deep Q-Networks (DQN)

Objective: Developed an intelligent agent to play Tic Tac Toe using reinforcement learning techniques.

Algorithm: Implemented a Deep Q-Network (DQN) to enable the bot to learn optimal strategies through self-play.

Frameworks and Libraries: Utilized TensorFlow and Keras for building and training the neural network, and OpenAI Gym for the environment setup.

State Representation: Represented the Tic Tac Toe board as a 1D array of length 9, with each element corresponding to a cell on the board (empty, player 1, player 2).

Action Space: Defined actions as placing a marker in any of the 9 positions on the board.

Reward System: Designed a reward structure that incentivizes winning moves, penalizes losing moves, and encourages moves leading to a draw.

Training Process: Trained the agent through numerous episodes of self-play, leveraging experience replay and a target network to stabilize learning.

Exploration vs. Exploitation: Used an epsilon-greedy policy to balance exploration of new moves and exploitation of learned strategies.

Performance Evaluation: Evaluated the bot's performance against baseline random and heuristic-based players, demonstrating significant improvement over time.

Results: Achieved a high win-rate against non-learning agents and competitive performance against more advanced heuristic strategies.

Challenges: Addressed challenges related to overfitting, reward shaping, and the balance between exploration and exploitation.

Future Work: Plans to extend the approach to more complex games and refine the DQN architecture for improved learning efficiency and performance.


