---
title: "Qualitative and Quantitative Analysis of Soft-Actor Critics with REDQ and Reset Mechanism"
excerpt: CSCI 375 Reinforcement Learning Course Project
collection: projects
---

*Final Project in NYU Shanghai CSCI 375 Reinforcement Learning class taught by [Prof. Keith Ross](https://sites.google.com/nyu.edu/keithross/home?authuser=0). This project is also supported by our amazing TA [Dr. Watcher Wang](https://watchernyu.github.io/me/).*

This paper presents a study on the Soft-Actor Critics (SAC) algorithm, one of the most fundamental methods in deep reinforcement learning. The study probes into multiple algorithmic aspects and configurations of SAC and applies recent advancements such as Randomized Ensembled Double-Q Learning (REDQ) and reset mechanism to the classic SAC algorithm. The author compares the performance of different variants of SAC using both quantitative and qualitative analysis on Hopper-v3 and HalfCheetah-v3 environments. The results show that the variant adopting REDQ and resetting algorithm outperforms all other variants in both environments with signficantly higher average test episode return. In the ablation studies, we also found that REDQ is a generally more robust mechanism to improve sample efficiency while the contribution of reset mechanism is insignificant. This study also shows how configuration details would alter SAC's performance.

[[Code](https://github.com/BaleChen/rl-final-project)] [[Report](https://github.com/BaleChen/rl-final-project/blob/main/Bale_Chen_RL_Final_Project_Report.pdf)]