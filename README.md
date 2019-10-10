<h1>BANANA NAVIGATION PROJECT</h1>      
<p><img src=" https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif " width="100" height="48" /></p>
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
  <li> Linux: click here</li>
  <li> Mac OSX: click here<</li>
  <li>Windows (32-bit): click here</li>
   <li>Windows (64-bit): click here</li>
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
<p>2.Follow the instructions in Navigation.ipynb to get started with training your own agent or to see an already trained agent.
   how I implemented the algorithim.</p>





