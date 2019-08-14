# Reinforcement Learning 

## Deep Q-Learning

### Homework
<p align="center"><img src="https://rawgit.com/IBIO4615-2019/Presentations/master/svgs/96fae4ae2a497a4d37ace544df0a8c74.svg?invert_in_darkmode" align=middle width=675.61703055pt height=119.81735864999999pt/></p>

## Deep Deterministic Policy Gradient
DDPG implement DPG algorithm with actor-critic parametrized with neural networks.\\

### Actor ###
Actor estimate policy <img src="https://rawgit.com/IBIO4615-2019/Presentations/master/svgs/a0bba743e0d45642c4c3e52b86657915.svg?invert_in_darkmode" align=middle width=37.298393549999986pt height=24.65753399999998pt/> which maps from state to action.\\ 

### Critic ###
Critic estimate action value function <img src="https://rawgit.com/IBIO4615-2019/Presentations/master/svgs/5b9f673276d4daa369c7ea9c3f51e061.svg?invert_in_darkmode" align=middle width=65.84041859999998pt height=24.65753399999998pt/> under policy <img src="https://rawgit.com/IBIO4615-2019/Presentations/master/svgs/a0bba743e0d45642c4c3e52b86657915.svg?invert_in_darkmode" align=middle width=37.298393549999986pt height=24.65753399999998pt/>.\\

### Homework
<p align="center"><img src="https://rawgit.com/IBIO4615-2019/Presentations/master/svgs/f7847d4148c03553310999db1ec4ddfb.svg?invert_in_darkmode" align=middle width=675.61710645pt height=157.80821925pt/></p>
  
  \item \textbf{(Optional)} In continous montain car is 
  <p align="center"><img src="https://rawgit.com/IBIO4615-2019/Presentations/master/svgs/1613575a5c9f5b2596a7589188ea6e71.svg?invert_in_darkmode" align=middle width=247.9763715pt height=59.178683850000006pt/></p> 
  Penalize velocity in mountain car and compare.
\end{itemize}



### My results
<p align="center">![DDPG Performance on swing up pendulum (Pendulum-v0)](./02_DDPG/Trained_Models/DDPG_Pendulum-v0/reward_vs_episode.png)</p>
