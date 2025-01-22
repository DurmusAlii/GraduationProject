
# Pick-and-Place Reinforcement Learning Project

This repository contains a reinforcement learning project implemented in a Jupyter Notebook using OpenAI Gym. The project focuses on training an agent in a custom 2D environment to efficiently pick and place objects.

## Overview
The source code is structured into three main sections:

1. **Environment Definition**: This section sets up the custom OpenAI Gym environment, including the action space, state space, and dynamics of the 2D grid world.
2. **Training Code**: Implements the reinforcement learning algorithm, utilizing TensorFlow and Keras for Q-learning. Prioritized Experience Replay (PER) is also integrated to enhance learning efficiency.
3. **Model Testing**: Tests the trained model and visualizes its performance using `matplotlib`.

This project was developed on Google Colab, and it is recommended to run the notebook in the same environment for optimal compatibility.

## Table of Contents
- [Source Code](Pick_and_place_rl.ipynb)
- [Project Report](report.pdf)
- [Dependencies](#dependencies)

## Dependencies
The following libraries are required to run the notebook:

- `numpy`
- `gym`
- `tensorflow`
- `keras`
- `matplotlib`
- `itertools`
- `collections`

It is recommended to use Google Colab for this project due to its pre-installed libraries and GPU support, which significantly speeds up training.

## How to Use
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Open the Jupyter Notebook (`Pick_and_place_rl.ipynb`) in Google Colab.
3. Run each cell sequentially to define the environment, train the model, and test its performance.
4. Review the detailed project findings in the [Project Report](report.pdf).
