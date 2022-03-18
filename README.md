# AI-Optimizer
AI-Optimizer is a next-generation deep reinforcement learning suit, providing rich algorithm libraries ranging from model-free to model-based RL algorithms, from single-agent to multi-agent algorithms. Moreover, AI-Optimizer contains a flexible and easy-to-use distributed training framework for efficient policy training.
![](./images/framework1.png)

AI-Optimizer now provides the following built-in libraries, and more libraries and implementations are coming soon.
- [Multiagent Reinforcement learning](marl)
- [Self-supervized Representation Reinforcement Learning](ssrl)
- [Offline Reinforcement Learning](offline-rl-algorithms)
- [Transfer Reinforcement Learning](transferrl)
- [Model-based reinforcement learning](mbrl)

## Multiagent Reinforcement Learning (MARL)
The Multiagent RL repo contains the released codes of representative research works of TJU-RL-Lab on Multiagent Reinforcement Learning (MARL). The research topics are classified according to the critical challenges of MARL, e.g., the curse of dimensionality (scalability) issue, non-stationarity, multiagent credit assignment, exploration-exploitation tradeoff, and hybrid action. To solve these challenges, we propose a series of algorithms from a different point of view. A big picture is shown below.

<p align="center"><img align="center" src="./multiagent-rl/assets/our-work.png" alt="our solutions"  /></p>



## Offline-rl-algorithms (Offrl)
Offline Reinforcement Learning (Offline RL), also known as Batch Reinforcement Learning (BRL), is a variant of Reinforcement Learning that requires an agent to learn to perform tasks from a fixed dataset without exploration. We plan to establish the ecology of Offline RL in the future. Driven by three critical challenges of Offline RL, we are working on research to address them respectively. For the limited data problem in Offline RL, we are working on designing different data augmentation techniques to expand the original datasets. Besides, we are designing multimodal datasets, which are more in line with the real world. For the overestimation problem in existing Offline RL methods, we plan to develop a unified algorithmic framework and a unified opensource code-level implementation framework. Finally, our ultimate goal is to land Offline RL methods in real-world decision-making scenarios by further investigating the offline to the online training regime.
![Ecology of Offline RL](https://github.com/TJU-DRL-LAB/AI-Optimizer/blob/main/offline-rl-algorithms/Ecology%20of%20Offline%20RL.png)

## Self-supervised Reinforcement Learning (SSRL)
SSRL repo contains the released codes of representative research works of TJU-RL-Lab on Self-supervised Representation Learning for RL. Since the RL agent always receives, processes, and delivers all kinds of data in the learning process (i.e., the typical Agent-Environment Interface), 
how to **properly represent such "data"** is naturally one key point to the effectiveness and efficiency of RL.

In this branch, we focus on three key questions:
- **What should a good representation for RL be?**
- **How can we obtain or realize such good representations?**
- **How can we making use of good representations to improve RL?**

Taking **Self-supervised Learning** (SSL) as our major paradigm for representation learning, we carry out our studies from four perspectives: 
**State Representation**,
**Action Representation**,
**Policy Representation**,
**Environment (and Task) Representation**.

The central contribution of this repo is **A Unified Algorithmic Framework (Implementation Design) of SSRL Algorithm**,
with the ultimate goal of establishing the ecology of SSRL.
See more [here](https://github.com/TJU-DRL-LAB/self-supervised-rl).


## transfer reinforcement learning

## model-based reinforcement learning 
This repo contains a unified opensource code implementation for the Model-Based Reinforcement Learning methods. MBRL-Lib provides implementations of popular MBRL algorithms as examples of using this library. The current classifications of the mainstream algorithms in the modern Model-Based RL area are orthogonal, which means some algorithms can be grouped into different categories according to different perspectives. But the core three directions for future work in MBRL are `faster planning`、` higher tolerance to model error` 、`scalability` to harder problems. Currently, we have implemented Dreamer, MBPO, MuZero, and we plan to keep increasing this list in the future. **We present one of the most comprehensive Model-Based libraries so far, covering most mainstream algorithms in the Model-Based RL area.** We will constantly update this repo to include new research made by TJU-DRL-Lab. See more [here](https://github.com/TJU-DRL-LAB/model-based-rl/tree/master).

# Contributing
AI-Optimizer is still under development. More algorithms and features are going to be added and we always welcome contributions to help make AI-Optimizer better. Feel free to contribute.
