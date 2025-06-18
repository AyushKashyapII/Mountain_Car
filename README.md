# 🚗 Mountain Car - Deep Q-Learning (DQN)

This project implements a **Deep Q-Learning (DQN)** agent to solve the classic **MountainCar-v0** environment from **OpenAI Gym**. The goal is to train an agent that learns how to drive a car up a steep hill using reinforcement learning.

---

## 🎯 Problem Overview

In the **MountainCar-v0** environment:
- The car starts at the bottom of a valley.
- The goal is to reach the flag on top of the right hill.
- The engine is not strong enough to climb the hill in one go.
- The agent must learn to build momentum by going back and forth.

---

## 🧠 Algorithm: Deep Q-Learning (DQN)

**Deep Q-Network** uses a neural network to approximate the Q-function:
- Input: State (position and velocity)
- Output: Q-values for each action
- Techniques used:
  - Experience Replay
  - Epsilon-Greedy Policy
  - Target Network for stable learning

---


