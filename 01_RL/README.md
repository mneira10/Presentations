# Reinforcement Learning 

## Deep Q-Learning

### Homework
<p align="center"><img src="https://rawgit.com/IBIO4615-2019/Presentations/None/svgs/7be4fc76040bc1bd1faaa6bad3b2f927.svg?invert_in_darkmode" align=middle width=675.61703055pt height=119.81735864999999pt/></p>

## Deep Deterministic Policy Gradient
DDPG implement DPG algorithm with actor-critic parametrized with neural networks.\\

### Actor ###
Actor estimate policy <img src="https://rawgit.com/IBIO4615-2019/Presentations/None/svgs/a0bba743e0d45642c4c3e52b86657915.svg?invert_in_darkmode" align=middle width=37.298393549999986pt height=24.65753399999998pt/> which maps from state to action.\\ 

### Critic ###
Critic estimate action value function <img src="https://rawgit.com/IBIO4615-2019/Presentations/None/svgs/5b9f673276d4daa369c7ea9c3f51e061.svg?invert_in_darkmode" align=middle width=65.84041859999998pt height=24.65753399999998pt/> under policy <img src="https://rawgit.com/IBIO4615-2019/Presentations/None/svgs/a0bba743e0d45642c4c3e52b86657915.svg?invert_in_darkmode" align=middle width=37.298393549999986pt height=24.65753399999998pt/>.\\

### Homework
<p align="center"><img src="https://rawgit.com/IBIO4615-2019/Presentations/None/svgs/f7847d4148c03553310999db1ec4ddfb.svg?invert_in_darkmode" align=middle width=675.61710645pt height=157.80821925pt/></p>
  
  \item \textbf{(Optional)} In continous montain car is ()

            $$R_t=\left\{\begin{array}{cc}
            100 - 0.1||u||_2  \quad & \text{goal reached}\\
            -0.1||u||_2 \quad & \text{otherwise} 
            \end{array}\right.$$ 

\end{itemize}



### My results
<p align="center">![DDPG Performance on swing up pendulum (Pendulum-v0)](./02_DDPG/Trained_Models/DDPG_Pendulum-v0/reward_vs_episode.png)</p>
