# [AdaBelief Optimizer: Adapting Stepsizes by the Belief in Observed Gradients](https://arxiv.org/abs/2010.07468)
Juntang Zhuang, Tommy Tang, Yifan Ding, Sekhar Tatikonda, Nicha Dvornek, Xenophon Papademetris, James S. Duncan

``` bibtex
@misc{zhuang2020adabelief,
      title={AdaBelief Optimizer: Adapting Stepsizes by the Belief in Observed Gradients}, 
      author={Juntang Zhuang and Tommy Tang and Yifan Ding and Sekhar Tatikonda and Nicha Dvornek and Xenophon Papademetris and James S. Duncan},
      year={2020},
      eprint={2010.07468},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

## Notes
* AdaBelief is a modified version of Adam that aims to perform as well as Adam while generalize like SGD while maintaining training stability. 
* It is based on 'belief' in the value of gradient calculated in the current step. By this, the authors mean to say that if the gradient is close
  to its exponential moving average (EMA), then it can be trusted and a large step can be take. Conversely, if it differs greatly from the EMA,
  then a small step is taken. 
  
  ![AdaBelief algorithm](/assets/AdaBelief1.png)
  ![AdaBelief action in different conditions](/assets/AdaBelief2.png)
* AdaBelief also takes into account the sign of the gradient at a step. If the gradient is the same sign as its EMA, then the denominator is small.     On the other hand, if they have the opposite sign, the denominator is large.
* In the tests conducted, it was found that AdaBelief consistently had performance comparable to or better than SGD and Adam.
* It performs well in cases where the gradient is large but where the curvature is small.

![AdaBelief intuition](/assets/AdaBelief3.png)
