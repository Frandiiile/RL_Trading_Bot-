# Portfolio Optimization using Reinforcement Learning

This repository contains code and resources for a project focused on utilizing Reinforcement Learning (RL) to optimize investment portfolios. The project explores the application of RL in the context of building optimal portfolios for stock trading and compares it with traditional portfolio theory approaches.

## Problem Statement

The primary objective of this project is to address the question: Given historical data for 3 different stocks, how can we allocate a fixed amount of money among these stocks on a daily basis to maximize the likelihood of returns? The project formulates this as a portfolio optimization problem and aims to develop a strategy (policy) for constructing portfolios that adapt over time based on new information.

## Approach

The project uses Reinforcement Learning, a branch of artificial intelligence, to build an agent that learns to allocate stocks at each time step by observing stock indicators. The agent's goal is to maximize the portfolio's value through systematic trial and error interactions with a trading environment. The RL approach is compared against the traditional Markowitz' efficient frontier approach, which is commonly used in portfolio management.

## Experiment Setup

The project sets up a custom environment to simulate the trading process. The agent interacts with the environment by receiving observations of stock indicators and making allocation decisions. The environment changes over time, and the agent learns to make optimal decisions that lead to the highest portfolio value. The experiments involve training the RL model and evaluating it over multiple runs of the environment.

## Results

After conducting experiments, the project reports the following outcomes:

- The RL approach achieved an average return increase of +20%.
- Markowitz' efficient frontier approach achieved an average return decrease of -1%.
- The RL strategy consistently outperformed Markowitz' approach in the experiments.

## Repository Contents

- **Code**: The repository includes the code implementation of the RL-based portfolio optimization using an Actor-Critic model.
- **Data**: Historical stock data for the 3 selected stocks used in the experiments.
- **Documentation**: Detailed explanations of the RL setup, experiment methodology, and results.

## Disclaimer

This project is for educational and experimental purposes only. It is not intended as financial advice. Always conduct your own research and consult financial professionals before making investment decisions.

## Author

The project is authored by Frandile Aimane, a data scientist. You can reach out to the author at Frandile.aimane@gmail.com.

## References

The project draws inspiration and knowledge from various sources, including scientific papers, tutorials, and frameworks. Some of the notable references include:

- [Reinforcement Learning](https://www.tensorflow.org/agents/overview)
- [Modern Portfolio Theory](https://en.wikipedia.org/wiki/Modern_portfolio_theory)
- [Efficient Frontier](https://www.sciencedirect.com/science/article/pii/S0957417420302803)
