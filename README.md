#  SoC Summer Project: OpenAI Gym - Flappy Bird

This repository contains my **Seasons of Code (SoC) Summer Project**.  
The goal was to **understand Reinforcement Learning (RL)** and **apply it to train an agent to play Flappy Bird** using a **custom OpenAI Gym environment**.

---

##  Weekly Progress

✅ **Week 1: Python Revision**  
- Revised core Python concepts:  
  - Data structures (lists, dictionaries, sets)  
  - NumPy basics  
 

✅ **Week 2: Reinforcement Learning Fundamentals**  
- Understood key RL concepts:  
  - Markov Decision Process (MDP)  
  - Bellmann's Equation 
  - Q-Learning basics  
- Learned how Neural Networks are used as function approximators in RL.  

✅ **Week 3: DQN Training on CartPole**  
- Used OpenAI Gym and Stable-Baselines3 to:  
  - Train a Deep Q-Network (DQN) agent on the **CartPole-v1** environment.  
  - Visualize agent performance.  
  - Save and load models for future use.  

✅ **Week 4: Custom Flappy Bird Gym Environment**  
- Built a **custom Flappy Bird environment** compatible with OpenAI Gym.  
- Key features:  
  - Discrete action space: **Flap / No Flap**  
  - Game physics: gravity, jump impulse, pipe movement  
  - Collision detection and scoring system   

✅ **Week 5: Training on Constant Pipe Gap Height**  
- Trained the DQN agent where the **pipe gap height remained constant**.  
- The agent successfully learned a stable strategy to avoid collisions.  

✅ **Week 6: Training on Variable Pipe Gap Height**  
- Increased difficulty by **randomizing the pipe gap height**.  
- Compared agent performance in both scenarios to analyze generalization ability.  

✅ **Week 7: Project Wrap-up & Demo Video**  
- Recorded a **project demo video** explaining:  
  - Project goals & weekly progress  
  - Training process and results  
  - Demo of the trained agent playing Flappy Bird  

---

## 📂 Repository Structure

| Folder/File            | Description |
|------------------------|-------------|
|assignment1_soc.ipynb   | Assignment on python basics|
|assignment2.ipynb       | trained DQN on cartpole env|
|custom_env_flappyBird.ipynb| custom flappy bird environment |
|const_height_flappybird.ipynb| pipe gap's height constant|
|var_height_flappybird.ipynb| pipe's gap height variable|
  



