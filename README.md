[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

The objective of this project is to train an agent to navigate (and collect bananas!) in a large, square environment.  

![Trained Agent][image1]

If you collect a yellow banana, you will receive a reward of +1, whereas if you collect a blue banana, you will receive a reward of -1.  As a result, the objective of your agent is to collect as many yellow bananas as possible while avoiding blue bananas as much as possible.  
The state space is composed of 37 dimensions and contains the agent's velocity, as well as ray-based perceptions of objects surrounding the agent's forward direction. Based on this information, the agent must determine the best course of action to take. There are four distinct actions available:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

During the course of 100 consecutive episodes, the agent must achieve an average score of +15 in order to solve the environment.
### Getting Started


1. Clone the repository git clone https://github.com/ethanchoi/udacity-p1-navigation.git

    To set up your Python environment, please follow the instructions in the DRLND GitHub repository (https://github.com/udacity/deep-reinforcement-    learning#dependencies). PyTorch, ML-Agents, and several other Python packages are required to complete this project.

2. Please click on one of the links below to download the environment. The only thing you need to do is select the appropriate environment for your operating system:    
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

3. Unzip (or decompress) the file in the 'udacity_p1-navigation/folder' in the DRLND GitHub repository. 

### Instructions

Follow the instructions in `Navigation.ipynb` and feel free to get started with training your own agent!  
