# [Nesterov Accelerated Gradient and Momentum](https://jlmelville.github.io/mize/nesterov.html)

## Notes
* Nesterov works by using "lookahead". This involves using a prediction of the future value of momentum in the current step and provides the algorithm a sort of "prescience".
* The equation for **Nesterov Accelerated Gradient** is given below  
$$v_{t+1} = \mu_{t} v_{t} - \epsilon_t\nabla f(\theta_{t} + \mu_{t} v_{t})$$
$$\theta_{t+1} = \theta_{t} + v_{t+1}$$
The coefficient of $v_t$ can be absorbed into the coefficents from the previous term.
* NAG first makes a large jump in the previous moving average of gradient. It then makes a small correction in the direction of gradient. 
Alternate formulation
$$\theta_{t+1} = (1+\mu)\theta_{t} - (1+\mu)\epsilon\nabla J(\theta_{t}) - \mu(\theta_{t-1} - \epsilon\nabla J(\theta_{t-1}))$$
![Nesterov momentum](/assets/Nesterov1.png)