In the "1DLinearRegression.ipynb" Jupyter Norebook, we solve for the slope $m$ and $y$-intercept $b$ in the equation 
<br>
<br>

$y$ = $m$ * $X$ + $b$            (1)

<br>

where $X$ is the independent variable and $y$ is a series of samples having noise. 
 
<br>
<br>
We will specify "ground truth" values of $m$ and $b$, generate noise-contaminated samples $y$ over a range of $X$, demonstrate how to recover $m$ and $b$ from the noisy data and compare them to the ground truth values. 
<br>
<br>

We will find $m$ and $b$ using three different methods:
<br>
1. Using the scikit-learn linear regression estimator
<br>
This is by far the easiest way to go. We just use it to get values for $m$ and $b$ to compare later to the PyTorch values. 
<br>
<br>
2. Fitting the data using gradient descent in PyTorch
<br>
Here we manually use gradient descent to update the estimates of $m$ and $b$. 
<br>
<br>
<br>
3. Using a PyTorch Neural Network
<br>
The final weight and bias values of a trained linear NN model are simply the m and b values we want to determine.
<br>
<br>

