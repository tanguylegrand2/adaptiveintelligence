# Reinforcement Learning: Simplified Chess Game Simulation

This project implements an **intelligent agent** that learns to play a simplified version of **chess**, using the principles of **reinforcement learning**. The aim is to help better understand how an agent can adapt and make decisions based on the state of its environment. This project is built without specialized libraries, focusing on custom implementations of the algorithms.

## Project Objective

The goal is to demonstrate the use of reinforcement learning in a simplified chess environment, to understand the dynamics between the agent and the environment. This project doesn't rely on external libraries but on custom reinforcement learning and decision-making algorithms.

## Technologies and Tools

- **Language:** Python
- **Game Environment:** Simplified chess
- **Reinforcement Learning:** Basic custom implementations
- **State and Action Management:** Scripts simulating piece movements and agent decisions
- **Jupyter Notebooks:** Used for experimenting with algorithms and visualizing results

## Key Features

- **Simplified Chess Game Environment**: A custom chess environment where an agent plays against itself.
- **Decision-Making Agents**: Simple reinforcement learning algorithms are applied to help the agent learn.
- **Reward and Penalty System**: The agent receives rewards or penalties based on its actions within the game.

## Installation

Clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/tanguylegrand2/adaptiveintelligence.git
cd adaptiveintelligence
```

No external dependencies are required, just standard Python libraries like `numpy`.

## Running the Project

To run a game simulation, execute the main file within a Jupyter Notebook environment.

```bash
jupyter notebook
```

In the notebook, you can observe how the agent plays and learns from each game.

## Main Files

- **`Chess_env.py`**: Contains the logic of the simplified chess environment, applying basic chess rules.
- **`generate_game.py`**: Generates random games or sets up specific scenarios for agent testing.
- **`degree_freedom_king1.py` and `degree_freedom_queen.py`**: Simulate the movement and action possibilities of different chess pieces.
- **`AssignmentTL.ipynb`**: Jupyter notebook demonstrating and testing learning algorithms applied to the environment.

## Results

By running the scripts, the agent experiments with different strategies, gradually improving its performance. Through multiple simulations, the agent aims to maximize its rewards by adapting its strategy to the changing state of the game.

## Future Improvements

- **Game Complexity**: Add more pieces or additional rules to further test the agent's robustness.
- **Agent Optimization**: Implement advanced learning techniques like Q-learning or Deep Q-learning to improve decision-making.




