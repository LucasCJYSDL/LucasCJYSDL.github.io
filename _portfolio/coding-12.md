---
title: "Multi-task Hierarchical AIRL"
excerpt: "A SOTA Multi-task Hierarchical Imitation Learning algorithm with broad applications, such as robotics."
collection: portfolio
date: 2023-01-01
---

[GitHub Link](https://github.com/LucasCJYSDL/Multi-task-Hierarchical-AIRL)

Codebase for my paper: Multi-task Hierarchical Adversarial Inverse Reinforcement Learning

Language: Python

The following parts are included:
- Benchmarks built with Mujoco and D4RL, including Hopper, Walker, Ant, Kitchen, and Point maze.
- An implementation of the multitask hierarchical imitation learning algorithm proposed in our paper and its ablations.
- Implementations of the SOTA IL, HIL, and Multi-task (Meta) IL algorithms as baselines, including Option-GAIL, Directed-Info GAIL, MAML-BC, SMILE, PEMIRL.

To reproduce the baselines algorithms is quite challenging since I need to rewrite/reframe the codes for each of them to make them have the same coding style/structure as ours, in order to make the comparisons fair. At the same time, I need to stick to the pseudo-codes in their paper (my main reference), and also include the tricks and parameter setting used in their original implementations (if provided).
