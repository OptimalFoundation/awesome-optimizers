# [Nesterov Accelerated Gradient and Momentum](https://jlmelville.github.io/mize/nesterov.html)

## Notes
* Nesterov works by using "lookahead". This involves using a prediction of the future value of momentum in the current step and provides the algorithm a sort of "prescience".
* The equation for **Nesterov Accelerated Gradient** (the Sutskever version, Bengio version is slightly different) is given below  
$$v_{t+1} = \mu_{t} v_{t} - \epsilon_t\nabla f(\theta_{t} + \mu_{t} v_{t})$$
$$\theta_{t+1} = \theta_{t} + v_{t+1}$$
The coefficient of $v_{t+1}$ can be absorbed into the coefficents from the previous term, $\mu_t$ and $\epsilon_t$.
* NAG first makes a large jump in the previous moving average of gradient. It then makes a small correction in the direction of gradient. 
Alternate formulation
$$\theta_{t+1} = (1+\mu)\theta_{t} - (1+\mu)\epsilon\nabla J(\theta_{t}) - \mu(\theta_{t-1} - \epsilon\nabla J(\theta_{t-1}))$$
![Nesterov momentum](/assets/Nesterov1.png)
* One of the main differences between classical momentum and Nesterov's accelerated gradient is that the momentum determines gradient before applying velocity to the parameter. Nesterov computes the gradient after applying velocity. This means that, if $\theta_t + \mu v_t$ is an update that causes a poor change in $\theta$, computing the gradient at that point would help direct the velocity towards a better $\theta_{t+1}$. This correction itself wouldn't be that different from what is provided by classical momentum but its effects could accumulate over time.