# Reinforcement Learning 

## Deep Q-Learning

### Homework
<p align="center"><img src="https://github.com/IBIO4615-2019/Presentations/master/svgs/7be4fc76040bc1bd1faaa6bad3b2f927.svg" align=middle width=675.61703055pt height=119.81735864999999pt/></p>

## Deep Deterministic Policy Gradient
DDPG implement DPG algorithm with actor-critic parametrized with neural networks.\\

### Actor ###
Actor estimate policy <img src="https://github.com/IBIO4615-2019/Presentations/master/svgs/a0bba743e0d45642c4c3e52b86657915.svg" align=middle width=37.298393549999986pt height=24.65753399999998pt/> which maps from state to action.\\ 

### Critic ###
Critic estimate action value function <img src="https://github.com/IBIO4615-2019/Presentations/master/svgs/5b9f673276d4daa369c7ea9c3f51e061.svg" align=middle width=65.84041859999998pt height=24.65753399999998pt/> under policy <img src="https://rawgit.com/IBIO4615-2019/Presentations/master/svgs/a0bba743e0d45642c4c3e52b86657915.svg" align=middle width=37.298393549999986pt height=24.65753399999998pt/>.\\

### Homework
<p align="center"><img src="https://github.com/IBIO4615-2019/Presentations/master/svgs/f7847d4148c03553310999db1ec4ddfb.svg" align=middle width=675.61710645pt height=157.80821925pt/></p>
  
  \item \textbf{(Optional)} In continous montain car is 
  <p align="center"><img src="https://github.com/IBIO4615-2019/Presentations/master/svgs/8d5f02b18c8033a42d962fe7e9240bf8.svg" align=middle width=283.5015645pt height=39.452455349999994pt/></p> 
  Penalize velocity in mountain car and compare.
\end{itemize}



### My results
<p align="center">![DDPG Performance on swing up pendulum (Pendulum-v0)](./02_DDPG/Trained_Models/DDPG_Pendulum-v0/reward_vs_episode.png)</p>
