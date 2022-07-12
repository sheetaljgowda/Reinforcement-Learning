# Reinforcement-Learning

The environment that we have defined is a Deterministic environment following Open AI gym. An environment is said to be deterministic when we know the outcome based on the current state. For instance, in a chess game, we know the exact outcome of moving any player.
• Open AI Gym is a toolkit that provides a wide variety of simulated environments to train agents, compare them, or develop new Reinforcement Learning algorithms.
• The main components of RL are Environment, Agent, Rewards, Goals and Actions, State, Policy.
• An agent is a learner and the decision-maker.
• The environment is the place where the agent learns and decides what actions to
perform.
• Action is a set of actions that the agent can perform.
• State is the state of the agent in the environment.
• A reward is nothing but a scalar value. For each action selected by the agent, the
environment provides a reward. It can be a positive or negative reward. It can be instant
or long-term reward
• In our model the following teams are set as mentioned below
The Set of Actions – 4
States – 16
Rewards – 5 rewards including the goal. Time steps – 15
The main objective is to create a working deterministic environment. Which achieves goal position while collecting the max number of rewards. There are 15 timesteps for the agent to fulfill this. The agent performs a random action.
