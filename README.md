# Dynamic-Fold-Gradient-Descent-DFGD-New-AI-Algorithm-methodology
Computation power is saved by 50%, with performance remaining unchanged or slightly improved, and the convergence speed is slightly better than that of SGD. 

Importantly,this thinking and method can be used at almost all optimization algorithm,particularly it have the step of calculating gradient.

The next step can be extended to more in-depth algorithm such as Adam and neural networks to take AI to the next level.

The inspiration of the folding convergence criterion for optimization algorithms not only enables continuous dynamic adjustment of selected dimensions for gradient descent training (combined with the data format of 1-1/n), but also allows continuous selection of dimensions for compression, including pruning and quantization. I now realize that it is a complete overarching theory for a scheme that significantly reduces both model training computation power and parameters while maintaining performance (in fact, it enables more precise pre-training).

Dynamic Fold Gradient Descent (DFGD) combined with parameter pruning (dimensions that are not in the gradient direction for a long time) can reduce the scale of large models while maintaining performance. DFGD provides information for parameter pruning, shares a gradient calculator, and determines pruning by analyzing frequency, making pruning more efficient and accurate, thereby enabling greater parameter optimization.
