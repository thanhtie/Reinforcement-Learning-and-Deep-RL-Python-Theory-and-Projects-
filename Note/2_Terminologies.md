## Environment:

Key words: 
- Suroundings
- Some set of rules

`Transition Dynamics`: Transition dynamics describe how the environment changes from one state to another in response to the agent's actions. In a deterministic environment, the outcome of an action is fully determined by the current state and the action taken. In contrast, in stochastic environments, there is randomness or uncertainty in the transition dynamics.

`Episodic vs. Continuous`: RL environments can be episodic, where interactions occur in discrete episodes with a clear start and end, or continuous, where interactions unfold continuously over time without distinct episodes.

`Static vs. Dynamic`: In static environments, the transition dynamics and reward structure remain constant over time. However, in dynamic environments, these properties may change over time, requiring the agent to adapt its behavior accordingly.

`Partial vs. Fully Observable`: Environments can be fully observable, where the agent has complete information about the state at each time step, or partially observable, where the agent's observations are incomplete or noisy, making it challenging to infer the true state of the environment.

## Agent:

Someone/Something perform in the environment or agent is the entity that interacts with the environment to achieve a certain goal. It's the decision-maker in the RL framework, responsible for taking actions based on the information it receives from the environment and its own internal state.

`Observations`: In many RL scenarios, the agent receives observations from the environment instead of having direct access to the complete state. Observations may be noisy or partial representations of the true state, requiring the agent to infer the underlying state and make decisions accordingly.


## Action:

Action refers to the decision or choice made by the agent at a particular time step. Actions are the means by which the agent interacts with the environment, influencing its state and potentially affecting future rewards.

`Action Space`: This refers to the set of all possible actions that the agent can take within the environment. Actions are the decisions made by the agent that can influence the environment's state. The action space can be discrete, like choosing a move in a game, or continuous, such as controlling the speed and direction of a vehicle.

`Temporal Dependency`: Actions taken by the agent influence the subsequent state of the environment, leading to a sequence of interactions over time. RL agents typically aim to maximize the cumulative reward they receive over this sequence of actions, which is often formalized as the discounted sum of future rewards.

`Exploration vs. Exploitation`: RL agents face the exploration-exploitation dilemma, where they must balance between exploring unknown parts of the environment to discover better strategies and exploiting known information to maximize immediate rewards. Agents employ various exploration strategies, such as ε-greedy, Thompson sampling, or Upper Confidence Bound (UCB), to navigate this trade-off effectively.

`Exploratory Actions`: To learn effectively, RL agents often take exploratory actions that might not yield immediate rewards but provide valuable information about the environment. Balancing between exploitative and exploratory actions is crucial for effective learning and adaptation.

`Memory and Experience Replay`: Some RL algorithms, especially those involving neural networks, utilize memory mechanisms like experience replay to store and sample past experiences. This allows the agent to learn from a diverse set of experiences and improve sample efficiency and stability during training.

`Learning Algorithm`: RL agents learn to improve their decision-making abilities through experience. Learning algorithms, such as Q-learning, SARSA, Deep Q-Networks (DQN), or Policy Gradient methods, update the agent's policy or value function based on observed rewards and transitions in the environment. These algorithms aim to find optimal policies that maximize long-term cumulative rewards.

## State:

state represents the current situation or configuration of the environment that the agent perceives at a given time step. The state encapsulates all relevant information necessary for the agent to make decisions about which actions to take. Understanding states is fundamental to the RL framework, as they serve as the foundation for the agent's decision-making process. 

`State Space`: The state space defines all possible configurations or situations the environment can be in. It's essentially a representation of the environment's internal state at any given time. States can be discrete, as in a board game where each state represents the positions of pieces on the board, or continuous, such as in robotic control where states might represent the joint angles and velocities of a robot arm.

## Goal / Done State:

Agent reached the goal or dead/loss (dump state).

`Goal`: The agent's ultimate objective is typically to maximize cumulative rewards over time. However, the specific goal may vary depending on the task and environment. The agent's learning process is guided by this overarching objective.

## Reward:

At each time step, the environment provides feedback to the agent in the form of rewards/punishment. Rewards indicate the desirability of the agent's actions. The goal of the agent is typically to maximize the cumulative reward it receives over time. Rewards can be positive, negative, or zero, depending on the outcome of the agent's actions.

`Policy`: The policy is the strategy or rule that the agent uses to select actions in different states of the environment. It maps states to actions and guides the agent's decision-making process. Policies can be deterministic or stochastic, depending on whether they always choose the same action in a given state or sample actions probabilistically.

`Value Function`: The value function estimates the expected cumulative reward that the agent can achieve from a given state or state-action pair. It helps the agent evaluate the desirability of different states or actions and guides its decision-making process. Value functions can be estimated directly or indirectly through methods like state-value functions (V-function) or action-value functions (Q-function).



