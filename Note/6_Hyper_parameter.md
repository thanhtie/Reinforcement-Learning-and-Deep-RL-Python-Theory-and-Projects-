
## `epsilon`: prob for choosing exploration or exploitation.

![image](https://github.com/thanhtie/Reinforcement-Learning-and-Deep-RL-Python-Theory-and-Projects-/assets/92991572/b8c63be0-c0c3-4e5e-9305-a65df2af6683)

At beginning should focus on exploration -> make epsilon is high
Then after having data learning -> can exploit -> reduce epsilon 


## `gamma`:  discount factor, how much the potential future rewards affect the update of the current Q-value

![image](https://github.com/thanhtie/Reinforcement-Learning-and-Deep-RL-Python-Theory-and-Projects-/assets/92991572/3c92a535-e98f-4ae2-9014-3dcbaebd2fa5)


+ Zero Gamma: The agent focuses only on the immediate reward, disregarding future consequences. This is akin to a myopic decision-making process where long-term benefits are ignored.

+ High Gamma (Close to 1): The agent values future rewards almost as much as immediate ones, leading to strategies that may involve delayed gratification or more complex sequences of actions to achieve a higher reward in the future.

## `alpha`: learning rate
