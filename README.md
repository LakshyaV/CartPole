# CartPole

## Getting Started

### Dependencies
Before you begin, make sure you have the following dependencies installed:

- Python 3.x
- OpenAI Gym
- NumPy
- Matplotlib

You can install these dependencies using the following command:

pip install gym numpy matplotlib
Running the Code

To run the CartPole project, execute the cartpole.py script:

python cartpole.py
This will start the training process, and you will be able to see the agent's performance in the Gym environment.

## Project Structure

cartpole.py: The main script that contains the implementation of the reinforcement learning agent using Q-learning.
utils.py: Utility functions for preprocessing and visualizing the CartPole environment.
q_table.npy: The Q-table saved after training. This allows you to load a pre-trained Q-table for evaluation without retraining the agent.
Training

The project uses Q-learning as the reinforcement learning algorithm to train the agent. The training process involves updating the Q-values in the Q-table based on the agent's actions and rewards received in the environment.

## Results

After training, you can observe the performance of the trained agent in the CartPole environment. The agent aims to balance the pole for as long as possible.
