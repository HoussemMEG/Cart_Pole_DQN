# Cart_Pole_DQN
OpenAI Gym is a training and testing environment for Reinforcement Learning Algorithms.

The self learning DQN (Deep Q-network) agent has as an objectif of stabilizing the pole to the vertical in a CartPole-v1 task.

More information about the task can be found here : https://gym.openai.com/envs/CartPole-v1/

<p align="center">
  <img src="https://cdn-images-1.medium.com/max/1600/1*oMSg2_mKguAGKy1C64UFlw.gif" alt="CartPole-v1" />
</p>

## Pre-Requisites
* Python v3.x
* Tensorflow-GPU = v1.2
* [Gym](https://github.com/openai/gym)
* deque

## Some details about the code
* agent.py: contain DQN code, uses an experience replay memory (buffer) to improuve learning and get better results [1].

* chariot.py: cart_pole environement and running agent.py. 

### General insight :
<p align="center">
  <img src="https://user-images.githubusercontent.com/48867769/91853305-495cf380-ec62-11ea-95ff-c535914ad51d.jpg" alt="Reinforcement-learning" />
</p>

The environement gives back to the agent on how well he is doing and the state of the environement and the agent have to improve his strategy (policy) to get a higher score (reward) knowing that.

To learn more about Deep Q-networks refere to [1]. (ref for a better learning)

<img src="https://user-images.githubusercontent.com/48867769/91851317-3e549400-ec5f-11ea-8015-88931e568863.png" alt="DQN-agent" style="width:50%;">

## Contributors
* Houssem Meghnoudj [mail](mailto:houssem.meghnoudj@gmail.com).

## References
[1] [Human-level control through deep reinforcement learning](https://www.nature.com/articles/nature14236)
