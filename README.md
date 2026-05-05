# FinRL — Course Project Submission

**Student:** Thibault Goutorbe  
**Institution:** AIvancity

---

## Project Overview

This repository contains my course project based on **FinRL**, an open-source framework for financial reinforcement learning. The goal of this project is to apply deep reinforcement learning (DRL) techniques to algorithmic trading and portfolio management problems.

FinRL enables the training of DRL agents on historical market data to develop automated trading strategies. This project explores the use of state-of-the-art DRL algorithms (such as PPO, A2C, DDPG, TD3, and SAC) to build and evaluate trading agents on financial markets.

---

## Project Structure

```
FinRL/
├── README.md          # Project documentation (this file)
```

---

## Objectives

1. Understand the FinRL framework and its components (environment, agent, training pipeline)
2. Implement a DRL-based trading agent using historical stock market data
3. Evaluate agent performance using standard financial metrics (cumulative returns, Sharpe ratio, max drawdown)
4. Compare multiple DRL algorithms on the same trading task

---

## Environment & Setup

This project uses the [FinRL library](https://github.com/AI4Finance-Foundation/FinRL) as its foundation.

### Requirements

- Python 3.8+
- `finrl`
- `stable-baselines3`
- `gym`
- `pandas`, `numpy`, `matplotlib`

### Installation

```bash
pip install finrl
pip install stable-baselines3
```

---

## References

- [FinRL: A Deep Reinforcement Learning Library for Automated Stock Trading](https://arxiv.org/abs/2011.09607)
- [AI4Finance-Foundation/FinRL on GitHub](https://github.com/AI4Finance-Foundation/FinRL)
- Liu, X., Yang, H., Chen, Q., Zhang, R., Yang, L., Xiao, B., & Wang, C. D. (2021). *FinRL: A deep reinforcement learning library for automated stock trading in quantitative finance.*
