Project overview:
In this project I used DQN (which is a deep reinforcement learning algorithm) to train an agent(player) to navigate and collect bananas.

The agent will score a reward of +1 if it picked yellow bananas ,on the other hand ,if it picked a blue banana it will score a reward of -1.the goal of the agent is to score a total reward of +13 over 100 episodes.

The state space has a dimension of size 37 which includes the the agent's velocity, along with ray-based perception of objects around the agent's forward direction. The action space has a dimension of size 4;it consists of the following actions:
(0)move forward.
(1)move backward.
(2)turn left .
(3)turn right.

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"






Setting up the environment:
1.Download the environment from the following links
    • Linux: click here 
    • Mac OSX: click here 
    • Windows (32-bit): click here 
    • Windows (64-bit): click here 
N/B(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link to obtain the environment.
2.Install Anaconda where you will run the code on Jupiter notebook.

3.Installl the following python modules:
    • numpy
    • PyTorch
    • UnityMLagent
    •  python 3.6
      
      
      
      
      
Instructions:
1.Download or clone this repository.
2.Follow the instructions in Navigation.ipynb to get started with training your own agent or to see an already trained agent.
3.optional:You can read the report.pdf file to get a better understanding on how I implemented the algorithim.





