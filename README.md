# Flappy Bird DQN Agent

A Deep Q-Learning reinforcement learning agent trained to play Flappy Bird using **PyTorch**, **Gymnasium**, and **flappy-bird-gymnasium**.

The agent uses a Deep Q-Network, experience replay, epsilon-greedy exploration, and a target network to learn how to play the game through trial and error.

## Description

This project implements a Deep Q-Network agent for the `FlappyBird-v0` environment. The model learns to choose actions by interacting with the environment and maximizing its reward over time.

The training process includes:

- Experience replay memory
- Epsilon-greedy action selection
- Target network synchronization
- Q-value optimization using Mean Squared Error loss
- Model saving when a new best reward is achieved

## Technologies Used

- Python
- PyTorch
- Gymnasium
- flappy-bird-gymnasium
- YAML
- Reinforcement Learning
- Deep Q-Learning

## Project Structure

```text
.
├── agent.py
├── dqn.py
├── experience_replay.py
├── parameters.yaml
├── runs/
│   ├── model.pt
│   └── logs
└── README.md
