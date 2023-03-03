# [Demon : Improved Neural Network Training with Momentum Decay](https://arxiv.org/abs/1910.04952)

John Chen, Cameron Wolfe, Zhao Li, Anastasios Kyrillidis ; 2021

```bibtex
@misc{https://doi.org/10.48550/arxiv.1910.04952,
  doi = {10.48550/ARXIV.1910.04952},
  
  url = {https://arxiv.org/abs/1910.04952},
  
  author = {Chen, John and Wolfe, Cameron and Li, Zhao and Kyrillidis, Anastasios},
  
  keywords = {Machine Learning (cs.LG), Image and Video Processing (eess.IV), Optimization and Control (math.OC), Machine Learning (stat.ML), FOS: Computer and information sciences, FOS: Computer and information sciences, FOS: Electrical engineering, electronic engineering, information engineering, FOS: Electrical engineering, electronic engineering, information engineering, FOS: Mathematics, FOS: Mathematics},
  
  title = {Demon: Improved Neural Network Training with Momentum Decay},
  
  publisher = {arXiv},
  
  year = {2019},
  
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```

## Notes
* Decaying momentum (Demon) is a momentum scheduling rule that aims to improve model performance. Model performance is affected by the 
  hyperparameters. Learning rate and momentum scheduling affect the process of hyperparameter tuning. 
* The momentum decay schedule mentioned is $$ β_t = β_{init} * (1 - t/T) / ((1 - β_{init}) + β_{init} * (1 - t/T)) $$
* SGD and Adam with Demon incorporated into them is given below

![Demon algorithm](assets/Demon1.png)
  
* The implementation of Demon in common optimization algorithms does not involve much additional effort. 
  
