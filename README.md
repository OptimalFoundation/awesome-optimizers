# :sparkles: Awesome Optimizers :chart_with_downwards_trend:

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/Dawn-Of-Eve/awesome-optimizers?display_timestamp=committer)
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/Dawn-Of-Eve/awesome-optimizers?include_prereleases)
![GitHub Repo stars](https://img.shields.io/github/stars/Dawn-Of-Eve/awesome-optimizers?style=social)
![GitHub forks](https://img.shields.io/github/forks/Dawn-Of-Eve/awesome-optimizers?style=social)


This repository is concieved to provide aid in literature reiviews to Optimization researchers by offering an up-to-date list of literature and corresponding summaries.

If this repository has been useful to you in your research, please cite it using the ___cite this repository___ option available in Github. This repository would not have been possible without these open-source [contributors](). Thanks! :sparkling_heart:

### Table of Contents

- [Legend](#legend)
- [Survey Papers]()
- [First-order Optimizers](#first-order-optimizers)
    - [Adaptive Optimizers](#adaptive-optimizers)
    - [Adam family of Optimizers](#adam-family-of-optimizers)
- [Second-order Optimizers](#second-order-optimizers)
- [Other Optimization-related Research](#other-optimisation-related-research)
    - [General Improvements](#general-improvements)
    - [Optimizer Analysis](#optimizer-analysis-and-meta-research)
    - [Hyperparameter tuning](#hyperparameter-tuning)
### Legend

| Symbol        | Meaning |
|---------------|---------|
| :outbox_tray: | Summary |
| :computer:    | Code    |


## Survey Papers

- [An overview of gradient descent optimization algorithms](https://arxiv.org/abs/1609.04747) 
    Sebastian Ruder; 2016

- [Descending through a Crowded Valley - Benchmarking Deep Learning Optimizers](https://arxiv.org/abs/2007.01547)
    Robin M. Schmidt, Frank Schneider, Philipp Hennig; 2020

## First-order Optimizers

- [Nesterov Accelerated Gradient momentum](https://jlmelville.github.io/mize/nesterov.html) [:outbox_tray:]() [:computer:]()
    Yuri Nesterov; _Unknown_

- [KOALA: A Kalman Optimization Algorithm with Loss Adaptivity](https://arxiv.org/abs/2107.03331) [:outbox_tray:]() [:computer:]()
    Aram Davtyan, Sepehr Sameni, Llukman Cerkezi, Givi Meishvilli, Adam Bielski, Paolo Favaro; 2021

### Adaptive Optimizers

- [RMSProp](http://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf) [:outbox_tray:]() [:computer:]()
    Geoffrey Hinton; 2013

### Adam Family of Optimizers

- [Adam: A Method for Stochastic Optimization](https://arxiv.org/abs/1412.6980) [:outbox_tray:]() [:computer:]()
    Diederik P. Kingma, Jimmy Ba; 2014

## Second-order Optimizers

- [Shampoo: Preconditioned Stochastic Tensor Optimization](https://arxiv.org/abs/1802.09568) [:outbox_tray:]() [:computer:]()
    Vineet Gupta, Tomer Koren, Yoram Singer


## Other Optimisation-Related Research

### General Improvements
- [Gradient Centralization: A New Optimization Technique for Deep Neural Networks](https://arxiv.org/abs/2004.01461) [:outbox_tray:](survey/gradient-centralization.md) [:computer:]()
    Hongwei Yong, Jianqiang Huang, Xiansheng Hua, Lei Zhang; 2020


### Optimizer Analysis and Meta-research
- [On Empirical Comparisons of Optimizers for Deep Learning](https://arxiv.org/abs/1910.05446) [:outbox_tray:]()
    Dami Choi, Christopher J. Shallue, Zachary Nado, Jaehoon Lee, Chris J. Maddison, George E. Dahl; 2019

- [Adam Can Converge Without Any Modification on Update Rules](https://arxiv.org/abs/2208.09632) [:outbox_tray:](survey/adam-can-converge.md)
    Yushun Zhang, Congliang Chen, Naichen Shi, Ruoyu Sun, Zhi-Quan Luo; 2022

### Hyperparameter Tuning
- [Gradient Descent: The Ultimate Optimizer](https://arxiv.org/abs/1909.13371) [:outbox_tray:]() [:computer:]()
    Kartik Chandra, Audrey Xie, Jonathan Ragan-Kelley, Erik Meijer; 2019
