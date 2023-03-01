# :sparkles: Awesome Optimizers :chart_with_downwards_trend:

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/Dawn-Of-Eve/awesome-optimizers?display_timestamp=committer)
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/Dawn-Of-Eve/awesome-optimizers?include_prereleases)
![GitHub Repo stars](https://img.shields.io/github/stars/Dawn-Of-Eve/awesome-optimizers?style=social)
![GitHub forks](https://img.shields.io/github/forks/Dawn-Of-Eve/awesome-optimizers?style=social)


This repository is concieved to provide aid in literature reiviews to Optimization researchers by offering an up-to-date list of literature and corresponding summaries.

If this repository has been useful to you in your research, please cite it using the ___cite this repository___ option available in Github. This repository would not have been possible without these open-source [contributors](). Thanks! :sparkling_heart:

### Table of Contents


- [:sparkles: Awesome Optimizers :chart\_with\_downwards\_trend:](#sparkles-awesome-optimizers-chart_with_downwards_trend)
    - [Table of Contents](#table-of-contents)
    - [Legend](#legend)
- [Survey Papers](#survey-papers)
- [First-order Optimizers](#first-order-optimizers)
  - [Momentum based Optimizers](#momentum-based-optimizers)
  - [Adaptive Optimizers](#adaptive-optimizers)
  - [Adam Family of Optimizers](#adam-family-of-optimizers)
- [Second-order Optimizers](#second-order-optimizers)
- [Other Optimisation-Related Research](#other-optimisation-related-research)
  - [General Improvements](#general-improvements)
  - [Optimizer Analysis and Meta-research](#optimizer-analysis-and-meta-research)
  - [Hyperparameter Tuning](#hyperparameter-tuning)


### Legend

| Symbol        | Meaning | Count |
|:--------------|:--------|:------|
| :page_facing_up:         | Paper   | 20    |
| :outbox_tray: | Summary | 3     |
| :computer:    | Code    | 0     |


# Survey Papers

1. [An overview of gradient descent optimization algorithms](https://arxiv.org/abs/1609.04747) 
    Sebastian Ruder; 2016

2. [Descending through a Crowded Valley - Benchmarking Deep Learning Optimizers](https://arxiv.org/abs/2007.01547)
    Robin M. Schmidt, Frank Schneider, Philipp Hennig; 2020

# First-order Optimizers

3. [Nesterov Accelerated Gradient momentum](https://jlmelville.github.io/mize/nesterov.html) [:outbox_tray:]() [:computer:]()
    Yuri Nesterov; _Unknown_

4. [KOALA: A Kalman Optimization Algorithm with Loss Adaptivity](https://arxiv.org/abs/2107.03331) [:outbox_tray:]() [:computer:]()
    Aram Davtyan, Sepehr Sameni, Llukman Cerkezi, Givi Meishvilli, Adam Bielski, Paolo Favaro; 2021

## Momentum based Optimizers

5. [On the Momentum Term in Gradient Descent Learning Algorithms](https://reader.elsevier.com/reader/sd/pii/S0893608098001166?token=3147494EED9FE670AF728F3408B795675246C9934481200C4E86611D7FE34FAEDDFF1E9BD5C6AE9455320BF21F3FEA3B&originRegion=eu-west-1&originCreation=20230223114928) [:outbox_tray:]() [:computer:]()
    Ning Qian; 1999
6. [Demon: Improved Neural Network Training with Momentum Decay](https://arxiv.org/abs/1910.04952) John Chen, Cameron Wolfe, Zhao Li, Anastasios Kyrillidis ; 2021

7. [Symbolic Discovery of Optimization Algorithms](https://arxiv.org/abs/2302.06675) [:outbox_tray:]() [:computer:]() Xiangning Chen, Chen Liang, Da Huang; 2023

## Adaptive Optimizers

8. [Adaptive Subgradient Methods for Online Learning and Stochastic Optimization](https://dl.acm.org/doi/10.5555/1953048.2021068) [:outbox_tray:]() [:computer:]() John Duchi, Elad Hazan, Yoram Singer; 2011

9. [ADADELTA: An Adaptive Learning Rate Method](https://arxiv.org/abs/1212.5701) [:outbox_tray:]() [:computer:]() 
    Matthew D. Zeiler; 2012

10. [RMSProp](http://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf) [:outbox_tray:]() [:computer:]()
    Geoffrey Hinton; 2013

## Adam Family of Optimizers

11. [Adam: A Method for Stochastic Optimization](https://arxiv.org/abs/1412.6980) [:outbox_tray:]() [:computer:]()
    Diederik P. Kingma, Jimmy Ba; 2014

12. [AdamP: Slowing Down the Slowdown for Momentum Optimizers on Scale-invariant Weights](https://arxiv.org/abs/2006.08217) [:outbox_tray:]() [:computer:]()
    Byeongho Heo, Sanghyuk Chun, Seong Joon Oh, Dongyoon Han; 2020

13. [AdaBelief Optimizer: Adapting Stepsizes by the Belief in Observed Gradients](https://arxiv.org/abs/2010.07468) Juntang Zhuang, Tommy Tang, Yifan Ding, Sekhar Tatikonda, Nicha Dvornek, Xenophon Papademetris, James S. Duncan ; 2020

14. [On the Variance of the Adaptive Learning Rate and Beyond](https://arxiv.org/abs/1908.03265) [:outbox_tray:]() [:computer:]()
    Liyuan Liu, Haoming Jiang, Pengcheng He; 2021

15. [Momentum Centering and Asynchronous Update for Adaptive Gradient Methods](https://arxiv.org/abs/2110.05454) Juntang Zhuang, Yifan Ding, Tommy Tang, Nicha Dvornek, Sekhar Tatikonda, James S. Duncan ; 2021 

# Second-order Optimizers

16. [Shampoo: Preconditioned Stochastic Tensor Optimization](https://arxiv.org/abs/1802.09568) [:outbox_tray:]() [:computer:]()
    Vineet Gupta, Tomer Koren, Yoram Singer; 2018


# Other Optimisation-Related Research

## General Improvements
17. [Gradient Centralization: A New Optimization Technique for Deep Neural Networks](https://arxiv.org/abs/2004.01461) [:outbox_tray:](survey/gradient-centralization.md) [:computer:]()
    Hongwei Yong, Jianqiang Huang, Xiansheng Hua, Lei Zhang; 2020


## Optimizer Analysis and Meta-research
18. [On Empirical Comparisons of Optimizers for Deep Learning](https://arxiv.org/abs/1910.05446) [:outbox_tray:]()
    Dami Choi, Christopher J. Shallue, Zachary Nado, Jaehoon Lee, Chris J. Maddison, George E. Dahl; 2019

19. [Adam Can Converge Without Any Modification on Update Rules](https://arxiv.org/abs/2208.09632) [:outbox_tray:](survey/adam-can-converge.md)
    Yushun Zhang, Congliang Chen, Naichen Shi, Ruoyu Sun, Zhi-Quan Luo; 2022

## Hyperparameter Tuning
20. [Gradient Descent: The Ultimate Optimizer](https://arxiv.org/abs/1909.13371) [:outbox_tray:]() [:computer:]()
    Kartik Chandra, Audrey Xie, Jonathan Ragan-Kelley, Erik Meijer; 2019
