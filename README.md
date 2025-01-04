# AI Course A-Z: Deep Reinforcement Learning Practice

This repository contains my implementations of deep reinforcement learning algorithms as part of the Udemy course [Artificial Intelligence A-Z](https://www.udemy.com/course/artificial-intelligence-az). The focus is on applying modern reinforcement learning techniques to real-world problems and game environments.

## Project Overview

### 1. **A3C for Kung Fu Master**
   - **Algorithm:** Asynchronous Advantage Actor-Critic (A3C).
   - **Environment:** Kung Fu Master (Atari).
   - **Highlights:**
     - Multi-environment training using the `EnvBatch` class.
     - Actor-Critic architecture for simultaneous policy and value function estimation.
     - Implementation of the A3C training loop with a progress bar.

### 2. **Deep Convolutional Q-Learning for Pac-Man**
   - **Algorithm:** Deep Convolutional Q-Network (DCQN).
   - **Environment:** Ms. Pac-Man (Atari).
   - **Highlights:**
     - Use of convolutional neural networks (CNNs) for visual feature extraction.
     - Implementation of experience replay and epsilon-greedy exploration strategies.
     - Training visualization to observe agent progress.

### 3. **Deep Q-Learning for Lunar Landing**
   - **Algorithm:** Deep Q-Network (DQN).
   - **Environment:** Lunar Lander (OpenAI Gym).
   - **Highlights:**
     - Neural network-based Q-value estimation for state-action pairs.
     - Replay memory for efficient training.
     - Custom training loop with performance tracking.

## Repository Contents

- **Jupyter Notebooks:**
  - `A3C_for_Kung_Fu_Partial_Code(1).ipynb`: A3C implementation for the Kung Fu Master environment.
  - `Deep_Convolutional_Q_Learning_for_Pac_Man.ipynb`: DCQN implementation for Ms. Pac-Man.
  - `Deep_Q_Learning_for_Lunar_Landing.ipynb`: DQN implementation for Lunar Lander.
- **Supporting Files:**
  - Videos demonstrating the trained models.
  - Hyperparameter configurations for each algorithm.

## Purpose

This repository serves as a personal learning project to practice and understand the fundamentals of deep reinforcement learning algorithms, including DQN, DCQN, and A3C. It also documents the application of these algorithms to various environments.

## Technologies Used

- **Programming Language:** Python
- **Frameworks/Libraries:** PyTorch, NumPy, OpenAI Gym, ImageIO
- **Development Tools:** Jupyter Notebook, IPython

## Notes

- This repository reflects my progress up to Part 3 of the course. It is primarily a personal project but is documented to provide insight into my learning journey and technical skills.

---
