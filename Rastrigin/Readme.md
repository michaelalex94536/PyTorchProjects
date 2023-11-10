
####  Here, we use PyTorch to solve for the coefficients of a one-dimensional Rastrigin function

See the following blog post: 
https://en.wikipedia.org/wiki/Rastrigin_function


Here is the 1D Rastrigin function:

*f(x)* = 10 + $x^{2}$ - 10 cos(2 $\pi$ *x*).    (1)


In the notebook, we show how to use gradient descent in PyTorch to solve for coefficients $A$ and $B$ in the more general form:

*f(x)* = A + $x^{2}$ - B cos(2 $\pi$ *x*).    (2)


The plot of the function shows it's oscillatory behavior and the global minimum at x = 0.  


![Signal](https://github.com/michaelalex94536/PyTorchProjects/blob/main/Rastrigin/images/Rastrigin.png)
