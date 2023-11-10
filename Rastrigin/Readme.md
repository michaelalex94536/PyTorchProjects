
####  Here, we use PyTorch to solve for the coefficients of a one-dimensional Rastrigin function

See the following blog post: 
https://en.wikipedia.org/wiki/Rastrigin_function


Here is the 1D Rastrigin function:

f(x) = 10 + x^2 - 10 cos(2pix).(1)


In the notebook, we show how to use gradient descent in PyTorch to solve for coefficients $A$ and $B$ in the more general form:

f(x) = A + x^2 - B cos(2pix).(2)


![Signal](https://github.com/michaelalex94536/PyTorchProjects/blob/main/Rastrigin/images/Rastrigin.png)
