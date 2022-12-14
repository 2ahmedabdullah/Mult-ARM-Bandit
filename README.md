# Multi-ARM-Bandit

## Overview

The multi-armed bandit problem is a classic reinforcement learning example where we are given a slot machine with n arms (bandits) with each arm having its own rigged probability distribution of success. Pulling any one of the arms gives you a stochastic reward of either R=+1 for success, or R=0 for failure.

<p align="center">
   <img src="ucb.png">
</p>

## Approach

Given: 4 Bandits with the success rates (17%, 67%, 82%, 47%) 

Aim: maximize the success rate using a suitable RL Agent


## Results

<p align="center">
   <img src="ucb1.png">
</p>

<p align="center">
   <img src="tm2.png">
</p>

The maximum success rate was achieved by UCB Agent, this was followed by Thompson Sampling.
