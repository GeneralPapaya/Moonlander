# Deep Q-Network (DQN) Agent for LunarLander-v3

This project implements a Deep Q-Network (DQN) agent trained to solve the LunarLander-v3 environment using the `stable_baselines3` library and Gymnasium.

## Features

- Training a DQN agent with an MLP policy on the LunarLander-v3 environment
- Customizable hyperparameters: learning rate, exploration schedule, buffer size, and network architecture
- Detailed training logs to monitor rewards, episode length, and exploration decay
- Optional visualization flags during training and testing
- Utilizes GPU acceleration if available for faster training

## Requirements

- Python 3.7 or higher
- gymnasium[box2d]
- stable-baselines3
- torch (PyTorch)

You can install dependencies using:

pip install gymnasium[box2d] stable-baselines3 torch

## Usage

1. Clone the repository

2. Run the training notebook or script to train the agent.

3. Use the provided flags to enable visualization during training or testing.

## Results

The agent progressively learns to land successfully, achieving episode rewards consistently above 200 after sufficient training steps.

## Contributing

Feel free to open issues or submit pull requests for improvements or bug fixes.

