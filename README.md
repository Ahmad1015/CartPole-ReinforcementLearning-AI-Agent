# CartPole Reinforcement Learning AI Agent

This repository contains the implementation of a Deep Q-Network (DQN) to solve the CartPole-v1 environment using reinforcement learning. The code is implemented in Python using PyTorch and Gymnasium.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Video Output](#video-output)
- [License](#license)

## Introduction
The goal of this project is to train an AI agent to balance a pole on a cart using a Deep Q-Network. The agent interacts with the environment and improves its policy based on the rewards received.

## Installation
To run this project, you need to install the required dependencies. You can do this by running the following commands:

```bash
pip install gymnasium
pip install "gymnasium[atari,accept-rom-license]"
apt-get install -y swig
pip install gymnasium[classic-control]
```
## Usage
To train the AI agent, execute the provided Jupyter Notebook or open the Google Colab Link. 
```bash
https://colab.research.google.com/drive/1lMHeGpbkvqeH_jXsNcwy98VTidNl1At2
```
The notebook will walk you through the following steps:
* Importing the necessary libraries.
* Defining the neural network architecture.
* Initializing the environment and setting the hyperparameters.
* Implementing the experience replay mechanism.
* Defining the DQN agent.
* Training the agent.
* Results
The DQN agent is trained for a maximum of 5000 episodes or until it reaches an average score of 500 over 100 consecutive episodes. The training progress, including the average score per 100 episodes, is printed during training.

Video Output
A video demonstration of the trained agent can be generated and viewed. To create the video, the trained agent interacts with the environment, and the frames are saved and compiled into an MP4 file.


https://github.com/Ahmad1015/CartPole-ReinforcementLearning-AI-Agent/assets/129595472/551b5263-821c-4891-ba01-5d409c755609


