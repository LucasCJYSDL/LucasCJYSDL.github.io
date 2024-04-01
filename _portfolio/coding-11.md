---
title: "Hierarchical AIRL"
excerpt: "A novel Hierarchical Imitation Learning algorithm based on AIRL."
collection: portfolio
date: 2022-10-01
---

[GitHub Link](https://github.com/LucasCJYSDL/HierAIRL)

Codebase for my paper: Hierarchical Adversarial Inverse Reinforcement Learning

Language: Python

The following parts are included:
- Benchmarks built with Mujoco, including Hopper, Walker, Ant box-pushing, and Point maze.
- An implementation of the hierarchical imitation learning (HIL) algorithm proposed in our paper.
- Implementations of the SOTA IL and HIL algorithms as baselines, including GAIL, AIRL, Option-GAIL, Directed-Info GAIL.

To reproduce the baselines algorithms is quite challenging since I need to rewrite/reframe the codes for each of them to make them have the same coding style/structure as ours, in order to make the comparisons fair. At the same time, I need to stick to the pseudo-codes in their paper (my main reference), and also include the tricks and parameter setting used in their original implementations (if provided).
