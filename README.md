# Reinforcement Learning Coursework Repository

This repository contains my implementations and experiments for several Reinforcement Learning (RL) homework assignments.

---

### **RL-HW2**
This folder focuses on value-based reinforcement learning methods.

- **`RL_PHW2_DQN.ipynb`**  
  Implements and trains a **Deep Q-Network (DQN)** agent on the **LunarLander-v2** environment from Gymnasium.  
  Includes network architecture design, experience replay, ε-greedy exploration, and training curves.

- **`RL_PHW2_MC_TD.ipynb`**  
  Applies **Monte Carlo** and **Temporal Difference (TD)** methods to estimate value functions on the **CliffWalking-v0** environment.  
  Includes On-Policy First-Visit MC, SARSA, and Q-learning results.

- **`greedy_policy.mp4`**  
  A video demonstration of the agent’s greedy policy after training.

---

### **RL-HW3**
This folder contains work on on-policy reinforcement learning algorithms.

- **`RL_HW3_On_Policy.ipynb`**  
  Implements and evaluates **REINFORCE** and **Proximal Policy Optimization (PPO)**.  
  Covers policy gradient estimation, variance reduction, and clipped objective optimization.

---

### **RL-HW4**
This folder focuses on actor-critic and imitation learning techniques.

- **`RL_HW4.ipynb`**  
  Implements the **Soft Actor-Critic (SAC)** algorithm on the **CartPole** environment in:
  - **Online RL setting:** Train SAC from scratch through environment interaction.  
  - **Offline RL + Imitation Learning:** Use the learned policy to collect expert trajectories and perform **behavioral cloning**.

---

## Topics Covered
- Value-based RL (MC, TD, SARSA, Q-learning)
- Deep Q-Learning (DQN)
- Policy Gradient methods  
- REINFORCE  
- Proximal Policy Optimization (PPO)  
- Soft Actor-Critic (SAC)  
- Behavioral Cloning & Offline RL  
- Gymnasium environments (LunarLander-v2, CliffWalking-v0, CartPole)
