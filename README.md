[//]: # (Image References)
[Banana Agent]: https://github.com/CatoGit/banana-navigation/blob/master/GIF.gif "Banana Agent"


# Banana Navigation Project using DQN

In this project, an agent learns to navigate and collect yellow bananas in a square world.

There exist yellow and blue bananas in the world. Yellow bananas yield a reward of +1 while blue bananas yield a reward of -1. 
The agent's goal is to maximize reward by collecting as many yellow bananas as possible. The environment is solved once the agent achieves an average of +13 reward over 100 episodes. This means the task itself it episodic.

## State space (Continuous)

The state space has 37 dimensions and consists of the agent's velocity and ray perception. The agent perceives banana objects and the walls on the edge of the enviornment.

## Action space (Discrete)

The agent can select four possible actions:

* 0 - move forward
* 1 - move backward
* 2 - turn left
* 3 - turn right

## Instructions

1. Download the environment for your operating system from one of these links:  
    * Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    * Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    * Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    * Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

2. Place the file in the `banana-navigation/` folder and unzip it.

3. Train your DQN agent using `banana-navigation.ipynb`. Make sure to have Python 3.6 with PyTorch and Tensorflow installed in order to use the unity environment on your computer.

4. Watch your trained agent. Enjoy!

![Trained Banana Agent][Banana Agent]

