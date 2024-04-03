Vision-Based Continuous CartPole with DQN

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch%20-%23EE4C2C.svg?&style=for-the-badge&logo=PyTorch&logoColor=white" />
</p>


Implementation of the continuous CartPole from OpenAI's Gym using only visual input for Reinforcement Learning control with Deep Q-Networks


You can change the discrete action space:

```python
n_actions = 11

action_space = [
    (-1.0), (-0.8), (-0.6),  # Action Space Structure
    (-0.4), (-0.2), (0),  # (Steering Wheel, Gas, Break)
    (0.2), (0.4), (0.6),  # Range        -1~1       0~1   0~1
    (0.8), (1.0)
]

```


