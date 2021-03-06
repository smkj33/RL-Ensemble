# Analysis of the paper “Ensemble Algorithms in Reinforcement Learning”

## Abstract

This article presents the work of Wiering and van Hasselt in "Ensemble Algorithms in Reinforcement Learning". 
Ensemble methods merge multiple reinforcement learning (RL) algorithms into a single agent 
with the objectif of increasing the learning speed and the obtained reward. 
While ensemble methods have already been used in the context of reinforcement learning for representing 
and learning a single value function [references 14-16 in paper], 
Wiering and van Hasselt introduce a novel technique that combines the policy of each RL learning. 
The individual RL algorithms implemented were: **Q-learning**, **Sarsa**, **Actor-Critic**, **QV-learning**, and **ACLA**. 
The ensemble methods are **majority voting**, **rank voting**, **Boltzmann multiplication**, and **Boltzmann addition**. 
They implemented their algorithms for 5 mazes problems with increasing complexity to assess their performance. 
For all the mazes except the first one, the state space is very large, 
therefore a neural network was used for value functions approximation. 
We reimplemented their algorithms and obtained the same results for the first maze. 
For the other mazes, our neural network did not converge. 
Possible causes for this non-convergence are discussed in this article.

* * *
This branch contains the latest updated code, results and articles describing the findings.
