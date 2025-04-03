# BananaWorldTrainer

[//]: # (Image References)
[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"
# Project 1: Autonomous Navigation Agent

### Problem Statement
In this project, an agent is placed in an unfamiliar UnityML environment where it must learn to navigate from scratch. The objective is to maximize its reward by collecting yellow bananas, each worth +1, while avoiding blue bananas, which incur a penalty of -1. The agent has no prior knowledge of the environment or the rules and learns solely through interactions and reward-based feedback.
![Trained Agent][image1]

The state space constitutes of 37 dimensions including agent's velocity and ray-based perception vector of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Future Work

- [Implement Prioritized Experience Replay](https://arxiv.org/abs/1511.05952)
- [Implement Double DQN](https://arxiv.org/abs/1509.06461)


# Dependencies

This is an amended version of the `python/` folder from the [ML-Agents repository](https://github.com/Unity-Technologies/ml-agents).  It has been edited to include a few additional pip packages needed for the Deep Reinforcement Learning Nanodegree program.
