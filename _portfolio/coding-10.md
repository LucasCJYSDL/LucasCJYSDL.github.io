---
title: "ODPP"
excerpt: "A novel Unsupervised Option Discovery algorithm based on Determinant Point Process."
collection: portfolio
date: 2022-05-01
---

[GitHub Link](https://github.com/LucasCJYSDL/ODPP)

Codebase for my paper: ODPP: A Unified Algorithm Framework for Unsupervised Option Discovery based on Determinantal Point Process

Language: Python

The following parts are included:
- Benchmarks built with Mujoco, including Point/Ant Maze and Ant Locomotion.
- An implementation of the option discovery algorithm proposed in our paper, including PPO, spectral learning, and DPP-related algorithms as the components.
- Implementations of the SOTA unsupervised option discovery algorithms as baselines: VIC, VALOR, DIAYN, and DCO (Deep Covering Option Discovery).

To reproduce the baselines algorithms is quite challenging since I need to rewrite/reframe the codes for each of them to make them have the same coding style/structure as ours, in order to make the comparisons fair. At the same time, I need to stick to the pseudo-codes in their paper (my main reference), and also include the tricks and parameter setting used in their original implementations (if provided).
