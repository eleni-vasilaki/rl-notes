# 📚 COM3240: Reinforcement Learning - An Introduction

Reinforcement learning (RL) is perhaps the most fascinating type of machine learning. It draws inspiration from psychology and has the ability to directly model human and animal behaviour. It is also among the most challenging machine learning techniques, largely due to the absence of specific feedback during training, which adds to the complexity of the learning process.

The core concept of reinforcement learning revolves around an **agent** that interacts with an **environment**, aiming to optimise a measure of **goodness**—or **reward**, in reinforcement learning terminology. Because the agent has limited or no way of knowing which actions are optimal for maximising the sum of future rewards, it relies on **randomness**, exploring actions at random to gain a sense of which are beneficial or detrimental with respect to its goal. As it gathers more information, the agent is able to make more **informed guesses** and progressively improve its performance.

A key philosophy of this work is to ground results in **logical principles**. Although it is not theoretical in the strictest sense, it aims to demonstrate that, starting from simple principles, it is possible to follow a chain of logical consequences to derive key **update rules** for reinforcement learning algorithms.

In what follows, you’ll find a set of **lecture notes presented as Jupyter notebooks**. The approach taken here is to view everything through the lens of **optimisation**. Every algorithm discussed is framed as the **minimisation or maximisation of an objective function**. This perspective does not delve into theoretical aspects such as algorithmic convergence but instead demonstrates how, by formulating a well-defined objective function, we can derive a wide range of reinforcement learning algorithms.

The material emphasises the importance of **manual derivations** for deep understanding. It begins with a revision of **differentiation** and **probabilities**, although some prior familiarity with these topics will be beneficial, as the content progresses quickly into more advanced concepts.

---

## **Table of Contents**

1. [Introduction to RL: Concepts, Matrix Operations and NumPy.](./notebooks/01_introduction.ipynb)
2. [Revisiting Probabilities: Dungeons, Dragons and other monsters.](./notebooks/02_probabilities.ipynb)
3. [Differentiation: The Concept of Optimisation, (Partial) Derivatives and (Partial) Differential Equations.](./notebooks/03_derivatives.ipynb)
4. [Reinforcement Learning through the lens of Optimisation; Immediate Rewards.](./notebooks/04_bandits.ipynb)
5. [Markov Decision Processes and the Bellman Equations.](./notebooks/under-construction.ipynb)
---
