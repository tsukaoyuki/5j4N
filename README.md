# 5j4N
The sequence of step sizes satisfying the Armijo condition has a trend such that step sizes start out as large values and are then gradually and monotonously decreased ([Armijo_step_size](./decay_step_size.png)).

We checked the behaviors of SGD+Armijo using different values of $c$. We found that, the larger $c$ and $b$ are, the smaller the step sizes become (Please see [number of SFO](./step_size.png) for details). 
