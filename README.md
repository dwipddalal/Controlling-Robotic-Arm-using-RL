
<div align = center>
<a href = "github.com/dwipdalal/joint-gym"><img width="700px" height="500px" src= "https://user-images.githubusercontent.com/76529011/215042798-66e1c161-3d6e-4670-a373-d335f91edc7d.png"></a>
</div>

--------------------------------

Joint-Gym is a pybullet-based wrapper for Reinforcement Learning-based tasks.

## Building simuation environement

- We used pybullet to build the pysics based simulation environment that can be embedded with physics. 

PyBullet is a physics engine that can be used for simulating rigid-body dynamics with contacts and is widely used in robotics and machine learning research. It is written in C++ but it provides a Python API which allows it to be used with Python.

The PyBullet Python API can be used to create, simulate and control physics in a PyBullet simulation. It provides functions for creating and manipulating objects, applying forces and torques, and retrieving information about the simulation state. You can also use PyBullet's Python API to connect to other Python libraries such as OpenAI's Gym, TensorFlow, and PyTorch to perform reinforcement learning tasks.

In summary, PyBullet is a powerful physics engine that can be used to simulate robotic arms and other multi-body systems, and its Python API allows it to be easily integrated with Python-based machine learning libraries.


## Some experiments that we ran to check for robustness of pybullet environment

- Controlling a 3r robot in pybullet

## Concepts of Reinforcement Learning 

Two major classes of algorithms:
- Model based algorithm
- Model free algorithm

Two classes of learning:
- Online Learning 
- Offline Learning

Two classes of policy:
- On-policy
- Off-policy

## Q Function
The action-value function, also known as the Q-function, is a fundamental concept in reinforcement learning that maps a state-action pair to the expected total reward of taking that action in that state and following a specific policy thereafter.

Formally, the action-value function is defined as:
Q(s, a) = E[R_t+1 + γR_t+2 + γ^2R_t+3 + ... | S_t = s, A_t = a]

where s is the current state, a is the action taken in that state, R_t is the reward received at time t, γ is a discount factor that determines the importance of future rewards, and E[.] is the expected value operator.

The Q-function represents the quality of taking a particular action in a specific state. By computing the Q-values for all actions in each state, an agent can determine the best action to take in each state and thus optimize its behavior to maximize its expected total reward.

## Documentation Sytle

We have used PEP 8 format style.
