# Reinforcement-Learning-based-AI-for-Snake-Game
# DESCRIPTION
Our project aims to develop an artificial intelligence (AI) agent capable of playing the classic Snake game using reinforcement learning techniques. The AI agent will learn to navigate the game environment, avoid obstacles, and consume food to maximize its score. We will implement a Q-learning algorithm to train the AI agent, allowing it to learn optimal strategies through trial and error.
We will be implementing a Snake game using Reinforcement Learning to teach an AI how to play it. We plan on using RL in the following ways : 
1) Game Environment: The game environment is created using Pygame, where the snake moves around the screen, eating food to grow while avoiding collisions with walls and itself.
2) State Representation: The state of the game is represented by the position of the snake's head, the positions of its body segments, and the position of the food.
3) Action Space: The AI agent can take four actions: move the snake up, down, left, or right.
4) Reward System: The agent receives a positive reward for eating food and a negative reward for colliding with walls or itself. The goal of the agent is to maximize its cumulative reward over time.
5) Q-Learning: We plan to use a neural network (Linear_QNet) to approximate the Q-values for each state-action pair. The QTrainer class implements the Q-learning algorithm, where the model learns to map states to actions that maximize the expected cumulative reward.
6) Training Loop: The AI agent plays the game iteratively, updating its Q-values based on the rewards received. The agent learns from its actions and improves its strategy over time.
By using reinforcement learning, the AI agent learns to play the Snake game effectively, demonstrating how RL can be applied to teach AI agents to perform complex tasks through trial and error.

# REINFORCEMENT LEARNING ALGORITHM
We plan to use the Q-learning algorithm which is used in reinforcement learning for training our AI agent. Q-learning is a model-free reinforcement learning algorithm that enables the agent to learn the values of state-action pairs iteratively and helps find the optimal action-selection policy for a given Markov decision process (MDP). Q-learning is based on the concept of estimating the quality of actions (Q-values) in a given state and updating these estimates iteratively through interactions with the environment. By exploring different actions and observing the resulting rewards, the agent updates its Q-values to learn the best actions to take in different states. 

![WhatsApp Image 2024-07-17 at 6 20 48 PM](https://github.com/user-attachments/assets/d68ea687-bce8-43a9-bff1-75f3e0013017)
![WhatsApp Image 2024-07-17 at 6 20 48 PM (1)](https://github.com/user-attachments/assets/9e4fae29-2266-471f-8740-77b03f043ae4)

# AUTHORS
1) Mihika Sanghvi
2) Mihika Dravid

