<h1>BANANA NAVIGATION PROJECT</h1>      
<img src="https://github.com/risper25/NAVIGATION/blob/master/navigation.gif " width="250" height="180" />
<h2>Introduction</h2>   
        
<p>In this project I used DQN (which is a deep reinforcement learning algorithm) to train an agent(player) to navigate and collect bananas.</p>

<p>The agent will score a reward of +1 if it picked yellow bananas ,on the other hand ,if it picked a blue banana it will score a reward of -1.the goal of the agent is to score a total reward of +13 over 100 episodes.</p>

<p>The state space has a dimension of size 37 which includes the the agent's velocity, along with ray-based perception of objects around the agent's forward direction. The action space has a dimension of size 4;it consists of the following actions:</p>
<p>(0)move forward.</p>
<p>(1)move backward.</p>
<p>(2)turn left.</p>
<p>(3)turn right.</p>


<h2>Setting up the environment:</h2>
<ol style="list-style-type:square;">
<li>Download the environment from the following links:
 <ul style="list-style-type:square;">
  <li> Linux: <a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip">click here</a></li>
  <li> Mac OSX:  <a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip">click here</a></li>
  <li>Windows (32-bit):<a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip">click here</a></li>
   <li>Windows (64-bit):<a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip">click here</a></li>
</ul> </li>
   
<p>N/B(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link to obtain the environment.</p>
<li>Install Anaconda where you will run the code on Jupiter notebook.</li>

<li>Installl the following python modules:
    <ul style="list-style-type:square;">
    <li>numpy </li>
     <li>PyTorch</li>
      <li>UnityMLagent</li>
     <li>python 3.6</li>
      </li> </ul>
</ol> 
<h2>Instructions:</h2>

<p>1.Download or clone this repository.</p>
<p>2.Follow the instructions in Navigation.ipynb to get started with training your own agent.
   You can also take a look at the file report.pdf to see how I implemented the algorithim</p>





