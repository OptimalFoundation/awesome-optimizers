# [Adam Can Converge Without Any Modification on Update Rules.](https://arxiv.org/pdf/2208.09632.pdf)
Zhang, Zhi-Quan; 2022

```bibtex
@misc{https://doi.org/10.48550/arxiv.2208.09632,
  doi = {10.48550/ARXIV.2208.09632},
  url = {https://arxiv.org/abs/2208.09632},
  author = {Zhang, 
            Yushun and Chen, 
            Congliang and Shi, 
            Naichen and Sun, 
            Ruoyu and Luo, 
            Zhi-Quan},
  title = {Adam Can Converge Without Any Modification On Update Rules},
  publisher = {arXiv},
  year = {2022},
  copyright = {arXiv.org perpetual, non-exclusive license}
}

```

## Notes  

*[Reddi et al. (2018)](on-the-convergence-of-adam.md)* states that :  

> For any $β_1, β_2$ s.t. $0 ≤ β_1 < √β_2 < 1$, there exists a problem such that Adam diverges.

1. Even though many varients of Adam came out after this, still Adam remains exceptionally popular. 
2. Without any modification on its update rules, Adam works well in practice.
3. To construct the divergence example, they change sample size, $n$, for different $(β_1, β_2)$, whereas in practical settings, $(β_1, β_2)$ is tuned after the sample size $n$ is fixed.

This paper suggests that:
1. For $β_2$ is large enough and $β_1 < √β_2,$ Adam converges to the neighborhood of critical points.
2. For any fixed $n$, there exists a function such that, Adam diverges to infinity when $(β_1, β_2)$ is picked in the red region.  

![adam-can-converge](assets/adam-can-converg.png)  


3. There is a phase transition from divergence to convergence when changing $β_2$.
4. Convergence and divergence regions of $(β_1, β_2)$ are problem-dependent.
5. “Divergence region” of $(β_1, β_2) $ expands as $n$ increases and converges to the whole region $[0,1)^2$ as $n$ goes to infinity.<br>
<br>

