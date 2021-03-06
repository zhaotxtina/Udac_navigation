# Udac_navigation

### Project Overview
For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.

![](images/navigation.gif)

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- 0 - move forward.
- 1 - move backward.
- 2 - turn left.
- 3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started

Getting Started
1. Download the environment from one of the links below. You need only select the environment that matches your operating system:

- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

(For Windows users) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in the DRLND GitHub repository, in the p1_navigation/ folder, and unzip (or decompress) the file.

### Instructions

The complete steps of results and solutions can be found in the folder. Here is the description of each file:

- Navigation.ipynb file: with fully functional code, all code cells executed and displaying output, and all questions answered. You can also download this via your workspace by clicking download as..
- model_ori.py, model.py and dgn_agent.py: the dqn pytorch model and agent modules
- README.md markdown file: Description of project and instructions
- report.html or report.pdf: export of the project report with the name Report.html or Report.pdf.
- pth_checkpoints folder: Contains several saved model weights of the successful agent, named Test1_checkpoint.pth,
Test2_checkpoint.pth,Test3_checkpoint.pth and Test4_checkpoint.pth.
- Images folder: images used for the project agent environment 


