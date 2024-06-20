# Deep Q-Network (DQN) Implementation and Training for Reinforcement Learning

This repository contains the Jupyter notebook for Programming Assignment 3. The assignment focuses on implementing and training a deep Q-network (DQN), a type of reinforcement learning algorithm. Follow the instructions below to set up and run the notebook.

## Project Overview

### Description

The goal of this project is to implement a Deep Q-Network (DQN) for a reinforcement learning task. DQNs are a type of deep learning model used to solve problems where an agent learns to make decisions by interacting with an environment. The key components of this project include:

1. **Understanding DQN**: Learning the theoretical aspects of DQN, including how it approximates Q-values using neural networks.
2. **Implementation**: Implementing the DQN algorithm from scratch, including the neural network architecture, experience replay mechanism, and target network updates.
3. **Training**: Training the DQN on a given environment to learn an optimal policy for decision-making.
4. **Testing and Evaluation**: Evaluating the performance of the trained model and understanding its behavior.

### Significance

Deep Q-Networks are significant in the field of artificial intelligence and machine learning for several reasons:

1. **Breakthrough in Reinforcement Learning**: DQNs were a major breakthrough in reinforcement learning, demonstrating that deep neural networks can be used to approximate complex policies and value functions.
2. **Wide Applicability**: DQNs can be applied to various tasks, including game playing, robotic control, and autonomous driving.
3. **Foundation for Advanced Algorithms**: Understanding and implementing DQNs provides a foundation for more advanced reinforcement learning algorithms like Double DQN, Dueling DQN, and Deep Deterministic Policy Gradient (DDPG).

## File Structure

- `PA3.ipynb`: The main Jupyter notebook containing the assignment instructions, code cells, and markdown documentation.
- `Layers.py`: Contains the code for different layers used in the DQN model.
- `DQN.py`: The script for setting up and training the deep Q-network.

## Setup Instructions

1. **Run a GPU Instance**:
   - Go to `Runtime` -> `Change runtime type` -> `Hardware accelerator` -> Select `GPU`.
   - Ensure that "using CUDA" prints in the training script.

2. **Prerequisites**:
   - Before writing any code, make sure you can run up to and including the `DQN.py` cell.
   - The `Test` cell should error out with a message about not implementing action (implementing this part is part of your assignment).

3. **Handling Prompts**:
   - When you reach the line:
     ```
     [Y]es, [N]o, [A]ll, n[E]ver, [R]ename, [Q]uit
     ```
     - Press the stop button on the cell, and it will continue running.

## How to Run

1. Open the `PA3.ipynb` notebook in Jupyter.
2. Follow the instructions provided in the markdown cells.
3. Run each cell sequentially to ensure that dependencies are loaded correctly.
4. Implement the required parts as indicated in the assignment.

## Notes

- Make sure all dependencies are installed before running the notebook.
- If you encounter any issues, refer to the assignment instructions and ensure you have followed all setup steps correctly.