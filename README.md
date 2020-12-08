# Navigation Project

Collecting bananas with Reinforcement Learning.

## Index

1. [Project](#project)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Files](#files)
5. [Acknowledgement](#acknowledgement)

<a name="project"></a>
## Project

The game consists of a square with bananas, some are colored yellow while others are colored blue, the actions that can be taken are to move:

- Up
- Down
- Right
- Left

Each yellow banana gives a reward of +1 whereas each blue banana gives a reward of -1, the goal is to collect as many yellow bananas as possible while avoiding blue bananas. To solve the task at hand, we used Deep Q Learning, [here](https://github.com/MauricioTrejo/NavigationProject/blob/master/Report.ipynb) is a complete description of the process followed.

<a name="requirements"></a>
## Requirements

Packages needed for this project:

tensorflow 1.7.1 and [torch 0.4.0](https://pytorch.org/get-started/previous-versions/)

<a name="installation"></a>
## Installation

In order to run this project is important to set a python environment, you can follow the instructions [here](https://github.com/udacity/deep-reinforcement-learning#dependencies). 
  - There are 2 ways to install tensorflow 1.7.1 in your environment, one is with conda and the other is with pip (which is the one we recommend since conda installer has problems with this version of tensorflow)
  - Also, is important to note that the installation of torch has to be from [here](https://pytorch.org/get-started/previous-versions/), otherwise, neither pip nor conda will find the version.

<a name="files"></a>
## Files

- [agent](https://github.com/MauricioTrejo/NavigationProject/blob/master/agent.py) is the py file containing the agent.
- [model](https://github.com/MauricioTrejo/NavigationProject/blob/master/model.py) is the py file containing the neural network.
- [weights](https://github.com/MauricioTrejo/NavigationProject/blob/master/weights.pth) contains the weights of the trained agent.
- [Report](https://github.com/MauricioTrejo/NavigationProject/blob/master/Report.ipynb) contains the report of the agent training.
- [data/Banana...](https://github.com/MauricioTrejo/NavigationProject/tree/master/data/Banana_Windows_x86_64) is Unity's environment.
- [python/](https://github.com/MauricioTrejo/NavigationProject/tree/master/python) has necessary files for Unity's environment.
- [banana_collector](https://github.com/MauricioTrejo/NavigationProject/blob/master/banana_collector.gif) is a gif with the environment of the project.

<a name="acknowledgement"></a>
## Acknowledgement

We want to thank [Unity](https://unity.com/) and [Udacity](https://www.udacity.com/) for the environment and training to solve this project.
