# Cart_Pole_DQN
OpenAI Gym is a training and testing environment for Reinforcement Learning Algorithms.

## Introduction
The self learning DQN (Deep Q-network) agent has as an objectif of stabilizing the pole to the vertical in a CartPole-v1 task.
More information about the task can be found here : https://gym.openai.com/envs/CartPole-v1/
![CartPole-v1](https://cdn-images-1.medium.com/max/1600/1*oMSg2_mKguAGKy1C64UFlw.gif)

## Pre-Requisites
* Python = v3.x
* Tensorflow-GPU = v1.2

## Some details about the code
* agent.py: contain DQN code, contain a replay buffer (memory) for better learning [1] (ref for more information about replay buffer).
* chariot.py: contain the cart_pole environement. 

### General insight :
The environement gives feed back to the agent on how well he is doing and the agent have to improve his strategy (policy) to get a higher score (reward)
to learn more about Deep Q-networks refere to [2]. (ref for a better learning)
