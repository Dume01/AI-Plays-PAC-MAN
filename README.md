# AI-Plays-PAC-MAN
# Deep Convolutional Q-Learning for Pac-Man

## Introduction
This project implements Deep Q-Learning with Convolutional Neural Networks (DCQN) to train an AI agent to play the classic arcade game Pac-Man. The agent learns to navigate through the maze, collecting pellets while avoiding ghosts, using a reinforcement learning algorithm.

## Table of Contents
1. [Building the AI](#building-the-ai)
2. [Training the AI](#training-the-ai)
3. [Visualizing the Results](#visualizing-the-results)

## Building the AI <a name="building-the-ai"></a>

### Creating the Architecture of the Neural Network
The neural network architecture consists of multiple convolutional layers followed by fully connected layers. It takes the game state as input and outputs Q-values for each possible action.

### Initializing the Deep Q-Learning Agent
The Deep Q-Learning agent initializes two neural networks: the local Q-network and the target Q-network. It also sets up the replay memory for experience replay.

## Training the AI <a name="training-the-ai"></a>

### Setting up the Environment
The environment is set up using the Gymnasium library, specifically the MsPacmanDeterministic-v0 environment.

### Initializing Hyperparameters
Hyperparameters such as learning rate, minibatch size, and discount factor are initialized for training the agent.

### Preprocessing the Frames
Frames from the game environment are preprocessed before being fed into the neural network.

### Training the Deep Q-Learning Agent
The agent is trained over multiple episodes, where it interacts with the environment, collects experiences, and learns from them using Q-learning updates.

## Visualizing the Results <a name="visualizing-the-results"></a>

### Showing a Video of the Trained Model
A video of the trained AI agent playing Pac-Man is generated and displayed.

