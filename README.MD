# Description
This repo contains three projects from the class CAP6629 Rinforcement Learning, offered by Florida Atlantic University, and taught by Dr. Zhen Ni. Each project covers a crucial part of my journey in reinforcement learning. The goal of this repo is to document what I have learned and hopefully also help others if they get stuck early on in their journey through reinforcement learning.

# Repo Layout
Below I will briefly describe the contents of the repo and each project folder. Each project folder has similar structure: a notebook containing all the code for the project, a `figures` folder containing plots made from the notebook, and a report summarizing the objective, finding, and discussion of the project.

The code in the notebook is heavily documented. So hopefully no additional instruction is needed to get one started. Users are also encouraged to skim through the report in each project folder to get more context of the code in the notebook.

# Project Overview

## Project 1: Multi-arm bandit
It contains analysis of how different $\epsilon$ values in the $\epsilon$-greedy method changes the expected return.

## Project 2: Tabular Method
This is a very ambitious endeavor to code all tabular methods covered in the lecture and analyze their performance on solving a simple grid world problem. Users are strongly encouraged to cross reference with the associated report to learn the algorithm of each tabular method. 

## Project 3: Actor-Critic Architecture
The Actor-Critic architecture is implemented to solve a grid world problem, the same one as in Project 2. However, unlike the tabular method, it is based on training neural network models to simulate the policy and state value function. Implementation borrows from the documentation on [Keras](https://keras.io/examples/rl/actor_critic_cartpole/) and [TensorFlow](https://www.tensorflow.org/tutorials/reinforcement_learning/actor_critic), but with my own twist.

# Playground
Try the notebook for free on Binder.

* Project 1: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FanchenBao/reinforcement_learning/HEAD?filepath=project_1%2Fp1_Bao.ipynb)
* Project 2: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FanchenBao/reinforcement_learning/HEAD?filepath=project_2%2Fp2_Bao.ipynb)
* Project 3: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FanchenBao/reinforcement_learning/HEAD?filepath=project_3%2Fp3_Bao.ipynb)