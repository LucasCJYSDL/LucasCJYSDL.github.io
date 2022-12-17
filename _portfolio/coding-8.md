---
title: "Scalable Option Discovery based on Spectral Clustering"
excerpt: "An option discovery algorithm based on spectral clustering which can be used for continuous control tasks."
collection: portfolio
date: 2022-01-01
---

[GitHub Link](https://github.com/LucasCJYSDL/Deep-Spectral-Option-Discovery)

Codebase for a temporarily-suspended research project of mine.

Language: Python

The following parts are included:
- An evaluation environment built with Pinball.
- Offline version of our algorithm:
    - A random walk data-collector
    - Estimating the spectral features of the continuous state space based on SOTA representation learning techniques
    - Spectral Clustering based on the estimated spectral features
    - Building a topological map based on the clustering results
    - Option discovery based on the offline planning results on the extracted topological graph
- Online version of our algorithm:
    - To be continued......
