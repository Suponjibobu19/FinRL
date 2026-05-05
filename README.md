# FinRL

## Overview
This project implements **FinRL-DeepSeek for Stock Trading**, focused on training automated trading agents that combine reinforcement learning (RL) with large language model (LLM) signals extracted from financial news.

## Task I: FinRL-DeepSeek for Stock Trading
The goal is to develop trading agents trained on stock prices and aligned financial news data. Extensions are encouraged, such as:
- new prompts or LLM feature engineering for news signals,
- new ways to inject LLM-processed news into RL observations or rewards,
- new RL algorithms (e.g., GRPO),
- more advanced training pipelines (e.g., adaptations of DeepSeek R1-style training).

## Dataset
We use the **Financial News and Stock Price Integration Dataset (FNSPID)**, which contains stock prices and ~15M time-aligned financial news records for Nasdaq companies (1999–2023). The processed training dataset based on FNSPID is provided.

Teams can also integrate public data (e.g., Twitter) or build scraping/API agents to collect new signals. Some directions focus on dataset improvements, others on trading agent improvements.

## Repository Contents
- `FinRL_DeepSeek_FNSPID_RL_Clean_SingleStock_MultiStock_GPU.ipynb`: main notebook (GPU-ready).
- `finrl_deepseek_clean_rl/`: exported results (tables, figures, equity curves, weights, panel).

Model checkpoints are excluded from Git (`finrl_deepseek_clean_rl/models/`).

## Running the Notebook
Open the notebook and follow the cells in order. The pipeline:
1) loads FNSPID data,
2) builds price and LLM-derived sentiment features,
3) trains PPO/A2C agents for single- and multi-stock experiments,
4) exports results to `finrl_deepseek_clean_rl/`.

If you do not have all dependencies installed, use the optional installation cell at the top of the notebook.
