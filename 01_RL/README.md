# Reinforcement Learning 

## Deep Q-Learning (DQN)


## Deep Deterministic Policy Gradient (DDPG)
DDPG implement DPG algorithm with actor-critic parametrized with neural networks.

### Actor ###
Actor estimate policy <img src="./svgs/a0bba743e0d45642c4c3e52b86657915.svg" align=middle width=37.298393549999986pt height=24.65753399999998pt/> which maps from state to action. 

### Critic ###
Critic estimate action value function under policy <img src="./svgs/a0bba743e0d45642c4c3e52b86657915.svg" align=middle width=37.298393549999986pt height=24.65753399999998pt/> <img src="./svgs/5b9f673276d4daa369c7ea9c3f51e061.svg" align=middle width=65.84041859999998pt height=24.65753399999998pt/>.


### My results
![DDPG Performance on swing up pendulum (Pendulum-v0)](./02_DDPG/Trained_Models/DDPG_Pendulum-v0/reward_vs_episode.png)

