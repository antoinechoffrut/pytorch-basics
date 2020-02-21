# PyTorch workbook

This repository collects short `juputer notebook`s using `PyTorch`
starting with the fundamentals.

_This is work in progress._

Topics currently covered:
- representation
    - samples are represented by row vectors in `PyTorch`  
- `PyTorch` basics  
    - `PyTorch` dataloaders  
    - `PyTorch` hook functions  
    - `PyTorch` `zero_gradient()`
- modules  
    - `Sequential`
    - `Embedding`  
- expressivity  
    - activation functions  
    - step functions constructed from activation functions  
    - bump functions constructed from activation functions  
- inspection and visualization  
    - accessing hidden states  
    - visualizing (gradient) vector fields
    - statistics on activations in a MLP  
- automatic diffrentiation  
    - `PyTorch`'s `backward()` function and the vector-Jacobian product  
- function approximation  
    - approximation of scalar, univariate functions with multi-layer
     perceptrons (MLP)  
    - evidence of gradient vanishing  
- optimization  
    - gradient descent (1D)
    - gradient descent with momentum (2D)
- regression  
    - logistic regression  
    - linear regression  
    - polynomial regression  
    - Fourier regression (low-pass filtering)  
