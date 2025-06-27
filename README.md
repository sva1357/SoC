#  SoC Summer Project: OpenAI Gym - Flappy Bird

This repository contains my summer project as part of the **SoC (Seasons of Code)** initiative. The goal was to understand reinforcement learning and apply it to train an agent to play Flappy Bird using a custom OpenAI Gym environment.

---

##  Weekly Progress

### ✅ Week 1: Python Revision
- Brushed up core Python concepts including:
  - Data structures (lists, dictionaries, sets)
  - NumPy basics
  - File I/O and exception handling

### ✅ Week 2: Reinforcement Learning Fundamentals
- Understood the key ideas of **Reinforcement Learning (RL)**:
  - Markov Decision Process (MDP)
  - Exploration vs Exploitation
  - Q-Learning
- Learned about **Neural Networks** and how they're used as function approximators in RL.

### ✅ Week 3: DQN Training on CartPole
- Used **OpenAI Gym** and **Stable-Baselines3** to:
  - Train a **Deep Q-Network (DQN)** agent on the classic `CartPole-v1` environment.
  - Visualize the agent's performance.
  - Save and load models.

### ✅ Week 4: Custom Flappy Bird Gym Environment
- Built a custom **Flappy Bird** environment compatible with OpenAI Gym.
- Key features:
  - Discrete action space: Flap / No Flap
  - Game physics: gravity, jump impulse, pipe movement
  - Collision detection and scoring system
- Prepared the environment for training with a DQN agent.

---

## 🛠 Technologies Used

- Python 3.x
- [OpenAI Gym](https://github.com/openai/gym)
- [Stable Baselines3](https://github.com/DLR-RM/stable-baselines3)
- Pygame (for Flappy Bird rendering)
- NumPy

---



---

## 📁 Repository Structure
| File             | Description                                     |
|------------------|-------------------------------------------------|
| `assignment1_soc.ipynb` | Python basics revision                          |
| `assignment2_soc.ipynb` | DQN training for CartPole using Stable-Baselines |
| `custom_env_flappyBird.ipynb` | Custom Flappy Bird Gym environment              |


